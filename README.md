# Available .CLOUD One-Word Domains (42,902)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-42%2C902%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .cloud one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **42,902 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 42,902 domains · **Median ask:** $302.49 · **High-demand under $2,500:** 252

**Last updated:** 2026-09-26
**Canonical page:** `https://unique.domains/domains/tld/cloud`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/cloud?utm_source=github&utm_medium=referral&utm_campaign=repo_cloud_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./cloud.csv">CSV</a> / <a href="./cloud.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cloud_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cloud_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CLOUD search](https://unique.domains/domains/tld/cloud?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cloud_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CLOUD search](https://unique.domains/domains/tld/cloud?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cloud_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cloud_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CLOUD one-word domain catalog.

### Files

- `cloud.csv`, public CSV extract (1,000 rows)
- `cloud.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cloud-oneword-domains/main/cloud.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price | renewal_price | attractiveness | demand | length | registrar      |
| ----------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------- |
| akee.cloud  | available | $5.29     | $25.99        | medium         | low    | 4      | namesilo       |
| firm.cloud  | resell    | —         | —             | high           | low    | 4      | Name.com, Inc. |
| and.cloud   | premium   | $6,250    | $6,250        | high           | medium | 3      | name.com       |
| acerb.cloud | available | $3.98     | $32.98        | medium         | low    | 5      | namecheap      |
| luca.cloud  | resell    | —         | —             | high           | high   | 4      | InterNetX GmbH |
| ayr.cloud   | premium   | $1,300    | $2,600        | high           | low    | 3      | namecheap      |
| aphid.cloud | available | $5.29     | $25.99        | high           | low    | 5      | namesilo       |
| prop.cloud  | resell    | —         | —             | high           | low    | 4      | —              |
| azt.cloud   | premium   | $1,300    | $2,600        | high           | low    | 3      | namecheap      |
| baisa.cloud | available | $9.99     | $39.99        | high           | low    | 5      | name.com       |
| raft.cloud  | resell    | —         | —             | high           | low    | 4      | Dynadot, LLC   |
| bbs.cloud   | premium   | $650      | $1,300        | high           | low    | 3      | namecheap      |
| belem.cloud | available | $5.29     | $25.99        | high           | low    | 5      | namesilo       |
| rang.cloud  | resell    | —         | —             | high           | low    | 4      | eNom, Inc.     |
| don.cloud   | premium   | $1,400    | $2,800        | high           | low    | 3      | namecheap      |
| bitis.cloud | available | $3.98     | $32.98        | high           | low    | 5      | namecheap      |
| turn.cloud  | resell    | —         | —             | high           | low    | 4      | Porkbun LLC    |
| dry.cloud   | premium   | $1,107    | $1,107        | high           | low    | 3      | namesilo       |
| boric.cloud | available | $3.98     | $32.98        | high           | low    | 5      | namecheap      |
| typo.cloud  | resell    | —         | —             | high           | low    | 4      | Dynadot, LLC   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 42,902 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 252 high-demand names under $2,500         |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cloud?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cloud_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cloud?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cloud_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cloud_oneword_domains&utm_content=related_pricing)

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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This is a curated list of one-word .cloud domain names, from short common nouns to name-brand-style terms. Examples in this set include enable.cloud, oliveoil.cloud, gettogether.cloud, and criteria.cloud, illustrating the range from purely descriptive to distinctly brandable. With 70,341 domains in this .cloud set and a median ask near $396.25, pricing spans from budget-friendly to premium ask levels. Investors comparing renewal costs and TLD footprint, and founders searching for a memorable, ownable name, can both use these traits to narrow a shortlist.

- 70,341 one-word .cloud domain names in this set
- Median ask near $396.25 across the selection
- Mix of common words, brand-style, and coined terms
- Updated daily to reflect current asking prices

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CLOUD One-Word Domains*. Version 2026-09-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CLOUD page](https://unique.domains/domains/tld/cloud?utm_source=github&utm_medium=referral&utm_campaign=repo_cloud_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cloud_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cloud_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cloud_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
