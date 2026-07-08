# OCR/HTR Recovery Custody

**Capability id:** `ruins-capability:ocr-htr-recovery-custody`
**Promotion:** Candidate -> Active -> Core
**Trigger pressure:** OCR4all, Transkribus/HTR, eScriptorium, and Kraken
historical-document recognition workflows
**Rubric:** v1.65

## Problem

Computational text recognition can make damaged, inaccessible, handwritten, or
typographically difficult sources searchable. It can also collapse many custody
layers into a single claim that "the text was recovered." OCR, HTR, ATR, layout
analysis, segmentation, ground truth, model training, validation metrics,
confidence scores, post-correction, normalization, search indexes, exported
PageXML/ALTO/hOCR text, and public AI-reading stories can become complete
transcription, edition, translation, authorship, date, provenance, corpus
inventory, absence proof, or historical interpretation.

## Core Rule

OCR/HTR recovery claims must keep object/image, layout, script/model scope,
ground truth, recognition output, confidence/error, post-correction,
normalization, edition boundary, corpus scale, and public memory separate.

## Required Controls

- OCR/HTR recovery gate.
- Source lock.
- Page-anchor audit.
- Refusal register.
- Cultural-memory register.
- Sibling-boundary register.
- Cross-case checklist.

## Source Pressure

| Source family | Pressure exposed |
|---|---|
| OCR4all historical-print workflow | OCR for historical print requires preprocessing, document analysis, segmentation, model training, recognition, correction, configuration, and export custody before full-text claims. |
| Transkribus / HTR archival research | Ground truth, model scope, CER/WER, handwriting variation, and platform transcripts must not become final readings or complete archival recovery. |
| eScriptorium / Kraken workflows | Open OCR/HTR pipelines expose layout, line segmentation, model training, script direction, character recognition, and structured export as separate evidence layers. |

## Research Inputs

- Reul et al., "OCR4all--An Open-Source Tool Providing a (Semi-)Automatic OCR
  Workflow for Historical Printings,"
  <https://www.mdpi.com/2076-3417/9/22/4853>.
- Terras et al., "Transforming scholarship in the archives through handwritten
  text recognition,"
  <https://www.sciencedirect.com/org/science/article/pii/S0022041819000080>.
- Kraken documentation, especially preprocessing, segmentation, recognition,
  model, and serialization separation, <https://kraken.re/5.3.0/index.html>.

## Decision

Promote directly to Core under rubric v1.65. OCR/HTR recovery custody fills the
Text, Corpus, and Mediated Recovery family gap for machine-readable text. It is
distinct from mediated recovery custody because the reusable pressure is not
scan/model recovery of one object, but conversion of images and layouts into
searchable or editable text across documents and corpora.
