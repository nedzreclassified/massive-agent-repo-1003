---
name: branch-guard
description: Prevent accidental git push to main/master branches without explicit approval
category: security
event: PreToolUse
matcher: Bash
language: bash
version: 1.0.0
---

# branch-guard

Prevents accidental `git push` commands to main or master branches. Allows pushes to feature/staging branches.

## Event Configuration

- **Event Type**: `PreToolUse`
- **Tool Matcher**: `Bash`
- **Category**: security

## What It Blocks

- `git push origin main`
- `git push --force origin master`
- Any variant targeting protected branches

## What It Allows

- `git push origin feature-branch`
- `git push origin develop`
- All other git commands
- All non-git commands

## Environment Variables

| Variable | Default | Description |
|----------|---------|-------------|
| `CC_PROTECT_BRANCHES` | `main:master` | Colon-separated list of protected branches |

### Example: Protect additional branches

```bash
export CC_PROTECT_BRANCHES="main:master:production:release"
```

## Requirements

- `jq` for JSON parsing

## Source

From [claude-code-hooks](https://github.com/yurukusa/claude-code-hooks) — battle-tested hooks from 140+ hours of autonomous Claude Code operation.
