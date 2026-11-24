# Copilot Instructions

> **Stub:** The full Copilot instructions have moved. See the path below.

## Where to Find the Full Content

```
platform-adapters/agent-tools/github-copilot/copilot-instructions.md
```

This stub remains at `.github/copilot-instructions.md` because GitHub auto-discovers it from that path. The adapter's [`quickstart.md`](../platform-adapters/agent-tools/github-copilot/quickstart.md) explains how to copy the full content here when adopting this template in a downstream repo.

## Why This Moved

This project uses a three-layer adapter architecture: a universal core, platform-specific adapters
(`platform-adapters/`), and optional tool-specific files like this one. See `AGENTS.md` in the
repository root — it is the universal entry point for all AI agents and contributors.

## Working Preferences for This Repository

- **Verify, don't guess.** For factual or "does X exist / support Y" questions, check sources (docs, the repo, the web) before answering. If something can't be verified, say so.
- **Return literal values.** When asked for a link, URL, command, path, or ID, give the exact value, not a description of how to find it.
- **Elicit success criteria; don't expect them up front.** Criteria often emerge during the work. For open-ended or ambiguous tasks, propose success criteria and 2–3 options before acting, then refine them from feedback. When an answer misses, state the assumption it was based on.
