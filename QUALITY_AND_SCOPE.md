# FE Civil Prep — Source/figure integrity and answer audit

## Precisely what is included

The site contains 2,294 numbered source positions (Learnova main: 1,052; M. R. Islam main: 802; four Learnova exams: 4 × 110). It also contains **1,824 exact source-page visual renderings** (809 + 638 + 98 + 95 + 96 + 88) from the user-provided PDF documents. These make every original printed diagram, equation, table and answer available in the page reader, without relying on OCR or rebuilding every drawing.

The vector illustrations (65 cards) are convenient study supplements, **not replacements** for the exact original page images. Each main-book/companion-exam question has a `sourcePage`, and all 1,052 main Learnova questions plus 440 companion-exam questions have a `solutionPage`. The Islam author solutions appear near the questions or on following pages, accessible in the same book reader.

## Engineering grading and unresolved risks

| Review category | Count | Website grading |
|---|---:|---|
| Targeted manually reconstructed/checked | 91 | Enabled, not professional certification |
| Provisional publisher-answer transcriptions | 791 | Enabled as provisional source-key comparison only |
| Review-only (including scanned/OCR and companion exams) | 1,412 | Disabled |
| **All indexed records** | **2,294** | **882 eligible** |

The manually checked work is a limited review, not an independent technical audit of all source problems. Existing publisher misprints, wrong explanations and ambiguous or inconsistent data may remain. Scanned OCR text is hidden by default when unreliable; the source-page image is the primary source. The four companion exams are indexed to exact question and solution pages but not automatically graded or independently solved.

The M. R. Islam file includes supplementary scanned chapters/exercises beyond the 802 main numbered items; all pages are present in the full-page viewer, but this extra material is not individually indexed as graded questions. Problems split over page boundaries can be viewed with **Next page**.

## Programmatic integrity tests conducted

- Checked that there are 2,294 unique source IDs, and each source/problem/solution page reference falls within its corresponding PDF.
- Mapped 440/440 companion exam positions to question and solution pages using source text headings.
- Verified all 1,824 page images are encoded as intact WebP data in the advertised JavaScript bundles.
- Verified each page-image bundle name, count and first/last page against the six PDF lengths.
- Verified application syntax and browser loading of representative Learnova, Islam, and companion-exam question and solution page images, including the final companion-exam page, using an isolated browser fixture.
- Checked principal navigation, answer reveal, book selection and next/previous page controls.

Not claimed: visual inspection of all 1,824 raster pages, independent mathematical checking of 2,294 answer keys, or a live GitHub-hosted deployment test. The site is not an NCEES practice exam or a certified FE readiness assessment.

## Source and redistribution rights

Learnova material is marked © 2025, and M. R. Islam material is also copyrighted. The user states they have publisher permission; the scope of that permission has **not** been independently verified. The NCEES handbook is not packaged in this version. Public hosting should proceed only when permission for web redistribution is confirmed.
