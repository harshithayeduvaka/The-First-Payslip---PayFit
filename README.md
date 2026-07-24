# The-First-Payslip---PayFit
# The First Payslip

**Why PayFit's biggest growth lever is the 45 days *after* the contract is signed.**

An independent go-to-market analysis of PayFit — the Paris-based payroll and HR platform serving 20,000+ European SMBs — arguing that its positioning is fighting the wrong battle, and that its strongest differentiator is invisible at exactly the moment buyers are deciding.

Built from `[N]` coded implementation reviews across PayFit, Personio and Factorial, plus public product, pricing and market data.

> **Not affiliated with, commissioned by, or reviewed by PayFit.** Every input is public. Every assumption is stated.

---

### 📊 [Read the deck (PDF)](deck/the-first-payslip.pdf) · 📋 [Method & codebook](method/CODEBOOK.md) · 📈 [Coded dataset](data/reviews-coded.csv) · 🧮 [Routing model](model/migration-scoring-model.xlsx)

---

## The question

PayFit competes against Personio, which is larger and IPO-bound, and Factorial, which is cheaper and broader. On feature breadth and on price, PayFit loses. So what's left?

I spent two years running end-to-end implementation for 65+ B2B accounts at Keka HR — the same product category, the same buyer, the same failure points. That work suggested an answer that doesn't appear anywhere in PayFit's marketing:

**HR software isn't lost at the demo. It's lost in week three of migration.**

This analysis tests whether that holds for PayFit, and what marketing should do if it does.

## What I found

**1 · Migration, not features, dominates implementation complaints.**
`[X]` of `[N]` reviews mentioning implementation cite data migration or compliance misconfiguration as the failure point. Feature gaps rank `[position]`.

**2 · PayFit's one clear advantage is unevaluable at the point of sale.**
Across five buying criteria, PayFit leads on payroll compliance depth alone — the single criterion an SMB buyer has no way to assess during a demo. It becomes visible only during migration, by which point marketing has stopped talking.

**3 · The anxiety curve peaks 45 days after marketing hands off.**
PayFit's published onboarding window is 2–6 weeks standard and 6–10 weeks for multi-entity setups. The moment of maximum customer risk — the first live payroll run — sits entirely inside that window, unowned by marketing.

## The argument

Reposition from *"better payroll software"* to *"the safest payroll switch in Europe."*

Not a product change. The same product, entered into a different fight — one where PayFit's compliance architecture becomes the reason to buy rather than a technical footnote, and where the 45-day migration becomes the proof point rather than the risk.

The repo contains the positioning case, a five-stage activation map with the churn risk at each stage, an eight-touch lifecycle sequence built to be A/B tested, and a scoring model that routes accounts by migration complexity rather than deal size.

## Method

| | |
|---|---|
| **Sample** | `[N]` verified reviews across PayFit, Personio, Factorial |
| **Sources** | G2, Capterra — `[date range]` |
| **Filter** | Reviews mentioning implementation, onboarding, setup or migration |
| **Coding** | Six-category taxonomy, defined before coding began — see [CODEBOOK.md](method/CODEBOOK.md) |
| **Supporting** | Public pricing, product documentation, funding disclosures, 2026 European SMB HR market coverage |

**On the data:** this repo contains coded categories, dates and my own short paraphrases. It does **not** contain review text, reviewer names, or anything else reproduced from G2 or Capterra. Source URLs are included so every code can be independently verified.

## What's in here

```
├── deck/           The full analysis as PDF
├── data/           Coded review dataset (CSV) — categories and paraphrases only
├── method/         Codebook, category definitions, stated assumptions
├── model/          Migration-complexity scoring model (XLSX)
└── memo/           Two-page written summary
```

## What I couldn't see

This is built entirely from outside. Five things would confirm or kill the thesis, and I don't have any of them:

- Actual churn timing — is the spike inside 90 days, or after month 12?
- Real onboarding completion rates against the published 2–6 week window
- CAC and payback by segment rather than blended
- Win/loss reasons on deals lost to Personio and Factorial
- Support ticket taxonomy for days 1–45

If internal data contradicts the migration thesis, the thesis changes. I've stated it precisely enough to be wrong.

## About

I'm Harshitha — MSc International Marketing & Business Development at SKEMA Paris, previously B2B implementation at Keka HR, currently building [ohmyATS](https://github.com/[your-username]/[ohmyats-repo]).

I write GTM analyses of B2B SaaS companies whose products I've worked adjacent to. Feedback and disagreement welcome — open an issue.

📧 yeduvakaharshitha@gmail.com · 💼 [LinkedIn](https://linkedin.com/in/[your-handle])

---

<sub>Licence: analysis and writing © Harshitha Yeduvaka, released under [CC BY 4.0](LICENSE). Cite freely with attribution.</sub>
