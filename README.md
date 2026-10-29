# WaveWare Access Database Demo

Animal diet and nutrition tracking project developed around Texas State Aquarium workflows using Microsoft Access.

This is a **near-final representative copy**, not the actual final submission, a current aquarium system, or animal-care guidance.

## Preview

![WaveWare main menu in Microsoft Access, with diet, inventory, weight, and reporting options.](assets/waveware-main-menu.png)

Main-menu screenshot supplied by the project owner.

## Download

[Download the editable Access database](https://github.com/Saner108/waveware-access-demo/releases/download/waveware-near-final-demo-2026-10-28/WaveWare_NearFinal_Employee_Demo.accdb)

[Release notes](https://github.com/Saner108/waveware-access-demo/releases/tag/waveware-near-final-demo-2026-10-28)

[SHA-256 checksum](https://github.com/Saner108/waveware-access-demo/blob/main/CHECKSUMS.sha256)

The `.accdb` file is supplied as a release attachment. This standalone repository is separate from the personal portfolio website.

## Demo Passwords

| Prompt | Code |
| --- | --- |
| Open the database file | `2710` |
| Manager menu | `1234` |

These passwords are intentionally public for the demo. They provide no confidentiality for this download and must not be reused for a real deployment.

## Data Scope

- Four employee names were replaced with `Demo Employee01` through `Demo Employee04`.
- Employee IDs and existing manager/staff roles were preserved.
- Other aquarium records were retained unchanged with the project owner's explicit approval to share them publicly. **This is not a fully anonymized or fully synthetic dataset.**
- Existing tables, fields, indexes, relationships, queries, forms, reports, macros, and database settings were preserved.
- The original USB database was left unchanged.

## Open the Demo

1. Download the `.accdb` file and open a working copy in Microsoft Access on Windows.
2. Enter `2710` when prompted for the file-opening password.
3. Start on the main menu. **MANAGER DIET ADJUSTMENTS** uses code `1234`.
4. Review saved code and macros before enabling active content. Only enable content you trust.

Changes made while exploring may be saved to your downloaded copy.

## Verification and Limits

All 25 user tables and 69 records were compared against the source, allowing only the eight employee-name fields to change. Schema definitions and saved Access object storage were compared separately. Decoded database pages, including unused content, were scanned for the original first and last names in their original, lowercase, and uppercase forms.

The file-opening password was verified, and the saved manager macro still checks `1234`. Navigation, forms, queries, calculations, and reports have **not been tested in native Microsoft Access after this edit**. No production-readiness or clinical-accuracy claim is made.
