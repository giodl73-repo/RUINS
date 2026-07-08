# OCR/HTR Recovery Checklist

Use this checklist when manuscript, archive, inscription, printed-book, form,
ledger, catalogue, or fragmentary corpus claims rely on OCR, HTR, ATR, layout
analysis, segmentation, model training, ground truth, post-correction, search
indexing, confidence scores, exported text, or normalized full text.

## Required Separations

| Layer | Required custody question |
|---|---|
| Object/image | Which manuscript, page, folio, fragment, scan, photograph, or image set is the source? |
| Layout | Were columns, zones, marginalia, tables, line breaks, reading order, or non-text regions segmented? |
| Script/model scope | Which hand, typeface, language, date range, script direction, or document class trained or constrained the model? |
| Ground truth | What manually corrected lines, pages, editions, or transcriptions trained and tested recognition? |
| Recognition output | Is the output OCR, HTR, ATR, baseline text, candidate transcription, search text, or model prediction? |
| Confidence/error | Are CER, WER, confidence, validation split, sample bias, and unreviewed regions reported separately? |
| Post-correction | What was corrected by humans, dictionaries, language models, rules, or LLMs after recognition? |
| Normalization | Were spelling, abbreviations, punctuation, lineation, names, dates, or language variants normalized? |
| Edition boundary | Is there a scholarly edition, diplomatic transcription, translation, or only machine-readable access text? |
| Corpus scale | Does a searchable collection stand for the whole archive, genre, community, institution, or period? |
| Public memory | Are "AI read the archive" and "lost voices recovered" stories contained as access afterlife? |

## Mandatory Refusals

A RUINS paper must refuse:

1. OCR/HTR output as a scholarly edition;
2. confidence score as correctness for a specific disputed reading;
3. keyword hit as proof of absence or presence without image/source audit;
4. normalized text as original spelling, punctuation, abbreviation, or layout;
5. post-corrected text as transparent machine output;
6. training data as representative of every hand, script, language, or document
   type in the collection;
7. searchability as complete recovery of a lost, damaged, or inaccessible
   corpus;
8. model improvement as resolved philology, authorship, dating, provenance, or
   historical interpretation.

## Cross-Case Test

| Test | OCR4all / historical print | Transkribus / HTR archives | eScriptorium / Kraken workflows | Core rule |
|---|---|---|---|---|
| Source condition | Early printed pages with difficult typography and layout. | Historical manuscripts, hands, and archival collections. | Multiscript historical documents with layout and transcription workflows. | Image, layout, and recognition layers must be distinct. |
| Model dependency | Workflow components, training, correction, and PageXML-style exports. | Ground truth, model training, CER/WER, and platform outputs. | Kraken models, segmentation, transcription, and exported structured text. | Model scope and training evidence are custody layers. |
| Overclaim pressure | Clean full text becomes reliable edition. | Searchable archive becomes recovered voices or complete corpus. | OCR/HTR pipeline becomes final transcription authority. | Machine-readable text is not edition, translation, or corpus closure. |

## Automatic Cap

A paper cannot score above `34` if it treats OCR, HTR, ATR, layout analysis,
segmentation, confidence score, model output, post-correction, normalized text,
search index, or exported full text as a complete transcription, edition,
translation, authorship claim, date, provenance, corpus inventory, absence
proof, or historical interpretation without this checklist or an equivalent
OCR/HTR recovery gate.

## Source Pressure

- OCR4all describes a historical-print OCR workflow with preprocessing,
  segmentation, recognition, training, correction, and structured export layers.
- Transkribus/HTR research foregrounds ground truth, model scope, CER/WER, and
  platform-generated transcripts.
- eScriptorium and Kraken expose the same custody problem for open workflows:
  layout, recognition, model training, script support, and exported text are
  separate evidence layers.

Source anchors:

- <https://www.mdpi.com/2076-3417/9/22/4853>
- <https://www.sciencedirect.com/org/science/article/pii/S0022041819000080>
- <https://kraken.re/5.3.0/index.html>
