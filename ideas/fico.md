# Fair Isaac Corporation (FICO) — Deep Dive
*Date: 2026-07 · Status at research date: WATCH*

> Historical research draft, July 2026. Prices, events and position-sizing examples refer to the dates in this note. Selected historical inputs were rechecked on October 1, 2026; other source claims and open verification items remain unverified. Later outcomes are not incorporated.

**Audit disposition (October 1, 2026):** WATCH retained as a research status. Historical financial inputs and after-SBC earnings arithmetic were corrected. The SOTP and automatic entry caps are withdrawn pending a segment-to-company earnings bridge, corporate costs, mortgage seasonality and actual adoption data; no current valuation refresh is implied.

---

## 1. Situation in three sentences

FICO is down ~47% from its Nov-2024 all-time high (~$2,382 close) to ~$1,251 (7/10/26 close) because the FHFA — after telegraphing it since October 2022 — began actual acceptance of VantageScore 4.0 at Fannie/Freddie on April 22, 2026, ending Classic FICO's ~30-year formal exclusivity in conforming mortgage underwriting; the stock printed its 52-week low of ~$870 that same day. Meanwhile the business itself is accelerating, not eroding: Q2 FY26 (March quarter) revenue grew 39% to $692M, Scores grew 60%, mortgage-origination score revenue grew 127% (on a 2x price increase to ~$10/score), guidance was raised, and management repurchased a record $605M of stock in the quarter. The research question is how quickly competing-score adoption could affect volumes, alongside political pressure on FICO’s price increases; the historical thesis assumes slow switching, but delivery-share evidence is incomplete and mortgage exposure remains an estimate. **Correction (September 2026 review; qualified October 1, 2026):** the mortgage revenue share is not reconciled; ~36–38% is one annualized non-mortgage scenario, not a consequence of the guide alone (see §5).

---

## 2. Who is selling and why (seller-identity analysis — the core of the edge)

**The price path indicates a de-rating; it does not identify sellers.** The historical quote series puts the stock near $2,382 in November 2024, $870 intraday in April 2026 and $1,250.90 on July 10 (exact closes/intraday extrema and corporate-action adjustments remain unverified). **Source/arithmetic correction (October 1, 2026, superseding the September EPS reconstruction):** FY24 diluted GAAP EPS was $20.45. A sum-of-reported-periods TTM approximation through March 2026 is $26.54 + $17.73 − $12.73 = $31.54. At the quoted prices that is ~116.5x at the peak versus ~39.7x in July, with ~54% EPS growth. Period EPS sums use different weighted share counts, so this is an approximation; the de-rating conclusion holds, but the draft's 80–90x peak and 45% EPS-growth pair is not supported. These calculations use the company releases linked in §9, while the historical prices still need an archived quote series.

**Possible seller cohorts (hypotheses; no fund-flow or transaction evidence ranks them):**

1. **Quality-growth/momentum funds that owned "the monopoly" at 60–90x.** For them, the FHFA announcement doesn't change 2026 EPS — it breaks the *narrative* that justified the multiple ("regulated toll road that can never be disturbed"). Once the story requires handicapping a hostile regulator, the position no longer fits the mandate. This could motivate selling, but their mandates and sales have not been verified; forced supply is not established.
2. **Headline-risk de-riskers.** FHFA Director Pulte has publicly called FICO a "monopoly who has ripped off Americans for decades" and complained about a "40% price increase [with no] legitimate basis"; a Senator opened an investigation into FICO's mortgage pricing (PYMNTS, 2026); CHLA published that FICO's tri-merge component rose ~1,500% in four years ($1.80 → $30). Institutional de-risking is plausible, but the April price decline does not establish who sold or whether they misunderstood implementation.
3. **Quant/momentum.** 200-day MA is $1,407 vs price $1,251; the historical downtrend could create trend-following supply; actual positioning and trading rules are unverified.
4. **The informed seller who may be partly right.** Some sellers correctly recognize that FY26 earnings embed a politically radioactive 2x price hike ($4.95 → ~$10/score) and that the peak-multiple era extrapolated a pricing runway that is now politically contested. This portion of the de-rating is rational, and we should not pretend otherwise.

**Why the panic looks overdone on the facts (the edge):** the April 22 announcement was a *limited rollout to approved sellers* — Freddie's own capital-markets notice (f498news.pdf, 4/22/26) says "a limited rollout with approved Sellers... working to ensure operational readiness before broad availability." As of the GSEs' July 6, 2026 update, there is still **no published data showing any material volume of VS4-scored loans actually delivered**, FHA has *not yet* implemented (it says "next few months"), and FICO 10T implementation "will follow at a later date." Management said on April 29: "We anticipate no loss of volume to Vantage in this fiscal year" — and raised guidance. The limited rollout is evidence of staged implementation, not proof that sellers misunderstood it; prices can reflect eventual competition before current volume loss appears.

---

## 3. Business quality & moat

**The Scores franchise is one of the best business models extant.** FICO writes an algorithm; the bureaus/resellers compute and distribute it; FICO collects a royalty on ~10 billion+ scores a year with essentially zero incremental cost. Company-level non-GAAP operating margin hit 65% in Q2 FY26; ROA ~37%, ROCE ~70% (stockanalysis.com). B2B Scores incremental margins are ~90%+ (estimate).

**Moat sources, ranked:**
1. **Coordination/switching costs across the securitization chain (the thesis's core hypothesis; evidence includes trade reporting).** A mortgage credit score is not a product one buyer chooses; it is a *language* spoken simultaneously by originators, LOS/POS software, mortgage insurers, servicers, rating agencies, GSE AUS engines, CRT investors, and MBS investors' prepay/credit models trained on 30 years of FICO-keyed data. Evidence of friction from the last 90 days: VS4 scores run ~10 points higher on average than Classic FICO with ~15% of loans differing by >50 points (per industry/HousingWire reporting), creating adverse-selection and prepay-model problems that BofA's agency-MBS research flagged publicly; S&P said it "could" rate VS4 collateral but via a *mapping back to FICO-based models*; lenders report they struggle to compare the two scores. "Lender choice" score-shopping is itself now cited as a looming risk *by investors* — which pressures the GSEs to keep the rollout slow and disclosed (VS4 loans carry special feature codes and, since Nov 2025, dedicated MBS disclosure fields).
2. **Two decades of head-to-head evidence outside mortgage.** VantageScore (owned by the three bureaus) has existed since 2006 with free/cheap pricing and has won limited *paid decisioning* share according to the incumbent's account: FICO's CEO puts VS revenue-relevant penetration at ~2%/"trivial" in cards and auto. VS's headline "42 billion scores used in 2025, +55%" is dominated by free consumer-education channels (Credit Karma et al.). Real but niche decisioning wins exist (Synchrony cards, SoFi, Toyota Motor Credit, Exeter auto ABS; ~$24B of 2025 ABS issuance referenced VS) — worth monitoring, not yet worth capitalizing.
3. **Brand as the unit of account.** "FICO" is the score consumers, regulators, and capital markets denominate in. Note myFICO B2C grew only 5% — the moat is B2B infrastructure, not consumer brand love.
4. **Counter-positioning moves now in flight.** FICO is (a) giving away FICO 10T free with Classic FICO, so the "modern score" slot need not default to VS4; (b) disintermediating the bureaus with the Mortgage Direct License Program (resellers compute scores directly; three of five major resellers signed as of April); (c) shifting to success-based pricing — 10T at $0.99/score + $65 funded-loan fee (revised April 2026 from $4.95 + $33) — which matches VS4's ~$0.99–$4.50 sticker prices at the application stage while monetizing closed loans. This may shift economics away from bureau markups, but the claim that markups explain most inflation needs a consistent cost decomposition and is not established here.

**Software segment — real and improving, not the crown jewel.** FY26 software revenue running ~$860M (est., Q1 $207.5M + Q2 $217M annualized; unverified for H2). Total software ARR $789M, +10% YoY; **platform ARR $349M, +49%** (mid-30s ex-migrations), platform NRR 136%, total NRR 109%. Decent vertical-SaaS economics inside a scores company; a legitimate second engine but only ~35% of revenue and much lower margin.

**Grade: business quality A+. Moat wide but with one gate — the moat protects *share*; it does not protect *price* from a regulator who owns the mandate.**

---

## 4. Normalized owner earnings & balance sheet (arithmetic shown; unverified inputs flagged)

**Reported base (all from company releases/transcripts unless noted):**

| Item | FY2025A | FY2026 guide (raised 4/28/26) |
|---|---|---|
| Revenue | $1,990.9M | $2.45B (+23%) |
| GAAP diluted EPS | $26.54 actual | $35.60 |
| Non-GAAP diluted EPS | $29.88 actual | $40.45 |
| FCF (CFO less capex) | FY25: $739.4M; TTM to 3/31/26: $866.8M | ~$950M–$1.0B (my estimate, unverified) |

Shares: ~23.2M (stockanalysis; a second source says 23.7M — minor discrepancy, use ~23.2–23.7M). Market cap ~$29.0B at $1,250.90.

**Mortgage concentration — the revenue actually at risk:**
- Q2 FY26 Scores revenue $475M, of which mortgage originations = 63% → **~$299M/quarter** (also = 72% of B2B). Mortgage grew +127% YoY.
- FY26 mortgage-scores revenue estimate: ~$1.0–1.1B of $2.45B → **~41–45% of total company revenue** (my estimate from quarterly disclosures; unverified). **Correction (September 2026 review; qualified October 1, 2026):** the implied non-mortgage seasonality needs reconciliation; the alternative ~36–38% mortgage share assumes a particular full-year non-mortgage run-rate (see §5), rather than following from the guide alone.
- At ~90% incremental margins, mortgage scores ≈ **55–60% of company operating profit** (estimate).
- Unit/price cross-check: Q2 FY25 mortgage revenue ≈ $132M ÷ $4.95 royalty ≈ ~27M scores; Q2 FY26 ≈ $299M ÷ ~$10 ≈ ~30M scores. Implies the +127% was ~2x price and ~+10% volume — i.e., **the "60% Scores growth" is a price event, not a demand event.** (Score-count arithmetic is mine and crude — prequal/soft pulls may be priced differently; unverified.)
- Pricing headroom context: FICO royalty ~$10 vs. tri-merge report retail of ~$47–$120+ per applicant and total credit-related costs per closed conventional loan reported near ~$540 in 2026 (MBA/CNBC/HousingWire; figures vary by source and include multiple pulls — treat as directionally right, unverified precisely). Against a ~$6,000–$12,000 all-in closing-cost stack, FICO's take remains small — the share of closing costs alone establishes neither economic willingness to pay nor political tolerance (Pulte quotes, Senate inquiry, CHLA's "1,500% in 4 years" letter).

**Owner-earnings correction (October 1, 2026):** FY26 non-GAAP NI guidance is **$946M**, directly reported; multiplying guided EPS by an unrelated current share count gave the draft's $955M. The guidance bridge is $825M GAAP NI + $185M SBC − $45M related tax adjustments − $19M excess tax benefit = $946M. Restoring the $140M after-tax SBC cost gives an **$806M earnings proxy** ($825M less the $19M excess tax benefit), not $900M–$1.0B owner earnings. Cash conversion, maintenance investment and working capital still need reconciliation. TTM FCF is $739.4M + $379.7M − $252.3M = **$866.8M**, but CFO adds back SBC; it cannot independently establish owner earnings without a dilution/cost adjustment. Do not both expense SBC and deduct the same awards again through a dilution charge.

Using the draft's **unverified** mortgage revenue of $1.0–1.1B, 90% incremental operating margin and 21% marginal tax rate consistently:
- A price rollback from $10 to $4.95, holding units/cost structure fixed, reduces revenue by 50.5% and after-tax earnings by ~$359–395M. The $806M proxy falls to **~$411–447M** before other changes.
- A 40% mortgage-volume increase at the current assumed price adds ~$284–313M after tax, lifting that proxy to **~$1.09–1.12B**.
- These are sensitivities, not a new base case. Mortgage revenue, price mix, incremental margin, volumes and tax effects remain assumptions; the valuation must be rebuilt before using these as owner earnings.

**Balance sheet (10-Q, 3/31/26):** total debt $3.64B (93% senior notes, w.a. 5.5%; issued $1.0B new notes during H1); cash + investments $272M; **net debt ~$3.37B ≈ 2.9x TTM EBITDA ($1.16B)**. Aggressive but serviceable given FCF; note they are levering up to buy back stock — $605M repurchased in Q2 (484k sh @ $1,251 avg, largest quarterly buyback in company history), plus $170M more in April (164k sh @ $1,040), against a $1.5B authorization (April 2026; supersedes June 2025's $1B — details unverified). Share count −3.0% YoY. The company repurchased stock during the decline; the ~20% price recovery from $1,040 is not a corporate trading profit or proof of intrinsic value. CEO Lansing's only 2025–26 Form 4 activity found was a small charitable-gift-linked sale at ~$1,733 (Nov 2025); no insider open-market buys found (checked openinsider-indexed sources).

---

## 5. Valuation: what the price implies, and base / bull / bear intrinsic-value range

**Current marks (7/10/26, $1,250.90):** market cap ~$29.0B and EV ~$32.4B; ~39.7x approximate trailing GAAP EPS; **35.1x FY26 GAAP guide and 30.9x non-GAAP guide**. **October 1, 2026 correction:** $29.0B equity / $866.8M TTM FCF ≈ **33.5x**, or ~29–30.5x on the unverified $950M–$1.0B FY26 FCF forecast. This FCF is after interest; dividing it into EV mismatches enterprise value with equity cash flow. The cited $49 NTM EPS/25.5x multiple is unverified: pro-rating the $40.45 FY26 and $46.38 FY27 estimates gives ~$44.90 (~27.9x), but quarterly seasonality could differ, so the September claim that NTM must lie between annual EPS estimates was too strong. EBIT/EV is ~3.9% on the estimated $1.26B FY26 EBIT. All of these remain multiples on earnings/FCF definitions requiring the SBC and reinvestment adjustments in §4.

**Terminal-value sensitivity:** $40.45 FY26 adjusted EPS growing 15% for five years, valued at 25x and discounted at 10%, gives ~$1,263/share; solving for $1,250.90 gives ~14.8% growth. This excludes interim distributions and assumes the growth/repurchase funding can be delivered; it is not a unique market-implied forecast or a full DCF. **October 1, 2026 correction:** a complete mortgage-loss case also cannot use the draft's $600M residual NI: even its unreconciled $710M mortgage earnings contribution leaves only $236M from the $946M adjusted-NI guide before considering stranded costs or tax changes. The after-SBC $806M proxy less $1.0–1.1B revenue × 90% × 79% leaves ~$24–95M under the stated mechanical assumptions. Both show concentration risk, but neither is a validated carve-out or terminal scenario.

**Historical sum-of-parts illustration (unreconciled; not a validated intrinsic-value range):**

| Piece | Basis | Bear | Base | Bull |
|---|---|---|---|---|
| Software | ~$860M rev; $789M ARR, platform 49% growth | $4.5B | $5.5B | $7.0B |
| Scores ex-mortgage | ~$540M rev, ~$340M after-tax operating contribution (estimate); 20-yr record vs VS | $7.0B | $8.5B | $10.0B |
| Mortgage scores | ~$1.05B rev, ~$710M after-tax operating contribution (estimate) | $3.0B (price rollback + slow share leak) | $10.5B (~15x: glacial share loss offset by volume recovery) | $17.0B (share holds, volumes normalize, funded-fee model expands $/loan) |
| Net debt | 3/31/26 | −$3.4B | −$3.4B | −$3.4B |
| **Equity value** | | **$11.1B ≈ $480/sh** | **$21.1B ≈ $910/sh** | **$30.6B ≈ $1,320/sh** |

**Correction (September 2026 review; qualified October 1, 2026):** ~$540M non-mortgage Scores revenue makes the components sum to $2.45B. The Q2 figures instead imply ~$176M for that quarter; $540M for the year requires the other three quarters to average ~$121M. This calls for a quarterly bridge but is not an arithmetic impossibility. A $660–700M non-mortgage annualization plus ~$860M software would leave ~$890–930M mortgage (~36–38% of the guide), conditional on that annualization. No split is verified. In addition, the table's earnings inputs must represent after-tax **operating** contributions if the pieces are enterprise values and net debt is subtracted; using net-income multiples and then subtracting debt would double count financing. Unallocated corporate costs, SBC, maintenance investment and separation costs are missing. The table and its quality-premium extensions therefore remain historical sensitivities, not support for entry prices.

**Quality-premium scenarios (historical, unsubstantiated):** the original note proposed $1,000–1,100 base and $1,550–1,700 bull ranges without a reconciled earnings bridge. **Arithmetic correction (September 2026 review):** 20/50/30 weighting at those range midpoints gives ~$1,109 using the table's $480 bear, or ~$1,137 using a separately assumed $620 bear. The claimed ~$1,190 requires near-upper-end inputs. At $870 the discount is only ~4% to the ~$910 table base or ~13–21% to the $1,000–1,100 premium base. **October 1, 2026 disposition:** these arithmetic averages neither repair missing corporate/SBC/reinvestment costs nor validate the scenario probabilities; the quality-premium valuation and entry-margin claims remain withdrawn.

---

## 6. Catalyst map (dated where possible)

- **Jul 24, 2026** — FHFA comment deadlines on pending proposals (per MBA Advocacy Update 7/6/26); watch for anything touching tri-merge/credit-report requirements.
- **Jul 29, 2026** — FQ3 FY26 earnings (consensus EPS ~$10.41): first full quarter under GSE VS4 acceptance. Watch: mortgage score volumes, any VS4 commentary, reseller sign-ups (last two of five), buyback pace.
- **"Next few months" (FHA's words, Jul 2026)** — FHA implementation of VS4 and FICO 10T; broadens the arena but also puts *FICO 10T* on equal modern footing.
- **H2 2026** — GSEs move from "limited rollout" to broad VS4 availability; FICO 10T historical data released Jul 1–6, 2026 → 10T GSE implementation "at a later date." Measure actual delivery share and operational milestones; elapsed time alone does not confirm the thesis.
- **~Nov–Dec 2026** — **FICO's CY2027 mortgage price announcement: the single most important catalyst.** Another aggressive hike invites regulatory/congressional retaliation; a flat or restructured (funded-fee) price signals détente and de-risks the multiple.
- **Ongoing, monthly** — GSE MBS disclosure data: VS4 loans carry special feature codes/dedicated disclosure fields (since Nov 2025). **VS4 share of GSE deliveries is directly measurable — this is the tripwire dataset.**
- **Undated** — Senate investigation into FICO mortgage pricing; FHFA "review of credit bureau policies"; any GSE-release-from-conservatorship action (changes FHFA's incentives unpredictably).

---

## 7. Pre-mortem: the three most likely ways this loses money, and tripwires/kill criteria

1. **Washington strikes the price lever (most likely, most damaging).** FHFA conditions GSE eligibility on score-price caps, forces a rollback of the 2026 2x hike, or a settlement/legislation caps royalties. The unreconciled mortgage revenue/profit share reprices down 30–50%; stock re-rates toward bear SOTP ($500–700). *Tripwires:* CY2027 price announcement content; any FHFA directive mentioning score pricing; Senate investigation escalating to hearings/subpoenas; FICO conceding price in the direct-license terms. *Kill criterion:* any mandated price rollback → thesis over, exit regardless of price. **Correction (September 2026 review):** the §5 table's bear SOTP is ~$480/sh ($11.1B ÷ ~23.2M shares), below the $500–700 quoted here; §5 does not derive that range, which roughly matches the bear case at the 25–28x quality-premium multiples (~$565–675/sh depending on method). The ~43% revenue share and alternative ~36–38% remain conditional estimates (see §5). The kill criterion is price-independent, so no trigger changes.
2. **Bi-merge / single-score revival.** July 2025's decision *kept* tri-merge, but MBA is actively lobbying to drop it and Pulte has teased "changes to credit report policies." Bi-merge cuts FICO mortgage units ~33% overnight (2 scores instead of 3); single-score −67%. The funded-loan-fee model partially hedges this (fee is per borrower per score under the Classic program — whether the $65 10T fee is per-loan or per-score is unverified; check contract terms). *Tripwires:* FHFA RFI outcomes after Jul 24; any GSE selling-guide amendment on report requirements. *Kill criterion:* formal bi-merge adoption without offsetting FICO price/fee restructuring → cut position at minimum.
3. **The margin becomes the market: real VS4 share compounds.** Aggregators with pricing incentives (UWM, Newrez already report eligibility/pricing wins on VS4's ~10-point-higher scores; Rocket is offering it) adopt VS4 as default for the marginal borrower; once ~20–30% of deliveries prove smoothly securitizable, the coordination moat dissolves bureau-by-bureau while bureaus price VS4 at $0.99/free (TransUnion $0.99; Equifax $4.50 w/ free bundle; Experian free — 2026 promos). Compounded by: mortgage volumes staying depressed (no rate relief), so the volume-recovery leg of the bull case never arrives. *Tripwires:* VS4-flagged share of GSE deliveries >2% by YE2026, >5% and accelerating by mid-2027; any top-5 lender making VS4 its *default* (not optional) score; GSE pricing grids offering better LLPAs on VS4 loans. *Kill criterion:* VS4 delivery share >10% with FICO mortgage volumes declining YoY → the glacial assumption is dead.

*Meta-risk:* leverage amplifies all three — 2.9x net debt/EBITDA means a profit shock compresses equity fast.

---

## 8. Verdict & the price/fact that changes it

**WATCH.** Primary disclosures support a staged GSE rollout and strong reported earnings at the historical research date. The size of the coordination moat and actual seller motivations are less firmly established: several adoption-friction claims rely on trade reporting, and small paid VantageScore wins already exist. **October 1, 2026 review:** FY25 actuals, the NI guide and SBC treatment are corrected in §4; the SOTP still lacks reconciled segment earnings and central costs. At $1,250.90, the historical multiple/growth sensitivities do not demonstrate a margin of safety. The former $870–1,050 entry levels and $1,150 fact-trigger cap are research alerts only until that valuation bridge is rebuilt; they are not automatic upgrades.

- **Price alert: ≤ ~$1,000–1,050** (about 25x FY26 non-GAAP guide) → reopen valuation, with no automatic PURSUE or sizing instruction. Even the unreconciled $1,000–1,100 quality-premium base offers only 0–10% upside at $1,000 and −5–5% at $1,050; the September correction already withdrew the claimed 20% cushion.
- **Fact alert (upgrade review):** a CY2027 pricing outcome without intervention and VS4-flagged GSE deliveries below 2% at YE2026 would reduce two risks, but do not by themselves justify the former $1,150 cap.
- **Fact alert (downgrade):** VS4 share >5% and accelerating pauses new entry (PASS). Existing-position exit criteria remain §7: mandated rollback; formal bi-merge without offsetting pricing; or VS4 share >10% together with falling FICO mortgage volumes. A lower multiple is not automatically safe, but no universal price-independent solvency claim follows from 2.9x leverage.

---

## 9. Verification checklist (exact documents to read next)

1. **FICO 10-Q for quarter ended 3/31/26 (filed ~May 2026, SEC EDGAR CIK 814547)** — confirm: mortgage-origination revenue disclosure, exact debt schedule/covenants, buyback detail, any new VS4/regulatory risk-factor language vs the 10-K.
2. **FICO FY2025 10-K (filed ~Nov 2025)** — FY25 actual revenue/EPS/FCF now reconciled to the release below; continue checking Scores B2B vs B2C split, mortgage % of FY25 revenue (baseline before the 2x hike), customer-concentration disclosure (the three bureaus as distributors).
3. **Freddie Mac & Fannie Mae single-family MBS disclosure files (capitalmarkets.freddiemac.com; Fannie single-family PoolTalk equivalents; DUS is multifamily)** — pull the VS4 special-feature-code fields monthly. *This is the single highest-value tracking series: actual VS4 delivery share.* Look for: count and UPB of VS4-flagged pools since May 2026.
4. **Fannie Mae "July 2026 Enterprise Credit Score Models and Credit Reports Initiative" fact sheet (singlefamily.fanniemae.com/media/34286)** — the approved-lender list criteria, rollout phases, and any stated timeline to "broad availability" and 10T adoption.
5. **FQ3 FY26 earnings release + call transcript (Jul 29, 2026)** — look for: mortgage score volume growth ex-price, "no volume loss to Vantage" reaffirmation or hedging, direct-license reseller count (needs to reach 5/5), funded-fee model uptake, CY27 pricing hints.
6. **FICO Mortgage Direct License Program contract summary (ficoscore.com/mortgagedirectlicense)** — verify whether the $65 (10T) / $33 (Classic) funded-loan fee is per borrower per score or per loan — this determines bi-merge sensitivity of the new model.
7. **MBA letter to FHFA (Dec 12, 2025) + CHLA pricing letter + the Senate inquiry documents (via PYMNTS 2/26 sourcing)** — gauge how concrete the price-rollback demands are and whether legislation is drafted or rhetorical.
8. **S&P structured-finance commentary on VantageScore 4.0 mapping (via asreport.americanbanker.com)** — read the actual criteria note: if rating agencies require FICO-mapped analysis for VS4 collateral, the switching cost is quantifiable and durable; if they publish native VS4 criteria, friction is decaying.
9. **FHFA VantageScore 4.0 Implementation FAQ (fhfa.gov/document/vantagescore-4.0-implementation-faq)** — check for any language reserving authority over score *pricing* (vs. score *choice*) — the difference between the WATCH and PASS worlds.
10. **FICO proxy (DEF 14A) and Form 4 flow** — comp incentives (is management paid on Scores revenue growth — i.e., incented to keep raising price into political fire?) and whether any insider buys appear below $1,000 (they bought none in the April panic personally; the company did).

### Primary financial sources checked October 1, 2026
- [FICO FY2025 earnings release, filed November 5, 2025](https://investors.fico.com/static-files/64719926-1a43-4ea9-a1fa-cd60c6559b1c): FY25 actual revenue, GAAP/adjusted EPS and FCF; FY24 EPS comparator.
- [FICO Q2 FY2026 release, April 28, 2026](https://fico.gcs-web.com/news-releases/news-release-details/fico-announces-earnings-1114-share-second-quarter-fiscal-2026): six-month EPS/FCF, updated NI guidance and SBC/tax reconciliation. Later FY26 releases are not incorporated into this July snapshot.
