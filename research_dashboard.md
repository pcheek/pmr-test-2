# Research Dashboard: Automated Tax-Aware Portfolio Management

**Study:** 10 synthetic depth interviews, 2026-09-22. Script: `research/02_interview_script.md` (12 questions). Assumptions under test: `research/00_source_basis.md` (ka-001 to ka-007). Subjects: `research/01_synthetic_personas.md`.

**Purpose of this document:** to record what the study found, including and especially where it contradicts the plan. Verdicts below are not rounded upward. Where a subject's own words contradict the interviewer's summary label, the words govern, and every such reclassification is stated explicitly.

**Headline:** the cohort's capturable-to-stated asset ratio is **29.3%**. Four of ten buy nothing at either price. One of ten would actually pay 25 basis points. No subject ranked fees as their first problem.

---

# PART A: QUANTITATIVE DASHBOARD

## A1. Assumption scorecard

**Verdict rule used:** plurality of the ten per-subject verdicts. Validated, Partially Validated and Invalidated are counted as three separate outcomes; a Partial is never merged into a Validated. Where plurality is tied, the lower verdict wins. Per-subject verdicts are taken from each transcript's Post-Interview Assessment, except where the subject's own words contradict the label, in which case the verdict is lowered and the reclassification is footnoted.

| ID | Assumption | Verdict | Validated | Partial | Invalidated | One-line reason |
|---|---|---|---|---|---|---|
| ka-001 | Trust in Automation (delegate without a human in the loop) | **Partially Validated** | 2/10 (20%) | 5/10 (50%) | 3/10 (30%) | Only Priya and Sofia can say how they know their automation works; six cannot verify anything ("the balance goes up"), and three require a named human for accountability. |
| ka-002 | Switching Friction / ACATS is the binding constraint | **Invalidated** | 0/10 (0%) | 1/10 (10%) | 9/10 (90%) | All ten said nothing mechanical is stopping their stranded asset. The binding constraint is the absence of a deadline, not the presence of friction. |
| ka-003 | Opaque fees and jargon are the primary pain | **Invalidated** | 0/10 (0%) | 3/10 (30%) | 7/10 (70%) | Zero subjects ranked fees first in Q3. Fees function as a purchase veto (Sofia, Priya, Wes) or are absent entirely (Trevor, Brandon); one subject finds jargon reassuring. |
| ka-004 | Tax drag relief is a paid-for benefit | **Invalidated** | 2/10 (20%) | 1/10 (10%) | 7/10 (70%) | Only Priya and Sofia have both a securities tax surface and a workaround. Seven have no reachable surface, no awareness of one, or complexity beyond automation's scope. |
| ka-005 | 25 bps (or $96 flat) is acceptable and capturable | **Partially Validated** | 0/10 (0%) | 7/10 (70%) | 3/10 (30%) | $96 flat is broadly acceptable, but only 1 of 10 would actually pay 25 bps, and 4 of 10 pay nothing at either price. No subject validated both halves. |
| ka-006 | Onboarding autonomy, no human contact | **Invalidated** | 4/10 (40%) | 1/10 (10%) | 5/10 (50%) | Five fail at the account-linking step: two hard refusals, one structural inability, one supervision requirement, one liability-and-advisor gate. Only Daniel is frictionless. |
| ka-007 | A spousal co-approver changes the buying process | **Validated** | 5/10 (50%) | 1/10 (10%) | 4/10 (40%) | Five have a real, exercised veto with a standing venue, and the co-approver's question is institutional legitimacy, not price. Caveat: the sample was built with 4 to 5 co-approvers, so this is a designed-in result. |

### Per-subject verdict matrix

| Subject | ka-001 | ka-002 | ka-003 | ka-004 | ka-005 | ka-006 | ka-007 |
|---|---|---|---|---|---|---|---|
| Priya Raghavan | Validated | Invalidated | Partial | Validated | Partial | Validated | Invalidated |
| Daniel Okonkwo | Partial | Invalidated | Invalidated | Invalidated | Partial | Validated | Invalidated |
| Sofia Marchetti | Validated | Partial | Invalidated | Validated | Partial | Partial | Partial |
| Marcus Webb | Partial | Invalidated | Invalidated | Partial | Partial | Validated | Validated |
| Grace Lim | Partial | Invalidated | Partial | Invalidated | Partial | Validated | Invalidated |
| Trevor Nash | Invalidated | Invalidated | Invalidated | Invalidated | Invalidated* | Invalidated | Validated |
| Anika Deshmukh | Partial | Invalidated | Partial | Invalidated | Partial | Invalidated | Validated |
| Brandon Ruiz | Invalidated* | Invalidated | Invalidated | Invalidated | Invalidated | Invalidated | Validated |
| Kate Hollis | Invalidated | Invalidated | Invalidated | Invalidated | Partial* | Invalidated | Validated |
| Wes Tanaka | Partial | Invalidated | Invalidated | Invalidated | Invalidated | Invalidated | Invalidated |

**Three reclassifications, all downward, stated for audit:**

1. **Brandon, ka-001: labelled "Partially Validated, in a way that does not help" in the transcript; recorded here as Invalidated.** He satisfies the coverage map's stated invalidation condition ("requires a named human for accountability"): Denise at the credit union branch, Rick the preparer, "a place with a building." His verified automation is his employer's plan and a target-date fund, not a third party, and he describes the offer as "a second person doing the job the fund already does."
2. **Trevor, ka-005: labelled "Partially Validated, in an inverted way"; recorded here as Invalidated.** The assumption is a conjunction: acceptable *and* capturable. 25 bps is acceptable to him as a structure, and capture is zero at any price by his own statement: "You could do it for free and I'd have the same problem."
3. **Kate, ka-005: labelled "VALIDATED on price"; recorded here as Partially Validated.** She accepts 25 bps as a structure and even prefers it, and she pays $0. Her assessment's own line is "Dollars she would actually pay to us today: $0." Price acceptance without capture is half the assumption.

---

## A2. Willingness-to-pay distribution

**Capturable assets** = stated investable assets minus (a) active-employer 401(k) and 403(b) balances, which cannot be moved while employed, (b) state-plan 529s, (c) illiquid private equity comp, and (d) any asset the subject explicitly refuses to move. Where a transcript computed the figure, it is used as-is. Where it did not, the figure is estimated from the account breakdown in `01_synthetic_personas.md` and flagged.

| # | Subject | Segment | Stated investable | Capturable | Est.? | Structure landed on | Annual $ they would actually pay | Their own benchmark |
|---|---|---|---|---|---|---|---|---|
| 1 | Priya Raghavan | Innovator | $420,000 | $110,000 | No | $96 flat | **$96** | $240 volunteered; $400 ceiling with docs |
| 2 | Daniel Okonkwo | Innovator | $95,000 | $89,000 | No | 25 bps | **$222** | $200 to $300, admitted "vibes" |
| 3 | Sofia Marchetti | Early Adopter | $500,000 | $207,000 | No | $96 flat | **$96** | $350 to $500 flat, built bottom-up |
| 4 | Marcus Webb | Early Adopter | $310,000 | $112,000 | **Yes** | $96 flat | **$96** | $200 to $250 |
| 5 | Grace Lim | Early Majority | $165,000 | $79,000 | **Yes** | $96 flat | **$96** (conversion not-yet) | $200, derived from Netflix and YNAB |
| 6 | Trevor Nash | Early Majority | $275,000 | $61,000 | No | 1% AUM (incumbent) | **$0** | $2,000 to $2,500 with a named human |
| 7 | Anika Deshmukh | Early Majority | $198,000 | $39,000 | **Yes** | $96 flat | **$96** | $200 to $250, capped by spousal threshold |
| 8 | Brandon Ruiz | Late Majority | $340,000 | $0 | **Yes** | free-DIY (incumbent) | **$0** | $400 to $500 one-time, for college projection |
| 9 | Kate Hollis | Late Majority | $480,000 | $127,000 | No | 1% AUM (incumbent) | **$0** | $2,000/yr for AMT-inclusive service |
| 10 | Wes Tanaka | Skeptic | $25,000 | $0 | **Yes** | free-DIY (incumbent) | **$0** | $500 one-time, nothing in year two |

**Estimation notes.** Marcus: $41K spouse rollover IRA + $54K taxable + ~$17K of surplus cash, excluding his $148K active 401(k), $22K of 529s and $190K of illiquid double-trigger RSUs he values at zero; a ~$38K tender payout lands in December as incremental new money. Grace: $31K Roth + $34K Betterment + $14K RSUs, excluding her $78K active 401(k). Anika: $18K RSUs + $21K joint brokerage only; she states $125K but that figure includes her own $86K active 401(k), which cannot move, and excludes her husband's $67K 401(k), which she will not ask for credentials to link. Brandon and Wes are recorded at $0 because both refuse third-party account access as a household rule rather than a preference; the theoretical surface absent that refusal is $62K and $25K respectively. Daniel's $89K exceeds his own $95K headline net of his active 401(k) because his stranded $41K old 401(k) is not inside the number he quotes for himself, a discrepancy present in the source material and left uncorrected here.

### Structure counts

| Structure | Count | Subjects |
|---|---|---|
| $96 flat | **5** | Priya, Sofia, Marcus, Grace, Anika |
| 25 bps | **1** | Daniel |
| free-DIY | **2** | Brandon, Wes |
| 1% AUM | **2** | Trevor, Kate |
| would not buy | 0 | (see note) |

**Note on the zero.** No subject refused every option in the abstract. Four refused *this product* at every price: Brandon, Wes, Trevor and Kate. Their landing is recorded as the arrangement they will actually be paying for next year, which is their incumbent. Read as purchase behaviour: **6 of 10 convert, 4 of 10 (40%) do not.** Of the six converts, three carry material conversion caveats (Priya moves 26% of assets on trial, Grace is a price-yes and a conversion not-yet, Anika converts to a knowingly partial product).

### THE CENTRAL NUMBER: capturable-to-stated ratio

> ## Stated investable assets: $2,808,000
> ## Capturable assets: $824,000
> ## **Capturable-to-stated ratio: 29.3%**

Upper-bound sensitivity: if Brandon's $62K and Wes's $25K are counted as theoretically addressable despite their refusals, capturable rises to $911,000 and the ratio to **32.4%**. Neither figure is above one third. Roughly seventy cents of every dollar in this segment's headline assets sits in an active-employer plan, a spouse's plan, a state 529, an illiquid private grant, or behind a refusal.

Two subjects caught this unprompted and corrected the interviewer mid-call:

- Sofia: "You just quoted me a number two and a half times larger than the fee I'd actually pay in year one, and I don't think you did it dishonestly, I think you did it because the deck says five hundred thousand. But it tells me you haven't modeled your own billable base."
- Kate: "Twenty-five basis points of four-eighty assumes you have four-eighty. You can't have four-eighty. Which is a much better number for me and a much worse number for you."

### Revenue totals across all 10

| Scenario | Total annual revenue | Per household |
|---|---|---|
| (a) $96 flat, charged mechanically to all 10 | $960 | $96 |
| (a') $96 flat, **realistic** (6 converts only) | **$576** | $58 |
| (b) 25 bps of capturable assets, all 10 | **$2,060** | $206 |
| (b') 25 bps of stated assets, all 10 (the plan's implied figure) | $7,020 | $702 |
| (b'') 25 bps, **realistic** (only Daniel would pay it) | **$222** | $22 |

**Per-subject 25 bps on capturable assets:** Priya $275, Daniel $222.50, Sofia $517.50, Marcus $280, Grace $197.50, Trevor $152.50, Anika $97.50, Brandon $0, Kate $317.50, Wes $0.

**The pricing trap, stated plainly.** On the six subjects who convert, 25 bps of capturable assets would yield $1,590 against $576 at the flat fee, a 2.8x revenue difference. Five of those six refuse the percentage on structure at any basis-point count, including amounts below the flat fee. The percentage is worth 2.8x and is collectible from one of them. Meanwhile 25 bps of *stated* assets ($7,020) overstates even the mechanical percentage case by 3.4x, which is the number most likely to be sitting in the model.

---

## A3. Objections ranked by frequency

| Rank | Objection | Count | Subjects |
|---|---|---|---|
| 1 | **Absence of a forcing function.** Nothing mechanical blocks the move and nothing makes it happen; no deadline, no consequence on any given Tuesday. | **10/10** | All ten |
| 2 | **Account linking is an obstacle.** Hard refusal, structural inability, supervision requirement, or a disclosure checklist that must be satisfied first. | 9/10 | All except Daniel |
| 3 | **Percentage-of-assets pricing rejected or attacked on structure**, not amount: revenue grows with the customer's savings rate. | 8/10 | Priya, Sofia, Marcus, Grace, Anika, Brandon, Kate, Wes |
| 4 | **Basis points is an illegible unit.** Flat is "a number I can say out loud"; a percentage produces no answer. | 7/10 | Priya, Sofia, Marcus, Grace, Anika, Brandon, Wes |
| 5 | **No reachable tax surface, or complexity beyond scope.** Assets are tax-deferred, too small to matter, real-estate-side, or require AMT and ISO work the product does not do. | 7/10 | Daniel, Grace, Trevor, Anika, Brandon, Kate, Wes |
| 6 | **The product does not address the subject's own top-ranked problem** (college cash flow, income smoothing, where new money goes, household comprehension, equity-comp modelling, tenant turnover). | 7/10 | Marcus, Grace, Trevor, Anika, Brandon, Kate, Wes |
| 7 | **$96 flat signals low capability or non-viability.** "What's missing," "nobody's looking at it," "too cheap to persist." | 6/10 | Priya, Daniel, Sofia, Marcus, Trevor, Kate |
| 8 | **The incumbent is good enough.** "What exactly am I fixing," my spreadsheet is free, my robo has never visibly failed, 22 years have worked. | 6/10 | Priya, Daniel, Anika, Brandon, Kate, Wes |
| 9 | **A named accountable human is required or wanted** (hard requirement for three, soft for three). | 6/10 | Marcus, Trevor, Grace, Anika, Brandon, Kate |
| 10 | **Institutional legitimacy and custody.** "Who are they and what happens if they go under," who is the custodian, ADV, SIPC. | 6/10 | Priya, Sofia, Marcus, Trevor, Brandon, Kate |
| 11 | **Household co-approval threshold**, roughly $300 to $500, above which the purchase becomes a meeting and the meeting does not happen. | 5/10 | Marcus, Trevor, Anika, Brandon, Kate |
| 12 | **Peer or social proof required before purchase.** A named person they know, or forum regulars, must have gone first. | 5/10 | Priya, Sofia, Grace, Brandon, Kate |
| 13 | **Partial migration only.** Trial-sized deposit, shadow mode, or a dashboard with a hole in it. | 4/10 | Priya, Sofia, Anika, Kate |
| 14 | **The incentive-alignment pitch lands as nothing, or as a competitor badmouthing the incumbent.** | 4/10 | Priya, Daniel, Trevor, Brandon |
| 15 | **The quoted 25 bps was computed on assets the provider cannot capture.** | 3/10 | Sofia, Anika, Kate |
| 16 | **The flat fee will be raised, tiered, or turned into a percentage later.** | 3/10 | Priya, Daniel, Sofia |
| 17 | **Undisclosed revenue behind the flat fee**: cash-sweep spread, securities lending, order flow, data. | 3/10 | Priya, Sofia, Wes |
| 18 | **A flat fee is a cancellable card charge**, and therefore a churn risk that a percentage does not have. | 1/10 | Daniel |
| 19 | **Methodology and rigour repel rather than reassure**; a published methodology document is a disqualifier. | 1/10 | Grace |

Objections 18 and 19 are single-subject and are retained because both invert a plan premise. See Part B, section 8.

---

## A4. Trigger events and conversion

| Subject | Trigger event | Date or window | Dated? | Converted |
|---|---|---|---|---|
| Priya Raghavan | 1,200-share RSU tranche vests, pushing employer-stock concentration past 40% of liquid net worth | **6 November 2026**, six weeks out | Yes | **Partial.** $96 flat, but only $110K of $420K (26%), run in parallel against her spreadsheet through one December |
| Daniel Okonkwo | $41K 401(k) stranded at a former employer; rollover form open in a browser tab for eleven weeks | None. 18 months elapsed, no date | **No** | **Yes.** 25 bps, $222, on the strength of done-for-you rollover alone |
| Sofia Marchetti | CPA-flagged wash sale destroyed $6,400 of losses (Rev. Rul. 2008-5); annual December harvest cycle | Recurring, December 2026 | Partly | **Yes.** $96 flat, conditional on a methodology document and shadow mode |
| Marcus Webb | Tender offer election; roughly $38K of unexpected cash landing in December | **7 November 2026** | Yes | **Yes** at $96, self-assessed 90% inside 30 days. **Defers** at $775, self-assessed one-in-three |
| Grace Lim | 14% raise and promotion two months ago; $1,100/month accumulating in checking | None. Cash-flow change with no deadline | **No** | **Not yet.** Yes on price, conversion gated on a named peer going first |
| Trevor Nash | Doug, his advisor of seven years, retires and hands the book to a colleague Trevor met once | **February 2027**, a four-month shopping window | Yes | **No.** Default outcome is Kyle, the successor advisor |
| Anika Deshmukh | Second child due February; parental leave in five months at reduced income; has asked twice for a full balance-sheet picture | **February 2027** | Yes | **Yes** at $96, on her own card, knowing the dashboard will show ~60% of household assets |
| Brandon Ruiz | Oldest child starts college; FAFSA and CSS Profile in progress; first tuition bill | **August 2027**, eleven months out | Yes | **No.** Credential refusal plus no felt investment problem |
| Kate Hollis | $52K RSU tranche vests, largest of her career; advisor proposes reinvesting at 1% | **December 2026**; advisor and CPA call **8 October 2026** | Yes | **No.** Rejected on coverage (nobody models the AMT), not on price |
| Wes Tanaka | **None.** $25K sitting inert at a credit union for three years, and he is content | n/a | n/a | **No** |

**Subjects with no trigger event:** Wes Tanaka, explicitly (the cohort's control case for funnel timing).
**Subjects with a real problem but no date attached:** Daniel (18 months of stated intent, no deadline) and Grace (cash accumulating, no deadline). Both are the clearest demonstrations of objection #1.

**The uncomfortable correlation.** Six of ten have a dated forcing event. Three of those six do not convert (Trevor, Brandon, Kate). Both subjects with no dated trigger at all still land on a price (Daniel converts, Grace does not). A trigger event is necessary to put someone in market and is not remotely sufficient to close them. Timing discipline buys attention, not revenue.

---

# PART B: QUALITATIVE INSIGHTS

## B5. Most representative verbatim quote per assumption

Selected for diagnostic value: each quote is the shortest statement that shows *why* the assumption passed or failed, not the most vivid statement about the topic.

**ka-001, Trust in Automation. Daniel Okonkwo:**
> "I don't know that it's working. I know that I haven't received an email telling me it's broken. Which is not the same thing."

Diagnostic because it separates trust from convenience tolerance in one sentence, and because Daniel is the cohort's most willing delegator. Six of ten gave a version of "the balance goes up" as their verification method. The counter-case, and the only shape of genuine trust found, is Priya: "I trust deterministic rules more than I trust people. I distrust discretion." The ceiling is Kate: "What I pay $1,400 for is not a return. TurboTax can generate a return. What I pay for is someone to call in October and someone to blame in April."

**ka-002, Switching Friction. Wes Tanaka:**
> "Nothing's stopped it. Nothing's started it. Those are different sentences and yours assumed the first one."

Diagnostic because it names the error in the assumption itself rather than answering it. The same structure appears ten times out of ten. Priya's completed ACATS took "a week and a half and about forty-five minutes," and her comment on the fourteen months before it was: "that wasn't friction, that was me."

**ka-003, Primary Pain. Sofia Marchetti:**
> "Fees aren't a job I want handed off. Fees are the filter I use to decide who I'd hand anything to. You asked me what work I want done; fees aren't work, they're the price of the work. So: not the pain. Absolutely the veto."

Diagnostic because it explains the whole pattern: extreme measured fee sensitivity coexisting with fees ranking last or nowhere. Compare Trevor, at the other end of the segment: "If you gave me ten things to hand off, fees wouldn't be in the ten."

**ka-004, Tax Optimization Value. Brandon Ruiz:**
> "Ninety-six percent of my money lives somewhere the tax code doesn't reach until I'm sixty-five."

Diagnostic because he computed it himself, unprompted and correctly, and because it is the clean structural invalidation rather than a preference. The other direction of failure is Kate: "That is not loss harvesting. It's not lot selection. It has nothing to do with my portfolio's allocation. And it is the single most valuable financial service I purchase."

**ka-005, Pricing and 25 bps Capture. Sofia Marchetti:**
> "It isn't the money. It's that you'd be charging me more each year for the same computation, and the mechanism by which your revenue grows is my savings rate. I would be paying you a royalty on my own discipline."

Diagnostic because she can trivially afford the fee she is refusing ($1,250 is "one point eight percent of what we save"), which locates the objection in structure and rules out a discount as the answer. Wes closed the escape route: "If you told me it was one basis point I'd say the same thing." Trevor and Kate supply the mirror image, in which the cheap flat price is itself the objection.

**ka-006, Onboarding Autonomy. Anika Deshmukh:**
> "I was completely willing. Zero security objection. I'd link everything of mine tomorrow, read-only, without reading the terms. And the product still fails, because the accounts that would make it worth having are not mine to give."

Diagnostic because it is a failure mode the script did not predict. The script anticipated two refusals, security and data-ownership. This is a third: structural inability to authorise, in a household where the co-approver holds the largest accounts. Wes supplies the pure data-ownership version and forecloses the usual remedy: "Read-only is what I'm objecting to. Reading is the thing I don't want."

**ka-007, Decision-Making Unit. Marcus Webb:**
> "I'm not the hard sell here, my wife is, and her first question won't be about fees. It'll be 'who are they and what happens if they go under.' If I can't answer that in two sentences at dinner, this doesn't happen, no matter how good the tax thing is."

Diagnostic because it captures both halves of what makes ka-007 actionable: the co-approver's question is institutional, and the failure mode is deferral rather than refusal. Four households produced almost the same question independently (Marcus's wife, Trevor's Jen, Brandon's wife, Kate's husband). Anika is the exception that matters more than the rule, and she is quoted in section 8.

---

## B6. Recurring vocabulary and language patterns

### Fees

**Words the segment actually used:** "a cut" and "everybody's getting a cut" (Trevor, Wes), "a royalty" (Priya, Sofia, Wes, three subjects independently), "a royalty on my thrift" (Wes), "a royalty on my own discipline" (Sofia), "a tax on inertia" (Priya), "a claim on my future" (Priya), "a claim on my balance sheet" (Wes), "a price for access versus a price for a service" (Sofia), "structure is destiny and amounts are marketing" (Sofia), "an advisor number" (Marcus, of $775), "a number I can say out loud" (Marcus, Grace, Brandon, all three unprompted), "a price I have to do math on" (Brandon), "something I can't name" (Grace), "a unit designed so I don't hear the dollar amount" (Priya, Sofia, Wes, three independent formulations of the same charge against basis points), "the price of not worrying" (Kate), "the fee isn't a pain, it's a price" (Kate), "additive, not substitutive" (Kate), "the price of the cheap seats" (Wes, of the flat fee), "the shape of the product" (Daniel, of 25 bps).

**Words almost nobody used.** "Hidden" appears from no subject. "Opaque" appears from no subject. "Gouging," "rip-off" (once, Grace, hypothetically), "extraction," "fee drag" and "AUM" are effectively absent from subject speech. This matters: the plan's language for the problem is not the segment's language for the problem. The two subjects most hostile to the fee structure (Sofia, Wes) do not describe fees as concealed; they describe them as *structurally illegitimate*, which is a different argument requiring a different answer.

**"Basis points" splits the cohort in three.** Fluent and self-converting to dollars without prompting: Priya, Sofia, Kate. Fluent but never converted in three years of paying it: Daniel ("I have never done that math... sixty-five dollars a year. That's nothing... And I work at a fintech. Put that in your notes"). Non-speakers for whom the unit does active harm: Grace ("that phrase did nothing in my brain and the number four hundred and twelve does a lot in my brain. Those should be the same amount of information and they're not"), Trevor (never repeated the unit back), Brandon, Anika (knows it only because a colleague used it at lunch), Wes (repeats it back flatly as a weapon).

### Taxes

**The vocabulary gap is the segment's real fault line, and it is binary.** Two subjects own the full technical register: "lot register," "specific-lot ID," "the sixty-one-day window," "substantially identical," "destroyed, not deferred," "Revenue Ruling 2008-5," "Publication 550," "basis reduction on the replacement shares," "asset location," "vests are purchases," "harvest surface," "carryforward," "phantom gain," "zero-basis 1099," "bracket constraint" (Priya, Sofia). Kate owns a different and non-overlapping technical register: "AMT preference item," "AMT crossover," "AMT credit carryforward," "ISO exercise window," "qualifying disposition," "compensation income, not gain," "the supplemental statement," "the IRS does not have an undo."

The remaining seven have no register at all. Marcus calls it "the tax thing" and "the April thing," and arrived independently at the best plain-language framing in the study: **"which shares to sell."** He also produced the clearest statement of the awareness gap: "There was a choice and I didn't know it was a choice." Trevor described lot selection secondhand as "the ones we'd had longest or the newest, one of the two." Daniel: "upload the PDFs and hope." Grace: "a 1099 something," and "tax strategy" framed explicitly as belonging to other people. Anika quotes her husband's "sell-to-cover" and "he harvested some losses in December" without owning either phrase. Brandon repeats Rick's "take three thousand against income" and answers "I don't have any gains."

**Product implication in the segment's own words:** Priya named the job to be done and it is not "tax-loss harvesting." It is **"the December cleanup."** Marcus named it too, and it is **"which shares to sell."**

### Advisors

**Hostile register (2 of 10):** "a guy in a Patagonia vest asking for a royalty," "the vest guy," "a quarterly PDF with a pie chart" (Wes). "One percent for thirty years," "that pipeline," "somebody with a CFP and a nice voice," "a risk questionnaire with a slider on it," "the single largest wealth transfer in retail finance" (Priya). Note that neither has ever had an advisor.

**Closed and past-tense register (2 of 10):** "the money guy," "the guy with the four phone calls," "fifteen hundred bucks a call," "the calls were the product," "I was paying for a relationship, and I don't want a relationship" (Marcus). "A man who was very nice to my father," "AUM in flat-fee clothing," "nice is not a control" (Sofia).

**Warm and specific register (3 of 10):** "my guy," "Doug," "Doug's shop," "Marcy" (named unprompted, credited with the only successful transfer of his life), "somebody who picks up" (Trevor). "Rick," "we use a guy," "a place with a building," "somebody I actually know using it" (Brandon). "Marty," "a person who owns the mistake," "a fee I'd defend in a deposition" (Wes, about his CPA, whom he prices by invoice and defends absolutely while attacking the advisory category).

**Absent register (2 of 10):** Grace has no negative word for advisors at all. No "conflict," no "salesman," no "cut." Her frame is exclusion: "those people," "minimums," "below the line," "I just assume I'm below the line." Anika's frame is favourable and instrumental: "someone to sit with me for thirty minutes and explain our own money to me," "someone who had no stake in me feeling stupid."

### Automation

"The market's not a thermostat" (Trevor, who owns a smart thermostat, a robot vacuum and a truck that drives itself on I-65). "I automate execution and I never automate a decision" (Sofia). "Neglect wearing a costume" (Daniel, on his stranded 401(k)). "An audit log and an undo. That's the entire trust requirement" (Sofia). "Show me the rule... I'll accept almost any outcome if I can audit how you got there" (Wes). "A system would be wrong in ways we could both see" (Anika, which is the study's single best argument for automation and it is an argument about marriage, not about accuracy).

### Where vocabulary splits by adoption segment: jargon reads three different ways

This is the finding that most directly contradicts premise S5-5, and it is a three-way split, not a two-way one.

1. **Jargon as extraction (Innovators and Early Adopters: Priya, Sofia, Wes, and Marcus in a milder form).** "'Optimized' is what you say when you have an objective function you don't want to disclose" (Sofia). "'We take security very seriously' is the word 'nothing' wearing a suit" (Priya). Wes repeats a jargon phrase back flatly and waits. Marcus: the record-keeper email "said something about a transition to enhance the participant experience," which irritates him as an obstacle to speed rather than as evidence of theft.
2. **Jargon as competence (Trevor, Early Majority).** Kyle, the successor advisor, talked for four minutes about "capturing upside in a higher-for-longer environment," and Trevor's reading was "this guy's going to be fine, he knows his stuff." His actual complaint about Kyle is the opposite of opacity: "he didn't ask me a single question about my kids or my income." Jargon was a positive signal and the absence of personal interest was the negative one.
3. **Jargon as self-disqualification (Grace, Early Majority; Anika in a controlled form).** "At some point I stopped looking because it made me feel stupid." "It's not that things make me suspicious. It's that they make me feel like I wandered into the wrong room." Grace's response to an offered methodology document: "my conclusion would not be 'this company is hiding something.' My conclusion would be 'oh, this is for people who read documents like this, and I'm not one of them.' And then I'd close it and not sign up, and I probably wouldn't tell you why."

Two subjects are jargon-neutral: Kate is professionally fluent in dense regulatory language and is neither impressed nor repelled; Daniel decodes it for a living and is unimpressed. Brandon's suspicion alarm is triggered by jargon, but the alarm is "what are you selling," sourced from a brother-in-law who sold insurance, not from an inference about concealed fees.

**Messaging consequence.** There is no single register. The document that converts Sofia (eight-section methodology, Revenue Ruling 2008-5 by name) is the document that silently loses Grace. Priya wants the rules published; Grace wants four sentences and a name she recognises; Trevor wants a last name and a phone number. Any one of these as the default pitch actively repels at least one adjacent segment.

---

## B7. The segment's biggest unmet need

### Primary: advance, plain-language, dollar-denominated notice of what is about to happen to your money, as a document a household can share

**The evidence is convergent to the point of being eerie: four subjects independently specified the same artefact, three of them using the same unit of measurement.**

- Kate, on the 2019 ISO exercise that cost her $19,000: "I wanted somebody to have said, in October, before I clicked: if you do this and hold, here is your AMT number, here's what it does to your April, and here's what happens to the credit in the following years. That's it. **Four sentences.** I would have paid real money for those four sentences and I had no idea I needed them."
- Anika, on her RSU sell-to-cover: "I wanted **the four sentences.** I wanted: here's how many shares vested, here's the price they used, here's the number of shares we sold, here's the dollar amount that went to the IRS, and here's why that number might be wrong and what happens in April if it is. Four sentences and a table. That's not a hard document to produce. Somebody chose not to produce it."
- Grace, on a 1099 she mistook for account fraud: "I wanted a sentence. I wanted the app to have said, in January, 'hey, here's a form, here's what it is, here's what you do with it, nothing is wrong.' **Four sentences.**"
- Marcus, on a record-keeper transition: "I wanted one email that said: here's what's happening, here's the date, here's what your money is in now versus before, here's the number, and here's what you need to do, which is nothing. **Five lines. In English.**"

Sofia's version is the engineering statement of the same requirement: "I wanted the order ticket to show me the method it was about to use. One line of text: 'this order will use FIFO.' I don't need it to be smart, I need it to be legible." Wes's is the adversarial version: "Show me the rule, show me the disbursement ledger, and let me check your arithmetic. I'll accept almost any outcome if I can audit how you got there. What I won't accept is 'trust us, this is the number.'" Priya's is the same demand aimed at documentation: the 2022 wash sale "wasn't the behavior, the failure was that the behavior was undocumented and I had to learn it from a 1099." Trevor's is the human-delivered version: one page, quarterly, "here's everything you own, here's what it's worth, here's whether you're on track."

**Count: 8 of 10 asked for this unprompted** (Priya, Sofia, Marcus, Grace, Trevor, Anika, Kate, Wes). Two did not: Daniel, who actively does not want to know ("I don't need a methodology doc. I'm not going to read a methodology doc"), and Brandon, who wants exactly this artefact for college cash flow rather than for investments ("here's the next six years with three kids in and out of school, here's where the gaps are").

**The willingness-to-pay evidence points the same way, and it is where all the large numbers in the study are.** Every four-figure price in this study attaches to a forecast or a plan, and none attaches to portfolio automation:

| Subject | Price they volunteered | For what |
|---|---|---|
| Kate | **$2,000/year**, "signed in the room," and she would cancel the advisory relationship to do it | An integrated October household projection with the ISO window and AMT crossover, with a named signatory |
| Trevor | **$2,000 to $2,500/year** | Someone actually watching it, who calls, does the December work, and sits with Jen and answers her question |
| Brandon | **$400 to $500 one-time**, "I'd write the check this month" | One page: what four years times three kids costs and where the money comes from |
| Wes | **$500 one-time**, and explicitly nothing in year two | A written plan: what you own, what happens if you sell the duplex in 2029, whether the $25K should be elsewhere |
| Anika | $96, and she named the real deliverable | "One page... showing me what I have, what it's in, and what it's costing me, in dollars, in sentences" |

Against that, the highest price volunteered for the product as described is Sofia's $350 to $500, and the median is $96. **The four subjects who refused to buy the product are the same four who volunteered the largest prices in the study, for a forecasting or planning artefact the product does not produce.** Kate's number alone is roughly 6x the flat fee and she was willing to fire her incumbent for it.

**Why this beats the alternatives.** It is not a comfortable finding, because it is closer to a document and a person than to an algorithm. But it is the only need that (a) 8 of 10 requested in their own words without prompting, (b) carries the study's only four-figure prices, (c) works in both directions of the fee debate, since it is what Grace needs in order to *understand* a price and what Sofia needs in order to *verify* an engine, and (d) is what unblocks ka-007, because the co-approver's question is answered by a page, not by a product feature. Anika put the mechanism most sharply: "The demo isn't for me. The demo is ammunition."

**Where it is weakest.** It is not a portfolio management business. Wes said so on the record about his own proposal: "that's a consulting practice, not a company." Brandon's version is not even about investments. And it is a capability with human judgment in it, which collides directly with the $96 price point that six subjects accepted, and which Kate and Trevor both read as proof that no human is present.

### Runner-up: execution of a decision the subject has already made and will not perform

The "click yes" product. Named by: Priya ("I don't need someone to hold my hand. I need something that will actually do the December cleanup I keep telling myself I'll do"), Daniel ("if you moved it for me I'd let you," and that is the entire product to him), Marcus ("if something told me here's the seventeen that should be invested, click yes, I'd click yes"), Grace ("If somebody said, put six hundred here and five hundred there, here's why in two sentences, I'd do it that afternoon. The work isn't the work. The work is the decision"), Trevor ("Somebody would have to tell me to move it. Specifically. 'Trevor, sell twelve thousand of this, here's where it goes, sign here'"), and Sofia in a more demanding form ("I'd expect to authorize it and I'd expect something else to execute it. And I'd expect to be shown the plan before it ran... If I saw that I'd approve it in ninety seconds").

**Count: 6 of 10.** Not supported by Brandon (nothing to execute), Wes (refuses delegation on principle: "the act of moving it is the act of understanding it"), Anika (cannot authorise the accounts that matter), and Kate (already buys execution, and values it: "the one percent bought the DocuSign and the associate who chases the fractional share").

**Why it is second and not first.** Willingness to pay for it is poor and one subject said so explicitly. Priya: "If someone built a business on 'we do your rollovers,' I'd use it and I wouldn't pay for it, because I'd be paying for the removal of my own procrastination on a task I value at about forty-five minutes." Daniel would pay for it, and told us his lifetime value is bad: "you'd get me cheap and you might not keep me." Marcus would pay $96 for it and $96 only. The need is broad, real and cheap. The primary need is narrower, harder, and is where the money is.

---

## B8. Contradictions and surprises

### 8a. The deadline-absence pattern on ka-002 is unanimous, and it is the study's strongest single result

Premise S5-8 holds that switching costs and ACATS are "a felt barrier, not a theoretical one." Ten out of ten subjects said, in near-identical words, that nothing is stopping the stranded asset and nothing is starting it.

> Priya: "Nothing. Nothing has to happen. That's the answer and it's humiliating." / Daniel: "Nothing's stopped it. There's no obstacle... there is no consequence for not doing it. Nothing happens on any particular Tuesday." / Sofia: "Nothing has to happen. I just haven't." / Marcus: "Nothing made it two and a half years. That's the honest answer." / Grace: "Nothing has to happen. That's the problem." / Trevor: "Nothing's stopped it. There's no form I'm scared of." / Anika: "Nothing has stopped it, because nothing has asked." / Brandon: "Nothing's stopped it. Nobody's asked me to do anything with it." / Kate: "Absolutely nothing has stopped it. Nothing has *started* it, which is different." / Wes: "Nothing's stopped it. Nothing's started it. Those are different sentences and yours assumed the first one."

Where mechanical friction was real, it was quantified and it did not bind. Sofia's 401(k) rollover took 34 calendar days, required a wet signature and a $96,000 paper check that sat in her kitchen for two days, and cost roughly $1,300 in out-of-market drift, five and a half times her entire annual expense ratio. It did not stop her. Her comment on the three-month delay before she started: "The delay was that nothing forced it until I sat down to do the Roth." Marcus's $41K rollover check sat eleven days under a stack of preschool forms. What finally unstuck it was Mint shutting down, which is to say an external deadline. Priya's completed ACATS took forty-five minutes of effort and she had no worst part to report: "The worst part of moving eleven thousand dollars was the fourteen months I spent not moving eleven thousand dollars, and that wasn't friction, that was me."

**Consequence.** Onboarding UX is not the lever on ka-002 and money spent reducing transfer steps is largely wasted. The lever is trigger-event timing and manufactured deadlines. Two further notes: Brandon has never once moved investments between institutions in 22 years, so there is no friction in his life to reduce; and Anika's statement is the cleanest disconfirmation available: "If you handed me a product that made transfers take four minutes instead of four weeks you would have solved a problem I have never once had."

### 8b. $96 flat reads as low capability, and it repels exactly the subjects who most need persuading

Six of ten had a negative reaction to the cheap price, and they split into two distinct failure modes that require opposite responses.

**Mode 1, low capability (Trevor, Kate, Marcus, Daniel).** Trevor: "My lawn guy is sixty-five a cut... You're telling me you'll manage two hundred seventy-five thousand dollars of my family's money for less than one month of lawn care? That doesn't sound cheap to me, it sounds like nobody's looking at it. I know exactly what an hour of a competent human being costs, and there is no version of ninety-six dollars where anybody is looking at my account." Kate: "Ninety-six dollars doesn't buy eight minutes of anyone's attention. It's a software license. Which is fine if it's honestly a software license, but then don't tell me you handle my RSU vests, because handling my RSU vests is a judgment call and judgment doesn't cost ninety-six dollars." Daniel: "My instinct isn't 'great deal.' My instinct is 'what's missing.'" Marcus: "Six thousand dollars bought me four phone calls, and ninety-six dollars is going to buy me what, exactly?"

**Mode 2, non-viability (Priya, Sofia, Daniel).** Priya: "My concern with the flat fee isn't that it's too cheap to be good, it's that it's too cheap to persist, and then in three years you either raise it, or you add a percentage tier, or you get acquired by someone who does, or you start monetizing my order flow or my data... I'd rather you charged me two hundred and forty. Genuinely." Sofia's suspicion drove her to the actual question: "What's the yield on uninvested cash in the account, and what's the spread you keep?" and then to the conclusion that "the ninety-six-dollar flat fee has a percentage fee hiding behind it whose size is set by a discretionary allocation decision that you control and I don't see."

**Both modes converge on the same recommendation from opposite directions.** Sofia: "Ninety-six dollars is less than I'd pay. You're leaving two hundred and fifty to four hundred dollars a year on the table with me, and you're doing it in a way that costs you twice, because the low price also triggered my suspicion reflex... At four hundred dollars flat I'd have assumed you were a real business. At ninety-six I assumed you were subsidized or selling something else." Priya independently volunteered $240. Marcus's stated threshold is "under a couple hundred a year, I don't want to talk about it," which is a ceiling of roughly $200, not $96. **Three of the five flat-fee converts named a price materially above $96, and the two subjects for whom price acceptance was easiest (Kate, who experiences 25 bps as a discount, and Trevor, whose benchmark is $2,000) were the two most repelled by the cheap tier.** The $96 price point is simultaneously leaving money on the table with the buyers and disqualifying the product with the non-buyers.

Wes added the structural read nobody in the plan appears to have anticipated: at his $25K balance the flat fee ($96) is 54% *more* than the percentage ($62.50), and he noticed what that implies. "The structure is: small accounts pay a floor, big accounts pay a royalty. The flat fee isn't a philosophy, it's a minimum. Don't sell me the flat fee as a principled stand when it's the price of the cheap seats."

### 8c. The household approval threshold sits between the two price points, and it decides conversion

Five subjects have a real spousal co-approval process and four of them named a dollar threshold above which a purchase becomes a household conversation. The thresholds cluster tightly: Marcus ~$500 ("anything recurring over about five hundred, we discuss"), Anika ~$300, Grace ~$300 (a personal rather than spousal ceiling, set by an $800/month parental obligation), Trevor a formal $10,000 written rule for asset moves but a "take it to Sunday night" reflex for any recurring service, Brandon and his wife a mutual veto on everything.

Anika stated the implication more precisely than the study design did:

> "Four hundred and ninety-five is a no. And not because it's unaffordable, we make two hundred and fifty-eight thousand dollars a year, four ninety-five is nothing. It's a no because four hundred and ninety-five dollars a year is a kitchen table conversation and ninety-six dollars is not. That's the entire difference between them. The structure isn't the deciding factor, the *approval threshold* is, and **you've drawn your two price points on either side of the line that runs through my marriage.**"

She also disclosed that her stated fair price was derived from the threshold rather than from value: "Two hundred is under the threshold where it becomes a household decision. That's the derivation. It's not a value calculation, it's a permission calculation."

Marcus quantified the same effect as a conversion probability rather than a preference: he would personally probably pay $775, and he put the odds of it actually happening at "a third" versus "ninety percent, this month" at $96. "That gap is not about the six hundred and eighty dollars. It's about which of those requires a meeting." And he named the mechanism, which is not rejection: "What happens is she says 'okay, look into it and let's talk about it next week,' and next week the tender election is due and I'm in a planning cycle at work and we never talk about it. That's how this dies. Not rejection. Deferral."

**Consequence.** There is a hard pricing cliff at roughly $300, and it is a process cliff rather than an economic one. A price above it does not lose the sale; it converts the sale into a meeting that does not get scheduled. Any price between $300 and $500 buys the worst of both outcomes: it is above the permission threshold and below the capability threshold.

### 8d. The capturable-assets gap: 29.3%, and two subjects found it before we did

Premise S3-3 puts investable assets at $25K to $500K and the pricing model applies 25 bps to that figure. Of $2,808,000 in stated assets across the cohort, $824,000 is capturable, **29.3%**. The gap is not caution or reluctance; it is structural and mostly statutory:

- **Active-employer 401(k) and 403(b) balances that cannot move while employed:** Priya $160K, Daniel $34K, Sofia $205K + Marco's $88K, Marcus $148K, Grace $78K, Trevor $124K + Jen's $61K, Anika $86K, Brandon $246K, Kate $188K + husband's $141K. That is roughly $1.56M, over half the cohort's stated assets, structurally unreachable.
- **State-plan 529s:** roughly $170K across six households.
- **Illiquid private equity comp:** Marcus's $190K of double-trigger RSUs, Daniel's ~$80K of unexercised options, both of which the holders value at zero.
- **Spouse-held accounts the subject cannot authorise:** Anika's husband's $67K, which is not a trust problem and not solvable by a better flow.
- **Hard refusals:** Brandon's entire balance sheet and Wes's, on credential and data-ownership grounds respectively, plus Wes's $210K solo 401(k) ("That one's not moving. Ever, probably").
- **Trial-sized initial deposits:** Priya will move $110K of $420K and run the service in parallel for two quarters. "I do not ACATS four hundred thousand dollars to you on day one, that's not happening, I don't care how good the docs are."

Kate and Sofia both corrected the interviewer's arithmetic in real time, and Kate went further and re-ran the whole business case on the corrected base: at $127K capturable, 25 bps is $320, her all-in goes from $2,200 to about $1,720 rather than to $1,200, "a saving of roughly four hundred and seventy dollars a year for a materially worse answer to my hardest question. Four hundred and seventy dollars is one night out and half a hockey season." Anika made the corresponding product point rather than the pricing point: a partial link produces "a dashboard with sixty percent of our money on it and a hole where the rest goes. Which is the app I already deleted."

**Consequence.** Every revenue projection built on stated investable assets is overstated by roughly 3.4x. The error compounds with the pricing error: 25 bps of stated assets is $7,020 across the cohort, 25 bps of capturable assets is $2,060, and 25 bps actually collectible is $222.

### 8e. The fee-grievance decay curve: fee pain is an episode, not a standing condition

Premise S5-3 makes fees and tax drag the primary fears, and S3-8 makes the segment fee-aware with varying intensity. What the interviews show is sharper and worse for the positioning: **fee grievance is an acute episode that resolves permanently once the subject fixes the fee, after which it stops being a pain and becomes a purchase filter.** Zero of ten ranked fees first in Q3.

Marcus supplied the decay curve explicitly, unprompted, with a date on it:

> "I think if you'd asked me in 2022 I'd have said fees, first, angry. Now it's taxes, then the new-money thing, then time in general, then fees... I already fired the expensive thing. That was the fee problem and I solved it. What's left is cheap."

The same shape appears in the two most fee-sensitive subjects in the cohort. Priya: "Fees aren't on the list because I've already solved them... You can't outsource a problem you've finished," and she ranks them "somewhere around ninth, below 'figure out whether a backdoor Roth is worth the paperwork.'" Sofia: "I've already solved my own fee problem. I got it down to four and a half basis points by myself. It took a bad discovery at twenty-nine and about six months of work, and it's done. Where fees are enormous is as a disqualifier... not the pain. Absolutely the veto." Kate never had the grievance at all: "The fee isn't a pain, it's a price, and I made a decision about it with the numbers in front of me. I've never lost sleep over $2,200. I have lost sleep over nineteen thousand."

**The positioning consequence is severe.** P-4 states the thesis is incentive alignment: the provider does not profit from opacity. Four subjects heard that pitch and told us what it did.

- Priya: "Telling me you're not conflicted is table stakes, it's not a product... I don't need someone to explain why the other guy is bad."
- Daniel: "If your pitch to me is 'we're aligned with you and the other guys aren't,' I'd go, sure, okay, cool. And it would not move me one inch."
- Brandon: "When somebody tells me there's money leaking out of my accounts that I can't see, my first thought isn't 'oh no,' my first thought is 'okay, what are you selling.'"
- Trevor: "I've been in sales for fifteen years. I know what it sounds like when a competitor badmouths the incumbent. It sounds exactly like that. It's the oldest play in the bag and I've run it myself."

The alignment story is inert with the people who already believe it and actively counterproductive with the people who do not. It landed as a product with nobody.

### 8f. Additional contradictions worth recording

**Jargon reads as competence for a third of the real market (contradicts S5-5).** Trevor's reading of "capturing upside in a higher-for-longer environment" was "this guy knows his stuff." The cohort notes flagged this as deliberate, and it held.

**Rigour is a repellent, not a reassurance, for part of the Early Majority (new failure mode).** Grace on a published methodology document: "I think that would push me away... my conclusion would be 'oh, this is for people who read documents like this, and I'm not one of them.' And then I'd close it and not sign up, and I probably wouldn't tell you why." This is the exact inverse of Sofia's eight-section methodology demand, in the same cohort, at overlapping asset levels. There is no single document that serves both.

**The co-approver can be the incumbent competitor (contradicts the whole shape of ka-007).** Marcus, Trevor, Brandon and Kate produced the expected co-approver question about institutional legitimacy. Anika produced a different and harder one: "Not 'who are you and what if you go under', he doesn't care about that, he's a software architect. His question is narrower and harder: *what does this do that my spreadsheet doesn't.* And 'it does it automatically' is not an answer to a man who likes doing it." The competitor in her household is free, already installed, emotionally invested, and holds the credentials.

**For solo buyers the co-approver is replaced by a crowd, and it is unbuyable.** Priya: "Not a person with authority, no. But I'd want *something*, and it's not a person, it's a crowd. I'd search r/Bogleheads for the company name and read every thread... If there were three threads saying the tax-lot logic did something weird, that would stop me faster than any spouse would." Grace's five-person group chat has a real and exercised veto: "If I'd asked about that savings account and two people said 'eh, I looked at that, seemed sketchy,' it would be over. I wouldn't research it further and decide they were wrong." She also stated she has never been first at anything financial.

**The incumbent advisor is a gate on the aggregation step, and the customer knows it and cannot route around it.** Kate: "My first move would be to forward the terms to my advisor and ask what he thinks... He'd say be careful. Of course he would. He'd have a reason that sounded like data security and the real reason would be that I'm his client. I know that. I'm not naive about the incentive. But I'd still ask, and if he pushed back with anything halfway credible I'd probably slow down, and slowing down for me has historically meant not doing it. You should write that down as a problem rather than let me talk my way out of it."

**Two subjects would pay more on a flat fee than less as a percentage, which is the script's own marker for a principled objection.** Priya: "I'd pay three hundred flat over two hundred in basis points, and I want you to understand that's not an economic statement, it's a structural one." Sofia: "Five basis points on two-oh-seven is a hundred and four dollars, which is basically your flat price, so a rational agent should be indifferent. I'm not indifferent, and I've decided that's not irrationality, it's a correct read on where the structure goes. Nobody's percentage fee has ever gone down." Wes lived the inversion: at his balance the flat fee costs 54% more than the percentage and he takes the flat fee anyway. Brandon volunteered the same: "Even then. I'd rather pay more and know what it is. I realize that's not rational but I'll stand on it." **A discount is not an answer to this objection, and four subjects closed that door before it was opened.**

**Fee invisibility is a retention feature, and the most willing buyer in the cohort said so.** Daniel: "A percentage comes out of the account. A flat fee hits my card. I see my card... If you charge me ninety-six bucks on my Amex, there is a real chance I cancel you in month fourteen during a subscription purge, and if you take it out of the portfolio I will literally never think about it again... Yeah. Yes. That's true and it's stupid and it's true." The transparency the positioning is built on is, for at least one segment, a churn mechanism.

**The onboarding assumption fails in three ways, not the two the script predicted.** Security refusal (Brandon: "That's not a 'convince me' no"). Data-ownership refusal (Wes: "Read-only is what I'm objecting to. Reading is the thing I don't want," and "data is an asset that conveys"). And three new modes: an engineering-quality screen (Priya abandoned a tool for requesting a password where OAuth exists, and imposed a five-item disclosure checklist), a supervision requirement (Trevor: "me alone at 10 p.m. with a hotel wifi and a screen asking for my Fidelity password? I close the laptop. Every time... If somebody walked me through it on the phone, I'd do it in six minutes"), and structural inability to authorise (Anika). None of the three is solved by a better flow.

**The product's actual output, in at least one household, is a marital conversation.** Anika, asked what we should have asked: "You should have asked what happens if it works... your product's actual output, in my house, is a conversation I've been avoiding for eight years, and you should know that's what you're selling me. I'd still buy it at ninety-six."

---

## B9. Study limitations

These are ten synthetic subjects, generated from a reconstructed set of premises, interviewed by the same party that holds the hypotheses. That is three compounding sources of circularity and it bounds what any number above can mean. The subjects cannot produce evidence: every dollar figure, date, error history, spreadsheet tab count and verbatim quote in this study was authored rather than observed, and where a transcript reports that a subject computed something correctly, that correctness is a property of the generation and not a finding about the world. The source basis itself states that the originating Business Plan and Misaligned Incentives documents were absent from the repository, so the seven assumptions were extracted from the study brief rather than from the plan they are meant to test, and any premise that is wrong is wrong in the same direction across all ten profiles. The cohort's most striking results are partly designed in and were disclosed as such in advance: four to five co-approvers, two hard aggregation refusals, one jargon-positive subject, one subject with no tax surface, one with no trigger, and exactly one for whom 25 bps is a price cut, which means ka-007's 50% validation rate and ka-004's 70% invalidation rate are substantially artefacts of sample construction rather than measurements of a population. The sample is also too small for any percentage in this document to carry a confidence interval; a single reclassified verdict moves a rate by ten points, and three verdicts were in fact reclassified here on judgment. Finally, the capturable-asset figures are the least defensible numbers in the study and the most load-bearing: four of ten were estimated by the analyst from account breakdowns rather than stated by the subject, and the decision to record Brandon and Wes at zero rather than at their theoretical surfaces moves the central ratio by three points. **Everything here should be read as a priority ranking over hypotheses to go and test against real people, not as a measurement of anything. Its only legitimate output is a list of questions worth the cost of asking a human, and the ranking of which assumptions are most likely to break first.**
