# Fair Isaac Corporation (FICO) — Deep Dive
*Date: 2026-07 · Status at research date: WATCH*

> Historical research draft, July 2026. Prices, events and position-sizing examples refer to the dates in this note. Source claims have not been revalidated for this edition; open verification items remain.

---

## 1. Situation in three sentences

FICO is down ~47% from its Nov-2024 all-time high (~$2,382 close) to ~$1,251 (7/10/26 close) because the FHFA — after telegraphing it since October 2022 — began actual acceptance of VantageScore 4.0 at Fannie/Freddie on April 22, 2026, ending Classic FICO's ~30-year formal exclusivity in conforming mortgage underwriting; the stock printed its 52-week low of ~$870 that same day. Meanwhile the business itself is accelerating, not eroding: Q2 FY26 (March quarter) revenue grew 39% to $692M, Scores grew 60%, mortgage-origination score revenue grew 127% (on a 2x price increase to ~$10/score), guidance was raised, and management repurchased a record $605M of stock in the quarter. The question is whether April 2026 marks the start of real revenue erosion or a regulatory head-fake — and the honest answer from the evidence is "mostly head-fake on *share*, but the real risk was never VantageScore; it is Washington attacking FICO's *price* lever, which now sits under ~43% of revenue."

---

## 2. Who is selling and why (seller-identity analysis — the core of the edge)

**The path of the stock tells you who left.** $2,382 (11/24) → ~$1,300s on Pulte's July 8, 2025 "effective immediately" VantageScore announcement → recovered to a 52-week high of $1,998 on Oct 2, 2025 (the day FICO announced its bureau-bypassing Direct License Program) → ground down through winter → $870 intraday panic low on April 22, 2026 (formal GSE implementation) → +44% off the low to $1,251 by July 10, 2026. Through this entire round trip, trailing EPS *rose* ~45%. The decline is 100% multiple compression: from ~80–90x trailing at the 2024 peak to ~40x trailing / ~31x FY26-guide today. (Price points: Macrotrends/stockanalysis.com; ATH and 52-wk figures vary slightly by source between close and intraday — 52-wk high also reported as $2,206 intraday May 2025 by one source; unverified to the dollar.)

**Seller cohorts, in rough order of importance:**

1. **Quality-growth/momentum funds that owned "the monopoly" at 60–90x.** For them, the FHFA announcement doesn't change 2026 EPS — it breaks the *narrative* that justified the multiple ("regulated toll road that can never be disturbed"). Once the story requires handicapping a hostile regulator, the position no longer fits the mandate. They sell regardless of price. This is classic non-fundamental, mandate-driven supply.
2. **Headline-risk de-riskers.** FHFA Director Pulte has publicly called FICO a "monopoly who has ripped off Americans for decades" and complained about a "40% price increase [with no] legitimate basis"; a Senator opened an investigation into FICO's mortgage pricing (PYMNTS, 2026); CHLA published that FICO's tri-merge component rose ~1,500% in four years ($1.80 → $30). Institutions that cannot underwrite political risk sold first and will read filings later. April 22's 13% one-day drop — on news that had been formally previewed on July 8, 2025 and in-principle since October 2022 — is the tell that the marginal seller was not doing implementation analysis.
3. **Quant/momentum.** 200-day MA is $1,407 vs price $1,251; the stock spent 2025–26 in a persistent downtrend, which mechanically forces trend-following supply.
4. **The informed seller who may be partly right.** Some sellers correctly recognize that FY26 earnings embed a politically radioactive 2x price hike ($4.95 → ~$10/score) and that the peak-multiple era extrapolated a pricing runway that is now politically contested. This portion of the de-rating is rational, and we should not pretend otherwise.

**Why the panic looks overdone on the facts (the edge):** the April 22 announcement was a *limited rollout to approved sellers* — Freddie's own capital-markets notice (f498news.pdf, 4/22/26) says "a limited rollout with approved Sellers... working to ensure operational readiness before broad availability." As of the GSEs' July 6, 2026 update, there is still **no published data showing any material volume of VS4-scored loans actually delivered**, FHA has *not yet* implemented (it says "next few months"), and FICO 10T implementation "will follow at a later date." Management said on April 29: "We anticipate no loss of volume to Vantage in this fiscal year" — and raised guidance. The seller sold a headline; the filings describe a pilot.

---

## 3. Business quality & moat

**The Scores franchise is one of the best business models extant.** FICO writes an algorithm; the bureaus/resellers compute and distribute it; FICO collects a royalty on ~10 billion+ scores a year with essentially zero incremental cost. Company-level non-GAAP operating margin hit 65% in Q2 FY26; ROA ~37%, ROCE ~70% (stockanalysis.com). B2B Scores incremental margins are ~90%+ (estimate).

**Moat sources, ranked:**
1. **Coordination/switching costs across the securitization chain (the thesis's core claim — verified as real).** A mortgage credit score is not a product one buyer chooses; it is a *language* spoken simultaneously by originators, LOS/POS software, mortgage insurers, servicers, rating agencies, GSE AUS engines, CRT investors, and MBS investors' prepay/credit models trained on 30 years of FICO-keyed data. Evidence of friction from the last 90 days: VS4 scores run ~10 points higher on average than Classic FICO with ~15% of loans differing by >50 points (per industry/HousingWire reporting), creating adverse-selection and prepay-model problems that BofA's agency-MBS research flagged publicly; S&P said it "could" rate VS4 collateral but via a *mapping back to FICO-based models*; lenders report they struggle to compare the two scores. "Lender choice" score-shopping is itself now cited as a looming risk *by investors* — which pressures the GSEs to keep the rollout slow and disclosed (VS4 loans carry special feature codes and, since Nov 2025, dedicated MBS disclosure fields).
2. **Two decades of head-to-head evidence outside mortgage.** VantageScore (owned by the three bureaus) has existed since 2006 with free/cheap pricing and has won essentially no *paid decisioning* share: FICO's CEO puts VS revenue-relevant penetration at ~2%/"trivial" in cards and auto. VS's headline "42 billion scores used in 2025, +55%" is dominated by free consumer-education channels (Credit Karma et al.). Real but niche decisioning wins exist (Synchrony cards, SoFi, Toyota Motor Credit, Exeter auto ABS; ~$24B of 2025 ABS issuance referenced VS) — worth monitoring, not yet worth capitalizing.
3. **Brand as the unit of account.** "FICO" is the score consumers, regulators, and capital markets denominate in. Note myFICO B2C grew only 5% — the moat is B2B infrastructure, not consumer brand love.
4. **Counter-positioning moves now in flight.** FICO is (a) giving away FICO 10T free with Classic FICO, so the "modern score" slot need not default to VS4; (b) disintermediating the bureaus with the Mortgage Direct License Program (resellers compute scores directly; three of five major resellers signed as of April); (c) shifting to success-based pricing — 10T at $0.99/score + $65 funded-loan fee (revised April 2026 from $4.95 + $33) — which matches VS4's ~$0.99–$4.50 sticker prices at the application stage while monetizing closed loans. This turns the bureaus' markup (the actual source of most tri-merge cost inflation) into FICO's political shield and margin pool.

**Software segment — real and improving, not the crown jewel.** FY26 software revenue running ~$860M (est., Q1 $207.5M + Q2 $217M annualized; unverified for H2). Total software ARR $789M, +10% YoY; **platform ARR $349M, +49%** (mid-30s ex-migrations), platform NRR 136%, total NRR 109%. Decent vertical-SaaS economics inside a scores company; a legitimate second engine but only ~35% of revenue and much lower margin.

**Grade: business quality A+. Moat wide but with one gate — the moat protects *share*; it does not protect *price* from a regulator who owns the mandate.**

---

## 4. Normalized owner earnings & balance sheet (arithmetic shown; unverified inputs flagged)

**Reported base (all from company releases/transcripts unless noted):**

| Item | FY2025A | FY2026 guide (raised 4/28/26) |
|---|---|---|
| Revenue | ~$1.99B (unverified to $M) | $2.45B (+23%) |
| GAAP EPS | $25.07 (per Barchart; guide was $25.60 — reconcile in 10-K) | $35.60 |
| Non-GAAP EPS | ~$29.15 (guide; actual unverified) | $40.45 |
| FCF | TTM through 3/31/26: $867M (company) / $901M (stockanalysis) | ~$950M–$1.0B (my estimate, unverified) |

Shares: ~23.2M (stockanalysis; a second source says 23.7M — minor discrepancy, use ~23.2–23.7M). Market cap ~$29.0B at $1,250.90.

**Mortgage concentration — the revenue actually at risk:**
- Q2 FY26 Scores revenue $475M, of which mortgage originations = 63% → **~$299M/quarter** (also = 72% of B2B). Mortgage grew +127% YoY.
- FY26 mortgage-scores revenue estimate: ~$1.0–1.1B of $2.45B → **~42–45% of total company revenue** (my estimate from quarterly disclosures; unverified).
- At ~90% incremental margins, mortgage scores ≈ **55–60% of company operating profit** (estimate).
- Unit/price cross-check: Q2 FY25 mortgage revenue ≈ $132M ÷ $4.95 royalty ≈ ~27M scores; Q2 FY26 ≈ $299M ÷ ~$10 ≈ ~30M scores. Implies the +127% was ~2x price and ~+10% volume — i.e., **the "60% Scores growth" is a price event, not a demand event.** (Score-count arithmetic is mine and crude — prequal/soft pulls may be priced differently; unverified.)
- Pricing headroom context: FICO royalty ~$10 vs. tri-merge report retail of ~$47–$120+ per applicant and total credit-related costs per closed conventional loan reported near ~$540 in 2026 (MBA/CNBC/HousingWire; figures vary by source and include multiple pulls — treat as directionally right, unverified precisely). Against a ~$6,000–$12,000 all-in closing-cost stack, FICO's take remains small — **economic headroom is real; political headroom is exhausted** (Pulte quotes, Senate inquiry, CHLA's "1,500% in 4 years" letter).

**Normalized owner-earnings range (fully-taxed, my arithmetic):**
- **Reported FY26 owner earnings:** non-GAAP NI ≈ $40.45 × 23.6M ≈ **$955M**; FCF similar (FCF conversion historically ~100%).
- **Bear-normalized ("politically safe pricing"):** roll mortgage price back to CY2025 ~$4.95 → revenue −~$500M, nearly all pre-tax profit → OE ≈ $955M − $500M×0.79 ≈ **~$560M**.
- **Bull-normalized ("mid-cycle volume"):** originations are cyclically depressed (~5M units/yr vs ~7–8M mid-cycle — unverified); +40% mortgage units at current pricing → +~$400M revenue → +~$315M after tax → OE ≈ **~$1.27B**.
- **Central normalized OE: ~$900M–$1.0B.** Note the uncomfortable symmetry: current earnings sit almost exactly at the midpoint of a range whose width is determined by politics, not operations.

**Balance sheet (10-Q, 3/31/26):** total debt $3.64B (93% senior notes, w.a. 5.5%; issued $1.0B new notes during H1); cash + investments $272M; **net debt ~$3.37B ≈ 2.9x TTM EBITDA ($1.16B)**. Aggressive but serviceable given FCF; note they are levering up to buy back stock — $605M repurchased in Q2 (484k sh @ $1,251 avg, largest quarterly buyback in company history), plus $170M more in April (164k sh @ $1,040), against a $1.5B authorization (April 2026; supersedes June 2025's $1B — details unverified). Share count −3.0% YoY. Management bought the panic — the April purchases at $1,040 now mark ~20% gains. CEO Lansing's only 2025–26 Form 4 activity found was a small charitable-gift-linked sale at ~$1,733 (Nov 2025); no insider open-market buys found (checked openinsider-indexed sources).

---

## 5. Valuation: what the price implies, and base / bull / bear intrinsic-value range

**Current marks (7/10/26, $1,250.90):** market cap ~$29.0B; EV ~$32.4B; trailing P/E 39.7; **P/E on FY26 guide: 35.1x GAAP, 30.9x non-GAAP**; NTM consensus P/E 25.5 (implies ~$49 NTM EPS); EV/EBITDA 27.9x; **EV/FCF 36x trailing, ~33x FY26E**. FY27 consensus EPS $46.38. Greenblatt lens: EBIT/EV ≈ 3.9% (FY26E EBIT ~$1.26B est.) — this is priced as a compounder, not a bargain. Ten-year multiple range: roughly ~25–30x (2016–18) to 80–90x+ (2024 peak) trailing (approximate, from charting services; unverified) — today sits at the low end of the *modern* range but above the pre-2019 range.

**What the price implies (reverse engineering):** $1,251 ≈ 15% EPS CAGR for 5 years (to ~$81 non-GAAP FY31, incl. ~3%/yr share shrink) × 25x exit, discounted at 10%. i.e., **the market is paying for near-full retention of the mortgage franchise plus continued growth, and offers no margin of safety against the political tail.** Conversely, the market is *not* pricing catastrophe: strip mortgage entirely (~$600M residual NI) and you'd be paying ~48x the remainder — so a full-loss scenario is nowhere in the price either.

**Sum-of-parts intrinsic value (my estimates, fully-taxed earnings, 10% hurdle):**

| Piece | Basis | Bear | Base | Bull |
|---|---|---|---|---|
| Software | ~$860M rev; $789M ARR, platform 49% growth | $4.5B | $5.5B | $7.0B |
| Scores ex-mortgage | ~$540M rev, ~$340M NI-equiv; 20-yr record vs VS | $7.0B | $8.5B | $10.0B |
| Mortgage scores | ~$1.05B rev, ~$710M NI-equiv | $3.0B (price rollback + slow share leak) | $10.5B (~15x: glacial share loss offset by volume recovery) | $17.0B (share holds, volumes normalize, funded-fee model expands $/loan) |
| Net debt | 3/31/26 | −$3.4B | −$3.4B | −$3.4B |
| **Equity value** | | **$11.1B ≈ $480/sh** | **$21.1B ≈ $910/sh** | **$30.6B ≈ $1,320/sh** |

These multiples are deliberately value-fund conservative (base ≈ 22x blended NI). Allowing a quality premium (25–28x blended, defensible given 65% margins/70% ROCE and the ex-mortgage engines' durability) stretches base to **~$1,000–1,100** and bull to **~$1,550–1,700**. Probability-weighting at 20/50/30 (bear/base/bull) on the quality-premium set: **~$1,190 — roughly today's price.** The April low of $870 was ~25–35% below base IV; today's $1,251 is not.

---

## 6. Catalyst map (dated where possible)

- **Jul 24, 2026** — FHFA comment deadlines on pending proposals (per MBA Advocacy Update 7/6/26); watch for anything touching tri-merge/credit-report requirements.
- **Jul 29, 2026** — FQ3 FY26 earnings (consensus EPS ~$10.41): first full quarter under GSE VS4 acceptance. Watch: mortgage score volumes, any VS4 commentary, reseller sign-ups (last two of five), buyback pace.
- **"Next few months" (FHA's words, Jul 2026)** — FHA implementation of VS4 and FICO 10T; broadens the arena but also puts *FICO 10T* on equal modern footing.
- **H2 2026** — GSEs move from "limited rollout" to broad VS4 availability; FICO 10T historical data released Jul 1–6, 2026 → 10T GSE implementation "at a later date." Every month of "limited rollout" is confirmation of the glacial thesis.
- **~Nov–Dec 2026** — **FICO's CY2027 mortgage price announcement: the single most important catalyst.** Another aggressive hike invites regulatory/congressional retaliation; a flat or restructured (funded-fee) price signals détente and de-risks the multiple.
- **Ongoing, monthly** — GSE MBS disclosure data: VS4 loans carry special feature codes/dedicated disclosure fields (since Nov 2025). **VS4 share of GSE deliveries is directly measurable — this is the tripwire dataset.**
- **Undated** — Senate investigation into FICO mortgage pricing; FHFA "review of credit bureau policies"; any GSE-release-from-conservatorship action (changes FHFA's incentives unpredictably).

---

## 7. Pre-mortem: the three most likely ways this loses money, and tripwires/kill criteria

1. **Washington strikes the price lever (most likely, most damaging).** FHFA conditions GSE eligibility on score-price caps, forces a rollback of the 2026 2x hike, or a settlement/legislation caps royalties. ~43% of revenue / ~60% of profit reprices down 30–50%; stock re-rates toward bear SOTP ($500–700). *Tripwires:* CY2027 price announcement content; any FHFA directive mentioning score pricing; Senate investigation escalating to hearings/subpoenas; FICO conceding price in the direct-license terms. *Kill criterion:* any mandated price rollback → thesis over, exit regardless of price.
2. **Bi-merge / single-score revival.** July 2025's decision *kept* tri-merge, but MBA is actively lobbying to drop it and Pulte has teased "changes to credit report policies." Bi-merge cuts FICO mortgage units ~33% overnight (2 scores instead of 3); single-score −67%. The funded-loan-fee model partially hedges this (fee is per borrower per score under the Classic program — whether the $65 10T fee is per-loan or per-score is unverified; check contract terms). *Tripwires:* FHFA RFI outcomes after Jul 24; any GSE selling-guide amendment on report requirements. *Kill criterion:* formal bi-merge adoption without offsetting FICO price/fee restructuring → cut position at minimum.
3. **The margin becomes the market: real VS4 share compounds.** Aggregators with pricing incentives (UWM, Newrez already report eligibility/pricing wins on VS4's ~10-point-higher scores; Rocket is offering it) adopt VS4 as default for the marginal borrower; once ~20–30% of deliveries prove smoothly securitizable, the coordination moat dissolves bureau-by-bureau while bureaus price VS4 at $0.99/free (TransUnion $0.99; Equifax $4.50 w/ free bundle; Experian free — 2026 promos). Compounded by: mortgage volumes staying depressed (no rate relief), so the volume-recovery leg of the bull case never arrives. *Tripwires:* VS4-flagged share of GSE deliveries >2% by YE2026, >5% and accelerating by mid-2027; any top-5 lender making VS4 its *default* (not optional) score; GSE pricing grids offering better LLPAs on VS4 loans. *Kill criterion:* VS4 delivery share >10% with FICO mortgage volumes declining YoY → the glacial assumption is dead.

*Meta-risk:* leverage amplifies all three — 2.9x net debt/EBITDA means a profit shock compresses equity fast.

---

## 8. Verdict & the price/fact that changes it

**WATCH.** The backlog thesis is *directionally verified but half-complete*. Verified: adoption friction is real and enormous (limited pilot rollout, no delivery volume yet, 10-point score mismatch, S&P mapping crutch, MBS-investor objections, FHA not live, 10T deferred); the 2006-founding VantageScore has never taken paid share from FICO in any open field; management is countering intelligently and buying back stock at scale. The half the backlog missed: **the bear case was never VantageScore taking share — it is the FHFA/Congress taking FICO's price**, and FY26's spectacular optics (+60% Scores growth) are manufactured by the very 2x price hike that is the political casus belli. At $1,251 (31x FY26 non-GAAP guide, EV/FCF ~33x, EBIT/EV ~3.9%), the price already assumes ~15% compounding with a premium exit multiple — approximately fair value with a fat left tail. The market offered $870–1,000 within the last 90 days; that range merits renewed valuation work, and panic headlines will likely offer it again.

- **Price that changes it: ≤ ~$1,000–1,050** (≈25x FY26 non-GAAP guide; ≈ base-case SOTP with quality premium and ~20%+ upside cushion) → upgrade to PURSUE, sized for the regulatory tail.
- **Fact that changes it (upgrade):** CY2027 mortgage pricing lands without FHFA retaliation **and** VS4-flagged GSE deliveries are <2% at YE2026 → the two live risks decay together; PURSUE up to ~$1,150.
- **Fact that changes it (downgrade):** mandated price rollback, bi-merge adoption, or VS4 delivery share >5% and accelerating → PASS/exit; the toll road has lost tolling power, and no multiple below 20x makes that safe with 2.9x leverage.

---

## 9. Verification checklist (exact documents to read next)

1. **FICO 10-Q for quarter ended 3/31/26 (filed ~May 2026, SEC EDGAR CIK 814547)** — confirm: mortgage-origination revenue disclosure, exact debt schedule/covenants, buyback detail, any new VS4/regulatory risk-factor language vs the 10-K.
2. **FICO FY2025 10-K (filed ~Nov 2025)** — pin down: FY25 actual revenue/EPS/FCF (my ~$1.99B / $25.07 / ~$780M figures are partially unverified), Scores B2B vs B2C split, mortgage % of FY25 revenue (baseline before the 2x hike), customer-concentration disclosure (the three bureaus as distributors).
3. **Freddie Mac & Fannie Mae single-family MBS disclosure files (capitalmarkets.freddiemac.com; Fannie DUS/PoolTalk equivalents)** — pull the VS4 special-feature-code fields monthly. *This is the single highest-value tracking series: actual VS4 delivery share.* Look for: count and UPB of VS4-flagged pools since May 2026.
4. **Fannie Mae "July 2026 Enterprise Credit Score Models and Credit Reports Initiative" fact sheet (singlefamily.fanniemae.com/media/34286)** — the approved-lender list criteria, rollout phases, and any stated timeline to "broad availability" and 10T adoption.
5. **FQ3 FY26 earnings release + call transcript (Jul 29, 2026)** — look for: mortgage score volume growth ex-price, "no volume loss to Vantage" reaffirmation or hedging, direct-license reseller count (needs to reach 5/5), funded-fee model uptake, CY27 pricing hints.
6. **FICO Mortgage Direct License Program contract summary (ficoscore.com/mortgagedirectlicense)** — verify whether the $65 (10T) / $33 (Classic) funded-loan fee is per borrower per score or per loan — this determines bi-merge sensitivity of the new model.
7. **MBA letter to FHFA (Dec 12, 2025) + CHLA pricing letter + the Senate inquiry documents (via PYMNTS 2/26 sourcing)** — gauge how concrete the price-rollback demands are and whether legislation is drafted or rhetorical.
8. **S&P structured-finance commentary on VantageScore 4.0 mapping (via asreport.americanbanker.com)** — read the actual criteria note: if rating agencies require FICO-mapped analysis for VS4 collateral, the switching cost is quantifiable and durable; if they publish native VS4 criteria, friction is decaying.
9. **FHFA VantageScore 4.0 Implementation FAQ (fhfa.gov/document/vantagescore-4.0-implementation-faq)** — check for any language reserving authority over score *pricing* (vs. score *choice*) — the difference between the WATCH and PASS worlds.
10. **FICO proxy (DEF 14A) and Form 4 flow** — comp incentives (is management paid on Scores revenue growth — i.e., incented to keep raising price into political fire?) and whether any insider buys appear below $1,000 (they bought none in the April panic personally; the company did).

