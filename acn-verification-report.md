# ACN Deep Dive — Verification Report
### Alpha with AI · July 2026

**What this is.** The public verification trail behind the Accenture (ACN) deep dive. Every figure in the piece traces to a document in the Source Key below. The research was run with Claude Code pulling filings directly from SEC EDGAR; every number was then checked back against the filed document, and historical claims were verified against two independent sources, preferring primary and contemporaneous ones. If a number in the edition bothers you, trace it here.

**The model:** [ACN Valuation Model (Google Sheets, view-only — make a copy to edit)](https://docs.google.com/spreadsheets/d/1q8BLqjVnfrbZGxcGqMy_9RyRZXT--rjw0EeCW3xktjI/edit?usp=sharing)

*This report is research documentation, not investment advice. The edition's full disclaimer applies.*

---

## Source Key (SEC EDGAR, CIK 0001467373 unless noted)

| Code | Filing | Period | Filed | Accession No. |
|---|---|---|---|---|
| 10-K25 | FY2025 10-K | FY ended 8/31/2025 | 2025-10-10 | 0001467373-25-000217 |
| 10-K23 | FY2023 10-K | FY ended 8/31/2023 | 2023-10-12 | 0001467373-23-000324 |
| 10-K21 | FY2021 10-K | FY ended 8/31/2021 | 2021-10-15 | 0001467373-21-000229 |
| 10-K14 | FY2014 10-K | FY ended 8/31/2014 | 2014-10-24 | 0001467373-14-000467 |
| 10-Q1 | Q1 FY26 10-Q | Qtr ended 11/30/2025 | 2025-12-18 | 0001467373-25-000222 |
| 10-Q2 | Q2 FY26 10-Q | Qtr ended 2/28/2026 | 2026-03-19 | 0001467373-26-000014 |
| 10-Q3 | Q3 FY26 10-Q | Qtr ended 5/31/2026 | 2026-06-18 | 0001467373-26-000032 |
| 8-K25 | Q4/FY25 earnings release | FY25 | 2025-09-25 | 0001467373-25-000213 |
| 8-KQ1 | Q1 FY26 earnings release | Q1 FY26 | 2025-12-18 | 0001467373-25-000221 |
| 8-KQ2 | Q2 FY26 earnings release | Q2 FY26 | 2026-03-19 | 0001467373-26-000013 |
| 8-KQ3 | Q3 FY26 earnings release | Q3 FY26 | 2026-06-18 | 0001467373-26-000031 |
| 8-K24 | Q4/FY24 earnings release | FY24 | 2024-09-26 | 0001467373-24-000266 |
| 8-KBB | 8-K Item 7.01 (buyback increase) | 6/23/2026 | 2026-06-23 | 0001467373-26-000035 |
| 424B4 | Accenture Ltd IPO prospectus (CIK 0001134538) | 2001 | 2001-07-19 | 0000950130-01-503166 |

## Revenue

| Period | Revenue ($000s) | YoY USD | YoY local currency | Source |
|---|---|---|---|---|
| FY2021 | 50,533,389 | — | — | 10-K21 |
| FY2023 | 64,111,745 | +4% | +8% | 10-K25 / 10-K23 |
| FY2024 | 64,896,464 | +1.2% (calc) | ~+2% | 10-K25 |
| FY2025 | 69,672,977 | +7% | +7% | 10-K25 / 8-K25 |
| Q1 FY26 | 18,742,125 | +6% | +5% | 8-KQ1 |
| Q2 FY26 | 18,044,066 | +8% | +4% | 8-KQ2 |
| Q3 FY26 | 18,718,144 | +6% | +3% | 8-KQ3 |
| 9M FY26 | 55,504,334 | +7% | +4% | 8-KQ3 |

FX contribution FY26: +1.4% (Q1), +4.4% (Q2), +2.5% (Q3). Guidance path: FY26 local-currency growth 2–5% (8-K25) → 2–5% (8-KQ1) → 3–5% (8-KQ2) → 3–4%, "4% to 5% excluding an estimated 1% impact from U.S. federal business" (8-KQ3). Q4 FY25 revenue $17.59B derived: FY25 total minus 9M FY25 $52,076,717K.

## Type-of-work mix

| Period | Consulting | Managed services | Source |
|---|---|---|---|
| FY2023 | $33,613M | $30,499M | 10-K23 MD&A |
| FY2024 | $33,195.1M | $31,701.4M | 10-Q1 MD&A |
| FY2025 | $35,106.8M (+5% LC) | $34,566.2M (+9% LC) | 10-K25 MD&A |
| 9M FY26 | $27,602.7M (+2% LC) | $27,901.6M (+6% LC) | 8-KQ3 |

9M FY26 is the first period in which managed services revenue exceeds consulting.

## Bookings — including the AI metric timeline

| Period | Total bookings | Consulting | Managed services | Source |
|---|---|---|---|---|
| FY2025 | $80.62B (−1%), book-to-bill 1.2 | $37.64B | $42.98B | 8-K25 |
| Q1 FY26 | $20.94B (+10% LC) | $9.88B | $11.06B | 8-KQ1 |
| Q2 FY26 | $22.11B (+1% LC, record) | $11.33B | $10.78B | 8-KQ2 |
| Q3 FY26 | $19.32B (−3% LC) | $10.26B (+11% LC) | $9.06B (−16% LC) | 8-KQ3 / 10-Q3 MD&A |

Bookings, per the filings' definition, "include new contracts, including those acquired through acquisitions" (10-K25 MD&A). Client bookings over $100M: 33 (Q1), record 41 (Q2), 104 YTD +13% (Q3 CEO quotes).

**AI bookings disclosure history (the vanished metric):**

| Earnings release | AI bookings disclosed | Accession |
|---|---|---|
| Q4 FY2024 | $1.0B quarter / $3.0B full year ("Generative AI") | 0001467373-24-000266 |
| Q4 FY2025 | $1.8B quarter / $5.9B full year ("Generative AI") | 0001467373-25-000213 |
| Q1 FY2026 | $2.2B ("Advanced AI") | 0001467373-25-000221 |
| Q2 FY2026 | None (full-text verified) | 0001467373-26-000013 |
| Q3 FY2026 | None; "advanced AI" appears once in the release, in the forward-looking-statements risk language (full-text verified) | 0001467373-26-000031 |

"Advanced AI" is defined in the FY2025 10-K as generative, agentic and physical AI. No AI *revenue* figure has ever been disclosed in these filings — bookings only.

## US federal exposure

Accenture Federal Services ≈ 36% of Health & Public Service revenues, 15% of Americas revenues, 8% of total FY2025 revenues (10-K25 Item 1). FY26 growth guide reduced by "an estimated 1% impact" from the US federal business (8-KQ1 onward). MD&A describes procurement delays, price and scope reductions, and contract terminations under DOGE; risk factors cite the GSA's instruction to all federal agencies to review consulting contracts, and an open DOJ civil and criminal investigation at AFS following the company's voluntary disclosure, with suspension or debarment named as possible outcomes (10-K25 Item 1A and contingencies note; repeated in all FY26 10-Qs).

## Headcount, utilization, margins

- Headcount: ~721k (FY22) → ~733k (FY23) → ~774k (FY24) → peak ~801k (Feb 2025) → ~779k (Aug 2025) → ~799k (May 2026). Sources: 10-K23, 10-K25, 10-Q MD&A People Metrics.
- Utilization: 91% (FY23) → 92% (FY24/25) → 93% all three FY26 quarters (10-Qs).
- GAAP operating margin: FY23 13.7% → FY24 14.8% → FY25 14.7% (adjusted 15.6%) → 9M FY26 15.4%. FY26 guide 15.3% GAAP / 15.8% adjusted (8-KQ3).
- Business optimization: FY23 $1,063.1M; FY24 $438.4M; Q4 FY25 $615.3M; Q1 FY26 $307.5M (program complete; $923M vs ~$865M guided). Gross margin FY25 31.9%, −70bps, "primarily due to higher payroll costs" (10-K25 MD&A).
- Pricing language progression (MD&A; pricing = contract profitability): "improved in several areas" (10-K25, 10-Q1) → "improved in some areas" (10-Q2) → "relatively stable" (10-Q3).

## Cash flow, capital return, balance sheet

- FY2025: OCF $11,474.4M; capex $600.0M; FCF $10.87B; dividends $3,700.2M; buybacks $4,619.5M (8-K25, 10-K25).
- FY2021 (for the five-year view): operating income $7,621.5M; OCF $8,975.1M; capex $580.1M → FCF $8.40B (10-K21, confirmed via SEC XBRL).
- 9M FY26: OCF $9,268.0M; capex $492.5M; FCF $8.78B; dividends $3,012.8M ($1.63/qtr, +10%); buybacks $5,193.3M (8-KQ3). FY26 guide: FCF $10.8–11.5B; capex cut from $1.0B to $0.7B at Q2 (8-KQ2).
- June 23, 2026: expected FY26 repurchases raised to $7.5B (8-KBB). Shares out ~622M (8/25) → ~612M (5/31/26).
- Net cash: cash $10,165.2M vs debt $5,142.3M at 5/31/26 ≈ $5.0B (10-Q3). The $5B senior notes issued Oct 2024 are the company's first term debt (10-K25 borrowings note).
- Stock-based compensation: FY25 $2,093.9M; 9M FY26 $1,644.5M (10-K25 Note 13; 8-KQ3).

## Acquisitions

Cash spend: FY23 $2,530.9M; FY24 $6,582.7M; FY25 $1,471.3M ("23 strategic acquisitions"); 9M FY26 $3,004.0M vs $789.5M in 9M FY25 (10-K25; 8-KQ3). Goodwill $25.3B ≈ 36.8% of total assets at 5/31/26 (10-Q3 Note 6). New "redeemable noncontrolling interests" line $493.9M at 5/31/26 (10-Q3). Inorganic revenue contribution is not disclosed in these filings.

## The AI risk factor (FY2025 10-K, Item 1A — quoted)

> "Some services and tasks currently performed by our people have been and will continue to be replaced by automation, including AI-enabled solutions, which will lead to reduced demand for our services and/or adversely affect the utilization rate of our professionals, if demand for those services is not replaced by demand for new solutions and services... If we are unable to introduce or if our clients do not accept new pricing or commercial models that reflect the value of these AI-enabled solutions, our results of operations may be adversely affected."

## Company history (two-source verified, primary/contemporaneous)

- ICC arbitration: final award dated Jul 28, 2000, parties notified Aug 7, 2000. Andersen Worldwide/Arthur Andersen sought ~$14.5B; awarded no damages — Arthur Andersen received the escrowed past transfer payments (~$512.3M principal plus interest) plus $556M under the Dec 2000 settlement, ≈ $1.0–1.1B all-in. Name surrendered by Dec 31, 2000. Sources: 424B4; NYT and Washington Post, Aug 8, 2000; CNN, Aug 7, 2000.
- "Accenture" ("accent on the future") submitted by Kim Petersen, an employee in the Oslo office, via the internal BrandStorming contest; effective Jan 1, 2001. Sources: company press release Oct 26, 2000; Washington Technology, Oct 26, 2000; 424B4.
- IPO priced $14.50, traded on NYSE from Jul 19, 2001. Sources: 424B4 cover; CNN, Jul 19, 2001.
- Arthur Andersen: Enron's auditor; convicted of obstruction Jun 15, 2002; ceased practicing before the SEC by Aug 31, 2002; conviction unanimously reversed May 31, 2005 (Arthur Andersen LLP v. United States, 544 U.S. 696) — the firm never returned. Sources: SEC release 2002-89; DOJ statement Jun 15, 2002; Supreme Court opinion.
- Revenue growth after the cloud scare: FY2014 net revenues $30,002,394K (10-K14) → FY2024 $64,896,464K (10-K25) — more than doubled on both net and total-revenue bases.

## Market data (Yahoo Finance daily closes, 2026-07-06 — market data, not filing data)

Close $136.96; 52-week high close $303.33 (2025-07-08), drawdown −54.8%; all-time high close $415.42 (2021-12-29), −67.0%. Market value $83.8B = ~612M shares (8-KQ3) × close (author calculation).

## Method notes

- Figures marked "my calc" in the edition are derived from the filed inputs listed here; everything else is quoted from the documents directly.
- Historical (non-filing) facts were cross-checked against two independent authoritative sources, preferring primary documents and reporting from the time; Wikipedia was used only to locate primary sources, never as a citation, and two of its figures were corrected against the primary record in the process.
- AI tools (Claude Code) pulled and reconciled the filings; every number was verified against the filed document before use. Dashboard data (FMP-sourced) was used for charts only; wherever a dashboard cell disagreed with a filing, the filing was used in the text.
