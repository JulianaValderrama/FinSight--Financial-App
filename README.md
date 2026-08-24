# FinSight-Financial-App
**FinSight** is a financial analytics platform designed to help SMEs transform financial and operational data into actionable insights.

The platform combines financial dashboards, forecasting, benchmarking, risk monitoring, reporting, and AI-assisted analysis to provide a clearer view of business performance, liquidity, and financial health.

## Key Features

- **Financial Dashboard** — Monitor revenue, EBITDA, cash position, margins, and key financial KPIs.
- **Forecasting & Scenario Analysis** — Evaluate how changes in revenue growth, margins, and collection periods affect future performance.
- **Sensitivity Analysis** — Identify the variables with the greatest impact on cash generation and profitability.
- **Industry Benchmarking** — Compare company performance against relevant peer and sector benchmarks.
- **Risk & Alerts** — Identify potential financial risks such as liquidity pressure, overdue receivables, and margin deterioration.
- **AI Financial Assistant** — Generate contextual insights around cash flow, profitability, working capital, forecasts, and financial risks.
- **Data Quality & Sources** — Upload and manage financial information while assessing data readiness.
- **Reporting** — Generate financial summaries for internal decision-making and stakeholder communication.
- **Compliance & Access Management** — Monitor permissions, security, and platform access.

## Financial Analysis

FinSight translates financial data into decision-oriented insights across areas such as:

- Revenue growth
- EBITDA and operating profitability
- Cash balance and liquidity
- Accounts receivable
- Working capital
- Gross margin
- Cash conversion
- FX and operating assumptions
- Forecast scenarios
- Industry-relative performance

The objective is not only to display financial information, but to help users understand **what is changing, why it is changing, and which variables could have the greatest financial impact**.

## Forecasting & Scenario Analysis

The forecasting module allows users to modify operating assumptions and assess their impact on future:

- Revenue
- EBITDA
- Cash balance
- Profitability
- Break-even timing

Sensitivity analysis highlights key drivers such as **collection delays, gross margin, and revenue growth**, helping users understand which assumptions have the greatest impact on financial performance.

## FinSight AI

The integrated financial assistant provides contextual analysis across the platform and helps interpret questions related to:

- Cash flow and liquidity
- Revenue trends
- EBITDA
- Receivables and collections
- Working capital
- Financial risks
- Forecasts and scenarios
- Industry benchmarks
- Executive financial summaries

The goal is to make financial analysis more accessible while keeping the underlying financial metrics visible to the user.

## Tech Stack

- React
- Vite
- JavaScript
- Tailwind CSS
- Recharts
- React Query
- Base44 SDK
- Radix UI

Additional libraries are used for PDF generation, forms, data visualization, and interface components.

## Project Structure

```text
src/
├── components/
│   ├── dashboard/
│   ├── forecasting/
│   ├── benchmarks/
│   ├── compliance/
│   ├── datasources/
│   └── onboarding/
├── pages/
│   ├── Dashboard.jsx
│   ├── Forecasting.jsx
│   ├── Benchmarks.jsx
│   ├── Alerts.jsx
│   ├── Reports.jsx
│   ├── DataQuality.jsx
│   ├── DataSources.jsx
│   └── Compliance.jsx
├── api/
├── hooks/
└── lib/
