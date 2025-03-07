# ISO Standards List

*2024-03-07*

This repository keeps the recent ISO standards list (updated at 2024-03-06). The dataset contains in-active and abandoned standards, international classification for standards (ICS), and TC/SC in responsible.

The repository is consisting of 2 files:

1. `harmonized_stage_code.json`: here is the same as https://www.iso.org/stage-codes.html but machine-readable format, JSON object.
2. `iso_standards_20250306_final.csv`: the following is a metadata for this file.

## Metadata

| Field | Description | Possible Values |
|---|---|---|
| `standards` | The standard code for ISO standards | e.g., `ISO 9001`, `ISO/IEC 27001` |
| `part` | The part of such ISO standard | string |
| `edition` | The year that published this standard | 4-digit year |
| `title` | The full name of ISO standard | e.g. `ISO 9001:2015 - Quality management systems — Requirements` |
| `flag` | The indication of the standard for editing, correction, or supplementary information | `Add`: Addendum, `PDAM`, `DAmd`, `Amd`: Amendment, `Cor`: Corrigendum, `Suppl`: Supplement, etc. |
| `LXName` | Level `X` name for title | string |
| `title` | Full title for ISO standard | string |
| `pubDate` | Publication date | Datetime (`YYYY-MM-DD`) |
| `stage` | Harmonized stage code | As `harmonized_stage_code.json` |
| `TC/SC` | Responsible echnical subcommittee | TC/SC in ISO |
| `ICS` | International Classification of Standards | ICS classification |
