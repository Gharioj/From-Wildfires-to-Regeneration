# Outreach Workspace — Salento

This directory is the authoritative outreach workspace for the Salento (Terra d'Otranto, Puglia) territorial campaign of the From-Wildfires-to-Regeneration project. It is the single place where contact management and outreach communications for potential Patrons, Strategic Partners, Introducers, Public Figures, and Organisations in Salento are created, maintained, and tracked.

This is one of several territorial campaigns under `outreach/`. See `outreach/README.md` for the overview of all territorial campaigns.

## Files

- **contacts.csv** — The single source of truth for all Salento outreach contacts.
- **email-addresses.txt** — Generated from `contacts.csv`. Do not edit manually.
- **master-email.md** — The master outreach email template for the Salento campaign.
- **patron-candidates-email.md**, **corporate-patrons-email.md**, **strategic-partners-email.md**, **introducers-email.md**, **public-figures-email.md**, **organisations-email.md** — Audience-tailored email templates derived from `master-email.md`.
- **batches/** — Per-audience CSV extracts and matching email-address lists, generated from `contacts.csv`.
- **output/** — Personalised, merge-resolved emails generated for every contact, organised by audience batch. Ready for review before sending.
- **sent-log.csv** — Records outreach history: what was sent, to whom, when, and its status.

## Rules

- All future Salento contacts are added here only.
- No duplicate contacts.
- No manual administration where automation is possible.
