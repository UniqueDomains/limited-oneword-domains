# Available .LIMITED One-Word Domains (12,274)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C274%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .limited one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,274 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,274 domains · **Median ask:** $18.84 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/limited`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/limited?utm_source=github&utm_medium=referral&utm_campaign=repo_limited_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./limited.csv">CSV</a> / <a href="./limited.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_limited_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_limited_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LIMITED search](https://unique.domains/domains/tld/limited?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_limited_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LIMITED search](https://unique.domains/domains/tld/limited?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_limited_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_limited_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LIMITED one-word domain catalog.

### Files

- `limited.csv` — public CSV extract (1,000 rows)
- `limited.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/limited-oneword-domains/main/limited.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| WiFi.limited      | available | $39.98    | —             | 83             | 37     | 5      | namecheap        |
| finals.limited    | available | $14.99    | —             | 80             | 7      | 6      | name.com         |
| ladies.limited    | available | $14.99    | —             | 80             | 17     | 6      | name.com         |
| getup.limited     | available | $14.99    | —             | 82             | 14     | 6      | name.com         |
| matcha.limited    | available | $14.99    | —             | 86             | 39     | 6      | name.com         |
| useit.limited     | available | $14.99    | —             | 94             | 7      | 6      | name.com         |
| edamame.limited   | available | $14.99    | —             | 80             | 9      | 7      | name.com         |
| playin.limited    | available | $14.99    | —             | 80             | 10     | 7      | name.com         |
| makeit.limited    | available | $14.99    | —             | 82             | 22     | 7      | name.com         |
| stirup.limited    | available | $14.99    | —             | 82             | 3      | 7      | name.com         |
| presents.limited  | available | $14.99    | —             | 80             | 9      | 8      | name.com         |
| shortcuts.limited | available | $14.99    | —             | 48             | 41     | 10     | name.com         |
| robots.limited    | resell    | —         | —             | 62             | 47     | 6      | Dynadot Inc      |
| jobs.limited      | premium   | $82.50    | —             | 79             | 42     | 4      | name.com         |
| grow.limited      | resell    | —         | —             | 80             | 42     | 4      | GoDaddy.com, LLC |
| homes.limited     | premium   | $123.75   | —             | 86             | 34     | 5      | name.com         |
| justin.limited    | available | $14.99    | —             | 58             | 38     | 7      | name.com         |
| tickets.limited   | premium   | $78.54    | $78.54        | 64             | 34     | 7      | namesilo         |
| spaces.limited    | premium   | $123.75   | —             | 54             | 30     | 6      | name.com         |
| stories.limited   | available | $14.99    | —             | 58             | 36     | 7      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,274 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/limited?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_limited_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/limited?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_limited_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_limited_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set is defined by one filter: the .limited extension. The result is a broad pool of single-word names ranging from generic terms like finals.limited and jewels.limited to shorter brand-style options like Acup.limited and Trex.limited. For founders, the main question is whether the word still feels clear and credible with .limited attached. For investors, the key check is whether the term has enough commercial relevance to justify attention beyond a low ask. When comparing these domains, focus on word quality first, then pricing, then any obvious trademark sensitivity in terms such as WiFi.limited or Trex.limited.

- Prioritize clear words that still read naturally with .limited
- Use median ask of 18.84 as a rough price anchor
- Check trademark exposure on branded or protected terms
- Favor concise dictionary words over awkward constructions

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LIMITED One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LIMITED page](https://unique.domains/domains/tld/limited?utm_source=github&utm_medium=referral&utm_campaign=repo_limited_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_limited_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_limited_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_limited_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
