# Capability Promotion Packet

Status: active ASHLAR checklist

Use this packet when a paper promotes a RUINS capability from candidate to
active, or from active to core. It keeps capability promotion quick while
requiring enough evidence that the registry remains useful.

## When To Use

Create or update a promotion packet when:

- a publication-ready paper introduces a new gate, register, cap, or refusal
  pattern;
- a role review names a reusable evidence pressure;
- exact-claim work is being demoted from P2 blocker to P3 future gate because
  the current paper refuses that claim surface;
- a capability appears in two papers and may become core; or
- `QUALITY_RUBRIC.md` gains a case-derived check or automatic cap.

The packet may live inside the paper package as `capability-promotion.md` when
the promotion is paper-specific. For cross-case upgrades, record the decision
directly in `docs/capability-expansion.md` and cite the triggering papers.

## Acceptance Criteria

| Criterion | Required question |
|---|---|
| Overclaim pressure | What exact claim would readers be tempted to overstate? |
| Control artifact | Which gate, register, source lock, page audit, refusal, or boundary rule controls it? |
| Review evidence | Which scorecard or role review names the capability or boundary? |
| Scope behavior | Does the current paper make the claim, refuse it, or hand it to a sibling system? |
| Promotion state | Is the capability candidate, active, or core after this review? |
| Rubric impact | Does this change future scoring or only the capability registry? |

## Fast Promotion Template

```text
# Capability Promotion: <capability title>

Capability id: ruins-capability:<slug>
Trigger paper: <paper id>
Promotion: Candidate -> Active | Active -> Core
Date: YYYY-MM-DD
Owner: ASHLAR

## Overclaim Pressure

<Name the tempting overclaim this capability prevents.>

## Control Artifact

| Artifact | Path | What it controls |
|---|---|---|
| <gate/register/review> | <relative path> | <claim boundary> |

## Review Evidence

| Review surface | Finding |
|---|---|
| ROLE_REVIEW.md | <role finding or ASHLAR decision> |
| SCORECARD.md | <score/cap/next-lift evidence> |

## Scope Decision

Current paper permission:
- Allowed:
- Refused:
- Future P3:
- Sibling handoff:

## Registry Change

Update `docs/capability-expansion.md`:
- State:
- Promotion basis:
- First paper:

Update `docs/rubric-amendments.md` if scoring semantics changed.
Update `QUALITY_RUBRIC.md` only if future score caps or checks changed.
```

## ASHLAR Decision Rule

Promote quickly when the control artifact is real. Do not wait for a second
paper if the first reviewed paper already exposes a distinct RUINS evidence
condition and the promotion prevents a concrete overclaim.
