# Modeling Bitcoin Portfolio Risk & Hedging Effectiveness using Regime-Aware DCC-MIDAS-X Models

## 1. Project Name

* Bachelor Graduation Thesis - June 2026 - Foreign Trade University HCM (FTU2)

* Evaluation Score: Excellent

## 2. Domain

* Quantitative Finance
* Financial Risk Management
* Programming, Software Engineer
* Portfolio Hedging

## 3. Served Stakeholder

Personal Bachelor Graduation Thesis Project

Academic Supervisor: Lê Trung Thành, PhD

## 4. Timeline

Mar – Jun 2026

## 5. Scope of Work

* Model Bitcoin volatility and dynamic correlations with: MSCI World, S&P GSCI, PIMCO Investment Grade Corporate Bond Index
* Examine the effect of Global Economic Policy Uncertainty (GEPU).
* Develop GARCH-MIDAS-X and DCC-MIDAS-X models with structural breaks.
* Construct time-varying Optimal Hedge Ratios (OHR) for dynamic portfolio hedging and effective risk management.
* Evaluate hedging effectiveness through in-sample, out-of-sample and transaction-cost tests.

## 6. Process and Approach

Input: Daily asset prices and monthly GEPU data
Sample: Oct 2016 – Dec 2025

* Data Preparation: Process financial returns and GEPU data.
* Structural Breaks: Apply Bai–Perron test to identify regime changes.
* Volatility Modelling: Estimate short- and long-run volatility using GARCH-MIDAS-X.
* Correlation Modelling: Estimate dynamic Bitcoin–asset correlations using DCC-MIDAS-X.
* Dynamic Hedging: Generate time-varying hedge ratios and hedged portfolios.
* Model Evaluation: Compare models using AIC, BIC, likelihood-ratio, Diebold–Mariano and Clark–West tests.
* Robustness: Conduct rolling out-of-sample tests, alternative train-test splits and transaction-cost analysis.

## 7. Outcome

* Identified three GEPU structural breaks: May 2019, Jan 2021 and Jul 2024.
* Bitcoin's relationship with traditional assets is asset-specific and regime-dependent.
* Structural-break models consistently improve model fit.
* Full DCC-MIDAS-X + Structural Break model achieves the highest hedging effectiveness:

  * BTC–MSCI: 17.05%
  * BTC–GSCI: 2.18%
  * BTC–PIMCO: 3.03%
* Forecasting improvements are statistically significant for BTC–MSCI and BTC–GSCI.
* Results remain robust after transaction costs of up to 50 bps.
* Bitcoin is better viewed as a conditional hedge/diversifier rather than a universal hedge.

## 8. My Role

**Project Owner / Engineer / Quantitative Researcher**

* Conducted 100% of project tasks independently.
* Responsible for research design, data processing, R programming, econometric modelling, statistical testing, hedging analysis and academic writing.

## 9. Lessons Learned

* Advanced GARCH, MIDAS and DCC modelling
* Quasi-Maximum Likelihood estimation
* Numerical optimization in R
* Structural-break analysis
* Statistical inference and forecast testing
* Dynamic portfolio hedging
* Out-of-sample backtesting and robustness testing

## Prerequisites

* R 4.5.x
* Statistics & Probability
* Financial Econometrics
* Time-Series Analysis
* Portfolio Theory
* Linear Algebra
