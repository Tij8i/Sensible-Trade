# Sensible Trade

Website for Sensible Trade — connecting Italian producers with Australian distributors.

## Live Site

https://sensibletrade.co

## Domain & Hosting

| Item | Details |
|------|---------|
| **Domain** | sensibletrade.co |
| **Registrar** | GoDaddy |
| **Registered** | January 19, 2026 |
| **Expires** | January 19, 2027 |
| **Hosting** | GitHub Pages |

## Email Infrastructure

| Item | Details |
|------|---------|
| **Provider** | Zoho Mail Lite (€12/year) |
| **Primary Inbox** | contact@sensibletrade.co |
| **Distribution Group** | alessiotixi@sensibletrade.co |

**Note:** The naming is inverted from ideal (alessiotixi@ should be the inbox, contact@ should forward), but this is the current setup.

### DNS Records (GoDaddy)

- **MX Records**: Zoho MX servers
- **SPF**: Configured for Zoho
- **DKIM**: Configured via Zoho

## Structure

- Jekyll-based static site
- Hosted on GitHub Pages
- Bilingual: English (/) and Italian (/it/)
- Single-page design with anchor navigation

## Pages

| Path | Description |
|------|-------------|
| `/` | English homepage |
| `/it/` | Italian homepage |
| `/producers/` | English producer landing page |
| `/it/produttori/` | Italian producer landing page |

## Sections

- Hero: Main value proposition
- What We Do: Product Sourcing, Export & Compliance, Logistics, Marketing
- Who We Work With: Target customer segments
- Why Work With Us: Value proposition
- Our Services: 4-column service overview
- Producer CTA: Link to producer page
- Contact: Email link

## Images

Located in `assets/img/`:
- `deli-shelf.jpg` — "Who we work with" section
- `liguria-coast.jpg` — "Why work with us" section

## Development

```bash
bundle install
bundle exec jekyll serve
```

## Related Systems

### Notion Databases
- **SG Prospect Database** — Companies (shared with Sensible Growth)
- **Contacts Database** — Individual contacts linked to companies
- **Conversations Log** — Conversation history linked to contacts

All three databases are linked: Conversations → Contacts → Companies
