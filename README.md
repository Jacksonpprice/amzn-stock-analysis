# Equity Valuation Model: DCF & Exit Multiple Analysis

## Overview
This project is a comprehensive **equity valuation model** built from publicly available financial statements (10-K data). The model evaluates a company’s intrinsic and market-based value using two core valuation methodologies:

- **Discounted Cash Flow (DCF)**
- **Exit Multiple (P/E) Valuation**

The analysis is conducted under **Upside and Downside scenarios**, allowing for comparison across growth, margin, and valuation assumptions. Final outputs include **enterprise value, equity value, and implied share price**.


---

## Key Features

### 1. Scenario-Based Revenue Forecasting
- Explicit **year-by-year revenue projections (2025–2029)**
- Separate **Upside (11%)** and **Downside (4%)** growth assumptions
- Historical data used as the baseline for forward projections

### 2. Full Unlevered Free Cash Flow (FCF) Build
Unlevered FCF is constructed using:
- EBIT
- Taxes
- Depreciation & Amortization
- Capital Expenditures
- Changes in Net Working Capital

This ensures valuation is independent of capital structure.

---

### 3. Discounted Cash Flow (DCF) Valuation
- **WACC calculated using CAPM**
  - Risk-free rate
  - Beta
  - Market risk premium
  - Cost of debt and tax shield
- Terminal value calculated using the **Gordon Growth Model**
- Explicit discounting of:
  - Forecast-period FCFs
  - Terminal value
- Results converted from **Enterprise Value → Equity Value → Share Price**

---

### 4. Exit Multiple Valuation
- Terminal equity value derived using **P/E multiples**
  - Upside: 35×
  - Downside: 25×
- Exit value discounted back to present using **WACC**
- Provides a **market-based valuation comparison** to the DCF

---

### 5. Valuation Comparison & Outputs
A dedicated Outputs tab summarizes:
- DCF vs Exit Multiple valuations
- Upside vs Downside outcomes
- Implied valuation range
- Enterprise-to-equity value bridge
- Key assumptions snapshot

This allows for **clear comparison of intrinsic vs market-driven valuation approaches**.

---

## Model Structure

- **Assumptions Tab**
  - WACC inputs
  - Growth rates
  - Margin assumptions
  - Exit multiples

- **Revenue Projections**
  - Scenario-based growth modeling

- **DCF Model**
  - FCF build
  - Discounting
  - Terminal value

- **Exit Multiple Model**
  - P/E-based valuation
  - Discounted exit equity value

- **Outputs Tab**
  - Final valuation summary
  - Share price comparison





---

## Author
**Jackson Price**  
B.S. Economics — University of Texas at Austin  
Minors: Business, Computer Science  

