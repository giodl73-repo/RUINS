# Data Custody Gate: Herculaneum Papyri Virtual Unwrapping

**Owner:** PALIMPSEST / ERRATA
**Status:** current-scope object/data custody gate
**Date:** 2026-07-05

This gate defines how RUINS may name scan, sample, volume, segment, and model
IDs from the Vesuvius Challenge open data. It authorizes dataset-path and
artifact-type claims only. It does not authorize recovered text, title,
authorship, translation, or work-identity claims.

## Anchored Data Structure

| Data surface | Anchor | Current RUINS use | Boundary |
|---|---|---|---|
| Open-data overview | ScrollPrize open-data docs lines 220-223 state that the repository provides access to X-ray scans, 3D volumes, segmented surfaces, and ML results for Herculaneum papyri. | Use to identify dataset scope. | Not text custody. |
| Pipeline artifacts | Lines 226-232 distinguish scan acquisition, volume reconstruction, masking/export, ML surface prediction, segmentation/surface extraction, and ink detection. | Use to separate artifact types. | Do not collapse pipeline artifacts into recovered text. |
| Repository structure | Lines 237-251 show sample directories such as `PHerc0332/`, `PHerc1667/`, `volumes/`, `segments/`, `representations/`, and `scans/`. | Use to name sample/path custody. | A sample ID is not a textual claim. |
| Volume identifiers | Lines 252-267 define OME-Zarr volume structure and give `20231201141544-3.240um-70keV-masked.zarr` as an example. | Use to describe volume-level custody and metadata encoded in IDs. | Does not validate any reading. |
| Segment artifacts | Lines 268-300 describe segment folders, mesh files, TIFXYZ coordinates, surface volumes, and ink-detection results. | Use to distinguish segment, mesh, surface-volume, and ink-output custody. | Segment artifacts remain computational representations. |
| Ink detection filenames | Lines 298-309 describe ink-detection result paths and filename components: sample, segment, volume, model, tile size, and stride. | Use to name an ink-output artifact without treating it as transcription. | Model-output only. |
| Representation outputs | Lines 310-324 describe derived prediction outputs and predicted papyrus surfaces as ML model outputs. | Use to classify predicted surfaces. | Do not treat predicted surfaces as physical scroll layers. |
| ID conventions | Lines 325-338 define UTC datetime IDs and long IDs with resolution, energy, and suffix. | Use to parse IDs conservatively. | IDs are custody metadata, not evidence of text. |
| Data access and citation | Lines 374-424 describe browser/Python S3 access examples, and lines 434-439 give citation and license. | Use for reproducible access and citation posture. | RUINS does not download or process volumes in this paper. |

## Claim Permissions

| Claim type | Current permission |
|---|---|
| Naming a sample directory such as `PHerc0332` or `PHerc1667` | Allowed as dataset-path custody. |
| Naming a volume ID with resolution/energy metadata | Allowed as volume-path custody. |
| Naming a segment ID, mesh, TIFXYZ, or surface-volume path | Allowed as computational artifact custody. |
| Naming an ink-detection output path | Allowed as model-output artifact custody. |
| Claiming the ink output is a transcription | Refuse. |
| Claiming a sample ID identifies a work/title/author | Refuse without scholarly custody. |
| Claiming a surface prediction is a physical layer | Refuse. |

## Current Decision

Object-level dataset custody is closed for current stable claims. RUINS may
name sample, volume, segment, representation, and ink-output IDs as dataset
artifacts. Exact recovered text, work identity, title, authorship, and
translation remain blocked pending scholarly text custody.

## References

- ScrollPrize open-data documentation:
  https://github.com/ScrollPrize/open-data?tab=readme-ov-file
- AWS Open Data, "Vesuvius Challenge - CT Scans of Herculaneum Papyri":
  https://registry.opendata.aws/vesuvius-challenge-herculaneum-scrolls/
