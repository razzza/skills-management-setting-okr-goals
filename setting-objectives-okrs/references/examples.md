# OKR Examples & Reference Material

## KR Formats (Leading vs Lagging)

### Leading Indicators (steerable weekly; "driver" metrics)

Use to manage the work in real time. These should be influenceable by the team.

Examples:
- Funnel step conversion (activation %, trial-to-paid %)
- Adoption/usage (WAU/MAU for a feature, retention in week 1)
- Reliability drivers (error budget burn rate, MTTR, incident count)
- Quality drivers (escaped defects per release, test coverage proxy, rework rate)
- Throughput drivers (cycle time, lead time, WIP, SLA compliance)

### Lagging Indicators (true outcomes; "result" metrics)

Use to confirm impact. Often slower and noisier.

Examples:
- Revenue, margin, bookings
- Churn/retention at longer horizons
- NPS/CSAT (often delayed and multi-causal)
- Market share
- Annualized cost reduction

**Guideline:** Most Objectives should have at least 1 Leading KR (to steer) and 1 Lagging KR (to validate).

---

## Quality Bar (Visual Rubric)

| Dimension | Level 1 (Weak) | Level 2 (OK) | Level 3 (Strong) | Level 4 (Excellent) |
|---|---|---|---|---|
| **Focus** | 4+ objectives; reads like backlog | 3–4 objectives; still crowded | 1–3 objectives; clear priorities | Ruthlessly focused; tradeoffs explicit |
| **KR Quality** | Task/vibes KRs; not measurable | Mostly measurable; some fuzzy | Outcome-based; measurable; verifiable | Mix of leading+lagging; crisp and audit-proof |
| **Baselines & Data** | Missing baselines/data sources | Some baselines; inconsistent sources | Baselines + targets + sources for all | Automated, trusted sources; minimal reporting burden |
| **Ownership** | Unclear owners | Owners exist but ambiguous accountability | Clear owners for every KR | Ownership + backup + escalation paths |
| **Controllability** | KRs depend heavily on other teams | Mixed influence | Mostly controllable | Strong influence; dependencies contracted |
| **Anti-Gaming** | No counter-metrics | Counter-metrics listed for some KRs | Counter-metrics for all key KRs | Counter-metrics tracked and reviewed weekly |
| **Social Alignment** | Not reviewed; surprises later | Some stakeholder review | Dependencies aligned and confirmed | Cross-team alignment reduces conflict and thrash |

---

## Discovery OKRs (for uncertainty-heavy work)

Use when work is exploratory and outcomes are unknown upfront.

**Objective:** *"De-risk <big bet> by validating <key assumptions>."*

Key Results (evidence of learning/decisions):
- "Conduct 12 interviews + synthesis; identify top 3 user needs with evidence."
- "Run 2 experiments; reach ≥X activation OR conclude non-viable with rationale."
- "Decision made: proceed/pivot/stop with documented rationale."

Still measurable — just focused on validated learning and decisions.

---

## Common Pitfalls (and fixes)

| Pitfall | Fix |
|---------|-----|
| "More OKRs = more ambition." | Fewer OKRs = more outcomes. |
| KRs controlled by other teams. | Use influence metrics or formalize dependency commitments. |
| Sandbagging targets. | Use baselines + historicals; calibrate across teams. |
| OKRs become a performance rating tool. | OKRs measure outcomes; performance includes behaviors + context + growth. |

---

## Metrics: Are Your OKRs Working?

**Leading:**
- Weekly KR updates happen (with numbers + confidence)
- Fewer priority conflicts in planning meetings
- Faster decision-making on tradeoffs

**Lagging:**
- Higher hit rate on critical outcomes
- Reduced mid-cycle thrash
- Better cross-team predictability

---

## Full Individual Goal Example (Engineering Manager)

```
BUSINESS / PEOPLE GOALS:

Goal 1 (Business):
  Team Objective: Strengthen platform reliability and engineering excellence
  Team KR: Reduce P0 incident rate by 40% and improve MTTR from 4h → 2h
  Goal: Improve product quality by reducing bugs through automated testing and code reviews.
  Success Measure: Bug count FROM current → TO 30% reduction by Q4. P0 issues resolved
  in 3 days (from 5), P1 in 2 weeks (from 4).
  Impact: Higher customer satisfaction, fewer support tickets, stronger reliability.
  My role: Get team access to testing tools, provide training by end of March, partner with
  QA leads to schedule quality reviews.

Goal 2 (Business):
  Team Objective: Accelerate customer-driven product innovation
  Team KR: Ship 2 customer-validated features to GA with ≥70% adoption
  Goal: Reduce time-to-market for new features by adopting agile methods.
  Success Measure: Feature cycle time FROM current → TO 20% reduction by Q3.
  Impact: Faster delivery to customers, incremental revenue from on-time releases.
  My role: Facilitate agile workshops by April, require project leads to host bi-weekly
  retros focused on customer feedback and value delivery.

Goal 3 (People):
  Team Objective: Build organizational capacity to scale
  Team KR: Increase senior technical leadership bench from 2 → 5
  Goal: Foster innovation and grow team capability through experimentation.
  Success Measure: Quarterly hackathons with ≥60% participation, 1+ idea shipped to production.
  Impact: Surfaces high-impact solutions, strengthens experimentation culture.
  My role: Host hackathons, allocate 5-10 hours/quarter for team to explore new technologies
  and attend conferences.

BARRIERS TO REMOVE:
  Barrier 1: Tech Debt
    Action: Address 50% of existing technical debt by Q3 to ensure maintainability and scalability.
    Support needed: Allocation of time and resources for refactoring and code improvements.
  Barrier 2: Skill Gaps
    Action: Identify and bridge skill gaps; provide targeted training for 2 team members with
    performance issues; hire 2 approved headcount by Q2.
    Support needed: $10K budget for training programs.

PERSONAL DEVELOPMENT:
  Skill to develop: Managing performance issues with genuine, real-time feedback.
  Company Value: Demonstrate high standards and accountability while supporting growth.
  How I will develop it: Set up twice-a-week code review sessions with underperforming team
  members to coach with real examples. Ask a People/HR partner or trusted mentor for feedback
  on my coaching approach.
  How I will know it worked: Team members show measurable improvement in code quality;
  skill gap addressed by Q3.

CROSS-FUNCTIONAL COLLABORATION:
  Partnership: Customer Success team
  Commitment: Bi-weekly standups to review customer feedback in real time; 2 CS partners
  included in design sprints; SLA of fixes to production within 3 weeks for P0, 5 weeks for P1.

What I won't do this cycle: New platform migration; non-critical feature requests from
non-strategic accounts.
```

---

## Manager Goal Reflection Examples

After individuals submit their goals, the manager reviews and responds. These examples show how managers confirm, redirect, and add context.

### Example 1: Confirming and sharpening goals

"Thank you for sharing your goals for the upcoming year. I appreciate the thought and detail you've put into them. I'm in agreement with your objectives and believe they align well with our overall team and org's goals. Here's a summary of what we discussed and areas where I think you can drive even greater impact:

Your goal to increase new customer acquisition is ambitious. To make this happen, we discussed focusing on building deeper relationships with potential clients. Consider industry events and networking opportunities to expand your reach. Leverage data analytics to identify high-potential leads to target your efforts more effectively.

To boost revenue, I would like to see you focus on strengthening your negotiation skills. While attending workshops is a great start, practicing these skills in real-world scenarios is critical. Role-playing different negotiation scenarios with colleagues can provide practical experience and build your confidence.

Overall, I'm confident in your ability to achieve these goals and make a significant impact on our team's success. I'm here to support you every step of the way."

### Example 2: Redirecting where misaligned

"Thank you for sharing your goals for the upcoming year. I appreciate the effort you've put into outlining them and the work that went into organizing with our stakeholders. You are a leader on our team, and we discussed how your role is evolving since being promoted. There was some misalignment from our conversation on how you'll execute on your goals, so I am summarizing below where we landed:

Enhance Product Quality: Your goal to reduce critical bugs by 30% is great. I would like you to set and share quarterly targets so our stakeholders know where we are headed, why, and how we are progressing. As a senior engineer on the team, it's important to bring others along early and often, otherwise we tend to see issues crop up and cause delays. I'd also like you to mentor junior team members on best coding practices. Take an active role in organizing and participating in hackathons and share your learnings with the team regularly.

Accelerate Development Cycles: Reducing time-to-market by 20% is aligned with our objectives. We discussed that you will take the lead in organizing stand-up meetings and retrospectives, with a focus on accountability: solve problems by making effective decisions and moving swiftly to execution.

Let's add this topic to our running 1:1 agenda to track progress and address any challenges you might encounter. I'm here to support you every step of the way."
