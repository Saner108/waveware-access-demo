# WaveWare Access Database Demo

An animal diet and nutrition tracking database developed around Texas State Aquarium workflows using Microsoft Access. It demonstrates how employee access, diet adjustments, inventory, weight tracking, and reporting can be organized in one Access application.

**This is a near-final representative demo, not the actual final submission, a current aquarium system, or animal-care guidance.**

**[Read the Project Documentation & User Guide (public PDF)](docs/WaveWare-Project-Documentation-Public.pdf)** — review the design, screenshots and documented workflows without opening Microsoft Access.

## What This Is

This repository provides a shareable copy of the WaveWare Access database. The downloadable `.accdb` file preserves the application's existing tables, fields, indexes, relationships, queries, forms, reports, macros, and database settings while replacing selected employee names with demo names.

The project is intended to show the database structure and workflow of the application, not to provide a production system or a complete clinical or animal-care solution.

## Why You Should Know This

This demo shows how Microsoft Access can connect operational data with forms, saved queries, reports, and role-based workflows. Reviewing it helps explain how the WaveWare application is organized and how a user can move from the main menu into diet, inventory, weight, and reporting features.

It also documents which data was changed for public sharing and which parts of the source database were preserved.

## What “Near-Final” Means

The release is a representative copy of the near-final database, not a finished production deployment. It is suitable for review and demonstration, but it does not claim that every workflow, form, query, calculation, macro, or report has been re-tested in native Microsoft Access after the sanitization edit.

## Explore the Demo

![WaveWare main menu in Microsoft Access, with diet, inventory, weight, and reporting options.](assets/waveware-main-menu.png)

The screenshot shows the application's main menu. The editable Access database is available as a release attachment:

[Download the editable Access database](https://github.com/Saner108/waveware-access-demo/releases/download/waveware-near-final-demo-2026-10-28/WaveWare_NearFinal_Employee_Demo.accdb)

| Resource | Purpose |
| --- | --- |
| [Project Documentation & User Guide](docs/WaveWare-Project-Documentation-Public.pdf) | Public-safe design narrative and source-version user manual; 27 pages with linked contents and bookmarks |
| [Access database release](https://github.com/Saner108/waveware-access-demo/releases/tag/waveware-near-final-demo-2026-10-28) | Download the `.accdb` demo and view release notes |
| [`CHECKSUMS.sha256`](CHECKSUMS.sha256) | Verify the downloaded database file |
| [`docs/CHECKSUMS.sha256`](docs/CHECKSUMS.sha256) | Verify the public PDF and two documentation preview images; paths are relative to the repository root |
| [`assets/waveware-main-menu.png`](assets/waveware-main-menu.png) | Preview the main application menu |

## Project Documentation & User Guide

The [public PDF](docs/WaveWare-Project-Documentation-Public.pdf) adapts the supplied April 21, 2026 report for portfolio sharing. Its public-edition notes are dated October 29, 2026. It includes the project context, conceptual database design, workflow descriptions, screenshots and a user manual.

| PDF pages | Contents |
| --- | --- |
| 2 | Public-edition scope, privacy changes and verification limits |
| 3–5 | Corrected, clickable contents |
| 6–11 | Executive summary, introduction and system analysis/design |
| 12–26 | Dashboard, animal/employee records, food lots, diet forms, alerts and reports |
| 27 | Conclusion and proposed follow-up checks |

The employee first and last name visible in a screenshot were permanently replaced with the generic labels **Demo** and **Employee**. Those labels are not a record-mapping claim about the separate release database. Other project records, including animal names, dates and numeric values, remain visible; the document is not fully anonymized or synthetic.

Overview, design and conclusion wording distinguishes **documented intentions from verified results**. The guide does not establish production use, measured efficiency gains, clinical accuracy or secure access controls. Its source-version screenshots and steps may differ from the near-final download. It is not official aquarium documentation or animal-care guidance. The original supplied PDF and existing Access release were not modified.

### Selected guide screenshots

These are static previews from the public guide, not new native Access test captures.

**Employee form — screenshot name replaced with generic demo text**

![WaveWare employee form with generic Demo and Employee name fields; identifier and manager role retained.](assets/waveware-employee-demo.png)

**Lot records — inventory and nutritional-input interface**

![WaveWare lot-record form with inventory quantities, nutritional-input fields and record navigation.](assets/waveware-lot-records.png)

## Demo Passwords

| Prompt | Code |
| --- | --- |
| Open the database file | `2710` |
| Manager menu | `1234` |

These passwords are intentionally public for the demo. They provide no confidentiality for this download and must not be reused for a real deployment.

## File Guide

### Access database

`WaveWare_NearFinal_Employee_Demo.accdb` is the editable Microsoft Access database supplied through the GitHub release. Open a working copy on Windows with Microsoft Access rather than editing the release attachment directly.

The file contains the preserved database objects and the publicly shareable employee-name substitutions described below. Changes made while exploring may be saved to your downloaded copy.

### Screenshot

`assets/waveware-main-menu.png` is a static preview of the main menu. It is provided for repository browsing and does not replace opening the database in Access.

### Project documentation

`docs/WaveWare-Project-Documentation-Public.pdf` is the public portfolio edition of the supplied project report. Its linked contents, PDF bookmarks and numbered footers refer to this 27-page edition. The two additional images above preview its employee and lot-record screens. Read page 2 for version, privacy and verification limits before following any workflow.

### Checksum

`CHECKSUMS.sha256` contains the SHA-256 digest for the release attachment. Use it to confirm that the downloaded file matches the published demo artifact.

## Open the Demo

1. Download the `.accdb` file from the GitHub release and open a working copy in Microsoft Access on Windows.
2. Enter `2710` when prompted for the file-opening password.
3. Start on the main menu. **MANAGER DIET ADJUSTMENTS** uses code `1234`.
4. Review saved code and macros before enabling active content. Only enable content you trust.
5. Explore the application using the downloaded copy so the release attachment remains unchanged.

## What Changed

Four employee names were replaced with `Demo Employee01` through `Demo Employee04`. Employee IDs and existing manager/staff roles were preserved.

Other aquarium records were retained unchanged with the project owner's explicit approval to share them publicly. Existing tables, fields, indexes, relationships, queries, forms, reports, macros, and database settings were preserved. The original USB database was not modified.

## Important Limits

- This is not a fully anonymized or fully synthetic dataset. Other aquarium records remain in the database.
- The demo is not a current aquarium system, the actual final submission, or animal-care guidance.
- The public passwords provide no confidentiality and must not be reused in a real deployment.
- Navigation, forms, queries, calculations, and reports have not been tested in native Microsoft Access after this edit.
- Review saved code and macros before enabling active content; only enable content you trust.
- No production-readiness or clinical-accuracy claim is made.

## Checks Performed

All 25 user tables and 69 records were compared against the source, allowing only the eight employee-name fields to change. Schema definitions and saved Access object storage were compared separately. Decoded database pages, including unused content, were scanned for the original first and last names in their original, lowercase, and uppercase forms.

The file-opening password was verified, and the saved manager macro still checks `1234`. The checksum file records the SHA-256 digest for the release attachment.

### Documentation publication checks — October 29, 2026

- Rendered all 27 public PDF pages for visual review; checked all 31 contents links and 11 PDF bookmarks against their destination pages.
- Reviewed the source screenshots and scanned the public embedded images, rendered pages and two preview images with local OCR. The removed employee first and last name were not found in that scan or in extracted PDF text. This is a scoped sharing check, not a guarantee of complete anonymization.
- Removed the original name-bearing image data through PDF redaction and saved a new, non-incremental PDF with unused objects discarded. Reviewed the replacement employee fields visually.
- Checked generic document metadata, absence of embedded attachments and JavaScript, and SHA-256 hashes for the public PDF/previews. The original supplied PDF remained byte-for-byte unchanged.
- No database edits, release replacement, native Access workflow tests, calculation validation or live deployment were performed for this documentation update. The earlier database-artifact checks above are not new tests from this publication.
