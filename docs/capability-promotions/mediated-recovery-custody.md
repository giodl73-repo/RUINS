# Capability Promotion: Mediated Recovery Custody

Capability id: `ruins-capability:mediated-recovery-custody`
Promotion: Candidate -> Core
Date: 2026-07-05
Owner: ASHLAR

Trigger paper:

- `panel-herculaneum-papyri-virtual-unwrapping`

## Overclaim Pressure

Scan data, segmentation, labels, model outputs, preprints, prize announcements,
and scholarly readings can be collapsed into "the text was recovered." RUINS
needs a capability that forces each mediated recovery layer to carry its own
claim grade before recovered-text or recovered-object claims publish.

## Control Artifacts

| Artifact | Path | What it controls |
|---|---|---|
| Data custody gate | `research/publications/panel-herculaneum-papyri-virtual-unwrapping/data-custody-gate.md` | Separates sample, scan, volume, segment, representation, and ink-output IDs from text claims. |
| Model-output custody gate | `research/publications/panel-herculaneum-papyri-virtual-unwrapping/model-output-custody-gate.md` | Blocks model output from becoming transcription, translation, author, title, doctrine, or complete reading. |
| Scholarly-text custody gate | `research/publications/panel-herculaneum-papyri-virtual-unwrapping/scholarly-text-custody-gate.md` | Allows source-scoped non-quotation recovered-text status while refusing extended Greek, translation, and independent philology. |
| RUINS rubric v1.6 | `QUALITY_RUBRIC.md` | Adds mediated recovery checks and caps for scan/model/preprint/public-announcement overclaiming. |

## Review Evidence

| Review surface | Finding |
|---|---|
| `reviews/SCORECARD.md` | Score `45/50`; data-custody, model-output, and scholarly-text gates are complete for current publication-ready claims. |
| `reviews/SCORECARD.md` | Caps require a quotation/source audit before extended recovered-text quotations, translations, or independent philological interpretation. |

## Scope Decision

Current paper permission:

- Allowed: source-scoped claims about object/data custody, model-output status,
  and non-quotation scholarly recovered-text boundaries.
- Refused: treating scan paths, segmentations, model outputs, preprints, prize
  pages, or public announcements as final text.
- Future P3: quotation/source audit, final-edition custody, and exact Greek or
  translation claims.
- Sibling handoff: FONTES / MUNDUS for exact text; MAXIM / LUCIA for Roman
  intellectual-history interpretation; AI methodology systems for implementation.

## Registry Change

Update `docs/capability-expansion.md`:

- State: Core.
- Promotion basis: Herculaneum creates data, model-output, and scholarly-text
  gates; `QUALITY_RUBRIC.md` includes the mediated recovery check and cap.
- First paper: Herculaneum papyri.

## ASHLAR Decision

Record `mediated-recovery-custody` as core. It has concrete gates, a reviewed
publication-ready paper, and explicit rubric support.
