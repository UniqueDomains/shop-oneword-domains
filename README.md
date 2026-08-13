# Available .SHOP One-Word Domains (5,471)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-5%2C471%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .shop one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **5,471 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 5,471 domains · **Median ask:** $907.25 · **High-demand under $2,500:** 15

**Last updated:** 2026-08-13
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

- `shop.csv`, public CSV extract (1,000 rows)
- `shop.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/shop-oneword-domains/main/shop.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                        |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------ |
| liii.shop      | available | $2.99     | $59.99        | medium         | low    | 4      | name.com                                         |
| generally.shop | resell    | $2.99     | —             | medium         | low    | 9      | Turingsign Inc.                                  |
| ace.shop       | premium   | $6,250    | $6,250        | high           | medium | 3      | name.com                                         |
| aided.shop     | available | $2.99     | —             | high           | low    | 5      | name.com                                         |
| curl.shop      | resell    | —         | —             | medium         | low    | 4      | Registrar of domain names REG.RU                 |
| act.shop       | premium   | $2,500    | —             | high           | low    | 3      | name.com                                         |
| octad.shop     | available | $0.98     | $48.98        | low            | low    | 5      | namecheap                                        |
| grey.shop      | resell    | —         | —             | high           | low    | 4      | ALIBABA.COM SINGAPORE E-COMMERCE PRIVATE LIMITED |
| add.shop       | premium   | $6,250    | —             | high           | low    | 3      | name.com                                         |
| xxxiv.shop     | available | $0.98     | $48.98        | low            | low    | 5      | namecheap                                        |
| home.shop      | resell    | —         | —             | high           | medium | 4      | GoDaddy.com LLC                                  |
| age.shop       | premium   | $3,125    | —             | high           | low    | 3      | name.com                                         |
| abasic.shop    | available | $0.98     | $48.98        | low            | low    | 6      | namecheap                                        |
| live.shop      | resell    | —         | —             | high           | medium | 4      | GMO Registry                                     |
| ago.shop       | premium   | $2,500    | —             | medium         | low    | 3      | name.com                                         |
| abatic.shop    | available | $0.98     | $48.98        | low            | low    | 6      | namecheap                                        |
| pity.shop      | resell    | —         | —             | high           | low    | 4      | Spaceship, Inc.                                  |
| aid.shop       | premium   | $1,250    | $1,250        | medium         | low    | 3      | name.com                                         |
| anuric.shop    | available | $2.99     | $59.99        | medium         | low    | 6      | name.com                                         |
| punk.shop      | resell    | —         | —             | high           | low    | 4      | Go China Domains, LLC                            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 5,471 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 15 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/shop?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/shop?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=related_pricing)

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

This selection covers 4,859 one-word domain names on the .shop extension, including artistry.shop, working.shop, treeoflife.shop, and coffeemaker.shop. The median asking price across the set is near $996, reflecting short, retail-oriented names built for ecommerce and product brands. Each name is a single word, making these domains easier to spell, remember, and use across marketing and storefronts.

- 4,859 available one-word .shop domains in this selection
- Median asking price near $996 across the set
- Short, single-word names suited for ecommerce and retail brands
- Examples include artistry.shop, overjoy.shop, and endorse.shop

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SHOP One-Word Domains*. Version 2026-08-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SHOP page](https://unique.domains/domains/tld/shop?utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_shop_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
