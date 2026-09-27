# HPHIDB

Matrimony & wedding-services platform — Laravel 12 REST API backend (`backend-code (2).zip`) and MySQL development database (`mphidb_dev_db_file.zip`).

## Documentation

| Document | Purpose |
|---|---|
| [docs/SRS.md](docs/SRS.md) | Software Requirements Specification — functional & non-functional requirements, API catalogue (118 endpoints), data model, and a consolidated list of known issues found in the current build |
| [docs/USER_MANUAL.md](docs/USER_MANUAL.md) | User Manual for members, vendors and administrators, plus installation/operations, error reference and limits |
| [docs/appendix/DATA_DICTIONARY.md](docs/appendix/DATA_DICTIONARY.md) | Column-level data dictionary of `mphidb_dev` (47 tables, 2 views, 75 foreign keys), ER diagram, seeded data and schema/code discrepancies |

### Word editions

Formatted Microsoft Word versions of the same documents — cover page, clickable table of contents with page numbers, headers/footers, styled tables, callouts and embedded diagrams — are in [`docs/word/`](docs/word/):

| File | Pages |
|---|---|
| [docs/word/SRS.docx](docs/word/SRS.docx) | 41 |
| [docs/word/USER_MANUAL.docx](docs/word/USER_MANUAL.docx) | 24 |
| [docs/word/DATA_DICTIONARY.docx](docs/word/DATA_DICTIONARY.docx) | 51 |

Cross-document links in the Word files point to the sibling `.docx` files, so keep the three together.

The frontend SPA (expected at `FRONTEND_URL=http://localhost:5173`) is not included in this repository; the documents describe user-facing behaviour at the API level.
