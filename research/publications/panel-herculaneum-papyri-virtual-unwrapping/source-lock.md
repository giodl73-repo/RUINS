# Source Lock: Herculaneum Papyri Virtual Unwrapping

**Owner:** PALIMPSEST
**Status:** first source lock
**Date:** 2026-07-05

This source lock defines what RUINS may say about Herculaneum papyri virtual
unwrapping in this paper. It separates object survival, scan custody, data
custody, segmentation, ink detection, scholarly reading, and public memory.

## Locked Sources

| ID | Source | Type | Locked use | Limits |
|---|---|---|---|---|
| S1 | Vesuvius Challenge overview | project/public source | Lines 37-45 define the challenge as ML/computer vision/geometry work on carbonized Herculaneum scrolls and name representation as an open problem. | Project state only; not scholarly edition custody. |
| S2 | Vesuvius Challenge overview | project/public source | Lines 52-63 separate geometric reconstruction and ink detection as open problems. | Supports layer separation, not solved-state claims. |
| S3 | Vesuvius Challenge story | project/public source | Lines 89-115 frame AD 79 burial, 1750 discovery, destructive opening, remaining unread scrolls, virtual unwrapping lineage, and 2023 challenge launch. | Public chronology; exact history needs historical custody. |
| S4 | Parsons et al., EduceLab-Scrolls arXiv | technical preprint | Lines 72-74 define the pipeline, dataset, labels, and verification claims. | Technical custody, not final papyrological edition. |
| S5 | Parsons et al., EduceLab-Scrolls arXiv | technical preprint | Lines 77-81 describe 79 AD destruction, 1752-54 discovery/excavation, more than 900 scrolls, physical unrolling damage, and noninvasive counter-methods. | Broad technical-history context. |
| S6 | Parsons et al., EduceLab-Scrolls arXiv | technical preprint | Lines 88-92 and 106-111 describe CT volumes, aligned labels, carbon-ink detection, model limits, and verification by visual, quantitative, and scholarly review. | Supports model-evidence boundaries; no exact text claims. |
| S7 | AWS Open Data registry | dataset registry | Lines 4-8 and 14-24 identify reconstructed micro-CT volumes, carbonized Herculaneum papyri, OME-Zarr distribution, license, docs, and manager. | Dataset custody, not interpretation. |
| S8 | UK Digital Restoration Initiative | institutional project source | Lines 73-74 define damaged texts, invisible-library framing, and virtual unwrapping as noninvasive tools. | Institutional context, not textual proof. |

## Locked Values And Claims

| Claim | Locked wording | Source | Grade |
|---|---|---|---|
| Case condition | Herculaneum papyri survival is carbonized, damaged, and partially unread without mediated recovery. | S1 / S3 / S5 | Source-specific |
| Method layers | Representation, geometric reconstruction, and ink detection are distinct problems. | S1 / S2 | Project/source-specific |
| Dataset custody | Vesuvius Challenge scan data includes reconstructed micro-CT volumes distributed as OME-Zarr. | S7 | Dataset custody |
| EduceLab method | The technical pipeline combines CT images, machine learning, geometry, labels, and verification methods. | S4 / S6 | Technical source custody |
| Destructive opening caution | Earlier physical opening produced text and scholarship but also destroyed or fragmented scroll material. | S3 / S5 | Source-specific caution |
| AI miracle refusal | Public AI-recovery narratives cannot substitute for scan, model, text, and scholarly custody. | S1 / S6 / S8 | RUINS refusal |

## Paper Use Rules

1. Always identify whether a claim rests on object, scan, surface, label, model,
   text, edition, or public narrative.
2. Do not treat CT volume custody as text custody.
3. Do not treat ink detection output as transcription.
4. Do not identify author, work, doctrine, or translation without scholarly
   custody.
5. Do not treat a prize milestone as final papyrological publication.
6. Do not provide conservation or handling guidance.

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
