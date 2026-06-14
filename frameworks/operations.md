# Operations: How We Work in Parallel

System for coordinating research agents and synthesizing findings into a decision.

---

## The Three Parallel Research Tracks

### Track 1: Subsector & Industry Research
**Agent assigned:** Industry/market researcher
**Owns:** Understanding which AEC subsectors have the highest density of great + underappreciated firms

**Tasks:**
1. Review [AEC Subsector Analysis](./aec-subsector-analysis.md) to understand scoring
2. For each high-signal subsector (Institutional, Engineering Specialists, Adaptive Reuse, Commercial Mixed-Use):
   - Identify 3-5 candidate firms within that subsector
   - Brief rationale for why they're interesting (known locally? recent transition? award history?)
3. Prioritize: Which subsector should we research deepest first?

**Output:** 
```
SUBSECTOR RESEARCH REPORT

Subsector: [Name]
Signal Score: [18-22]

Candidate Firms (prioritized):
1. [Firm Name] — [Brief reason: e.g., "university architect, strong local reputation, recent merger created positioning gap"]
2. [Firm Name] — [Brief reason]
3. [Firm Name] — [Brief reason]

Recommendation:
[Which subsector should we dive deepest on first, and why?]
```

**Timeline:** Start now. Report back in 1-2 days.

---

### Track 2: Candidate Deep Research
**Agent assigned:** Research analyst
**Owns:** Evaluating specific firms using the 2.5-hour Research Workflow

**Tasks:**
1. Wait for Track 1 to identify candidate firms
2. For each prioritized candidate, use [Research Workflow](./research-workflow.md) (2.5 hours per firm)
3. Document findings in a research note (see below)
4. Score on [Candidate Scorecard](./candidate-scorecard.md)
5. Report top 3-5 scoring firms

**Output:**
Create a research note file: `candidates/[Firm-Name].md`

Include:
- Overall score (0-24) and PASS/FAIL
- Summary (1-2 sentences)
- Key observation (the opening line you'd lead with)
- Scorecard breakdown (all 12 criteria rated)
- Portfolio highlights
- Competitive position
- The gap (quality vs. recognition)
- Disqualifying factors (if any)
- Confidence level
- Next steps

**Template:** See [Research Workflow](./research-workflow.md) > Output Template

**Timeline:** 2.5 hours per firm. Start with 3-5 candidates. Report back with scores.

---

### Track 3: Buyer Identification & Qualification
**Agent assigned:** Network researcher
**Owns:** Mapping AIA conference relationships and qualifying buyers

**Tasks:**
1. Document all AIA conference relationships (from Saul's notes, if available)
2. For each person met at AIA, use [Buyer Matching Framework](./buyer-matching-framework.md) to qualify
3. Rate each contact: High / Medium / Low buyer potential
4. For high-potential contacts, research their companies and projects
5. Document active pipelines and project timing
6. Report top 5-10 qualified buyers with sector/project focus

**Output:**
Create a buyer database file: `buyers/[Name]-[Company].md`

Include:
- Name, company, title, how met
- Decision authority level (High / Medium / Low)
- Active pipeline (Y/N) and project type
- Timeline (3mo / 6mo / 12mo)
- Openness to new relationships
- Initial take on buyer quality
- Next step (reach out / qualify further / pass)

**Template:** See [Buyer Matching Framework](./buyer-matching-framework.md) > Buyer Types & Matching Template

**Timeline:** Start now. Document all known AIA relationships. Report buyer list by end of 1st day.

---

## Synthesis Loop: When to Introduce Findings

### Checkpoint 1 (End of Day 1)
**Track 1 + Track 3 report:**
- Which high-signal subsector should we focus on first?
- Who are 3-5 qualified buyers from your AIA network?

**Action:** Review findings. Assign Track 2 to deep-research top candidates from Track 1's prioritized subsector.

---

### Checkpoint 2 (End of Research)
**Track 2 reports:**
- Top 3-5 firms scored on the scorecard
- Which firms pass (≥20)?

**Action:** For passing firms, match to buyers from Track 3. Make connections.

---

### Checkpoint 3 (Final Synthesis)
**All tracks synthesize:**
- One firm ≥20 on scorecard
- One qualified buyer matched to that firm
- Research notes documented
- Approach strategy ready

**Action:** Approach firm with buyer signal

---

## File Structure

```
frameworks/
├── README.md (this guide)
├── operations.md (this file)
├── candidate-scorecard.md
├── research-workflow.md
├── aec-subsector-analysis.md
├── buyer-matching-framework.md
│
├── candidates/
│   ├── [Firm-Name].md (research note from Track 2)
│   ├── [Firm-Name].md
│   └── ...
│
└── buyers/
    ├── [Name]-[Company].md (qualified buyer from Track 3)
    ├── [Name]-[Company].md
    └── ...
```

---

## Communication Protocol

Agents report findings back to the main hub (you) as:

1. **Research notes** (Markdown files in `candidates/` or `buyers/`)
2. **Summary report** (Brief message with key findings + recommendations)

**What the main hub (you) does:**
- Synthesizes across all three tracks
- Identifies passing candidates
- Matches firms to buyers
- Decides next actions
- Keeps momentum

**No handholding.** Agents move independently and report findings. The hub coordinates.

---

## Success Metrics

✓ **Track 1:** Subsectors prioritized, 3-5 candidates identified per subsector
✓ **Track 2:** Top candidates scored; at least one firm scoring ≥20
✓ **Track 3:** 5-10 qualified buyers identified and documented
✓ **Synthesis:** One firm + one buyer matched; approach ready

---

## Immediate Action Items

**For Track 1 (Subsector Research):**
- [ ] Review AEC Subsector Analysis framework
- [ ] Identify high-signal subsectors
- [ ] List 3-5 candidate firms per subsector
- [ ] Prioritize which to research first
- [ ] Report by EOD today

**For Track 3 (Buyer Identification):**
- [ ] Document all AIA conference relationships
- [ ] Qualify each contact using Buyer Framework
- [ ] Rate by buyer potential
- [ ] Report top 5-10 qualified buyers by EOD today

**For Track 2 (Deep Research):**
- [ ] Wait for Track 1 priority
- [ ] Start deep-dive on first 2-3 candidates
- [ ] Follow 2.5-hour Research Workflow
- [ ] Document findings in `candidates/` directory
- [ ] Score on Candidate Scorecard
- [ ] Report top scorers

---

## Notes for Agents

- **Be thorough but move fast.** 2.5 hours per candidate is the target. Depth matters, but momentum matters more.
- **Document as you go.** Don't wait until the end to write notes. Research note should be complete after the deep-dive.
- **Trust the frameworks.** The scorecard and workflow are designed to surface signal quickly. Follow them.
- **Surface the gap.** The most important output is: what's the one non-obvious observation about this firm that makes them a candidate? That's your opening line.
- **Match firms to buyers.** Don't just find great firms. Find great firms that have buyers waiting for them.

---

## Timeline

- **Day 1:** Subsector research + buyer identification complete. Candidates prioritized.
- **Day 2-3:** Deep research on top 3-5 candidates. Scoring complete.
- **Day 3-4:** Buyer matching. One firm + one buyer identified.
- **Day 4:** Approach ready. Saul makes introduction.

This can move faster. But don't sacrifice depth for speed. Signal > speed.
