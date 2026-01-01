# Systematic Intraday Futures Strategy

## Executive Summary
A systematic trading framework designed for US Index Futures (NASDAQ, Dow Jones, S&P 500). The strategy operates on a strict intraday basis (Tuesday - Friday, NY Session) to minimize overnight risk and capitalize on specific volatility windows.

![Equity Curve](Equity%20Curve%20with%20compounding.png)

## Performance Highlights (Historical Simulation)
*Data Period: Jan 5, 2022 - Dec 19, 2024*

| Metric | Result | Note |
| :--- | :--- | :--- |
| **Total Return** | **1,100%** | Compounded |
| **Sharpe Ratio** | **6.94** | High risk-adjusted return |
| **Win Rate** | **46.4%** | Focus on high R:R ratio (Avg 3.38%) |
| **Max Drawdown** | **-8%** | Strict risk management protocols |

## Core Methodology
The strategy utilizes a 5-pillar approach to filter market noise and identify high-probability setups:

1.  **Regime Detection:** Filters out market conditions with historically low probabilities.
2.  **Event Sensitivity:** Avoids execution during high-impact news events/economic calendar releases.
3.  **Holiday Effects:** Adjusts engagement based on lower liquidity/volatility around bank holidays.
4.  **Strict Selection:** "Quality over Quantity" approach—days with no clear signal result in no trade.
5.  **Adaptive Risk:** Dynamic position sizing based on market structure to protect capital.

## Data & Validation
* **Interactive Data:** The repository includes the full HTML backtest report (`Equity Curve with compounding.html`) for detailed trade-by-trade analysis.
* **Technology Stack:** Proprietary Algorithm / Python Validation (In Progress).
