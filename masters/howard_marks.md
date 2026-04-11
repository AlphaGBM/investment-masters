# Howard Marks -- Oaktree Capital Management

## One-Line Summary
Understand where we are in the cycle, practice second-level thinking, and buy when others are fearful -- especially in credit.

## Core Methodology

### Investment Philosophy
- **Second-level thinking**: First-level = "It's a good company, buy." Second-level = "Everyone thinks it's good, so it's overpriced -- don't buy." Successful investing requires thinking differently AND better than consensus
- **Cycle awareness**: Markets are a pendulum swinging between greed and fear. Your job is to know where the pendulum is
- **Risk is not volatility**: Risk is the probability of permanent capital loss. Low prices = low risk (not high risk as CAPM suggests)
- **The role of luck**: Acknowledge that outcomes involve skill AND luck. Don't confuse a lucky outcome with a good decision

### Position Sizing
- **Aggressiveness varies with cycle position**: At cycle bottoms, be aggressive. At cycle tops, be defensive
- Primarily a credit investor: distressed debt, high yield, convertibles
- Portfolio construction focused on downside protection -- "If we avoid the losers, the winners take care of themselves"

### Risk Control / Exit
- **Asymmetric risk/reward**: Only invest when upside significantly exceeds downside
- **"Move forward, but with caution"**: His most common advice -- rarely all-in or all-out
- Key question: "Is the market pricing in too much optimism or too much pessimism?"
- Exit when: assets move from undervalued to fairly valued (don't wait for overvaluation)

## Key Frameworks

### The Pendulum
```
Euphoria  <------>  Depression
   |                    |
   v                    v
 Sell               Buy aggressively

The market spends most of its time moving TOWARD extremes,
not at the midpoint. The midpoint is a point of transition,
not a point of rest.
```

### Cycle Position Indicators
| Indicator | Bottom Signal | Top Signal |
|-----------|--------------|------------|
| Credit spreads | Wide (>600bps HY) | Tight (<300bps HY) |
| Investor sentiment | "No one will ever buy stocks again" | "This time is different" |
| Risk premiums | High -- overpaying for safety | Low -- ignoring risk |
| IPO/SPAC activity | Dead | Booming |
| Leverage | Deleveraging | Easy money, covenant-lite |
| VIX | Elevated (>30) | Suppressed (<15 for extended period) |

## Recent Views
- Oaktree memos (free on oaktree.com) provide real-time cycle commentary
- Recent theme: "Sea change" in interest rates -- the 40-year bond bull market is over. Implications for all asset valuations.

## Lessons for Your Strategy
- **Build a cycle indicator**: Combine VIX, credit spreads, sentiment, and leverage data to estimate cycle position
- **Adjust aggressiveness**: Portfolio beta should vary with cycle -- more defensive at tops, more aggressive at bottoms
- **Don't try to pick the exact bottom/top**: "You can't predict. You can prepare."
- **Margin of safety scales with uncertainty**: Require bigger discounts in uncertain environments

## AlphaGBM Systematic Equivalent
- TROS risk control: Maps Marks' cycle framework into a quantified VIX state machine
- Market sentiment dashboard: VIX percentile, put/call ratio, fear & greed index as cycle indicators
- Risk score adjustment: Higher risk scores (more cautious) when cycle indicators point to late-stage

## Sources
- *The Most Important Thing* (Howard Marks, 2011)
- *Mastering the Market Cycle* (Howard Marks, 2018)
- Oaktree memos (1990-present): [oaktreecapital.com/insights](https://www.oaktreecapital.com/insights)
- Interviews and conference presentations
