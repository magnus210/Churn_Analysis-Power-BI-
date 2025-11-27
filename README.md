# Customer Churn Analysis Dashboard

> An interactive Power BI dashboard analyzing customer churn patterns, payment behaviors, and revenue impact for a telecommunications company

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Analysis](https://img.shields.io/badge/Analysis-Customer%20Churn-blue)
![Status](https://img.shields.io/badge/Status-Complete-green)

## Dashboard Preview

![Dashboard](visuals/Dashboard%20visuals.png)

## Executive Summary

This dashboard analyzes **7,043 customers** to identify churn patterns and their impact on revenue. The analysis reveals critical insights about contract types, payment methods, and service preferences that drive customer retention.

### Key Metrics at a Glance

| Metric | Value | Insight |
|--------|-------|----------|
| **Total Customers** | 7,043 | Base for analysis |
| **Senior Citizens** | 16% | Minority segment |
| **Avg Monthly Charges** | $64.80 | Revenue per customer |
| **Lost Revenue** | $2.9M | Due to churn |
| **Gained Revenue** | $13.2M | From retained customers |

## Key Findings & Insights

### 1. Contract Type is the #1 Churn Predictor

| Contract Type | Churn Rate | Risk Level |
|---------------|------------|------------|
| Month-to-month | **43%** | 🔴 HIGH |
| One-year | 11% | 🟡 MEDIUM |
| Two-year | 3% | 🟢 LOW |

**💡 Insight:** Month-to-month customers are **14x more likely to churn** than two-year contract customers. This is the most significant factor in predicting customer departure.

**🎯 Recommendation:** Incentivize customers to move from month-to-month to annual contracts with discounts or added benefits.

---

### 2. Payment Method Correlates with Churn Risk

| Payment Method | % of Customers | Churn Risk |
|----------------|----------------|------------|
| Electronic Check | 33.58% | 🔴 Highest churn |
| Mailed Check | 22.89% | 🟡 Medium |
| Bank Transfer | 21.92% | 🟢 Low |
| Credit Card | 21.61% | 🟢 Low |

**💡 Insight:** Electronic check users (the largest segment at 33.58%) show the highest churn rates. This may indicate:
- Less committed customers choosing flexible payment
- Potential payment friction causing dissatisfaction
- Customers not wanting automatic recurring charges

**🎯 Recommendation:** Offer incentives to switch from electronic check to auto-pay methods (bank transfer/credit card).

---

### 3. Fiber Optic Users Need Attention

| Internet Service | % of Customers | Observation |
|------------------|----------------|-------------|
| Fiber Optic | 43.96% | Largest segment, higher churn |
| DSL | 34.37% | Moderate segment |
| No Internet | 21.67% | Phone-only customers |

**💡 Insight:** Despite being the premium service, fiber optic customers show elevated churn. Possible reasons:
- Higher monthly costs ($64.80 avg) causing price sensitivity
- Service quality expectations not being met
- Competition offering better fiber deals

**🎯 Recommendation:** Review fiber optic pricing strategy and service quality. Consider loyalty discounts for long-term fiber customers.

---

### 4. Gender is Not a Churn Factor

| Gender | % of Customers |
|--------|----------------|
| Male | 50.48% |
| Female | 49.52% |

**💡 Insight:** Near-equal gender distribution with no significant difference in churn behavior. Retention strategies should not be gender-specific.

---

### 5. Revenue Impact Analysis

```
📉 Lost Revenue:   $2.9M  (from churned customers)
📈 Gained Revenue: $13.2M (from retained customers)
📊 Net Position:   +$10.3M
```

**💡 Insight:** Despite significant churn, the business maintains positive revenue growth. However, the $2.9M loss represents recoverable revenue with better retention strategies.

**🎯 Potential Recovery:** Reducing month-to-month churn by just 10% could recover ~$300K annually.

## Dashboard Components

| Visual | Type | Purpose |
|--------|------|----------|
| Payment Method Distribution | Pie Chart | Shows customer payment preferences |
| Internet Service Distribution | Pie Chart | Displays service type breakdown |
| Churn Rate by Contract | Bar Chart | Highlights contract impact on churn |
| Lost vs Gained Revenue | Bar Chart | Financial impact visualization |
| Gender Split | Donut Chart | Demographic distribution |
| KPI Cards | Cards | Key metrics at a glance |

## Tech Stack

| Tool | Purpose |
|------|----------|
| **Power BI Desktop** | Dashboard development |
| **DAX** | Calculated measures & KPIs |
| **Power Query** | Data transformation |

## Project Structure

```
Churn_Analysis-Power-BI-/
├── data/                      # Source data files
├── visuals/
│   ├── Churn_Analysis.pbix    # Power BI file
│   └── Dashboard visuals.png  # Dashboard screenshot
└── README.md                  # Project documentation
```

## How to Use This Dashboard

1. **Download** the `.pbix` file from the `visuals` folder
2. **Open** in Power BI Desktop
3. **Interact** with filters to drill down by:
   - Contract type
   - Payment method
   - Internet service
   - Demographics
4. **Analyze** specific customer segments for targeted retention strategies

## Business Recommendations

### Immediate Actions
- [ ] Launch retention campaign for month-to-month customers
- [ ] Offer annual contract discounts (10-15% off)
- [ ] Incentivize auto-pay enrollment

### Medium-term Initiatives
- [ ] Review fiber optic pricing vs. competitors
- [ ] Implement early warning system for churn risk
- [ ] Create loyalty program for 2+ year customers

### Long-term Strategy
- [ ] Develop predictive churn model using ML
- [ ] A/B test retention offers
- [ ] Build customer lifetime value scoring

## Future Improvements

- [ ] Add predictive churn scoring using ML integration
- [ ] Include customer feedback/NPS correlation
- [ ] Add time-series analysis for churn trends
- [ ] Create customer segmentation (RFM analysis)
- [ ] Build automated alerts for at-risk customers

## Author

Created as part of a business intelligence portfolio project demonstrating Power BI skills in customer analytics and churn analysis.

---

*This dashboard helps stakeholders make data-driven decisions to reduce customer churn and maximize revenue retention.*
