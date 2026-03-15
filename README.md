# Credit Card Risk Analysis Dashboard
### Built with Power BI | UCI Credit Card Dataset

---

## 📊 Project Overview

This dashboard analyses credit card customer data to identify delinquency 
risk issues and trends. The goal is to help risk teams take **proactive action 
before risk materialises** — rather than reacting after defaults occur.

---

## 🎯 Key Metrics

| Metric | Description |
|---|---|
| **Probability of Default** | Primary metric used to anticipate which customers are likely to default before it happens |
| **Default Rate** | Percentage of customers who fail to repay their credit card balance |
| **Delinquency Rate** | Percentage of loans past due date but not yet defaulted — an early warning signal for Default Rate |

---

## 📈 Dashboard Pages

### 1. Summary Page
High-level overview of portfolio performance including key metrics and 
overall risk exposure.

![Summary Page](Overview.jpg)

### 2. Delinquency Risk Analysis
Deep-dive into risk trends and indicators across the portfolio.

![Delinquency Risk Analysis](Credit_Risk_Analysis.jpg)

#### Key Insights:
- 📈 **Delinquency rate grew from 4.89% to 11.30%** between Apr–Sep 2005, 
  signalling an accelerating risk trend
- 💳 **Low credit limit customers carry the highest default risk** — 
  the lower the credit limit tier, the higher the delinquency rate
- 💸 **High spenders are 2x less likely to default** — low spending 
  customers (< 10K) show the highest delinquency rate at 15.08%
- 📊 **Very high utilisation customers (>75%) carry the most risk** 
  at 13.51% delinquency rate, indicating financial stress

---

## 🔍 Risk Indicators Analysed

- **Spending Behaviour** — Does a customer's monthly spend impact their 
  likelihood of default?
- **Credit Limit Tiers** — Do customers with lower credit limits default more?
- **Credit Utilisation Buckets** — Are customers who maximise their credit 
  limit at higher risk?

---

## 📁 Repository Structure
```
📁 credit-card-risk-analysis/
├── 📄 README.md
├── 📄 Credit_Card_Risk_Analysis.pdf
├── 📁 screenshots/
│   ├── summary_page.png
│   └── delinquency_dashboard.png
```

---

## 📄 Full Report

👉 [View Full PDF Report](Credit_Card_Risk_Analysis.pdf)

---

## 🛠️ Tools Used

- **Power BI Desktop** — Dashboard design and visualisation
- **DAX** — Custom measures and calculated columns
- **Power Query** — Data transformation and bucketing
- **Dataset** — [UCI Machine Learning Repository — Default of Credit Card Clients]
  (https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients)


