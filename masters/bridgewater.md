# Ray Dalio -- Bridgewater Associates

## One-Line Summary
Diversify across uncorrelated return streams, balance risk not dollars, and build systems that work in any economic environment.

## Core Methodology

### Portfolio Construction
- **All-Weather**: Allocate by risk contribution, not dollar amount. Each economic regime (growth up/down x inflation up/down) gets balanced exposure
- **Risk parity**: Lever up low-risk assets (bonds) and de-lever high-risk assets (equities) to equalize risk contribution
- **Uncorrelated alpha**: Pure Alpha fund seeks returns from ~100 uncorrelated bets across global markets
- **Systematic**: Every investment decision has a documented logic that can be tested and debugged

### Position Sizing
- **Risk budget based**: Positions sized by volatility, not conviction
- **EWMA volatility**: Exponentially weighted moving average for dynamic risk adjustment
- Target portfolio volatility: ~10-12% annualized for All-Weather
- Leverage used to bring low-vol assets (bonds, TIPS) to target risk level

### Risk Control / Exit
- **"The Holy Grail of Investing"**: 15+ uncorrelated return streams reduce portfolio risk dramatically
- Drawdown limits per strategy
- Stress testing against historical crises (1929, 1971 Nixon shock, 2008, COVID)
- Correlation monitoring: if correlations spike, reduce exposure

## Latest Holdings (13F)
*CIK: 0001350694 -- updated quarterly via SEC EDGAR*

| Top Holdings | Approx. Weight | Notes |
|-------------|---------------|-------|
| SPY/IVV | ~15% | US equity exposure via ETFs |
| EEM/VWO | ~8% | Emerging markets |
| TLT/IEF | ~12% | Treasury bonds (risk parity) |
| GLD/IAU | ~6% | Gold allocation |
| PG, JNJ, KO | ~3% each | Defensive equity allocation |

*Check latest: [SEC EDGAR - Bridgewater 13F](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001350694&type=13F&dateb=&owner=include&count=10)*

## Recent Views
- "Cash is trash" (in low-rate environment) -- but reversed stance as rates rose in 2022-2023
- On the current cycle: Emphasizes "big cycle" framework -- debt, political, and international order cycles all converging

## Lessons for Your Strategy
- **Risk parity beats equal-weight**: Allocate by volatility contribution, not dollar amount
- **Dynamic rebalancing**: Use EWMA to adjust exposure as volatility changes
- **Regime awareness**: Different assets win in different economic regimes -- position for all four quadrants

## AlphaGBM Systematic Equivalent
- All-weather portfolio: Automated risk parity with EWMA volatility response
- VIX state machine: Maps to Dalio's economic quadrants for regime detection
- Portfolio rebalance: Dynamic, volatility-adjusted position sizing

## Sources
- *Principles* (Ray Dalio, 2017)
- *Principles for Dealing with the Changing World Order* (Ray Dalio, 2021)
- Bridgewater Daily Observations (for institutional clients)
- All Weather white paper: publicly available summary
- SEC 13F filings
