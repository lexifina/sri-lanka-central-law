# Central Province (Sri Lanka): legislative texts in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Central, Sri Lanka, which global-law reads at `sri-lanka/central/acts/`.

English texts published by the Central Provincial Council in the Gazette Extraordinary, Part IV (A). This is a partial collection of texts as published. Amendments have not been consolidated into their enabling statutes, and current in-force completeness has not been established.

| Record | What it contains | Date basis |
| --- | --- | --- |
| Existing statute folders | Four statutes as published, oldest version available | Gazette publication dates retained from the earlier record; assent-based commencement remains to be checked |
| `mineral-tax-order-2014/000-text.md` | The full English mineral tax order under section 9(1), including its signature and office date | 2014-04-01, explicitly stated in the order |

The Council's catalogue entry numbered 1996-03 links to this order, not to the full Finance (Supplementary Provisions) Statute No. 03 of 1996. The enabling statute remains outside this collection. The order's wording “five per centum (0.5%)” is preserved as published; this record does not resolve that inconsistency.

## Source and language

[Central Provincial Council: statutes](https://www.cp.gov.lk/web/statutes/?lang=en), with the English Gazette PDFs linked by the Council. English only; the official texts' language-precedence clauses remain in the text. No OCR text is included in this addition.

## Reading the history

Each folder represents a legislative instrument. The mineral tax order is a single file because its body is one operative paragraph. `git log -- mineral-tax-order-2014` shows its recorded version, and `git blame mineral-tax-order-2014/000-text.md` identifies its publisher credit. There is one version, labelled oldest version available; this is not a consolidated history.

## Verification and credits

The mineral tax order's paragraphs were compared against an independent reading of the official PDF, with every paragraph present and no trailing official text missing. Versions also undergo the repository's corpus and commit-trailer checks. Commits for first available texts are attributed to the publisher; Lexifina is the committer. Earlier statutes retain their existing text and date conventions.

## Limits

The Council's listing contains records without English files and records without linked texts. Other English PDFs remain outside this addition pending reliable extraction, scan transcription checks, or commencement verification. Full current-text coverage and later amendments have not been established.

## Licence

Official legislative texts and official translations are excluded from copyright protection by Sri Lanka's Intellectual Property Act No. 36 of 2003, section 8. Source credit: Central Provincial Council; Gazette of the Democratic Socialist Republic of Sri Lanka, Department of Government Printing. See [LICENSE](LICENSE).
