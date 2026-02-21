# IRA Portfolio — Full Diagnostic Scan
**Date:** February 20, 2026

---

## Portfolio Holdings

| Holding | Weight | Role |
|---|---|---|
| VTI | ~21% | US equity core |
| VXUS | ~15% | International equity |
| BNDW | ~16% | Global bonds |
| XLK | ~11% | Tech sector tilt |
| QUAL | ~11% | Quality factor |
| SCHD | ~10% | Dividend / income |
| XLV | ~8% | Healthcare defense |
| AVGO | ~4% | Conviction growth |
| VRT | ~3% | Infrastructure / AI |
| AMZN | ~2% | Conviction growth |

---

## 1. Component Breakdown

| Holding | Weight | Declared Role | Asset Class |
|---|---|---|---|
| VTI | ~21% | Total US equity market beta | Broad equity |
| BNDW | ~16% | Global bond diversifier | Fixed income |
| VXUS | ~15% | ex-US geographic diversification | International equity |
| XLK | ~11% | Technology sector tilt | Sector equity |
| QUAL | ~11% | Quality factor — high ROE, low leverage, earnings stability | Factor equity |
| SCHD | ~10% | Dividend income + quality screens | Factor equity |
| XLV | ~8% | Defensive healthcare, inelastic demand | Sector equity |
| AVGO | ~4% | Semiconductor + software infrastructure conviction | Single stock |
| VRT | ~3% | AI data center power/cooling infrastructure | Single stock |
| AMZN | ~2% | Cloud + e-commerce + AI platform conviction | Single stock |

**Structural architecture:** A multi-layer core-satellite with a fixed income sleeve. The addition of BNDW materially differentiates this IRA from a pure-equity portfolio — it introduces the only true non-equity diversifier in the portfolio. The equity layer is US-heavy with deliberate tilts toward technology, quality, income, and AI infrastructure.

**Underlying intent:** Balanced, factor-aware portfolio with a growth bias, defensive coverage through bonds and healthcare, and concentrated high-conviction individual names.

---

## 2. Redundancies, Overlaps, and Hidden Correlations

### The Large-Cap US Quality Triple-Overlap

VTI, QUAL, and SCHD all overweight profitable, large-cap US companies. They are not independent.

| Holding | What It Actually Holds |
|---|---|
| VTI | ~3,700 US stocks, ~75% weight in large-cap |
| QUAL | ~125 US large-cap stocks screened for ROE, leverage, earnings stability — a concentrated slice of VTI's top tier |
| SCHD | ~100 US stocks screened for dividend growth + quality metrics — another concentrated slice of VTI's profitable tier |

- VTI vs. QUAL correlation: ~0.93 — QUAL is not diversifying VTI; it is amplifying its quality/large-cap tilt.
- SCHD vs. QUAL correlation: ~0.72 — Both are quality-factor expressions with meaningful top-holdings overlap.

Effective large-cap US quality exposure:
  VTI (21%) + QUAL (11%) + SCHD (10%) = 42%

Nearly half the portfolio is large-cap US quality equity in three different wrappers.

### The Technology Double-Count

VTI allocates approximately 30% to technology internally:

| Layer | Tech Exposure |
|---|---|
| VTI (~30% tech × 21%) | ~6.3% |
| XLK (direct) | 11.0% |
| **Effective tech sector** | **~17–18%** |

VRT (+AI infra, ~0.82 tech beta at 3%) adds a further ~2.5% risk-equivalent.
Effective tech-adjacent exposure: ~19–20%

### AVGO — Quadruple Exposure

| Layer | AVGO Effective Weight |
|---|---|
| Direct holding | 4.0% |
| XLK (~5–6% of XLK × 11%) | ~0.6% |
| QUAL (AVGO is a top quality-screen name, ~2–3% of QUAL × 11%) | ~0.3% |
| VTI (~0.8% of VTI × 21%) | ~0.2% |
| **Effective AVGO exposure** | **~5.1%** |

### AMZN — Triple Exposure

| Layer | AMZN Effective Weight |
|---|---|
| Direct holding | 2.0% |
| VTI (~3.5% of VTI × 21%) | ~0.7% |
| QUAL (AMZN is a quality-screen inclusion) | ~0.2% |
| **Effective AMZN exposure** | **~2.9%** |

Note: AMZN is classified as Consumer Discretionary (XLY), not Technology (XLK), so XLK does not hold it.

### Correlation Matrix

| Pair | Correlation | Implication |
|---|---|---|
| VTI ↔ QUAL | ~0.93 | QUAL is a filtered subset of VTI — near-duplicate |
| VTI ↔ XLK | ~0.88 | Tech sector amplifies market beta |
| VTI ↔ SCHD | ~0.78 | Defensive tilt but high co-movement |
| QUAL ↔ SCHD | ~0.72 | Both quality-factor proxies |
| XLK ↔ VRT | ~0.82 | VRT is AI-infrastructure; moves with Nasdaq |
| VXUS ↔ VTI | ~0.78 | Global equity co-movement |
| **BNDW ↔ VTI** | **~-0.10 to +0.15** | **The portfolio's only genuine diversifier** |
| XLV ↔ VTI | ~0.62 | Lowest equity-to-equity correlation — real defense |

BNDW and XLV are the only two holdings that provide meaningful risk offset to the equity core.

---

## 3. Regime Exposure Evaluation

| Regime | Portfolio Response | Expected Range | Key Driver |
|---|---|---|---|
| **Goldilocks Growth** | Strong | +18–26% | All equity tilts fire; BNDW lags but doesn't drag |
| **Inflation Surge (CPI > 5%)** | Painful | -15–28% | Equities reprice lower; BNDW suffers simultaneously — double pain |
| **Deflation / Credit Crisis** | Moderate buffer | -10–20% | BNDW rallies (flight to quality); XLV resilient; equity core falls |
| **Recession with Rate Cuts** | Moderate | -8–15% | BNDW rallies strongly offsetting equity drag; SCHD + XLV buffer |
| **Liquidity Crisis (2008/2020)** | Partial buffer | -22–38% | BNDW provides offset not available in pure equity portfolios; still significant drawdown |

**Key improvement over a pure-equity portfolio:** BNDW creates a meaningful deflation/recession buffer that a pure-equity portfolio completely lacks.

**Critical remaining gap:** Inflation is the portfolio's Achilles heel. In a 2021–2022-style environment:
- Equities fall due to rate hikes
- BNDW falls simultaneously (bonds lose value as rates rise)
- Zero offset from real assets (no TIPS, gold, commodities, energy)

The portfolio has 0% in inflation-sensitive assets. This is the single largest unhedged macro risk.

---

## 4. Concentration Risks and Blind Spots

### Concentration Risks

**1. Large-cap US quality (~42% in VTI + QUAL + SCHD)**
Three vehicles holding variations of the same universe. In a US-specific shock — earnings recession, fiscal crisis, dollar event — all three decline together with minimal differentiation.

**2. Tech narrative (~19–20% effective)**
VTI + XLK + VRT bring substantial technology exposure. A tech multiple compression (rate spike, AI disappointment, regulatory action) affects nearly a fifth of the portfolio through two vectors: sector weight and single-stock names.

**3. Individual stock concentration (~9% in AVGO + VRT + AMZN)**
Three single names totaling 9% of the portfolio. Each carries idiosyncratic event risk (earnings miss, guidance cut, regulatory action, CEO transition). AVGO and VRT are both AI-cycle dependent — they are correlated single-stock risks, not independent convictions.

### Blind Spots

| Blind Spot | Severity | Comment |
|---|---|---|
| **Zero inflation hedge** | Critical | No TIPS, no gold, no commodities, no energy ETF. In stagflation, equities fall AND bonds fall simultaneously. |
| **QUAL adds no unique diversification vs. VTI** | Significant | At 0.93 correlation, QUAL is an expensive way to slightly tilt VTI toward quality. The allocation could be redeployed more efficiently. |
| **Emerging market within VXUS underweighted** | Moderate | VXUS is ~75% developed markets. Explicit EM exposure (India, Southeast Asia) would add genuine diversification beyond VXUS's DM tilt. |
| **No real asset exposure** | Moderate | REITs, infrastructure, or commodity producers would provide inflation pass-through and low equity correlation. |
| **Short-duration vs. long-duration bond ambiguity** | Moderate | BNDW holds a mix of short and long duration. In a rate-spike scenario, the long-duration component causes meaningful NAV loss. |

---

## 5. Top Three Fragilities

### Fragility #1 — Inflation Regime (Stagflation)
**Trigger:** CPI re-accelerates above 4–5%; Fed is forced to maintain or raise rates; fiscal deficit stays elevated; bond market reprices term premium

**Mechanism:**
- BNDW (16%) loses NAV as rates rise — the "safe" allocation becomes a drag
- VTI + XLK + QUAL reprice lower as discount rates rise
- Growth equities (AVGO, VRT, AMZN) take the worst multiple compression
- Zero real assets means no portfolio component benefits

**Estimated portfolio drawdown: -18% to -30%**
**Probability (next 24 months):** Low to moderate — base case is disinflation, but re-acceleration is the primary tail risk in 2026

---

### Fragility #2 — Tech/AI Multiple Compression
**Trigger:** Hyperscaler capex freeze, AI ROI disappointment, regulatory action on big tech, or a rate spike above 5.5%

**Mechanism:**
- XLK falls 25–40%
- AVGO, VRT decline 35–50%
- AMZN falls 20–30%
- VTI falls 15–20% (30% tech weight internally)
- QUAL falls 15–18% (tech names score high on quality metrics — they're included)

**Estimated portfolio drawdown: -20% to -32%**
**Probability (next 24 months):** Moderate — AI valuations are stretched; concentration of capex in three hyperscalers is a single-point-of-failure risk

---

### Fragility #3 — Factor Redundancy Destroying Expected Diversification
**Trigger:** This is a structural fragility, not an event. In a drawdown, VTI + QUAL + SCHD will all fall simultaneously because they hold the same underlying companies.

**Mechanism:**
- Investors sell large-cap US quality in a risk-off rotation
- VTI, QUAL, and SCHD all decline with correlation approaching 1.0 in stress
- The three positions that look like "diversification" provide no independent support
- The portfolio behaves as if the investor holds 42% VTI, not three separate quality vehicles

**Estimated excess drawdown vs. expected: -4% to -8% worse than the allocation sheet suggests**
**Probability:** Not an event — this is always true. The diversification benefit of QUAL vs. VTI is essentially zero in any meaningful stress scenario.

---

## Scan Summary Scorecard

| Dimension | Score | Notes |
|---|---|---|
| **Structural clarity** | B | Core-satellite visible; fixed income is the key differentiator |
| **Redundancy management** | C | VTI + QUAL + SCHD triple-overlap is the main flaw |
| **Regime coverage** | B- | BNDW covers deflation/recession; inflation gap is critical |
| **Inflation protection** | D | Zero real assets — the portfolio's most exposed blind spot |
| **Single-stock discipline** | C+ | 9% in 3 individual names; AVGO is already triple-held in ETFs |
| **Geographic diversification** | B+ | VXUS at 15% is the correct structural weight |
| **Factor design** | C+ | Quality tilt is valid; execution is redundant |
| **Liquidity / Crisis buffer** | B- | BNDW provides meaningful protection absent in pure-equity portfolios |

**Overall diagnostic grade: B-**

This is a more thoughtfully constructed portfolio than a typical retail allocation — BNDW is a genuine structural addition. The primary flaw is factor redundancy (VTI/QUAL/SCHD all doing the same job) and the complete absence of inflation protection. These are fixable with surgical changes, not a full rebuild.
