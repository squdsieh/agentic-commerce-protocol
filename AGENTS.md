# agentic-commerce-protocol

## Agentic OS Workflow

This repository participates in the local Agentic OS vault at `/Users/saddamqudsieh/Documents/Agentic-OS-Vault`.

Startup order for Codex work:

1. Read `/Users/saddamqudsieh/AGENTS.md` or the active global Codex operating contract.
2. Read this file.
3. Read vault notes:
   - `02-Projects/agentic-commerce-protocol/Index.md`
   - `02-Projects/agentic-commerce-protocol/Current-State.md`
   - `02-Projects/agentic-commerce-protocol/Commands.md`
   - `02-Projects/agentic-commerce-protocol/Risks.md`
   - latest active context in `02-Projects/agentic-commerce-protocol/Handoffs.md`
4. Inspect current repo files, tests, package scripts, git state, and live systems before implementation or release claims.

Repo and live systems are stronger than vault notes. If Obsidian conflicts with code, command output, tests, provider dashboards, deployment state, or live behavior, update the stale note after verifying the stronger source.

## Project Source Of Truth

- Repo path: `/Users/saddamqudsieh/Documents/GitHub/agentic-commerce-protocol`
- Remote: `https://github.com/agentic-commerce-protocol/agentic-commerce-protocol.git`
- Primary branch: `main`
- Risk level: `medium`
- Source of truth: repo + protocol docs/tests

## Commands

Detected command routes from the current project scan:

- `cd /Users/saddamqudsieh/Documents/GitHub/agentic-commerce-protocol`
- `PATH="$HOME/.local/node-v22/bin:$PATH" pnpm validate:all`
- `PATH="$HOME/.local/node-v22/bin:$PATH" pnpm compile:schema`

Before claiming completion, run the smallest relevant verification gate first, then broaden based on risk.

## Knowledge Layers

- OKF: Use the OKF path recorded in the vault when it exists; otherwise use repo docs and source files directly.
- Graphify: Run `graphify update .` after code edits only when this repo has Graphify output or repo guidance requires it.
- Obsidian: use for routing, task packets, decisions, handoffs, and evidence pointers only.

## Safety

- Do not commit or write secrets, `.env*`, credentials, signing keys, provider exports, private records, generated caches, dependency folders, Graphify output, OKF output, or full repo copies into the vault.
- Stop at private credential prompts and report the exact next user-owned action.
- Keep changes scoped to the requested outcome and do not revert unrelated user work.
