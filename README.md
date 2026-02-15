# Earnings Surprise Prediction in the Indian Retail Sector
Project Summary

Built an end-to-end earnings surprise forecasting framework using multi-year panel data across 25+ Indian consumer-facing companies.

The framework integrates:

Analyst consensus estimates

Company fundamentals

Price and volume dynamics

Sector-level indicators

Market regime signals

The objective was to study whether pre-announcement information can systematically anticipate earnings beats and misses.

🔎 Key Results
1️⃣ Predictive Performance

Achieved ~83–86% classification accuracy

ROC-AUC of ~0.76–0.79

Performance consistent across:

Stable market conditions

Elevated volatility regimes

Models successfully captured directional EPS surprise with strong out-of-sample validation under rolling time splits.

2️⃣ Trading Strategy Backtest

Designed:

Pre-earnings positioning strategy

Post-earnings continuation strategy

Using model-generated signals:

Generated ~7–9% cumulative alpha over two quarters

Maximum drawdown remained below 3%

Risk-adjusted performance aligned with documented post-earnings announcement drift (PEAD) effects

Backtesting assumptions:

Strict chronological validation

No lookahead bias

Realistic execution timing

📊 Data & Feature Groups
Price & Positioning Signals

1M / 3M momentum

Pre-announcement drift

Volatility regime

Abnormal trading volume

Fundamental Indicators

Revenue growth acceleration

Margin expansion

Cash flow trends

Leverage dynamics

Estimate Signals

Consensus EPS

Revision momentum

Estimate dispersion

Sector & Regime Signals

Sector momentum

Market volatility regime indicators

🧠 Modeling Framework

Models evaluated:

Logistic Regression (baseline)

Random Forest

Gradient Boosting (XGBoost / LightGBM)

Validation approach:

Rolling walk-forward splits

Regime robustness testing

Out-of-sample evaluation

📈 Research Implications

Findings suggest:

Earnings surprises exhibit partial predictability in sector-focused settings

Positioning and demand proxies add incremental signal beyond fundamentals

PEAD-style continuation effects remain economically exploitable under disciplined risk control

👤 Author

Raghav Mundra
Economics + Computer Science
BITS Pilani
