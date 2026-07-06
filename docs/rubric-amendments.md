# RUINS Rubric Amendments

Status: foundation policy  
Pattern sources: LUCIA forward-only amendment, Design Labs rubric evolution,
Games Design play-observe-amend loop, CERES spec-amendment discipline

RUINS evolves through papers. A paper can reveal that the rubric is missing a
distinction, but it must not silently rewrite the standard under earlier papers.

## Forward-Only Policy

1. Scores are archival records. A score names the rubric version and paper scope
   under which it was assigned.
2. New case findings may amend the rubric, registers, templates, or capability
   map going forward.
3. Earlier papers are not silently rescored under a later standard.
4. If an older paper is revisited, create a new review record that names the
   later rubric version and explains the change.
5. A rubric amendment can extend or refine an existing rule, but it must not
   reverse an earlier rule without an explicit reversal finding.

## Amendment Types

| Type | Meaning | Example in RUINS |
|---|---|---|
| Extension | Adds a new evidence surface, capability, register, or scoring cue. | Great Zimbabwe adds interpretive violence and colonial denial as a ruin condition. |
| Refinement | Tightens an existing rule while preserving its earlier meaning. | Cahokia refines abandonment from "loss event" into layered transformation. |
| Reversal | Rejects an earlier rule or makes old scores misleading. | Not allowed silently; requires ASHLAR review and an explicit migration note. |

## Amendment Trigger

Open an amendment when two or more papers expose the same gap, or when one paper
cannot be scored honestly without a new distinction.

| Trigger | Required artifact |
|---|---|
| Repeated scoring gap | Add or promote a row in `docs/capability-expansion.md` and update `QUALITY_RUBRIC.md` if scoring changes. |
| New ruin condition | Add a capability candidate or fast-promote it to active if a publication-ready paper already contains the controlling artifact. |
| Scope drift | Add or update a sibling-boundary register before expanding the paper. |
| Source-custody gap | Add source-lock or page-anchor requirements before raising the score. |
| Register gap | Add a new register only if it removes repeated ambiguity across papers. |

Use [`capability-promotion-packet.md`](capability-promotion-packet.md) before
changing a capability state in the registry.

## Amendment Record Template

```text
## YYYY-MM-DD - <short name>

Type: Extension | Refinement | Reversal
Triggered by: <paper(s)>
Changed artifact: QUALITY_RUBRIC.md | MODULE.md | template | register | capability map
Old rule preserved: yes/no
Reason:
- ...
Follow-up:
- ...
```

## Current Amendment Log

| Date | Type | Trigger | Change |
|---|---|---|---|
| 2026-07-04 | Extension | Knossos and Antikythera | Treat modern reconstruction/restoration as a separately scored evidence layer. |
| 2026-07-04 | Refinement | Alexandria and Cahokia | Require loss event/process separation rather than singular destruction framing. |
| 2026-07-04 | Extension | Great Zimbabwe | Add interpretive violence, damaged custody, and colonial denial as valid RUIN conditions. |
| 2026-07-04 | Extension | House of Wisdom | Add institutional memory where a named institution, broader ecology, destruction, and later public image diverge. |
| 2026-07-04 | Refinement | All publication-ready case papers | Require operational refusal registers for mature case papers. |
| 2026-07-05 | Extension | Herculaneum papyri virtual unwrapping | Add mediated recovery custody: scan, segmentation, model output, scholarly transcription, edition status, and public milestone must be gated separately before publication claims. |
| 2026-07-05 | Extension | Maya codices destroyed corpus | Add destroyed corpus custody: a tiny surviving witness set cannot define the range, scale, genre map, or destroyed inventory of the absent corpus without separate controls. |
| 2026-07-05 | Extension | Palmyra replica reconstruction | Add replica-status custody: replicas, facsimiles, restorations, and digital models need provenance, scale, material, method, and authority boundaries before they can support reconstruction claims. |
| 2026-07-05 | Extension | Vinland saga site crosscheck | Add saga-memory crosscheck: literary tradition, archaeological site evidence, routes, names, events, and public identity claims must stay separately graded. |
| 2026-07-05 | Refinement | House of Wisdom and Dead Sea Scrolls fragment custody | Add scope-gated publication: a paper can become publication-ready when exact-claim surfaces are explicitly refused and demoted to P3 future gates rather than left as current P2 blockers. |
| 2026-07-05 | Refinement | Capability expansion process | Replace proposal-only capability tracking with candidate, active, and core states plus fast promotion for reviewed publication-ready papers. |
| 2026-07-05 | Extension | Uluburun and Kyrenia shipwreck context-loss papers | Add shipwreck context-loss: recovered cargo, hull reconstruction, replica performance, museum display, digital catalog, and dating output must not become original operating context without a gate. |
| 2026-07-05 | Extension | Roman concrete and Tyrian purple partial-transmission papers | Add partial technical transmission: texts, material traces, samples, contexts, experiments, and public memory must not become a complete ancient technique without a custody gate. |

## Re-Scoring Rule

Publication-ready papers remain valid under the rubric version used in their
scorecard. If a later amendment would materially change a score, ASHLAR writes a
new review file instead of editing the old one in place.
