# Outreach Workspace

This directory is the authoritative outreach workspace for the From-Wildfires-to-Regeneration project's Patron, Strategic Partner, Introducer, Public Figure, and Organisation outreach. It is organised by territorial campaign, one subdirectory per territory.

## Territorial campaigns

- **[Sicilia/](Sicilia/)** — the original campaign, covering Sicily.
- **[Salento/](Salento/)** — the Salento (Puglia) campaign.

Each territorial campaign directory is self-contained and follows the same internal structure and methodology:

- **contacts.csv** — the single source of truth for that territory's outreach contacts.
- **email-addresses.txt** — generated from `contacts.csv`. Do not edit manually.
- **master-email.md** — the master outreach email template for that territory.
- **patron-candidates-email.md**, **corporate-patrons-email.md**, **strategic-partners-email.md**, **introducers-email.md**, **public-figures-email.md**, **organisations-email.md** — audience-tailored email templates derived from `master-email.md`.
- **batches/** — per-audience CSV extracts and matching email-address lists, generated from `contacts.csv`.
- **output/** — personalised, merge-resolved emails generated for every contact, organised by audience batch. Ready for review before sending.
- **sent-log.csv** — records outreach history for that territory.
- **README.md** — territory-specific documentation.

## Rules

- Contacts belong in their territory's `contacts.csv` only — no cross-territory mixing.
- No duplicate contacts within a territory.
- No manual administration where automation is possible.
- New territorial campaigns should follow the same structure and methodology as Sicilia and Salento.
