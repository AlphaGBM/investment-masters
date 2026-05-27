---
name: investment-masters
description: >
  Investment master methodology distillation. Extract core principles from 15 top
  fund managers (Buffett, Dalio, Simons, Soros, Marks, Lynch, Druckenmiller, etc.), track their 13F holdings,
  compare philosophies, and map insights to your own strategy. Use when: learning
  investment frameworks, analyzing a master's approach, checking institutional holdings,
  writing investment research, comparing risk management styles.
  Triggers on: "what would Buffett think", "Dalio's risk parity", "13F holdings
  Bridgewater", "compare Buffett vs Soros", "investment masters", "hedge fund
  strategy", "Ackman's thesis approach", "Howard Marks cycle"
globs:
  - "masters/*.md"
---

# Investment Masters

Distill investment philosophies from 15 top fund managers into actionable frameworks.

## What This Skill Does

| Capability | Description |
|-----------|-------------|
| **Distill Methodology** | Extract core investment principles from public letters, books, interviews, and 13F filings |
| **Track 13F Holdings** | Quarterly institutional holdings from SEC EDGAR (free, public data) |
| **Compare Masters** | Side-by-side comparison of philosophies, risk management, position sizing |
| **Map to Strategy** | Show how each master's principles translate to systematic, quantifiable rules |
| **Generate Content** | Output analysis as research reports, articles, or structured notes |

## The 15 Masters

| # | Master | Style | Key Source |
|---|--------|-------|-----------|
| 1 | **Bridgewater (Dalio)** | Risk parity / All-weather | *Principles* + All Weather white paper |
| 2 | **Buffett** | Value / Moat | 60 years of shareholder letters |
| 3 | **Renaissance (Simons)** | Pure quant / Statistical arbitrage | *The Man Who Solved the Market* |
| 4 | **AQR (Asness)** | Factor investing / Momentum | 200+ published research papers |
| 5 | **Tepper** | Contrarian / Extreme opportunity | 2009 financial crisis bottom-fishing |
| 6 | **Soros** | Macro / Reflexivity | *The Alchemy of Finance* |
| 7 | **Ackman** | Concentrated / Event-driven | 2020 CDS hedge, public presentations |
| 8 | **Howard Marks** | Cycles / Second-level thinking | *The Most Important Thing* + memos |
| 9 | **Hillhouse (Zhang Lei)** | Long-termism / China | *Value* |
| 10 | **ARK (Wood)** | Disruptive innovation | Big Ideas annual report |
| 11 | **Duan Yongping** | Value / 本分 / Circle of competence | Xueqiu essays, 2006 Buffett lunch |
| 12 | **Peter Lynch** | GARP / Invest in what you know | *One Up on Wall Street* |
| 13 | **Druckenmiller** | Macro / Concentrated asymmetric bets | Quantum Fund, Duquesne interviews |
| 14 | **Liang Wenfeng (High-Flyer)** | Quant / AI-driven | 幻方量化 + DeepSeek |
| 15 | **Linda Raschke** | Short-term technical / Swing | *Street Smarts*, Market Wizards |

## How to Use

### Distill a Single Master

```
Distill Buffett's investment methodology
```

The AI follows the master profile and outputs: core principles, position management, risk control, latest holdings, and strategic takeaways.

### Compare Masters

```
Compare Dalio and Buffett on risk management
```

```
How do Soros and Marks differ on market cycles?
```

### Track 13F Holdings

```
What did Bridgewater buy/sell last quarter?
```

13F data comes from [SEC EDGAR](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&type=13F) -- free, public, updated quarterly.

| Master | CIK | Filing Entity |
|--------|-----|--------------|
| Bridgewater | 0001350694 | BRIDGEWATER ASSOCIATES LP |
| Berkshire | 0001067983 | BERKSHIRE HATHAWAY INC |
| Appaloosa (Tepper) | 0001656456 | APPALOOSA MANAGEMENT LP |
| Pershing Square (Ackman) | 0001336528 | PERSHING SQUARE CAPITAL MGMT |
| Soros Fund | 0001029160 | SOROS FUND MANAGEMENT LLC |
| Hillhouse | 0001510057 | HILLHOUSE CAPITAL MGMT LTD |
| ARK Invest | 0001803918 | ARK INVESTMENT MANAGEMENT LLC |

*Note: Renaissance Medallion and AQR's internal funds are not in 13F (proprietary capital). AQR's registered funds file separately.*

### Generate Research

```
Write a research report on the 5 common principles across all 15 masters
```

```
Draft an article on how Marks' cycle theory applies to today's market
```

## 5 Common Principles

Despite radically different styles, all 15 masters converge on these:

### 1. Systems Over Intuition
Dalio built the All-weather system. Simons built quantitative models. AQR built factor frameworks. **The best investors don't rely on gut feeling -- they build repeatable systems.**

### 2. Risk Management Over Stock Picking
- Dalio: "Diversification is the holy grail of investing"
- Marks: "Risk management is not about avoiding risk, but understanding it"
- Tepper: Bets big in extremes, stays conservative otherwise
- **No one survives long-term without disciplined risk control.**

### 3. Clear Thesis + Willingness to Be Wrong
- Ackman: Every position has a clear thesis and exit criteria
- Buffett: "If you can't explain why you bought it simply, you shouldn't buy it"
- Soros: "Invest first, investigate after" -- but exits immediately when wrong
- **Know why you own it. Exit when the thesis breaks.**

### 4. Cycle Awareness
- Marks' pendulum theory
- Dalio's economic quadrants
- Tepper's panic buying
- **Markets perpetually swing between excess optimism and excess pessimism.**

### 5. Long-term > Short-term
- Buffett: "My favorite holding period is forever"
- Zhang Lei: "Long-termism isn't long-term holding, it's long-term value creation"
- Exception: Renaissance profits from short-term statistical arbitrage
- **Choose your time frame and stick to it.**

## Data Sources

| Source | Type | Access | Update Frequency |
|--------|------|--------|-----------------|
| SEC EDGAR 13F | Institutional holdings | Free, public | Quarterly (45 days after quarter end) |
| Shareholder letters | Philosophy, outlook | Free, public | Annual |
| Published books | Deep methodology | One-time | N/A |
| Conference talks / interviews | Current views | Free (YouTube, podcasts) | Ongoing |
| Oaktree memos (Marks) | Cycle analysis | Free on oaktree.com | ~Monthly |
| ARK Big Ideas | Innovation thesis | Free on ark-invest.com | Annual |

## Update Schedule

- **13F holdings**: Quarterly (Feb/May/Aug/Nov, ~45 days after quarter end)
- **Important letters/memos**: Event-driven, as published
- **New masters**: Can be added on request

## Related

- [AlphaGBM Skills](https://github.com/AlphaGBM/skills) -- 26 AI skills for options intelligence with real market data

---

*Built by [AlphaGBM](https://alphagbm.com) -- Investment intelligence informed by the world's best investors.*
