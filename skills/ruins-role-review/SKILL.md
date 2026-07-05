# ruins-role-review

Use this skill to run ASHLAR's RUINS role review and score a paper.

## Inputs

- `paper_id`: package under `research/publications/`
- `round`: review round or reason, such as `first`, `source-lock`, or
  `publication-review`

## Required Reads

Before reviewing, read:

1. `.roles/ROLE.md`
2. Each role file in `.roles/panel/`
3. `QUALITY_RUBRIC.md`
4. `docs/capability-expansion.md`
5. The full paper package, including registers and source-lock files if present

## The Five Roles

| Role | Core question |
|---|---|
| Fragment Custodian | Are the surviving traces and source conditions classified correctly? |
| Absence Historian | Does the paper distinguish loss event, loss process, damaged custody, and later memory? |
| Reconstruction Skeptic | Do claims, models, translations, restorations, and numbers outrun evidence? |
| Cultural Memory Reader | Is later memory treated as afterlife evidence rather than original-state proof? |
| Sibling Boundary Editor | Does the paper hand off non-RUINS work instead of absorbing it? |

## Review Protocol

Write or update:

- `reviews/ROLE_REVIEW.md`
- `reviews/SCORECARD.md`

The role review must include:

1. panel findings by role,
2. P1 findings,
3. P2 findings,
4. P3/future-use findings,
5. ASHLAR decision.

The scorecard must include:

1. score and band,
2. caps,
3. dimension scores,
4. blocking findings,
5. open P2 findings,
6. next lift.

## Scoring Discipline

- Apply automatic caps exactly.
- Do not let a strong topic compensate for weak source posture.
- Do not raise above `44/50` while open P2 findings remain.
- Treat future-scope work as P3 only if current claims are already bounded.
- If a review exposes a repeated method gap, invoke `ruins-method-evolve`.

## Output Checklist

- [ ] All roles represented
- [ ] Severity levels assigned
- [ ] Score dimensions add to stated total
- [ ] Caps match `QUALITY_RUBRIC.md`
- [ ] Next lift is actionable
- [ ] Method gaps are routed to `ruins-method-evolve`
