# Available .SHOP One-Word Domains (4,434)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-4%2C434%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .shop one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **4,434 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 4,434 domains · **Median ask:** $1,021.95 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/shop`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/shop?utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./shop.csv">CSV</a> / <a href="./shop.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SHOP search](https://unique.domains/domains/tld/shop?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SHOP search](https://unique.domains/domains/tld/shop?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SHOP one-word domain catalog.

### Files

- `shop.csv` — public CSV extract (1,000 rows)
- `shop.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/shop-oneword-domains/main/shop.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain               | status    | ask_price | renewal_price | attractiveness | demand | length | registrar    |
| -------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------ |
| barup.shop           | available | $2.99     | —             | 82             | 2      | 6      | name.com     |
| Maidens.shop         | available | $48.98    | —             | 80             | 4      | 7      | namecheap    |
| Rhianna.shop         | available | $48.98    | —             | 81             | 3      | 7      | namecheap    |
| comeby.shop          | available | $2.99     | —             | 82             | 3      | 7      | name.com     |
| gelpen.shop          | available | $2.99     | —             | 82             | 1      | 7      | name.com     |
| kangeroo.shop        | available | $2.99     | —             | 80             | 1      | 8      | name.com     |
| memorise.shop        | available | $2.99     | —             | 84             | 6      | 8      | name.com     |
| dogstail.shop        | available | $2.99     | —             | 94             | 1      | 8      | name.com     |
| makenews.shop        | available | $2.99     | —             | 80             | 1      | 9      | name.com     |
| showering.shop       | available | $2.99     | —             | 80             | 2      | 9      | name.com     |
| embracing.shop       | available | $2.99     | —             | 82             | 4      | 9      | name.com     |
| OKboomer.shop        | available | $48.98    | —             | 82             | 6      | 9      | namecheap    |
| votingage.shop       | available | $2.99     | —             | 52             | 18     | 10     | name.com     |
| velcro.shop          | resell    | —         | —             | 80             | 61     | 6      | Dynadot Inc. |
| chase.shop           | premium   | $6,250    | —             | 66             | 85     | 5      | name.com     |
| cherryonthecake.shop | available | $2.99     | —             | 60             | 13     | 18     | name.com     |
| check.shop           | resell    | —         | —             | 76             | 37     | 5      | GMO Registry |
| mac.shop             | premium   | $6,250    | —             | 84             | 83     | 3      | name.com     |
| giveortake.shop      | available | $2.99     | —             | 52             | 13     | 12     | name.com     |
| sound.shop           | resell    | —         | —             | 70             | 36     | 5      | GMO Registry |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 4,434 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/shop?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/shop?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .shop domains, which makes it relevant for buyers seeking commerce-first naming. The extension signals retail intent immediately, so the best candidates tend to be simple, readable words with clear product, category, or brand potential. Examples such as dogsit.shop, gelpen.shop, carcoat.shop, and saveas.shop show the range: some are literal and commercial, while others are broader and more brandable. Pricing matters here because the median ask is 1,022. When comparing these domains, weigh commercial clarity against flexibility, and treat names with obvious third-party associations, such as Rhianna.shop, with extra caution.

- One-word .shop domains with direct ecommerce relevance
- Median ask is 1,022 across 4,434 listed domains
- Literal words can be clearer; broad words can brand better
- Avoid names with obvious trademark or celebrity overlap

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SHOP One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SHOP page](https://unique.domains/domains/tld/shop?utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
