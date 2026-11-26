# Judiciary Decisions Archive

A responsive, single-page archive prototype for organizing decisions from the Supreme Court, Court of Appeals, and Courts Martial, plus Supreme Court resolutions.

## Run locally

Open `index.html` in a modern browser. No build step or dependencies are required.

## Included

- Search by case number, case title, court, issuing division/panel, author, or notes.
- Filter records by court and by decision/resolution type.
- Record details with optional source-document links.
- An add-record portal with basic required-field validation. Resolutions are restricted to Supreme Court entries.
- Court/division-or-panel/record hierarchy fields to make each record's issuing structure visible.
- Browser-local persistence using `localStorage`.

## Important production limitation

This is a front-end prototype, not a secure or shared records system. Anyone who can access the page can use the add-record form, and records are saved only in the current browser. For real publication, connect the interface to a server-side database and authenticated, role-based admin API; validate uploads and URLs server-side; keep an audit log; and use access controls and backups. Do not treat illustrative or user-entered records as official without verifying them against authoritative court publications.
