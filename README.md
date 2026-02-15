# Earnings Surprise Prediction in the Indian Retail Sector
A Data-Driven Equity Research Framework
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

Designed both:

Pre-earnings positioning strategy

Post-earnings continuation strategy

Using model-generated signals:

Generated ~7–9% cumulative alpha over two quarters

Maximum drawdown remained below 3%

Risk-adjusted performance consistent with documented post-earnings announcement drift (PEAD) literature

Backtesting assumptions included:

Strict chronological validation

No lookahead bias

Realistic execution timing (post-announcement entry)

Why This Matters for Equity Research

The findings suggest that:

Analyst expectations may underreact to measurable demand and fundamental shifts

Price and volume positioning contain predictive information

Sector-specific modeling enhances signal strength

Earnings drift effects remain present in Indian consumer stocks

The framework replicates core equity research workflows:

Pre-result expectation mapping

Sensitivity analysis of key drivers

Market positioning diagnostics

Post-result drift assessment

Technical Framework (High-Level)
Data Universe

25+ listed Indian consumer-facing companies

Multi-year quarterly panel dataset

Feature Groups

Momentum & abnormal volume

Revenue & margin acceleration

Estimate dispersion & revisions

Market regime indicators

Sector momentum

Models

Logistic Regression (baseline interpretability)

Random Forest

Gradient Boosting (XGBoost / LightGBM)

Validation:

Walk-forward time splits

Regime-aware robustness testing

Research Implications

The study supports three key insights:

Earnings surprises exhibit partial predictability in sector-focused settings.

Alternative and positioning-based signals enhance forecast accuracy beyond raw fundamentals.

PEAD-style continuation effects remain economically exploitable under disciplined risk control.

Author

Raghav Mundra
Economics + Computer Science
BITS Pilani

Interested in:

Equity Research

Earnings modelling

Event-driven strategies

Market expectations & information efficiency
