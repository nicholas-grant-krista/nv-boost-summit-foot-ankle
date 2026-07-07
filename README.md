# {{CUSTOMER_NAME}} — NVM Boost

Customer delivery repo. Created and maintained by Krista.

- **Customer:** {{CUSTOMER_NAME}}
- **Slug:** {{CUSTOMER_SLUG}}
- **Domain:** {{DOMAIN}}
- **Active Lines:** {{ACTIVE_LINES}}

## Structure

| Folder | Contents |
|---|---|
| `/docs` | Landing page HTML, served via GitHub Pages (source: `main` / `/docs`) |
| `/reports` | PDF deliverables — performance reports, audits |
| `/campaigns` | Ad copy, email campaigns, search campaign specs |
| `/context` | Per-customer context store, read and written by Boost skills |

## Conventions

- Krista commits directly to `main`. No branches, no PRs.
- Commit message format: `[<Line Name>] <description> – YYYY-MM-DD`
- Multi-file deliverables land as a single atomic commit (Commit Files request).
- Placeholder tokens (`{{...}}`) are resolved by Krista at provisioning time.

## Do not edit manually

Manual edits are not blocked, but Krista is the system of record. If a manual change is needed, use the same commit message convention so the log stays a clean delivery history.
