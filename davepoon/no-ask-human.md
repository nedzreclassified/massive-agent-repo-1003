---
name: no-ask-human
description: Detect when Claude Code asks questions and remind it to decide autonomously instead
category: automation
event: PostToolUse
matcher: ""
language: bash
version: 1.0.0
---

# no-ask-human

Detects when Claude Code's output contains questions directed at the user ("Should I...?", "Would you like...?") and reminds the agent to decide autonomously instead of asking.

Essential for autonomous/unattended operation where no human is available to answer questions. Every question is a blocking call with no one on the other end.

## Event Configuration

- **Event Type**: `PostToolUse`
- **Tool Matcher**: `""` (every tool invocation)
- **Category**: automation

## Patterns Detected

- "Should I...?"
- "Would you like...?"
- "Do you want...?"
- "Which approach/option...?"
- "What do you think...?"
- "Shall I...?"
- "Do you prefer...?"
- "Can you confirm...?"
- "Is that okay...?"
- "Let me know if..."

## Decision Framework (provided to agent)

1. Technical choices → pick the standard/conventional option
2. Implementation details → follow existing code conventions
3. Ambiguous specs → follow common industry practices
4. Errors → investigate and fix (up to 3 attempts)
5. If truly blocked → document the blocker and move to the next task

## Environment Variables

| Variable | Default | Description |
|----------|---------|-------------|
| `CC_NO_ASK_ENABLED` | `1` | Set to `0` to disable |
| `CC_NO_ASK_PATTERNS_FILE` | (none) | Path to file with additional patterns (one regex per line) |

## Design Philosophy

This hook never blocks (always exit 0). It issues a reminder only. It can't unsend text, but it trains the agent via system message feedback to self-correct in future interactions.

## Requirements

- `jq` for JSON parsing

## Origin

Born from running Claude Code in autonomous 24/7 mode where every question hangs the session until a human checks in. Some sessions asked 3+ questions, burning 30+ minutes of idle time each. This hook reduced question frequency by ~90%.

## Source

From [claude-code-hooks](https://github.com/yurukusa/claude-code-hooks) — battle-tested hooks from 140+ hours of autonomous Claude Code operation.
