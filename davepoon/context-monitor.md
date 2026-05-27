---
name: context-monitor
description: Monitor context window remaining capacity with graduated warnings (CAUTION → WARNING → CRITICAL → EMERGENCY)
category: performance
event: PostToolUse
matcher: ""
language: bash
version: 1.0.0
---

# context-monitor

Monitor how much context window remains during a Claude Code session. Issues graduated warnings so you never get killed by context exhaustion.

## Event Configuration

- **Event Type**: `PostToolUse`
- **Tool Matcher**: `""` (every tool invocation)
- **Category**: performance

## How It Works

1. Reads Claude Code's debug log to extract actual token usage
2. Falls back to tool-call-count estimation when debug logs are unavailable
3. Saves current % to `/tmp/cc-context-pct` (other scripts can read this)
4. At CRITICAL/EMERGENCY, writes an evacuation template to your mission file

## Warning Thresholds

| Level | Remaining | Action |
|-------|-----------|--------|
| CAUTION | ≤40% | Be mindful of consumption |
| WARNING | ≤25% | Finish current task, save state |
| CRITICAL | ≤20% | Run /compact immediately |
| EMERGENCY | ≤15% | Stop everything, evacuate |

## Environment Variables

| Variable | Default | Description |
|----------|---------|-------------|
| `CC_CONTEXT_MISSION_FILE` | `$HOME/mission.md` | Path to mission/state file for evacuation template |

## Requirements

- `jq` for JSON parsing
- Claude Code debug logs at `~/.claude/debug/` (optional, falls back to estimation)

## Origin

Born from a session that hit 3% context remaining with no warning. The agent died mid-task and all in-flight work was lost.

## Source

From [claude-code-hooks](https://github.com/yurukusa/claude-code-hooks) — battle-tested hooks from 140+ hours of autonomous Claude Code operation.
