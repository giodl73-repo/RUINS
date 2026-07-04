# Custody Register: Indus Script Non-Decipherment

**Owner:** PALIMPSEST
**Status:** fourth custody pass
**Date:** 2026-07-04

This register separates direct artifact survival, catalog traditions, analytic
datasets, and public summaries. RUINS can use each layer, but it must not treat
them as interchangeable.

## Custody Layers

| Layer | Example | Evidence condition | RUINS use | Risk |
|---|---|---|---|---|
| Material artifacts | Seals, tablets, sealings, pottery marks, and related objects | Direct material evidence, mediated by excavation and collection records | Establish that signs survive on objects. | Site, collection, and publication access vary by object. |
| Corpus volumes | CISI volumes 1 and 2; CISI 3.x bibliographic targets | Published catalog evidence | Track artifact records, sign drawings, provenience, and catalog numbers. | Volumes 1 and 2 have direct PDF custody; CISI 3.x has bibliographic/publisher metadata but not direct volume PDF custody. |
| Concordances | Mahadevan M77 and sign-list traditions | Secondary cataloging and normalization | Use source-specific sign counts and sequence values. | M77 has direct PDF custody; sign identity and variant grouping remain modern decisions. |
| Analytic datasets | EBUDS subset in Yadav et al.; later digitized or deduplicated datasets | Derived research dataset | Test statistical order, directionality, and model behavior. | Dataset pruning choices cannot become universal corpus facts. |
| Interpretive papers | Linguistic, non-linguistic, economic, and computational analyses | Argument built from corpus and model layers | Grade claims and refusals. | A model may support structure without translating meaning. |
| Public summaries | Encyclopedic, news, and technology coverage | Tertiary/current framing | Track public memory and locate bibliography leads. | Not a primary authority for paper claims. |

## Access Posture

| Source target | Current access | Claim allowed now | Before stronger use |
|---|---|---|---|
| Yadav et al. 2009 n-gram paper | Direct public arXiv access | Source-specific M77 and EBUDS values; structure-without-translation language. | No further access needed for the locked claims already quoted. |
| Rao 2018 economics paper | Direct public arXiv access | Administrative/economic interpretation as hypothesis. | Do not use as decipherment evidence. |
| Nair 2026 preprint | Direct public arXiv access | Current method pressure; not consensus. | Check publication status before treating as peer-reviewed consensus. |
| Farmer/Sproat/Witzel 2004 | Direct public PDF endpoint verified at `https://safarmer.com/fsw2.pdf`; temp inspection on 2026-07-04 confirmed 39-page PDF titled "The Collapse of the Indus-Script Thesis: The Myth of a Literate Harappan Civilization." | Debate-position summary; may summarize the authors' non-linguistic critique, lost-manuscript critique, and political/academic-sustaining-forces argument. | Quote sparingly from direct text; keep the conclusion graded as a serious critique, not field closure. |
| CISI volume 1, *Collections in India* | Direct Internet Archive PDF custody verified from item `TheIndusScript.TextConcordanceAndTablesIravathanMahadevan`; temp inspection on 2026-07-04 confirmed 862-page image-container PDF, 31,508,998 bytes, SHA-1 `ecc3bdcf6a32e8aac80a4e1de1c9f2e1343a68db`. | Use as a direct custody target for the India corpus volume and for source-layer descriptions of the photographic corpus. | Do page-specific audit before citing object-level catalog entries, photographs, or provenience details. |
| CISI volume 2, *Collections in Pakistan* | Direct Internet Archive PDF custody verified from item `TheIndusScript.TextConcordanceAndTablesIravathanMahadevan`; temp inspection on 2026-07-04 confirmed 486-page image-container PDF, 35,870,617 bytes, SHA-1 `e9f1ccbd523eb45cac5cdc90395f4ae22a369e9d`. | Use as a direct custody target for the Pakistan corpus volume and for source-layer descriptions of the photographic corpus. | Do page-specific audit before citing object-level catalog entries, photographs, or provenience details. |
| CISI volume 3.1, *New material... Part 1: Mohenjo-daro and Harappa* | Official Tiedekirja product target identified at `https://tiedekirja.fi/en/corpus-of-indus-seals-and-inscriptions-3-1`; search metadata records ISBN `978-951-41-1040-5`. | Name as a later corpus-volume target and bibliographic member of the CISI series. | Retrieve direct volume or library copy before using its object-level catalog entries. |
| CISI volume 3.2, *Shahr-i Sokhta; Mundigak; Mehrgarh...* | Official Tiedekirja product target identified at `https://tiedekirja.fi/en/corpus-of-indus-seals-and-inscriptions-3-2`; search metadata records ISBN `978-951-41-1134-1`, ISSN `1239-6982`, Humaniora series no. 383, 2019. | Name as a later corpus-volume target and bibliographic member of the CISI series. | Retrieve direct volume or library copy before using its object-level catalog entries. |
| CISI volume 3.3, *Indo-Iranian Borderlands* | Official Tiedekirja product target identified at `https://tiedekirja.fi/en/corpus-of-indus-seals-and-inscriptions-3-3`; search metadata records ISBN `978-951-41-1153-2`, Humaniora 386, 2022, lxxxvii + 683 pp. A direct review PDF by Fuls is available. | Name as a later corpus-volume target; use review only for bounded series-level context. | Do not treat the review as custody of the volume itself. Retrieve direct volume or library copy before object-level claims. |
| Mahadevan M77 | Direct Internet Archive PDF custody verified from item `TheIndusScript.TextConcordanceAndTablesIravathanMahadevan`; temp inspection on 2026-07-04 confirmed 842-page image-container PDF, 36,288,883 bytes, SHA-1 `f13143f4fb458f1b4d6bd24201cc30291ce9ba80`. OCR text supports the source posture that the volume is a sourcebook of texts, concordance, and tables, with decipherment outside its scope. | Source-specific values as reported by Yadav et al.; independent M77 source-layer description; cautious citation of M77 as a concordance/sourcebook. | Do page-specific audit before making independent sign-list, variant, or object-level claims beyond the already locked Yadav values. |

## Rule

No object-level or sign-level claim should cite a tertiary source when a corpus
volume, concordance, or primary excavation report is the actual authority.

## Direct-Custody Notes

| Date | Source | Custody action | Result |
|---|---|---|---|
| 2026-07-04 | Steve Farmer downloads page | Verified public downloads page and link list. | Page reachable; `/fsw2.pdf` appears as the Indus-script thesis article endpoint. |
| 2026-07-04 | `https://safarmer.com/fsw2.pdf` | Verified PDF endpoint and inspected metadata from a temporary local copy. | Endpoint returned `200 OK`; PDF is 39 pages and about 1.4 MB. |
| 2026-07-04 | Internet Archive metadata for item `TheIndusScript.TextConcordanceAndTablesIravathanMahadevan` | Verified direct file records for M77, CISI volume 1, and CISI volume 2. | Metadata includes stable file names, sizes, hashes, and derivative OCR files. |
| 2026-07-04 | Mahadevan M77 PDF | Downloaded temporary copy and inspected with `pdfinfo`; checked derivative OCR for source-scope wording. | Direct custody complete at volume level; page-specific claim audit still required for sign-list details. |
| 2026-07-04 | CISI volume 1 PDF | Downloaded temporary copy and inspected with `pdfinfo`; checked derivative OCR for corpus-purpose and archive-production wording. | Direct custody complete at volume level; object-level claims still require page-specific audit. |
| 2026-07-04 | CISI volume 2 PDF | Downloaded temporary copy and inspected with `pdfinfo`; checked derivative OCR for Pakistan-collections scope and publication notes. | Direct custody complete at volume level; object-level claims still require page-specific audit. |
| 2026-07-04 | Tiedekirja CISI 3.1-3.3 product targets | Located official publisher/product URLs and bibliographic metadata through search surfaces; direct page opening is blocked by the publisher's anti-bot challenge. | Bibliographic custody improved, but direct volume custody remains incomplete. |
| 2026-07-04 | Fuls review of CISI 3.3 | Verified direct review PDF and public review surfaces. | Useful for series-level context and counts attributed to the review; not authority for object-level corpus claims. |

## Stronger-Use Boundary

Farmer/Sproat/Witzel can now support a bounded summary of the critique. M77 and
CISI volumes 1 and 2 now have direct volume-level custody. CISI volumes 3.1-3.3
have bibliographic custody through publisher targets and secondary review
surfaces, but not direct volume custody. None of these sources support
independent object-level or sign-level assertions until page-specific audit is
complete.
