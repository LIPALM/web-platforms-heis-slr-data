# Supplementary data: Integrated Web Platforms for Administrative Support and Tickets Management in Higher Education: A Systematic Review

This repository accompanies the manuscript by Lucas Lipa Matta and Mario Rolando Chura Ortiz (submitted to the *Journal on Interactive Systems*, JIS). It documents the **41 original articles (AO, studies S1–S41)** included in the review, together with the search strategy and the evidence used in the synthesis. The 10 secondary systematic reviews (SLRs) discussed in the Related Work section are not part of this dataset.

## Contents

| File | Description |
|---|---|
| `data/01_included_original_articles.csv` | The 41 included original articles: ID (S1–S41, same numbering as Table 6 of the manuscript), authors, year, title, venue, item type, volume, issue, pages, DOI, URL, ISSN/ISBN, language. |
| `data/02_search_strings.csv` | Boolean search string of each functional block (A–G) and the date each search was run. |
| `data/03_search_results_by_database.csv` | Number of records returned by each database for each block, with the filters and content-type breakdown shown by the platforms. |
| `data/04_evidence_support_matrix.csv` | One row per study (S1–S41) with the functional module, architecture pattern, development methodology and AI component, plus 0/1 indicators for access-control, validation, workflow and challenge categories. It reproduces the study lists cited in Tables 7–10 and the Results section of the manuscript. |
| `data/05_selection_summary_by_block.csv` | Raw results, review-filter counts and number of included SLRs and AO per block (Table 5 of the manuscript). |

## Method summary

- **Protocol:** Kitchenham guidelines and PRISMA 2020.
- **Search dates:** 18 August 2026 for blocks A–G; 2 November 2026 for the complementary search in SBC OpenLib (SOL).
- **Period covered:** 2000–2026.
- **Eligibility:** peer-reviewed journal and conference articles in English or Spanish reporting software prototypes, experimental tests, process simulation or performance analysis, on tickets/ITSM, complaints, queues, visitor access, hierarchical workflows or digital transformation in higher education (see Tables 3–4 of the manuscript).
- **Result:** 91,060 raw records → 10 SLRs + 41 AO = 51 included studies.

## Notes on the data

- Study IDs follow the order of Table 6 of the manuscript.
- In `03_search_results_by_database.csv`, content-type counts on SpringerLink and ScienceDirect are the facets shown by each platform and may overlap; the block totals match Table 5 of the manuscript.
- `04_evidence_support_matrix.csv` is derived from the synthesis tables of the manuscript, not from an independent re-extraction.
- Bibliographic metadata was exported from Zotero (DOI.org/Crossref and publisher records). The full texts of the articles are **not** redistributed here; use the DOI to access them from the publishers.

## How to cite

Lipa Matta, L., & Chura Ortiz, M. R. (2027). *Integrated Web Platforms for Administrative Support and Tickets Management in Higher Education: A Systematic Review* [Supplementary data]. DOI: *to be added after Zenodo deposit*.

## License

Data in this repository: Creative Commons Attribution 4.0 International (CC BY 4.0), consistent with the journal's license.
