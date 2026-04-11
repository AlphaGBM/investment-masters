# Jim Simons -- Renaissance Technologies

## One-Line Summary
Use mathematical models and massive datasets to find statistical patterns in markets -- no human judgment, no macro views, pure signal extraction.

## Core Methodology

### Stock Selection / Timing
- **No fundamental analysis**: Zero interest in what a company does, its earnings, or management
- **Pattern recognition**: Find statistically significant, non-obvious patterns in price/volume/alternative data
- **Short holding periods**: Medallion fund average holding period is 1-2 days
- **Massive diversification**: Thousands of small bets simultaneously across global markets
- **Alternative data pioneer**: Used satellite imagery, weather data, trading flow data before it was mainstream

### Position Sizing
- **Model-driven**: Position sizes determined entirely by the model's signal strength and expected Sharpe
- **Risk budget per signal**: Each signal has a volatility allocation, not a dollar allocation
- **Leverage**: Medallion uses significant leverage (estimated 5-10x) because individual bets are small and diversified
- **Automatic rebalancing**: Continuous, algorithmic rebalancing -- no human intervention

### Risk Control / Exit
- **Stop-losses embedded in models**: If a pattern stops working, the model drops it automatically
- **Correlation monitoring**: Constantly monitors cross-strategy correlation; reduces exposure when correlations spike
- **Regime detection**: Models adapt to changing market conditions (trending vs mean-reverting)
- **Capacity constraint**: Medallion capped at ~$10B and closed to outside investors since 1993 -- returns decay with size

## Performance
- Medallion Fund: ~66% annual gross returns (1988-2018), ~39% net of fees
- Fees: 5% management + 44% performance -- investors still got ~39% net
- Worst year: -0.5% (relative -- never lost significant capital)
- Sharpe ratio estimated at 3-4+

## Why 13F Doesn't Help
Renaissance's publicly filed 13F shows the RIEF and RIDA funds (institutional money), NOT the Medallion fund. Medallion's actual positions are never disclosed and change too rapidly for quarterly snapshots to be useful.

## Lessons for Your Strategy
- **Quantitative discipline**: If you can't backtest it, don't trade it
- **Small edge x many bets > big edge x few bets**: Diversification of signals reduces risk dramatically
- **Data quality matters more than model complexity**: Garbage in = garbage out
- **Capacity kills alpha**: The best strategies stop working at scale -- don't over-allocate

## Sources
- *The Man Who Solved the Market* (Gregory Zuckerman, 2019)
- MIT and Stony Brook lectures by Simons
- Renaissance Technologies SEC filings (RIEF/RIDA only)
