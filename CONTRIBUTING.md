# Contributing to Awesome Neobanks

Thank you for helping keep this list accurate and comprehensive!

## How to Add an Entry

1. **Fork** this repository and create a new branch.
2. **Add** the entry to the correct section in `README.md`.
3. **Add** the same entry to `_data/neobanks.yml` or `_data/payment_systems.yml` (for the website).
4. **Submit** a pull request with a brief description.

## Criteria

An entry is accepted if it meets **all** of the following:

- ✅ The service is **live and publicly accessible**
- ✅ It is a **neobank, digital bank, or payment service** (not a traditional brick-and-mortar bank)
- ✅ The description is **neutral, factual, and under 120 characters**
- ✅ There is **no duplicate** of an existing entry
- ✅ The link is **direct** — no referral or affiliate URLs

## What is NOT accepted

- ❌ Services that are closed, in stealth mode, or invite-only
- ❌ Traditional banks without a meaningful digital-first offering
- ❌ Marketing copy or promotional language in the description
- ❌ Duplicate entries

## README format

```markdown
| [Name](https://example.com) | 🇺🇸 US | Concise, neutral description under 120 characters |
```

## YAML format (for the website)

### Neobank entry (`_data/neobanks.yml`)

```yaml
- name: Example Bank
  url: https://examplebank.com
  description: "Concise, neutral description of the service"
  region: Europe        # Europe | Americas | Asia-Pacific | Middle East & Africa
  countries: [UK, DE]   # ISO 2-letter country codes
  tags: [cards, savings, business]
  founded: 2020
  hq: "London, UK"
```

### Payment system entry (`_data/payment_systems.yml`)

```yaml
- name: Example Pay
  url: https://examplepay.com
  description: "Concise, neutral description of the service"
  category: Payment Gateway   # Payment Gateway | Cross-Border | BNPL | Open Banking | Banking-as-a-Service | Crypto Payments
  region: Global              # Global | Europe | Americas | Asia-Pacific
  tags: [API, merchants]
  founded: 2018
  hq: "New York, US"
```

## Questions?

Open an [issue](https://github.com/ittermit/awesome-neobanks/issues) — happy to help.
