# RUINS Quality Rubric

**Version:** v1.13

RUINS uses two different review instruments:

- **Finding severity** (`P1`, `P2`, `P3`) for concrete issues.
- **Paper score** (`0-50`) for readiness and calibration across papers.

Scores do not replace role findings. A paper with any unresolved `P1` cannot be
publication-ready, even if the numeric score is high.

Rubric evolution is forward-only. Use
[`docs/rubric-amendments.md`](docs/rubric-amendments.md) for amendment rules and
[`docs/capability-expansion.md`](docs/capability-expansion.md) for repeated
case-derived capability gaps.

## Score Bands

| Score | Band | Meaning |
|---:|---|---|
| 45-50 | Publication-ready | Strong evidence discipline, clear refusals, source posture locked. |
| 38-44 | Stable working paper | Usable internally; needs source lock, examples, or polish. |
| 30-37 | Promising draft | Correct shape, but important surfaces remain underdeveloped. |
| 20-29 | Fragile draft | Core idea visible, but evidence/refusal/role alignment is weak. |
| 0-19 | Not ready | Cannot be relied on; likely confuses evidence with speculation. |

## Dimensions

| Dimension | Points | Role owner | What earns full credit |
|---|---:|---|---|
| Evidence condition | 10 | Fragment Custodian | Surviving traces are classified by direct, copied, reported, contextual, reconstructed, and absent evidence. |
| Loss/process clarity | 8 | Absence Historian | The paper distinguishes event, process, survival layer, interpretation layer, and later memory. |
| Claim-grade discipline | 10 | Reconstruction Skeptic | Claims are graded conservatively; reconstruction, statistics, reports, and public images do not outrun evidence. |
| Refusal quality | 7 | Reconstruction Skeptic / Safety Editor | The paper names specific claims it will not make and explains why. |
| Cultural-memory handling | 6 | Cultural Memory Reader | Later memory is treated as evidence of afterlife, not as direct evidence of the original object. |
| Sibling boundary | 5 | Sibling Boundary Editor | The paper names handoffs and does not expand into general encyclopedia, place, custody, identity, ritual, lineage, or production work. |
| Source posture | 4 | Fragment Custodian / Paper Editor | Source targets are identified, metadata-only where needed, and publication claims wait for source lock. |

## Case-Derived Capability Checks

Before promotion, ASHLAR should ask whether the paper exercises a known RUINS
capability or exposes a new one:

| Check | Question |
|---|---|
| Evidence layer granularity | Does the paper use the right evidence layers for this ruin condition? |
| Custody damage | Did recovery, looting, restoration, dispersal, interpretation, or edition history damage the evidence bridge? |
| Memory afterlife | Is later memory classified without upgrading original-state claims? |
| Reconstruction status | Are models, restorations, replicas, translations, and public images labeled separately? |
| Mediated recovery custody | If evidence passes through scans, models, transcriptions, editions, or public announcements, are those custody layers gated separately before publication claims? |
| Destroyed corpus custody | If a tiny witness set survives from a larger lost corpus, does the paper prevent surviving examples from standing in for the absent whole? |
| Replica-status custody | If a replica, facsimile, restoration, or digital model exists, is it prevented from becoming object-equivalent without explicit status and provenance? |
| Saga-memory crosscheck | If literary memory and archaeological evidence partially overlap, are text, site, route, name, and public identity claims kept in separate grades? |
| Scope-gated publication | If exact source, text, route, reading, specification, or reconstruction claims remain unaudited, does the paper explicitly refuse those surfaces and keep future work as P3 rather than current scope? |
| Shipwreck context loss | If a shipwreck preserves cargo, hull, reconstruction, display, catalog, or dating evidence, are cargo, operating context, recovery, reconstruction, route, owner, crew, and afterlife claims separately gated? |
| Partial technical transmission | If a technique survives through text, material, sample, context, experiment, or memory, are those surfaces prevented from becoming a complete ancient technique without a custody gate? |
| Colonial denial register | If a site has colonial, racialized, settler, foreign-builder, or ownerless-history interpretations, are those narratives refused as archaeology and preserved only as interpretive history or cultural memory? |
| Catastrophe image audit | If a vivid destruction image dominates the case, are event, source tradition, material loss, inventory, blame, closure, and later memory separately gated? |
| Deliberate textual destruction | If a report, edict, or tradition describes intentional text destruction, are source mediation, target category, exemptions, survival, corpus effect, and memory image separately gated? |
| Dispersed object provenance custody | If objects survive outside original context, are object identity, provenance, current holding, legal/governance action, physical movement, digital/replica display, and living memory separately gated? |
| Cast void identity custody | If a body void, footprint, trackway, cast, scan, or impression stands in for a vanished living actor, are substrate, impression, cast/model, taxon, gait, identity, group relation, and public memory separately gated? |
| Refusal specificity | Are the strongest likely overclaims explicitly blocked? |
| Sibling boundary | Does each non-RUINS consequence name its owning sibling system? |

## Automatic Caps

| Condition | Maximum score |
|---|---:|
| Any unresolved `P1` finding | 29 |
| No source map | 32 |
| No claim audit | 34 |
| No refusal section | 35 |
| No role review | 37 |
| No source lock for a case paper | 42 |
| Publication makes a live translation, identification, or reconstruction claim without source lock | 29 |
| Publication treats a scan, model output, preprint, prize page, or public announcement as final scholarly text/status without a custody gate | 34 |
| Publication infers corpus-wide content, scale, or genre range from a tiny surviving witness set without corpus-custody controls | 34 |
| Publication treats a replica, facsimile, restoration, or digital model as the damaged original without replica-status custody | 34 |
| Publication lets a saga, chronicle, legend, or place-name identify a site/route/event without independent evidence custody | 34 |
| Publication claims scope-gated readiness while still making the exact claim that the gate refuses | 34 |
| Publication treats shipwreck cargo, hull reconstruction, replica performance, museum display, digital catalog, or dating output as complete original operating context without a shipwreck context-loss gate | 34 |
| Publication treats a text, sample, material trace, experiment, public summary, or reconstruction as a complete ancient technique without partial-technical-transmission controls | 34 |
| Publication treats colonial, racialized, settler, foreign-builder, lost-race, or ownerless-history narratives as live archaeological alternatives without a colonial-denial register | 34 |
| Publication treats a vivid catastrophe image as a complete loss event, destroyed inventory, final blame account, or civilizational closure without a catastrophe-image audit | 34 |
| Publication treats a deliberate destruction report as a complete inventory, corpus map, destroyed-book count, exact quotation, or total intellectual-loss explanation without deliberate-textual-destruction controls | 34 |
| Publication treats possession, title, loan, return, replica, digital record, or display as complete provenance, original context, restitution, or reunification without dispersed-object custody controls | 34 |
| Publication treats a body void, footprint, trackway, cast, scan, or impression as complete identity, species certainty, gait reconstruction, social relation, emotional state, or population history without cast-void identity controls | 34 |

## Scoring Procedure

1. Each role scores only its owned dimensions.
2. ASHLAR records a synthesis score and identifies caps.
3. The synthesis must list the next work needed to move up one band.
4. Do not raise a paper above `42` until source candidates and numeric claims
   are locked.
5. Do not raise a paper above `44` until role review confirms there are no open
   `P2` findings.
6. If review exposes a repeated gap or a new one-paper capability with a
   concrete control artifact, record it in `docs/capability-expansion.md` or
   `docs/rubric-amendments.md` before relying on it as a future scoring rule.

## Review Output Template

```text
Score: NN/50
Band: <band>
Caps: <none or cap reason>

Dimension scores:
- Evidence condition: N/10
- Loss/process clarity: N/8
- Claim-grade discipline: N/10
- Refusal quality: N/7
- Cultural-memory handling: N/6
- Sibling boundary: N/5
- Source posture: N/4

Blocking findings:
- ...

Next lift:
- ...
```
