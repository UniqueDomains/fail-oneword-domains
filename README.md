# Available .FAIL One-Word Domains (12,280)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C280%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .fail one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,280 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,280 domains · **Median ask:** $20.54 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/fail`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/fail?utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./fail.csv">CSV</a> / <a href="./fail.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .FAIL search](https://unique.domains/domains/tld/fail?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .FAIL search](https://unique.domains/domains/tld/fail?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .FAIL one-word domain catalog.

### Files

- `fail.csv`, public CSV extract (1,000 rows)
- `fail.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/fail-oneword-domains/main/fail.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                   |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------- |
| ago.fail   | available | $14.99    | $46.99        | medium         | low    | 3      | name.com                                    |
| lose.fail  | resell    | —         | —             | medium         | low    | 4      | GoDaddy Online Services Cayman Islands Ltd. |
| bag.fail   | premium   | $38.94    | $38.94        | high           | low    | 3      | namesilo                                    |
| Ava.fail   | available | $14.99    | —             | high           | medium | 3      | name.com                                    |
| daily.fail | resell    | —         | —             | high           | low    | 5      | GoDaddy.com, LLC                            |
| bud.fail   | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                                    |
| lcd.fail   | available | $14.99    | —             | high           | low    | 3      | name.com                                    |
| but.fail   | premium   | $38.94    | $38.94        | high           | low    | 3      | namesilo                                    |
| UPC.fail   | available | $14.99    | —             | high           | low    | 3      | name.com                                    |
| bye.fail   | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                                    |
| acre.fail  | available | $14.99    | —             | medium         | low    | 4      | name.com                                    |
| cod.fail   | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                                    |
| babe.fail  | available | $14.99    | —             | high           | low    | 4      | name.com                                    |
| cot.fail   | premium   | $38.94    | $38.94        | high           | low    | 3      | namesilo                                    |
| barn.fail  | available | $14.99    | —             | high           | low    | 4      | name.com                                    |
| due.fail   | premium   | $82.50    | —             | high           | low    | 3      | name.com                                    |
| bass.fail  | available | $14.99    | —             | medium         | low    | 4      | name.com                                    |
| err.fail   | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                                    |
| belt.fail  | available | $14.99    | —             | high           | low    | 4      | name.com                                    |
| eye.fail   | premium   | $38.94    | $38.94        | medium         | low    | 3      | namesilo                                    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,280 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/fail?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/fail?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=related_pricing)

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

This list features one-word .fail domain names spanning everyday nouns, verbs, and short phrases such as watches.fail, gearup.fail, and thanksgiving.fail. With a median ask near $20.54 across 12,280 names, these domains suit buyers seeking short, memorable options in a distinctive TLD. Because .fail carries an unconventional tone, pricing tends to stay accessible, making it easier to test brandable ideas without heavy upfront cost.

- 12,280 one-word .fail domains available across many themes
- Median ask around $20.54 per domain
- Short, single-word names that are easy to recall
- Unconventional TLD keeps pricing accessible for testing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FAIL One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FAIL page](https://unique.domains/domains/tld/fail?utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
