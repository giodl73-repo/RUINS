# Model Output Custody Gate: Herculaneum Papyri Virtual Unwrapping

**Owner:** ERRATA / Reconstruction Skeptic
**Status:** current-scope model-output custody gate
**Date:** 2026-07-05

This gate defines what RUINS may say about ink-detection, segmentation, surface
prediction, and other computational outputs. It closes the model-output custody
gate for current stable claims. It does not authorize exact recovered text,
author, title, translation, doctrine, or work-identity claims.

## Model Output Ladder

| Layer | What it can support | What it cannot support alone |
|---|---|---|
| Raw CT / reconstructed volume | Volumetric custody, scan parameters, and path identity. | Text, ink, transcription, or work identity. |
| Segmentation / mesh | Candidate surface geometry and computational unwrapping path. | Physical unrolling or final page order. |
| Representation / predicted surface | Model-mediated papyrus-surface hypothesis. | Physical layer certainty without validation. |
| Ink-detection output | Candidate ink-presence evidence under a named model and parameters. | Transcription, translation, author, title, doctrine, or complete reading. |
| Human/papyrological review | Review status for candidate letters, words, or passages. | Whole-scroll or whole-library recovery unless source-scoped. |
| Scholarly edition / publication | Exact text, translation, work identity, and interpretation claims. | Dataset or model custody unless linked back to artifacts. |

## Claim Permissions

| Claim type | Current permission |
|---|---|
| Naming an ink-detection output path | Allowed as model-output artifact custody. |
| Saying a model output is candidate ink evidence | Allowed if model/path scoped. |
| Saying a model output is a transcription | Refuse. |
| Saying a model output identifies a title, author, or work | Refuse without scholarly custody. |
| Saying a model output is "readable text" | Refuse unless review status and transcription custody are named. |
| Saying a model output has no uncertainty | Refuse. |
| Comparing model output to source-grounded validation labels | Allowed only where source/method custody is named. |

## Minimum Custody For Text Claims

Before RUINS may make any exact recovered-text claim, the claim must identify:

1. Dataset artifact path or source.
2. Model or method output path.
3. Review status.
4. Transcription or edition custody.
5. Translation custody, if a modern-language claim is made.

Missing any one layer keeps the claim below exact text status.

## Current Decision

Model-output custody is closed for current stable claims. RUINS may discuss
ink-detection and surface-prediction artifacts as model outputs, but exact
recovered text and work identity remain blocked by scholarly text custody.

## References

- Parsons et al., "EduceLab-Scrolls: Verifiable Recovery of Text from
  Herculaneum Papyri using X-ray CT":
  https://arxiv.org/html/2304.02084v4
- ScrollPrize open-data documentation:
  https://github.com/ScrollPrize/open-data?tab=readme-ov-file
