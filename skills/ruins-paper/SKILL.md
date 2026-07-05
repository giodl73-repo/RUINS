# ruins-paper

Use this skill to create or extend a RUINS paper package under
`research/publications/<paper-id>/`.

## Inputs

- `paper_id`: kebab-case paper id, usually `panel-...`
- `track`: RUINS track name
- `case`: the ruin, corpus, technique, site, institution, or memory surface
- `target_status`: usually `working-draft` for a new paper

## Required Reads

Before writing or editing the package, read:

1. `MODULE.md`
2. `QUALITY_RUBRIC.md`
3. `docs/capability-expansion.md`
4. `.roles/ROLE.md`
5. One publication-ready sibling package with the closest evidence condition

## Required Package Files

Create or update these files:

| File | Purpose |
|---|---|
| `README.md` | Local navigation and package status. |
| `_panel.yaml` | Paper-specific role focus. |
| `plan.md` | Research question, core argument, boundaries, and next work. |
| `paper.md` | Draft paper with evidence, loss, reconstruction, memory, refusals, and handoffs. |
| `source-map.md` | Metadata-only source and evidence surface map. |
| `chronology.md` | Loss-event, loss-process, custody, and memory layers. |
| `claim-audit.md` | Conservative claim grades and phrases to challenge. |
| `refusal-register.md` | Operational claims the paper blocks. |
| `cultural-memory.md` | Later memory as afterlife evidence. |
| `sibling-boundary.md` | Handoffs to MAXIM, FONTES/MUNDUS, CANON, PORTO, RITE, GENES, CERES, or LUCIA. |
| `reviews/ROLE_REVIEW.md` | First ASHLAR role-panel review. |
| `reviews/SCORECARD.md` | First score against `QUALITY_RUBRIC.md`. |

## Authoring Protocol

1. Identify the paper's distinct RUINS condition. Do not pick a case only
   because it is interesting.
2. Name what survives, what is missing, what is reconstructed, what is later
   memory, and what must be refused.
3. Keep source-map work metadata-only until `ruins-source-lock` is run.
4. Give the paper a conservative first score. A new paper without source lock
   cannot exceed `42/50`; without role review it cannot exceed `37/50`.
5. Update root `README.md` and `research/publications/README.md` only after the
   package exists.

## Output Checklist

- [ ] Distinct RUINS condition named
- [ ] Required package files present
- [ ] Claims graded conservatively
- [ ] Refusals are case-specific
- [ ] Sibling boundaries explicit
- [ ] Scorecard includes caps and next lift
- [ ] Root/publication indexes updated
