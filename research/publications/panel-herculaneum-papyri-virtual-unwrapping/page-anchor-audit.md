# Page Anchor Audit: Herculaneum Papyri Virtual Unwrapping

**Owner:** PALIMPSEST / ERRATA
**Status:** current-scope page audit
**Date:** 2026-07-05

This audit locks page or line anchors for the current publication-ready
methodology claims. It supports claims about project state, evidence layers,
scan/data custody, method boundaries, destructive opening history, and public
recovery memory. It does not authorize exact Greek readings, work
identifications, translations, or claims about specific scroll IDs beyond
source-scoped examples.

## Anchored Claims

| Claim surface | Anchor | Current RUINS use | Boundary |
|---|---|---|---|
| Project type and scope | Vesuvius Challenge lines 37-40 define the project as machine learning, computer vision, and geometry work on carbonized Herculaneum scrolls, and distinguish passage-level work from entire-scroll goals. | Use for public project-state custody and milestone framing. | Not a scholarly edition or text-critical source. |
| Representation problem | Vesuvius Challenge lines 44-45 state that carbonized/crushed scrolls are hard to trace in raw scan data and that structured representations such as segmentation simplify downstream work. | Use to separate raw scan, representation, and downstream interpretation. | Do not claim representation is solved for all scrolls. |
| Geometric reconstruction problem | Vesuvius Challenge lines 52-55 state that better image representation is not enough and that mapping, stitching, and extracting readable papyrus sheets remain separate work. | Use to distinguish segmentation/geometry from text. | Do not equate virtual unwrapping with physical unrolling. |
| Ink detection problem | Vesuvius Challenge lines 61-63 say text has been recovered from two of five scrolls and ink remains elusive in others. | Use to block universal recovered-library claims. | Project status, not final papyrological publication. |
| Burial and preservation story | Vesuvius Challenge lines 89-101 describe AD 79 burial, preservation, eighteenth-century discovery, fragility, destructive opening, and unread remaining scrolls. | Use for public chronology and damage/access tension. | General public chronology; exact excavation history needs historical custody. |
| Launch and prize context | Vesuvius Challenge lines 111-121 describe 2023 launch, passage prizes, 2024 pipeline refinement, multiple-scroll work, and new text revealed. | Use as public research-organization and milestone afterlife. | Prize milestones are not editions. |
| Technical pipeline and dataset | Parsons et al. lines 72-74 state that the paper presents a pipeline using X-ray CT, ML, geometry, a dataset, labels, and verification by visual, quantitative, and scholarly review. | Use for method-layer custody. | Technical preprint, not exact text custody. |
| Material and destructive-opening context | Parsons et al. lines 77-81 describe AD 79 burial, 1752-54 discovery, more than 900 scrolls, past opening, and damage/loss. | Use for loss/process clarity. | Broad technical history, not site monograph custody. |
| Dataset design and labels | Parsons et al. lines 88-92 describe CT volumes, aligned labels, and ink-presence model limits, with no OCR/paleography knowledge in the model. | Use to separate labels, ink detection, and transcription. | Does not authorize exact readings. |
| Validation and limits | Parsons et al. lines 106-111 describe fragment benchmark validation, ground-truth infrared images, hidden-text recovery, and the transition from proof of concept toward scaling. | Use for model-output discipline and feasibility boundary. | Do not convert feasibility into complete-library recovery. |
| Open data custody | AWS Open Data lines 4-8 identify the Vesuvius Challenge CT scan dataset as reconstructed micro-CT volumes of carbonized Herculaneum papyri distributed as OME-Zarr. | Use for dataset custody. | Dataset registry, not text interpretation. |
| License and access metadata | AWS Open Data lines 14-24 identify the CC BY-NC 4.0 license, documentation, and Vesuvius Challenge management. | Use for source/data posture. | Does not by itself validate any reading. |
| Virtual unwrapping lineage | UK DRI lines 73-74 frame damaged texts as locked by destruction/decay and name virtual unwrapping as a noninvasive restoration process. | Use for institutional lineage and method memory. | Institutional framing, not proof of a specific recovered text. |

## Current Decision

The paper can stand as publication-ready for its current methodology scope. It
has page anchors for the core RUINS claim that Herculaneum virtual unwrapping
must separate object, scan, segmentation, labels, model output, scholarly
reading, and public memory. Exact recovered-text quotation, translation, and
independent philological claims remain gated by
[`scholarly-text-custody-gate.md`](scholarly-text-custody-gate.md).

## References

- Vesuvius Challenge:
  https://scrollprize.org/
- Parsons et al., "EduceLab-Scrolls: Verifiable Recovery of Text from
  Herculaneum Papyri using X-ray CT":
  https://arxiv.org/html/2304.02084v4
- AWS Open Data, "Vesuvius Challenge - CT Scans of Herculaneum Papyri":
  https://registry.opendata.aws/vesuvius-challenge-herculaneum-scrolls/
- University of Kentucky Digital Restoration Initiative:
  https://www2.cs.uky.edu/dri/
