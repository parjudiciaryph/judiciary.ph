# Philippine Judicial Archive

A responsive prototype for browsing court decisions and Supreme Court resolutions, with a separate leadership directory.

## Features

- Searchable, filterable table of archive records
- Supreme Court, Court of Appeals, and Courts-Martial overview and project-provided court descriptions
- Ordered positions and office holders in a separate directory, initially empty
- Password prompt for adding records and managing the directory
- Browser-local data storage; no backend or shared data
- Responsive layout and in-page navigation

## Court information

The descriptive text in the court-information section was provided by the project owner. It has not been independently verified and may contain errors about court composition, jurisdiction, or military justice. It is prominently labeled as unverified draft material. Confirm all claims with current Philippine law and authoritative sources before publishing or relying on it.

## Run locally

Open `index.html` in a modern browser. No build process or packages are required.

## Security and production limitations

The `JUDICIARY2026` value is embedded in static JavaScript. This is only a convenience gate; anyone can inspect or bypass it. It is not secure authentication and must not protect confidential data. A real deployment needs server-side identity and authorization, a shared database, audit logging, backups, and controls on every write. Records and directory data remain in the current visitor's browser.

The page clears previous v1/v2 prototype records and directory entries once per browser using a migration marker, and starts the v3 archive and roster empty.
