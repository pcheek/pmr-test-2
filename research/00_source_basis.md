# Source Basis and Grounding Record

**Status: RECONSTRUCTED, NOT SOURCED.** The repository `pcheek/pmr-test-2` was empty at the
time this study was generated. No `Business Plan` or `Misaligned Incentives` documents were
present in the repo, on any branch, or in any commit.

Every persona trait, script question, and finding in this study traces back to one of the
premises below. Those premises were extracted from the study brief itself, not from the
original source documents. If any premise is wrong, the personas built on it are wrong in the
same direction, and this file is the place to correct it.

---

## Step 3: End User Profile (reconstructed premises)

| # | Premise | Source of premise |
|---|---|---|
| S3-1 | Age band 28 to 45 | Brief, demographics spec |
| S3-2 | Household income $75K to $250K+ | Brief, demographics spec |
| S3-3 | Investable assets $25K to $500K | Brief, demographics spec |
| S3-4 | Account types: 401(k), RSU/equity comp, taxable brokerage | Brief, demographics spec |
| S3-5 | Salaried professionals with meaningful equity compensation | Brief, spectrum spec ("high equity comp") |
| S3-6 | Self-directed or semi-self-directed investors, already using at least one retail platform (Fidelity, Wealthfront, YNAB class of tool) | Brief, behavioral spec |
| S3-7 | Financially literate but not professional investors; consume peer financial media (r/Bogleheads, ChooseFI, Blind) | Brief, media diet spec |
| S3-8 | Fee-aware, with fee sensitivity varying in intensity across the segment | Brief, psychographics spec |
| S3-9 | A material subset has a spouse or partner who co-approves financial decisions | Brief, `ka-007` |
| S3-10 | Tax complexity is present and self-managed via workarounds (wash sale tracking, RSU vest timing, spreadsheet lot tracking) | Brief, behavioral spec |

## Step 5: Persona, "Maya Chen" (reconstructed premises)

| # | Premise | Source of premise |
|---|---|---|
| S5-1 | Named persona is Maya Chen; the 10 synthetic users are derived from her archetype but are distinct individuals, not copies | Brief, Step 1 instruction |
| S5-2 | Core philosophy leans Bogleheads / low-cost index, passive-by-conviction | Brief, psychographics spec (Bogleheads named as the example) |
| S5-3 | Primary fears are fees and tax drag, i.e. silent value leakage rather than market risk | Brief, psychographics spec |
| S5-4 | Skeptical of traditional advisors, specifically the 1% AUM model and its incentive misalignment | Brief, "Misaligned Incentives" title plus attitude-toward-advisors spec |
| S5-5 | Reacts negatively to jargon; treats opaque language as a signal of extraction | Brief, `ka-003` |
| S5-6 | Trigger events are discrete and dated: job change with 401(k) rollover, RSU vest | Brief, profile spec |
| S5-7 | Expects to self-serve onboarding without a sales call | Brief, `ka-006` |
| S5-8 | Switching costs (ACATS transfer) are a felt barrier, not a theoretical one | Brief, `ka-002` |

## Step 20: Key Assumptions Under Test

| ID | Assumption | Riskiness rank used in script ordering |
|---|---|---|
| `ka-001` | Trust in Automation: the segment will delegate portfolio decisions to an automated system without a human advisor in the loop | 2 |
| `ka-002` | Switching Friction / ACATS: switching cost is the binding constraint, and it can be reduced enough to unblock transfers | 3 |
| `ka-003` | Primary Pain of Opaque Fees and Jargon: opacity, not performance, is the top-ranked pain | 4 |
| `ka-004` | Tax Optimization Value: tax drag relief is a paid-for benefit, not a nice-to-have | 5 |
| `ka-005` | Pricing and 25 bps Value Capture: 25 bps (or a $96 flat equivalent) is both acceptable and capturable | 1 |
| `ka-006` | Onboarding Autonomy: users will complete account linking and funding with no human contact | 6 |
| `ka-007` | Decision-Making Unit: a spousal or partner co-approver is present often enough to change the buying process | 7 |

Riskiness ranking rationale: pricing (`ka-005`) is ranked riskiest because the entire unit
economics rest on it and it is the assumption most easily flattered by a founder-led
interview. Trust in automation (`ka-001`) is second because it gates adoption regardless of
price. Onboarding autonomy and the DMU are ranked last because they shape the funnel rather
than the value proposition.

## Product premises (used only in Step 2 closing question and Step 4 synthesis)

| # | Premise |
|---|---|
| P-1 | The offering is automated portfolio management with tax-aware behavior (loss harvesting, lot selection, RSU vest handling) |
| P-2 | Candidate price points under test are $96/year flat and 25 bps of assets, benchmarked against free/DIY and against the incumbent 1% AUM advisor |
| P-3 | Onboarding is self-serve and requires account aggregation plus an ACATS transfer |
| P-4 | Positioning thesis is incentive alignment: the provider does not profit from opacity |

These product premises are deliberately withheld from the interview script until the closing
willingness-to-pay question, per the Step 2 guideline.
