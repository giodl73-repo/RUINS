# Claim Audit: Herculaneum Papyri Virtual Unwrapping

**Owner:** ERRATA
**Status:** source-locked working audit

Use [`source-lock.md`](source-lock.md) for current claim boundaries. Use
[`data-custody-gate.md`](data-custody-gate.md) for sample, volume, segment,
representation, and ink-output IDs. Use
[`model-output-custody-gate.md`](model-output-custody-gate.md) for model-output
claim boundaries. Use
[`scholarly-text-custody-gate.md`](scholarly-text-custody-gate.md) for
source-scoped recovered-text and work-identity boundaries.

## Claim Grades

| Claim | Max grade now | Audit note |
|---|---|---|
| The papyri were buried/carbonized and survived materially. | Source-specific | Public project and technical sources support broad case condition. |
| CT volumes preserve a mediated witness. | Source-specific | Dataset custody supports scan claims. |
| Surface segmentation equals physical unrolling. | Refuse | It is computational reconstruction. |
| Ink detection equals transcription. | Refuse | Detection is model output and needs review. |
| A recovered passage identifies an author/work/doctrine. | Source-specific | Requires papyrological or edition custody. |
| "AI read the library" is an evidence claim. | Refuse | Treat as public recovery memory. |
| A sample or volume ID can be cited as a dataset artifact. | Dataset-path custody | Allowed only as path/metadata custody, not text custody. |
| An ink-output path is a transcription. | Refuse | It is model-output custody, not text custody. |
| A model output can support candidate ink evidence. | Model/path-scoped | Allowed only with model, artifact, and uncertainty boundaries. |
| PHerc. 1667 was fully virtually unwrapped/read under review criteria. | Source-scoped scholarly custody | Allowed only as a claim from Angelotti et al.; do not quote extended text here. |
| PHerc. 139 title/author attribution identifies Philodemus, On Gods, Book 8. | Source-scoped scholarly custody | Allowed only as a claim from Angelotti et al.; no independent interpretation. |

## Phrases To Challenge

| Phrase | Replacement |
|---|---|
| "the AI read the scroll" | "the pipeline/model exposed candidate text later reviewed" |
| "the scroll says" | "the current reading/transcription reports" |
| "digitally unrolled" | "virtually unwrapped under this reconstruction method" |
| "the lost library is restored" | "some material is newly readable under current custody" |
| "raw scans reveal text" | "scan data supports downstream surface and ink-detection work" |
