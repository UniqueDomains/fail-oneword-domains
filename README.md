# Available .FAIL One-Word Domains (12,277)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C277%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .fail one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,277 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,277 domains · **Median ask:** $20.52 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `fail.csv` — public CSV extract (1,000 rows)
- `fail.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/fail-oneword-domains/main/fail.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| finals.fail    | available | $14.99    | —             | 80             | 7      | 6      | name.com  |
| getup.fail     | available | $14.99    | —             | 82             | 14     | 6      | name.com  |
| useit.fail     | available | $14.99    | —             | 94             | 7      | 6      | name.com  |
| playin.fail    | available | $14.99    | —             | 80             | 10     | 7      | name.com  |
| makeit.fail    | available | $14.99    | —             | 82             | 22     | 7      | name.com  |
| pierogi.fail   | available | $14.99    | —             | 82             | 7      | 7      | name.com  |
| getlife.fail   | available | $14.99    | —             | 80             | 5      | 8      | name.com  |
| leaveon.fail   | available | $14.99    | —             | 80             | 1      | 8      | name.com  |
| messages.fail  | available | $14.99    | —             | 80             | 16     | 8      | name.com  |
| rumcake.fail   | available | $14.99    | —             | 81             | 3      | 8      | name.com  |
| shortcuts.fail | available | $14.99    | —             | 48             | 41     | 10     | name.com  |
| jobs.fail      | premium   | $123.75   | —             | 79             | 42     | 4      | name.com  |
| aliens.fail    | available | $14.99    | —             | 56             | 35     | 6      | name.com  |
| tickets.fail   | premium   | $78.54    | $78.54        | 64             | 34     | 7      | namesilo  |
| spectra.fail   | available | $14.99    | —             | 62             | 34     | 7      | name.com  |
| partners.fail  | premium   | $82.50    | —             | 61             | 32     | 8      | name.com  |
| William.fail   | available | $50.98    | —             | 74             | 31     | 7      | namecheap |
| solutions.fail | premium   | $82.50    | —             | 56             | 31     | 9      | name.com  |
| letsgo.fail    | available | $14.99    | —             | 57             | 31     | 7      | name.com  |
| Jim.fail       | premium   | $92.40    | $92.40        | 78             | 28     | 3      | namecheap |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,277 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/fail?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/fail?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .fail domains. That makes the set unusual by default: the extension carries a clear negative or ironic tone, so the strongest names are the ones where that tone is intentional, memorable, or commercially useful. Examples such as Acup.fail, finals.fail, jewels.fail, popup.fail, and matcha.fail show the range from broad dictionary words to more niche terms. For founders, the key question is whether the name is easy to explain and own with confidence. For investors, the key question is whether the word-extension pairing is sharp enough to justify the ask and any ongoing renewal exposure.

- All names in this selection use the .fail extension
- Median ask across the set is 20.52
- Best fits usually have intentional irony or critique
- Check renewal terms before treating a low ask as cheap

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FAIL One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FAIL page](https://unique.domains/domains/tld/fail?utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fail_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
