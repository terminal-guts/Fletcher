# Manager Log: Fletcher Project Oversight

**Role:** Audit, manage, clarify. Not building. Continuously updated.

**For agents:** Check this document for management guidance, clarifications, and issues you should be aware of.

---

## Current Status (2026-06-14)

**North Star:** `methodology_identifying_great_underappreciated_companies.md` is the canonical methodology.

**Key Decision:** The methodology document (5 stages: Sourcing → Evaluation → Approach → Pitch → Execution & Learning) is THE framework. All agent work aligns to this.

**Active Research Work:**
- 2 projects in `projects/research/` (eSeis, petrochemical-specialists-phase2) using OLD framework
- These need re-alignment or clarification on whether old framework is still valid

---

## Issues Flagged for Resolution

### Issue 1: Existing Research Using Wrong Framework
**Status:** NEEDS CORRECTION

Multiple research projects were evaluated using the vault strategy's 6+6 criteria (great + underappreciated) instead of the canonical methodology:

**Affected projects:**
- `projects/research/eseis-first-contact-strategy.md` 
- `projects/research/petrochemical-specialists-phase2.md`

**Problem:** Both use vault strategy framework (great signals + underappreciated signals), but the canonical methodology prescribes a different approach:
- Gate 1: Financial screens + moat assessment
- Gate 2: Blocking factor identification
- Gate 3: Addressability & opportunity sizing

**Action needed:** 
- [ ] Clarify with Saul: Is eSeis evaluation still valid, or should it be re-evaluated using the methodology gates?
- [ ] If re-evaluation needed, determine: Do they pass Gate 1 (financial + 2+ moats)? What's the blocking factor?

---

### Issue 2: Methodology Document Has Gaps
**Status:** BLOCKING — Agents cannot fully execute without clarity

**Missing clarity:**

1. **Financial Screens for Private Companies (Gate 1.1)**
   - Methodology requires: ROE > 12%, ROIC > WACC + 2%, Operating CF > 80% of Net Income
   - Problem: Most private companies don't publish these metrics
   - Needed: Proxy methods or alternative screening for private companies
   - Recommendation: "If public data unavailable, estimate using [method]" or "For private companies, use revenue growth + employee retention as proxy"

2. **Moat Scoring Edge Cases (Gate 1.2)**
   - Rule: "Company must have at least 2 moats scored as 'Strong'"
   - Gap: What if company has 2 weak + 1 strong? 3 weak? What about borderline "Weak/Strong"?
   - Needed: Clearer scoring guidance or tiebreaker rules

3. **Blocking Factor Validation Threshold (Gate 2.3)**
   - Section lists 4 YES/NO questions: specific? solvable 3-6mo? unlocks growth? not their competency?
   - Gap: If 3 are YES and 1 is NO, is that auto-reject or proceed with caution?
   - Needed: "If all 4 are YES → proceed. If any NO → reject" OR "If 3+ are YES → proceed"

4. **Outreach Follow-up Protocol (Stage 2)**
   - Methodology prescribes 3 outreach paths but no guidance on:
     - How many touches before closing the loop?
     - Follow-up cadence (wait 1 week before follow-up? 2 weeks?)
     - When to move to next candidate?
   - Needed: "If no response after [X] days, send one follow-up. If still no response after [Y] days, move to next candidate."

5. **Pricing/Engagement Structure (Stage 3.2)**
   - Methodology says: "Pricing/structure: TBD"
   - Problem: Agents can't pitch if pricing is undefined
   - Needed: Saul to clarify: Fixed fee? Time + materials? Equity stake? Success bonus? Ranges?

6. **Sourcing Channel Efficiency (Stage 0.1)**
   - Listed channels "in priority order" but no data on:
     - Expected hit rate per channel (what % of sourced candidates pass evaluation?)
     - Time investment per channel (hours/month to run each?)
     - How to know if a channel is working or should be shut down?
   - Needed: "Track conversion rate per channel. Discontinue if <[X]% pass evaluation."

---

### Issue 3: Methodology Doesn't Reference Vault Context
**Status:** CLARITY NEEDED

Methodology stands alone but doesn't explain:
- Why Fletcher exists (vault strategy: find one genuinely great underappreciated company, go all in)
- What Saul's actual capabilities are beyond "sales, ops, tech, regulatory"
- Whether there's an industry focus or truly open to any sector
- What "underappreciated" means (methodology mentions "stuck for fixable reasons" but not the quality/recognition gap)

**Action needed:**
- [ ] Clarify: Is methodology intentionally broader than vault strategy? Or should it reference the vault?
- [ ] If broader: Document the relationship (vault = initial AEC focus, methodology = general framework)

---

### Issue 4: "Underappreciated" Not in Gate 1
**Status:** POTENTIAL MISALIGNMENT

Vault strategy emphasizes finding "genuinely great BUT underappreciated" companies (quality > recognition gap).

Methodology's Gate 1 checks "Greatness" (financial + moat) but doesn't explicitly check for "underappreciated."

**Questions:**
- Is underappreciation implicit in the blocking factor (i.e., if they're great but stuck, they're by definition underappreciated)?
- Or should Gate 1 have a sub-check: "Are they currently underappreciated?" (low visibility, locally known, peer recognition > market recognition)?

**Saul to clarify:** Do we only pursue genuinely underappreciated companies, or are great-but-already-known companies also targets if they have solvable blocking factors?

---

## Clarifications Needed from Saul

1. **eSeis Status:** Valid under new methodology or needs re-evaluation?
2. **Methodology Scope:** Is it intentionally broader than vault strategy?
3. **Underappreciation:** Required gate or implicit in blocking factor?
4. **Pricing:** What's the engagement cost/structure?
5. **Financial Proxies:** How to screen private companies without public data?

---

## Agent Guidance (Check Here for Direction)

### For Sourcing Agents
- Use the 5 sourcing channels in Stage 0.1
- Document every sourced candidate with the Stage 0.2 checklist
- Track which channel produced each candidate (we'll measure effectiveness)
- Expect to hear back on financial proxy methods for private companies soon

### For Evaluation Agents
- **Use the three-gate methodology:** Gate 1 (Greatness) → Gate 2 (Blocking Factor) → Gate 3 (Addressability)
- **NOT the vault strategy's 6+6 framework.** (That's outdated for this project.)
- For Gate 1.1 (financial screens): If public data unavailable, flag to manager before scoring
- For Gate 2.3 (blocking factor validation): If fewer than 4 YES answers, flag to manager before rejecting
- Document everything; we learn from each evaluation
- If you find research that was done with the old framework, flag it to manager for clarification

### For Outreach Agents
- Use Stage 2 outreach templates
- Wait for manager guidance on follow-up cadence before sending
- Don't pitch pricing/structure until manager provides it (Stage 3.2)

---

## Decisions Made

- **Canonical Methodology:** `methodology_identifying_great_underappreciated_companies.md` is the source of truth
- **Vault Strategy Status:** Reference context, not the active evaluation framework
- **Manager Role:** Audit and clarify gaps; not building frameworks

---

## Next Steps

1. **Saul clarifies the 5 issues above** (pricing, financial proxies, underappreciation requirement, eSeis status, scope)
2. **Manager updates methodology document** with missing clarity (private company proxies, scoring thresholds, follow-up protocol)
3. **Agents begin sourcing** with clear channels and tracking
4. **Manager audits first evaluations** to ensure gate logic is applied correctly

---

### Issue 5: Minor Naming Inconsistencies (README vs Methodology)
**Status:** MINOR - Low priority

Stage names differ slightly:
- README: "Stage 3: Pitch" vs Methodology: "Stage 3: Value Proposition & Pitch"
- README: "Stage 4: Execution" vs Methodology: "Stage 4: Engagement & Execution"

**Fix:** Update README stage names to match methodology exactly for consistency.

---

### Issue 6: Engagement Logging Structure Mismatch
**Status:** CLARITY NEEDED

**Problem:** 
- README mentions: "engagement logs go in `engagement-logs/[company-name]/`"
- Actual research: stored in `projects/research/[name].md`
- Directory doesn't exist: no `engagement-logs/` folder in repo

**Should we:**
1. Create `engagement-logs/` structure as README prescribes?
2. Keep using `projects/research/` and update README?
3. Split: research in `projects/research/`, engagement logs elsewhere?

---

## Tracking

- **eSeis:** Waiting for clarification on methodology (re-evaluate or valid?)
- **petrochemical-specialists-phase2:** Not yet audited; check after eSeis clarity
- **Methodology gaps:** 6 blocking issues documented above
- **Engagement logging:** Structure mismatch between README and actual repo

---

---

## Audit Summary (2026-06-14)

**Status:** Manager oversight structure in place. Methodology is clear and actionable, but has gaps that block full agent execution. Existing research projects need re-alignment.

**Critical (blocks agent work):**
1. Framework mismatch: existing research using vault strategy, not methodology
2. Pricing/engagement structure undefined (Stage 3)
3. Financial proxies for private companies undefined (Gate 1)

**Important (needed for clarity):**
4. Blocking factor validation threshold unclear (Gate 2.3)
5. Outreach follow-up protocol missing (Stage 2)
6. Sourcing channel tracking undefined (Stage 0)

**Minor:**
7. Engagement logging structure mismatch
8. Stage naming consistency between README and methodology

**What's working well:**
- Clear five-stage structure
- Good decision trees and templates
- Learning/iteration baked in
- Autonomy guidance for agents

**Next action:** Saul clarifies the 5 critical questions in "Clarifications Needed from Saul" section above.

*Last updated: 2026-06-14*
*Manager: Ongoing audit and clarification role*
