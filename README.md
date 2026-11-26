# Philippine Judicial Archive

A responsive, military-inspired prototype for the public archive of:

- Supreme Court decisions and resolutions
- Court of Appeals decisions
- Court Martial decisions

## Current prototype behavior

- Decisions are presented as a browsable table, with search and court/type filters.
- The leadership directory is separate from case hierarchy. It starts empty and supports ordered positions and position holders.
- Archive records and directory entries can be added only after entering the requested password in the front-end admin gate.
- Existing v1 prototype data is cleared from the browser's local storage when the updated page loads; the new archive and directory start empty.
- Court collection, leadership directory, archive, and About navigation links scroll directly to their sections.
- All data remains in the current browser's local storage; it is not shared across visitors.

## Important security limitation

`JUDICIARY2026` is embedded in this static page's JavaScript. This is a convenience gate, not secure authentication: visitors can inspect the source and bypass it. Do not use it to protect confidential records or rely on it for real admin security. A production system needs a server-side authentication service, authorization checks on every write, a shared database, audit logging, backups, and appropriate access controls. The password should be rotated and stored server-side before any production use.

## Run locally

Open `index.html` in a modern browser. No build process or packages are required.
