<div align="center">

# Investment Masters

**Distill investment wisdom from the world's best fund managers.**

*15 masters' methodologies + 13F tracking, built for AI agents and human investors*

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) [![Masters](https://img.shields.io/badge/masters-15-green.svg)](#the-15-masters) [![13F](https://img.shields.io/badge/13F-SEC%20EDGAR-orange.svg)](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&type=13F)

[Quick Start](#quick-start) · [The 15 Masters](#the-15-masters) · [5 Common Principles](#5-common-principles) · [AlphaGBM Skills](https://github.com/AlphaGBM/skills)

</div>

## What Is This?

The best "open-source code" in investing is the public record: shareholder letters, SEC filings, books, interviews, and memos. This repo distills **15 top fund managers' methodologies** into structured, actionable profiles that any AI agent or human can use.

This is not "AI roleplay as Buffett." This is **methodology extraction** -- understanding *why* they buy, *how* they manage risk, and *when* they exit.

### What Sets This Apart

| | AI Roleplay Tools | Generic Finance Bots | **Investment Masters** |
|--|-------------------|---------------------|----------------------|
| Source | LLM training data | News feeds | **Primary sources: letters, 13F, books, memos** |
| Depth | Surface-level quotes | Price alerts | **Full methodology: selection, sizing, risk, exit** |
| Verifiable | "Buffett would say..." | N/A | **Every claim has a source citation** |
| Actionable | Entertainment | Information | **Maps to systematic investment rules** |
| 13F Tracking | No | No | **Quarterly holdings with CIK links** |

## Quick Start

### For Claude Code

```bash
git clone https://github.com/AlphaGBM/investment-masters.git .claude/skills/investment-masters
```

### For Cursor

```bash
git clone https://github.com/AlphaGBM/investment-masters.git .cursor/skills/investment-masters
```

Then ask your AI:

> "Distill Buffett's investment methodology"
>
> "Compare Dalio and Marks on risk management"
>
> "What did Bridgewater buy last quarter?"
>
> "Write a research report on the 5 common principles"

## The 15 Masters

| # | Master | Style | Profile |
|---|--------|-------|---------|
| 1 | **[Bridgewater (Dalio)](masters/bridgewater.md)** | Risk parity / All-weather | Principles, All Weather white paper |
| 2 | **[Buffett](masters/buffett.md)** | Value / Moat | 60 years of shareholder letters |
| 3 | **[Renaissance (Simons)](masters/renaissance.md)** | Pure quant / Statistical arbitrage | The Man Who Solved the Market |
| 4 | **[AQR (Asness)](masters/aqr.md)** | Factor investing / Momentum | 200+ research papers |
| 5 | **[Tepper](masters/tepper.md)** | Contrarian / Extreme opportunity | 2009 crisis bottom-fishing |
| 6 | **[Soros](masters/soros.md)** | Macro / Reflexivity | The Alchemy of Finance |
| 7 | **[Ackman](masters/ackman.md)** | Concentrated / Event-driven | 2020 CDS hedge |
| 8 | **[Howard Marks](masters/howard_marks.md)** | Cycles / Second-level thinking | The Most Important Thing + memos |
| 9 | **[Hillhouse (Zhang Lei)](masters/hillhouse.md)** | Long-termism / China | Value |
| 10 | **[ARK (Wood)](masters/ark.md)** | Disruptive innovation | Big Ideas report |
| 11 | **[Duan Yongping](masters/duan_yongping.md)** | Value / 本分 / Circle of competence | Xueqiu essays, Buffett lunch |
| 12 | **[Peter Lynch](masters/lynch.md)** | GARP / Invest in what you know | *One Up on Wall Street* |
| 13 | **[Druckenmiller](masters/druckenmiller.md)** | Macro / Concentrated asymmetric bets | Quantum Fund, Duquesne |
| 14 | **[Liang Wenfeng (High-Flyer)](masters/liang_wenfeng.md)** | Quant / AI-driven | 幻方量化 + DeepSeek |
| 15 | **[Linda Raschke](masters/raschke.md)** | Short-term technical / Swing | *Street Smarts*, Market Wizards |

## 5 Common Principles

Despite radically different styles, all 15 converge on these:

1. **Systems Over Intuition** -- Dalio built All-weather. Simons built quant models. AQR built factor frameworks. The best investors don't rely on gut feeling.

2. **Risk Management Over Stock Picking** -- Dalio: "Diversification is the holy grail." Marks: "Risk management is not about avoiding risk, but understanding it."

3. **Clear Thesis + Willingness to Be Wrong** -- Ackman: every position has written exit criteria. Soros: exits immediately when wrong. Know why you own it.

4. **Cycle Awareness** -- Marks' pendulum. Dalio's quadrants. Tepper's panic buying. Markets swing between excess optimism and excess pessimism.

5. **Long-term > Short-term** -- Buffett: "My favorite holding period is forever." Exception: Renaissance profits from short-term statistical arbitrage.

## 13F Tracking

Quarterly institutional holdings from SEC EDGAR (free, public):

| Master | CIK | EDGAR Link |
|--------|-----|-----------|
| Bridgewater | 0001350694 | [13F filings](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001350694&type=13F&dateb=&owner=include&count=10) |
| Berkshire (Buffett) | 0001067983 | [13F filings](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001067983&type=13F&dateb=&owner=include&count=10) |
| Appaloosa (Tepper) | 0001656456 | [13F filings](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001656456&type=13F&dateb=&owner=include&count=10) |
| Pershing Square (Ackman) | 0001336528 | [13F filings](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001336528&type=13F&dateb=&owner=include&count=10) |
| Soros Fund | 0001029160 | [13F filings](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001029160&type=13F&dateb=&owner=include&count=10) |
| Hillhouse | 0001510057 | [13F filings](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001510057&type=13F&dateb=&owner=include&count=10) |
| ARK Invest | 0001803918 | [13F filings](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001803918&type=13F&dateb=&owner=include&count=10) |

*Renaissance Medallion and AQR's internal funds are proprietary and not in 13F.*

## Example Queries

| Query | What the AI Does |
|-------|-----------------|
| "Distill Buffett's methodology" | Outputs full profile: principles, sizing, risk control, latest 13F, takeaways |
| "Compare Dalio vs Marks on risk" | Side-by-side analysis of risk philosophies |
| "Ackman's latest 13F changes" | Pulls latest Pershing Square filing from EDGAR |
| "What's the Tepper signal?" | Explains the panic-buying framework with current market indicators |
| "Write a report on master principles" | Generates structured article from the 5 common principles |
| "How would Soros view today's market?" | Applies reflexivity framework to current conditions |

## Project Structure

```
investment-masters/
├── README.md           # This file
├── SKILL.md            # AI agent skill definition
├── LICENSE             # MIT
└── masters/            # Individual master profiles
    ├── ackman.md
    ├── aqr.md
    ├── ark.md
    ├── bridgewater.md
    ├── buffett.md
    ├── druckenmiller.md
    ├── duan_yongping.md
    ├── hillhouse.md
    ├── howard_marks.md
    ├── liang_wenfeng.md
    ├── lynch.md
    ├── raschke.md
    ├── renaissance.md
    ├── soros.md
    └── tepper.md
```

## Related

- **[AlphaGBM Skills](https://github.com/AlphaGBM/skills)** -- 26 AI skills for options intelligence with real market data
- **[AlphaGBM](https://alphagbm.com)** -- Full platform: stock analysis, options scoring, strategy builder

## Contributing

Want to add a master or improve a profile? PRs welcome:

- Add new master profiles following the template in SKILL.md
- Update 13F holdings after each quarterly filing
- Add notable quotes, interviews, or new publications
- Translations (currently EN + CN)

## License

MIT -- see [LICENSE](LICENSE).

---

<div align="center">

**Built by [AlphaGBM](https://alphagbm.com). Stand on the shoulders of giants.**

</div>
