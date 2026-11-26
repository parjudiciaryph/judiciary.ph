# Philippine Judicial Archive

A responsive, military-inspired prototype for organizing judicial records and a separate leadership directory.

## Archive

- Supreme Court decisions and resolutions
- Court of Appeals decisions
- Court Martial decisions
- A browsable tabular list with case title, docket, court, type, date, and division/panel
- Search and court/record-type filters
- Detail view with optional source-document link
- Admin form to add records; resolutions are limited to Supreme Court entries

## Leadership directory

The leadership section is distinct from court hierarchy. It lists positions in display order with the office holder and, where available, a source link. Manage Directory lets administrators add or replace a position and holder in local browser storage. The default names and links are starting reference data, not a live feed; verify and maintain them from official sources. Court-martial convening authority is case- and order-dependent and is not represented as a single permanent command chain.

## Run locally

Open `index.html` in a modern browser. No build process or packages are required.

## Production requirements

This is not a secure or official records system. Production deployment needs server-side storage, authenticated role-based administration, validated document uploads, audit logs, backups, access controls, and a process to verify archive records and leadership information against authoritative publications.
