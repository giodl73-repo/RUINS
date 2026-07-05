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
| Repeated scoring gap | Add a row to `docs/capability-expansion.md` and update `QUALITY_RUBRIC.md` if scoring changes. |
| New ruin condition | Add a capability candidate and identify which paper exposed it. |
| Scope drift | Add or update a sibling-boundary register before expanding the paper. |
| Source-custody gap | Add source-lock or page-anchor requirements before raising the score. |
| Register gap | Add a new register only if it removes repeated ambiguity across papers. |

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

## Re-Scoring Rule

Publication-ready papers remain valid under the rubric version used in their
scorecard. If a later amendment would materially change a score, ASHLAR writes a
new review file instead of editing the old one in place.
