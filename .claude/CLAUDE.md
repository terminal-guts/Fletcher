# Fletcher — Product Codebase

## Company & Strategy Context

This is the product for Fletcher. Company context loads automatically:

- @./vault/Company/strategy.md — current strategy and direction
- @./vault/Company/goals.md — goals and OKRs
- @./vault/references/index.md — shared facts, decisions, research

Saul and Adam's personal context and voice load from global `~/.claude/CLAUDE.md` (set once, applies to all projects).

**Setup:** The vault is included as a git submodule. After cloning, run `git submodule update --init` to fetch it.

## Build & Deploy

[Add project-specific conventions, build commands, deployment process, stack decisions here]

## Using the knowledge base during development

**For static imports:** the strategy and goals files above load at session start. This covers 95% of use cases.

**For dynamic vault search (optional):** if you need to search the vault during a session, set up the Obsidian MCP server (see ~/.claude/CLAUDE.md for setup steps).

## Project structure

- `src/` — source code
- `tests/` — test suite
- `.claude/` — Claude Code config (this file)

---

**Note:** Changes to product code stay in this repo's git history. Changes to company knowledge go in the separate vault.
