# ruins-source-lock

Use this skill when a RUINS paper needs to move from draft toward stable working
paper or publication-ready status by locking source support for current claims.

## Inputs

- `paper_id`: package under `research/publications/`
- `claim_scope`: current paper claims to lock
- `target_status`: `stable-working-paper` or `publication-ready`

## Required Reads

Before source-locking, read:

1. `research/publications/<paper_id>/paper.md`
2. `source-map.md`
3. `claim-audit.md`
4. `refusal-register.md`
5. `QUALITY_RUBRIC.md`
6. `docs/capability-expansion.md`

## Source Protocol

1. Prefer primary, official, or peer-reviewed sources for current claims.
2. Use public/heritage summaries only with source labels and clear limits.
3. Separate source types: direct material, direct textual, copied textual,
   reported, translated, reconstructed, public memory, and secondary synthesis.
4. Lock only what the paper currently says. Do not expand claims just because a
   source is interesting.
5. Add page or line anchors before publication-ready status when exact values,
   translations, institutional claims, population figures, dates, or causal
   explanations are used.

## Required Artifacts

| File | Requirement |
|---|---|
| `source-lock.md` | Locked sources, allowed uses, limits, locked claim wording, and paper use rules. |
| `page-anchor-audit.md` | Page/line anchors for current claims when publication-ready status is requested. |
| `claim-audit.md` | Updated claim grades after locking. |
| `paper.md` | Source-lock note and bounded wording. |
| `reviews/ROLE_REVIEW.md` | Updated P2/P3 findings. |
| `reviews/SCORECARD.md` | Updated score and caps. |

## Promotion Rules

- No source lock: maximum `42/50`.
- Source lock but open P2 findings: maximum `44/50`.
- Page anchors complete and no open P2 findings: publication-ready is allowed
  if the score is at least `45/50`.
- New source claims that are not locked remain future-scope P3s or lower the
  score.

## Output Checklist

- [ ] Locked sources have allowed uses and limits
- [ ] Claims are source-specific, not harmonized into false certainty
- [ ] Page-anchor audit exists when needed
- [ ] Refusal register still blocks overclaims
- [ ] Scorecard caps match rubric rules
- [ ] Future-scope claims are separated from current paper scope
