# Trip Ledger release website

This folder contains the static V1 landing, Support, and Privacy pages intended for public hosting before TestFlight/App Store submission.

## Publication blockers

Replace every bracketed placeholder before publication:

- `[SUPPORT_EMAIL]`
- `[PUBLISHER LEGAL NAME]`
- `[PUBLICATION DATE]`

Then confirm the public URLs and add them to `03_Product_Documents/APP_STORE_CONNECT_METADATA_DRAFT.md`.

## Local preview

Open `index.html` directly in a browser or serve this directory with a local static-file server. No build step, JavaScript, cookies, analytics, fonts, or third-party assets are required.

## Pre-publication verification

1. Search recursively for `[` and confirm no placeholders remain.
2. Check all three pages in narrow and wide layouts and in Light/Dark Mode.
3. Confirm keyboard navigation and visible focus behavior.
4. Validate HTML and verify every internal and external link.
5. Confirm the final policy against the exact release candidate and App Store privacy answers.
6. Confirm the support mailbox is monitored.

The Bank of Canada links document the external reference-rate service. Trip Ledger's developer does not receive the Bank's request logs, but the Bank states that its web servers may record IP address and request metadata.

