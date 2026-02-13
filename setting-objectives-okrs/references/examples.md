# OKR Examples (Short Reference)

## KR styles (drivers vs outcomes)

### Driver metrics (weekly levers)

Use these to steer the work while you still have time to change course. The team should be able to move them directly.

Examples:
- Step rates (activation %, trial→paid %)
- Feature use (WAU/MAU, week‑1 retention)
- Reliability levers (error budget burn, MTTR, incidents)
- Quality levers (escaped bugs/release, rework %, test signal)
- Flow levers (cycle/lead time, WIP, SLA hit rate)

### Outcome metrics (end results)

Use these to confirm real impact. They usually move slower and have more noise.

Examples:
- Revenue / bookings / margin
- Longer-term retention or churn
- NPS / CSAT (often delayed, many causes)
- Share in market
- Annual run‑rate savings

**Rule of thumb:** For each Objective, include at least one driver KR (steer) and one outcome KR (prove).

---

## Quality bar (quick rubric)

| Area | Weak | OK | Strong | Great |
|---|---|---|---|---|
| **Focus** | Too many “priorities” | Still crowded | 1–3 clear bets | Explicit tradeoffs and “won’t do” |
| **KR wording** | Tasks / vibes | Mostly measurable | Clear outcomes + numbers | Balanced drivers + outcomes; audit‑ready |
| **Baselines** | None | Partial | Baseline + target + source | Automated, trusted sources; low overhead |
| **Ownership** | No single owner | Owner exists, fuzzy | Owner per KR | Owner + backup + escalation |
| **Control** | Depends on others | Mixed | Mostly in your control | Dependencies are agreed/contracted |
| **Anti‑gaming** | No guardrails | Some guardrails | Guardrails on key KRs | Guardrails reviewed weekly |
| **Alignment** | Not socialized | Light review | Dependencies confirmed | Cross‑team plan reduces churn |

---

## Discovery OKRs (when you don’t know yet)

Use this pattern for exploration where the answer isn’t known upfront.

**Objective:** *Reduce risk on \<big bet> by testing \<assumptions>.*

KRs (evidence, not activity for activity’s sake):
- Interview 12 users; synthesize; top 3 needs with proof.
- Run 2 experiments; hit ≥X activation **or** document why it won’t work.
- Make a decision (ship / pivot / stop) with a written rationale.

Still measurable — the measurement is learning + decisions.

---

## Common traps (and better alternatives)

| Trap | Better |
|---|---|
| “More OKRs means we’re ambitious.” | Fewer bets, stronger outcomes. |
| KRs owned by other teams. | Track your influence, or lock the dependency. |
| Targets are too easy. | Start from baseline + history; calibrate with peers. |
| OKRs become a rating system. | OKRs are outcomes; performance includes scope, behaviors, growth. |

---

## Signs your OKRs are helping

**Early signals:**
- Weekly updates happen (numbers + confidence)
- Fewer priority fights in planning
- Faster calls on tradeoffs

**Later signals:**
- Key outcomes land more often
- Less mid‑cycle churn
- Better cross‑team predictability

---

## Short individual goal example (Eng Manager)

```text
GOALS

1) Reliability
Objective: Improve platform stability.
KRs: P0 incidents -40%; MTTR 4h→2h.
My part: unblock tooling + training by Mar; set weekly review cadence.

2) Delivery speed
Objective: Ship customer-validated value faster.
KRs: 2 features to GA with ≥70% adoption; cycle time -20% by Q3.
My part: run agile workshops by Apr; enforce bi-weekly retros with action items.

3) Team growth
Objective: Grow senior technical leadership.
KRs: senior bench 2→5; 1 hackathon idea shipped/quarter.
My part: host hackathons; carve out 5–10 hrs/quarter for exploration.

BLOCKERS
- Tech debt: cut 50% by Q3; need time allocation.
- Skill gaps: targeted coaching for 2 people; hire 2 by Q2; $10k training.

DEVELOPMENT
Skill: give real-time performance feedback.
Plan: 2×/week coaching via code review; get mentor/HR feedback.
Proof: measurable quality lift by Q3.

COLLAB
Partner: Customer Success.
Cadence: bi-weekly sync; fixes SLA: P0 ≤3 wks, P1 ≤5 wks.

WON’T DO
- Major platform migration; low-value feature asks.
```

---

## Manager response examples (short)

### Example 1: Agree + tighten

> I’m aligned on the goals. Two tweaks: add quarterly checkpoints for acquisition, and pick one “driver” KR you can move weekly. For revenue, practice negotiation in real deals (prep + debrief), not just training. Let’s review progress monthly.

### Example 2: Misalignment + reset

> The targets make sense, but execution needs to change. For bug reduction: publish quarterly targets and bring stakeholders in earlier; add mentoring as part of the plan. For cycle time: you lead standups/retros with clear accountability and faster decisions. We’ll track this in our 1:1.
