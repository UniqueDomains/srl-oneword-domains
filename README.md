# Available .SRL One-Word Domains (16,909)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-16%2C909%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .srl one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **16,909 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 16,909 domains · **Median ask:** $37.25 · **High-demand under $2,500:** 21

**Last updated:** 2026-08-18
**Canonical page:** `https://unique.domains/domains/tld/srl`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/srl?utm_source=github&utm_medium=referral&utm_campaign=repo_srl_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./srl.csv">CSV</a> / <a href="./srl.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_srl_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_srl_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SRL search](https://unique.domains/domains/tld/srl?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_srl_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SRL search](https://unique.domains/domains/tld/srl?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_srl_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_srl_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SRL one-word domain catalog.

### Files

- `srl.csv`, public CSV extract (1,000 rows)
- `srl.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/srl-oneword-domains/main/srl.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain   | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| -------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| add.srl  | available | $31.99    | $31.99        | high           | low    | 3      | namesilo  |
| see.srl  | premium   | $54.28    | $30.68        | high           | low    | 3      | namesilo  |
| bce.srl  | available | $31.99    | $31.99        | medium         | low    | 3      | namesilo  |
| able.srl | premium   | $57.50    | $32.50        | high           | low    | 4      | name.com  |
| btw.srl  | available | $31.99    | $31.99        | high           | low    | 3      | namesilo  |
| auto.srl | premium   | $54.28    | $30.68        | medium         | medium | 4      | namesilo  |
| ego.srl  | available | $31.99    | $31.99        | medium         | low    | 3      | namesilo  |
| boat.srl | premium   | $54.28    | $30.68        | high           | low    | 4      | namesilo  |
| gal.srl  | available | $31.99    | $31.99        | medium         | low    | 3      | namesilo  |
| city.srl | premium   | $54.28    | $30.68        | high           | medium | 4      | namesilo  |
| hug.srl  | available | $31.99    | $31.99        | high           | low    | 3      | namesilo  |
| fill.srl | premium   | $54.28    | $30.68        | medium         | low    | 4      | namesilo  |
| ice.srl  | available | $31.99    | $31.99        | medium         | medium | 3      | namesilo  |
| fish.srl | premium   | $54.28    | $30.68        | high           | low    | 4      | namesilo  |
| ink.srl  | available | $31.99    | $31.99        | high           | medium | 3      | namesilo  |
| goal.srl | premium   | $54.28    | $30.68        | high           | low    | 4      | namesilo  |
| jan.srl  | available | $31.99    | $31.99        | high           | low    | 3      | namesilo  |
| good.srl | premium   | $57.50    | $32.50        | high           | medium | 4      | name.com  |
| jot.srl  | available | $31.99    | $31.99        | high           | low    | 3      | namesilo  |
| hill.srl | premium   | $54.28    | $30.68        | medium         | low    | 4      | namesilo  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 16,909 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 21 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/srl?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_srl_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/srl?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_srl_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_srl_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list of domains covers one-word names on the .srl extension, an uncommon TLD where 11,778 of 12,549 entries are still available and 767 carry premium status. Pricing sits far below typical premium markets: 11,473 domains ask under $500, with a median around $38.14. Demand is thin overall — 12,148 fall into the low bucket — but a small top tier (20 domains) scores in the top 15% for demand, and a handful, like show.srl and watch.srl, show large gaps between ask price and reference price.

- 11,778 of 12,549 .srl domains are available now
- Median ask ~$38.14, with 11,473 domains under $500
- Only 46 domains rank mid-to-high on demand
- 767 domains carry premium status

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SRL One-Word Domains*. Version 2026-08-18. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SRL page](https://unique.domains/domains/tld/srl?utm_source=github&utm_medium=referral&utm_campaign=repo_srl_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_srl_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_srl_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_srl_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
