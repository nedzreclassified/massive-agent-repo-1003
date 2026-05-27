# Massive Agent Repo — 1005 Claude Code Subagents

> # ⚠️ THIS IS AN AGGREGATION — NOT ORIGINAL WORK
>
> **Every agent in this repository was created by someone else.** This repo simply collects, organizes, and deduplicates agents from **10 open-source projects** so they can be used together. **Full credit goes to the original authors.** Each agent file retains the license of its source repository.
>
> **If you find any agent useful, please star the upstream repo** — that's where the actual engineering work happened. The complete list of sources, authors, and links is in [ATTRIBUTION.md](ATTRIBUTION.md).
>
> The 10 source projects are listed below in the "What's inside" table, each with a direct link to the upstream repository.

---

A curated aggregation of **1005 specialist subagents** for [Claude Code](https://claude.com/claude-code), pulled from 10 open-source collections and deduplicated by name. Drop them into `~/.claude/agents/` and Claude Code will auto-discover them — invoke any agent via the Task tool with `subagent_type: "<agent-name>"`.

## What's inside

| Folder | Source repo | Count | Strength |
|---|---|---|---|
| `anthropic-official/` | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | 19 | First-party Anthropic agents — `code-reviewer`, `security-auditor`, `architecture-critic`, `silent-failure-hunter`, etc. Highest signal. |
| `voltagent/` | [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) | 152 | Broad specialist coverage across 10 categories (core dev, language specialists, infra, quality, data/AI, DX, specialized domains, business, meta-orchestration, research) |
| `wshobson/` | [wshobson/agents](https://github.com/wshobson/agents) | 103 | Plugin-bundled experts: payments, ML ops, incident response, design systems, SEO |
| `davepoon/` | [davepoon/claude-code-subagents-collection](https://github.com/davepoon/claude-code-subagents-collection) | 538 | The largest collection — auto-delegation patterns, full lifecycle coverage |
| `zerox-furai/` | [0xfurai/claude-code-subagents](https://github.com/0xfurai/claude-code-subagents) | 131 | Uniform-format multi-language specialists |
| `vijaythecoder/` | [vijaythecoder/awesome-claude-agents](https://github.com/vijaythecoder/awesome-claude-agents) | 28 | AI dev-team archetype (Tech Lead, Analyst, domain experts) |
| `webdevtodayjason/` | [webdevtodayjason/sub-agents](https://github.com/webdevtodayjason/sub-agents) | 12 | NPM-installable agent manager |
| `zhsama/` | [zhsama/claude-sub-agent](https://github.com/zhsama/claude-sub-agent) | 13 | Spec-driven workflow with quality gates |
| `iannuttall/` | [iannuttall/claude-agents](https://github.com/iannuttall/claude-agents) | 6 | Refactor, content, frontend-design, PRD-writer |
| `charles-adedotun/` | [charles-adedotun/claude-code-sub-agents](https://github.com/charles-adedotun/claude-code-sub-agents) | 3 | Workflow-stage system |

**Total: 1005 agents** (deduplicated by `name:` field across all sources)

## Quick start

```bash
# 1. Clone this repo
git clone https://github.com/nedzreclassified/massive-agent-repo-1003.git ~/massive-agent-repo

# 2. Symlink agents into your Claude Code agents folder
mkdir -p ~/.claude/agents
for dir in anthropic-official voltagent wshobson davepoon zerox-furai vijaythecoder webdevtodayjason zhsama iannuttall charles-adedotun; do
  for f in ~/massive-agent-repo/$dir/*.md; do
    [ -f "$f" ] || continue
    ln -sf "$f" "~/.claude/agents/$(basename "$f")"
  done
done

# 3. Restart Claude Code — agents are discovered at session start
```

## Browse before invoking — [AGENTS_CATALOG.md](AGENTS_CATALOG.md)

The catalog is a plain-English index of every agent: name, one-line description, and source. Agents are grouped into 28 categories (Security & Compliance, Backend Development, Frontend Development, AI/ML/LLM, Testing & QA, etc) so you can scan quickly.

## Parallel-dispatch — the high-leverage pattern

The single biggest performance win is **fanning out specialists in parallel via the Task tool** instead of doing multi-domain work serially. When a task touches ≥2 domains, dispatch all relevant specialists in **one message with multiple Task tool calls**, not separate sequential calls.

### Common patterns

- **PR review** → dispatch `code-reviewer` + `security-auditor` + `silent-failure-hunter` + `test-engineer` + `architecture-critic` in parallel
- **New feature** → `backend-developer` + `frontend-developer` + `database-optimizer` + `security-auditor` in parallel
- **Bug triage** → `legacy-analyst` + `silent-failure-hunter` + `code-explorer` in parallel
- **Performance issue** → `performance-engineer` + `database-optimizer` + relevant `*-pro` in parallel
- **Refactor** → `code-simplifier` + `architecture-critic` + `type-design-analyzer` in parallel

## When NOT to dispatch a specialist

- One-line edit — just do it
- Reading a single file — just Read
- Trivial questions

Specialists are for **work**, not lookups. Use them when ≥5 minutes of cross-file work would otherwise be serial.

## Deduplication strategy

When two source collections shipped an agent with the same `name:` field, we kept the higher-priority version:

1. Anthropic Official (first-party)
2. VoltAgent (curated, well-structured)
3. wshobson (broad coverage)
4. davepoon, 0xfurai, vijaythecoder (community)
5. Smaller collections (iannuttall, zhsama, etc)

Some agents from wshobson have plugin-prefixed names (e.g. `backend-development-backend-architect`) to avoid colliding with canonical Anthropic names — those are retained alongside the canonical versions.

## Attribution & Licenses

This is an aggregation. **All credit goes to the original authors.** Each agent file retains its source project's license. See [ATTRIBUTION.md](ATTRIBUTION.md) for the full list of upstream repos and licenses.

If you find an agent useful, **star the upstream repo** — that's where the work was done.

## Contributing

This repo mirrors public collections. Please contribute to the upstream repos directly. If you find a packaging bug here (broken file, missing attribution), open an issue.

## License

This aggregation is published under MIT, but **each `.md` file retains the license of its source repository**. See ATTRIBUTION.md for source licenses.
