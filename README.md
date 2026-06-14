# Fletcher

Find genuinely great but underappreciated companies and help them become what they deserve.

---

## Quick Navigation

**New here?** Start with the [Methodology](./methodology_identifying_great_underappreciated_companies.md) — that's the full playbook.

**Core entry points:**
- **[Methodology](./methodology_identifying_great_underappreciated_companies.md)** — Full end-to-end playbook (all five stages)
- **[Stage 0: Sourcing](./methodology_identifying_great_underappreciated_companies.md#stage-0-sourcing--discovery)** — How we find candidates
- **[Stage 1: Evaluation](./methodology_identifying_great_underappreciated_companies.md#stage-1-evaluation--is-this-a-good-fit)** — The three gates (Greatness, Blocking Factor, Addressability)
- **[Stage 2: Approach](./methodology_identifying_great_underappreciated_companies.md#stage-2-approach--outreach)** — How to contact them
- **[Stage 3: Pitch](./methodology_identifying_great_underappreciated_companies.md#stage-3-value-proposition--pitch)** — What we offer
- **[Stage 4: Execution](./methodology_identifying_great_underappreciated_companies.md#stage-4-engagement--execution)** — How we work together
- **[Stage 5: Learning](./methodology_identifying_great_underappreciated_companies.md#stage-5-learning--refinement)** — How we improve the method

---

## The Methodology

We find great companies that are stuck for fixable reasons, then help them get unstuck. The process has five stages:

1. **Sourcing** — Find candidates via research agents, networks, events, public signals
2. **Evaluation** — Three gates (Greatness, Blocking Factor, Addressability)
3. **Approach** — Contact the founder in a way that opens the door
4. **Pitch** — Clarify what we offer and why it fits them
5. **Execution** — Work together for 2-3 months; they own the outcome

**This methodology is self-learning:** Each engagement teaches us something. We update the playbook continuously based on what works and doesn't.

---

## Project Structure

```
fletcher/
├── methodology_identifying_great_underappreciated_companies.md ← CORE PLAYBOOK
│                                                                 (Read this first)
│
├── vault/                         ← Company knowledge (git submodule)
│   ├── Company/strategy.md        ← Strategic direction
│   ├── Company/goals.md           ← Weekly priorities
│   └── references/                ← Shared knowledge
│
├── engagement-logs/              ← Documentation from each engagement
│   └── [company-name]/           ← Folder per engagement
│       ├── research-notes.md     ← What we learned about them
│       ├── blocking-factor.md    ← The specific problem
│       ├── engagement-log.md     ← How it went
│       └── learnings.md          ← What this taught us
│
└── [Add product code here]
```

**The methodology document is the source of truth.** It lives at the repo root and gets updated continuously as we learn what works.

---

## For Agents

**Get started:**
1. Read the [Methodology](./methodology_identifying_great_underappreciated_companies.md) end-to-end (20-30 min)
2. Focus on the stage you're working on (Sourcing, Evaluation, Approach, Pitch, or Execution)
3. Follow the specific gates/frameworks in that stage
4. Document your findings and learnings
5. Update the methodology if you discover something that changes it

**Key principles:**
- Work autonomously; ask only if direction is unclear
- The methodology is the source of truth; follow it consistently
- Document as you go; engagement learnings go in `engagement-logs/[company-name]/`
- If you find the methodology wrong or incomplete, update it (not secretly; mark changes clearly)

---

## How This Works

1. **Sourcing Agent** — Finds candidates using the channels defined in Stage 0
2. **Evaluation Agent** — Runs each candidate through the three gates (Stage 1)
3. **Approach Agent** — Makes contact and schedules conversations (Stage 2)
4. **Pitch Agent** — Clarifies the value prop and gets commitment (Stage 3)
5. **Execution Agent** — Works with the company for 2-3 months (Stage 4)

**All agents update the methodology continuously** as they learn (Stage 5)

---

## Context

**Company strategy:** See [vault/Company/strategy.md](./vault/Company/strategy.md)

**Weekly goals:** See [vault/Company/goals.md](./vault/Company/goals.md)

**Saul's voice & rules:** See `.claude/CLAUDE.md` (loaded per Claude Code session)

**Current state:** Methodology 1.0 is written and documented. Ready for first engagements. Updates will happen as real companies are sourced and evaluated.

---

## The Bet

**Relationship-first, conviction-driven model.** Find one genuinely great company. Understand them deeply. Approach with understanding of their blocking factor. Commit fully to helping them solve it.

This is not a service business. It's a partnership business. We win when they win. The methodology is how we consistently find and help the right ones.

---

See `.claude/CLAUDE.md` for Claude Code configuration and project-specific instructions.
