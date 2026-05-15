# Retail Transaction Analysis: Diagnosing the Feb–Apr Revenue Decline

## Overview

This project analyzes retail transaction data from May 2023 to April 2024 to investigate the sharp revenue decline that occurred during February–April 2024. The analysis focuses on identifying whether the decline was caused by changes in product performance, customer purchasing behavior, transaction timing, regional contribution, or payment preferences.

The business maintained relatively stable monthly revenue around $2.0M–$2.1M for most of the observed period. However, revenue suddenly dropped in February 2024 and continued declining into April 2024, signaling a potential shift in customer behavior or external market conditions.

To identify the root cause, this project explores multiple business dimensions including:

- Monthly revenue performance and MoM growth
- Product category contribution
- Unit sales distribution
- Customer transaction timing
- Regional purchasing behavior
- Payment method performance

The analysis concludes that the revenue decline was not driven by product imbalance, payment method preference, or transaction activity changes. Instead, the findings strongly suggest that seasonality or external market factors may be the primary contributors.

---

# Problem Statement

Understanding retail transaction behavior to identify the potential drivers behind the February–April 2024 revenue decline.

Key business questions:

1. Did any product category underperform during the decline?
2. Were customers purchasing less frequently during certain hours?
3. Did regional purchasing behavior change significantly?
4. Did payment method preferences impact revenue generation?
5. Is the decline caused by internal operational patterns or external factors?

---

# Tools & Technologies

- Microsoft Excel — Data cleaning, reporting, and chart preparation
- SQL / PostgreSQL — Data exploration and business analysis
- Power BI — Dashboard visualization and storytelling

---

# Dataset Information

- Analysis Period: May 2023 – April 2024
- Dataset Type: Retail Transaction Dataset
- Scope of Analysis:
  - Revenue trends
  - Product performance
  - Transaction behavior
  - Regional contribution
  - Payment methods

---

# Analysis Breakdown

## 1. Monthly Revenue & MoM Growth Rate

Analyze monthly revenue performance and identify revenue trend changes across the 12-month period.

### Key Findings

- Revenue remained stable around $2.0M–$2.1M from May 2023 to January 2024.
- February 2024 recorded a significant decline of -7.02% MoM.
- April 2024 experienced the largest decline at -10.70% MoM.
- Average monthly growth across the entire period was -1.08%.
- January 2024 was the peak revenue month with $2.10M.

### Business Insight

The sudden decline after a long stable period indicates an abnormal pattern rather than a gradual slowdown. This suggests the need for deeper investigation into external market conditions, customer retention, or seasonal effects.

### Monthly Revenue Table

| Month    | Revenue | MoM Growth |
| -------- | ------- | ---------- |
| May 2023 | $2.07M  | -          |
| Jun 2023 | $2.04M  | -1.53%     |
| Jul 2023 | $2.10M  | 2.92%      |
| Aug 2023 | $2.09M  | -0.79%     |
| Sep 2023 | $2.03M  | -2.77%     |
| Oct 2023 | $2.02M  | -0.33%     |
| Nov 2023 | $2.03M  | 0.41%      |
| Dec 2023 | $2.10M  | 3.24%      |
| Jan 2024 | $2.10M  | 0.41%      |
| Feb 2024 | $1.96M  | -7.02%     |
| Mar 2024 | $2.08M  | 6.23%      |
| Apr 2024 | $1.86M  | -10.70%    |

---

# 2. Product Category Analysis

## Revenue Distribution by Product Category

### Key Findings

| Product Category | Revenue |
| ---------------- | ------- |
| Books            | $6.16M  |
| Clothing         | $6.11M  |
| Electronics      | $6.10M  |
| Home Decor       | $6.08M  |

### Business Insight

All product categories contributed almost equally to total revenue, with only a 1.2% gap between the highest and lowest category. This indicates that no individual product category significantly caused the February–April decline.

The balanced revenue distribution also suggests that the business portfolio is well diversified.

---

## Unit Sales Distribution

### Key Findings

| Product Category | Units Sold | Distribution |
| ---------------- | ---------- | ------------ |
| Books            | 124,164    | 25.15%       |
| Electronics      | 123,566    | 25.03%       |
| Clothing         | 123,253    | 24.97%       |
| Home Decor       | 122,673    | 24.85%       |

### Business Insight

Unit sales closely mirror revenue distribution across all categories. The difference between the highest and lowest category is only 1,491 units (1.22%).

This confirms that product demand remained stable throughout the analysis period and product performance was not the root cause of the revenue decline.

---

# 3. Transaction Time Analysis

## Customer Transaction Activity by Hour

### Key Findings

- Peak transaction hour: 7 PM with 4,221 transactions
- Midnight transactions remained high at 4,060+
- Lowest transaction hour still recorded nearly 4,000 transactions
- Difference between peak and lowest hour was only 275 transactions

### Business Insight

Customer activity remained consistently active throughout the day, indicating strong 24/7 purchasing behavior.

The absence of significant dead hours suggests:

- Customers shop across all time periods
- Operational readiness should remain active throughout the day
- Marketing campaigns should not focus only on peak hours
- Infrastructure scalability is important for maintaining customer experience

### Hourly Transaction Overview

| Hour  | Transactions |
| ----- | ------------ |
| 12 AM | 4,060        |
| 1 AM  | 4,192        |
| 7 PM  | 4,221        |
| 10 PM | 3,946        |

---

# 4. Regional Analysis

## Transaction Volume by Region

### Key Findings

Top performing regions:

| Region                | Transaction Volume |
| --------------------- | ------------------ |
| Armed Forces Europe   | 3,637              |
| Armed Forces Americas | 3,550              |
| Armed Forces Pacific  | 3,488              |

Regular regions averaged around 1,500+ transactions.

### Business Insight

Military-based regions significantly outperformed regular regions, generating nearly 2x higher transaction volume.

This suggests that Armed Forces customers represent a highly active and valuable customer segment driven by collective and recurring purchasing behavior.

---

## Net Revenue by Region

### Key Findings

| Region                | Revenue |
| --------------------- | ------- |
| Armed Forces Americas | $902K   |
| Armed Forces Europe   | $889K   |
| Armed Forces Pacific  | $870K   |

Regular regions generated approximately $385K–$395K.

### Business Insight

The Armed Forces segment not only generated higher transaction volume but also significantly higher revenue contribution.

This confirms that:

- High transaction activity translated directly into revenue
- Military-based customers are a critical revenue driver
- Regional segmentation plays a major role in overall business performance

---

# 5. Payment Method Analysis

## Transaction Volume by Payment Method

### Key Findings

| Payment Method | Transactions |
| -------------- | ------------ |
| PayPal         | 24,711       |
| Credit Card    | 24,658       |
| Cash           | 24,634       |
| Debit Card     | 24,498       |

### Business Insight

All payment methods performed almost equally with only a 0.86% gap between the highest and lowest method.

This indicates:

- Customers show no strong payment preference
- All payment channels are equally accessible
- Payment experience remained stable during the decline period

---

## Revenue Contribution by Payment Method

### Key Findings

| Payment Method | Revenue |
| -------------- | ------- |
| PayPal         | $6.14M  |
| Cash           | $6.12M  |
| Debit Card     | $6.11M  |
| Credit Card    | $6.10M  |

Average transaction value across all methods remained around $248–$249.

Median transaction value ranged between $198–$202.

### Business Insight

The nearly identical performance across all payment methods confirms that payment behavior was not a contributing factor to the February–April decline.

The balanced distribution suggests customers used payment channels interchangeably without strong preference.

---

# Summary of Key Findings

## Revenue

Revenue remained stable at approximately $2.0M–$2.1M for eight months before sharply declining in February and April 2024.

## Product Performance

All product categories contributed almost equally in both revenue and unit sales. Product performance was not the driver of the decline.

## Transaction Behavior

Customer transactions remained highly active throughout the day with no major inactivity periods detected.

## Regional Performance

Armed Forces regions dominated both transaction volume and revenue contribution, generating nearly 2x higher performance than regular regions.

## Payment Methods

All payment methods showed nearly identical transaction volume, revenue contribution, and transaction value distribution.

---

# Recommendations

## 1. Investigate Seasonal Patterns

The revenue decline cannot be explained by product, payment, or transaction behavior.

Future analysis should focus on:

- Seasonal purchasing patterns
- Economic conditions
- Competitor activity
- Multi-year trend comparison

---

## 2. Strengthen Armed Forces Customer Strategy

Since Armed Forces regions contribute significantly higher revenue:

- Create exclusive promotions for military-based customers
- Develop loyalty programs
- Offer targeted product bundles
- Increase retention efforts for this segment

---

## 3. Maintain 24/7 Operational Readiness

Because customer activity remains high throughout the day:

- Ensure platform scalability
- Maintain operational uptime
- Optimize staffing and support coverage
- Run marketing campaigns across multiple time periods

---

## 4. Maintain Payment Method Diversity

Since all payment methods perform equally:

- Continue supporting all payment channels
- Avoid over-investment into a single payment method
- Focus on seamless customer payment experience

---

## 5. Conduct Deeper Drill-Down Analysis

Additional investigation is recommended for:

- Customer retention and churn during Feb–Apr 2024
- Regional decline comparison
- External economic or seasonal events
- Competitor pricing and campaign activity

---

# Conclusion

This analysis successfully identified that the February–April 2024 revenue decline was not caused by internal transactional behavior, product imbalance, or payment method preference.

The findings strongly suggest that external or seasonal factors may have played a larger role in the decline.

The business currently demonstrates:

- Balanced product performance
- Stable customer purchasing behavior
- Strong payment channel adoption
- Highly valuable Armed Forces customer segments
- Consistent 24/7 customer activity

Future business strategy should prioritize deeper seasonal analysis, retention monitoring, and regional optimization to better anticipate future revenue fluctuations.

---

# Author

Retail Transaction Analysis Project

Data Analyst Portfolio Project by Faraj Hafidh

## Social Links

- LinkedIn: [www.linkedin.com/in/faraj-hafidh](http://www.linkedin.com/in/faraj-hafidh)
- Portfolio: [https://farajhafidh.vercel.app/](https://farajhafidh.vercel.app/)
- Instagram: [https://www.instagram.com/hahahafidh\_/](https://www.instagram.com/hahahafidh_/)
