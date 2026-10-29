# WaveWare Access Database Demo

An animal diet and nutrition tracking database developed around Texas State Aquarium workflows using Microsoft Access. It demonstrates how employee access, diet adjustments, inventory, weight tracking, and reporting can be organized in one Access application.

**This is a near-final representative demo, not the actual final submission, a current aquarium system, or animal-care guidance.**

## What This Is

This repository provides a shareable copy of the WaveWare Access database. The downloadable `.accdb` file preserves the application's existing tables, fields, indexes, relationships, queries, forms, reports, macros, and database settings while replacing selected employee names with demo names.

The project is intended to show the database structure and workflow of the application, not to provide a production system or a complete clinical or animal-care solution.

## Why You Should Know This

This demo shows how Microsoft Access can connect operational data with forms, saved queries, reports, and role-based workflows. Reviewing it helps explain how the WaveWare application is organized and how a user can move from the main menu into diet, inventory, weight, and reporting features.

It also documents which data was changed for public sharing and which parts of the source database were preserved.

## What “Near-Final” Means

The release is a representative copy of the near-final database, not a finished production deployment. It is suitable for review and demonstration, but it does not claim that every workflow, form, query, calculation, macro, or report has been re-tested in native Microsoft Access after the sanitization edit.

The original USB database was left unchanged. This repository and its release attachment are separate from the personal portfolio website.

## Explore the Demo

![WaveWare main menu in Microsoft Access, with diet, inventory, weight, and reporting options.](assets/waveware-main-menu.png)

The screenshot shows the application's main menu. The editable Access database is available as a release attachment:

[Download the editable Access database](https://github.com/Saner108/waveware-access-demo/releases/download/waveware-near-final-demo-2026-10-28/WaveWare_NearFinal_Employee_Demo.accdb)

| Resource | Purpose |
| --- | --- |
| [Access database release](https://github.com/Saner108/waveware-access-demo/releases/tag/waveware-near-final-demo-2026-10-28) | Download the `.accdb` demo and view release notes |
| [`CHECKSUMS.sha256`](CHECKSUMS.sha256) | Verify the downloaded database file |
| [`assets/waveware-main-menu.png`](assets/waveware-main-menu.png) | Preview the main application menu |

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
