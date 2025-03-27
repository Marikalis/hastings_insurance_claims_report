# Insurance Claims Analysis for Head-On Collisions

## 1. Introduction

This analysis focuses on historical insurance claims data for head-on collisions to provide actionable insights. The primary goal is to understand which factors most significantly influence claim costs and to provide recommendations to improve pricing and reserving decisions. The dataset includes various factors such as third-party involvement, weather conditions, and the notifier of the claim.

## 2. Key Findings

### A. Distribution of Claim Costs (Incurred)

- The incurred claims are heavily right-skewed.
- Most claims fall in a lower cost range, but a few significantly larger claims inflate the average.
- These high-value claims pose a significant financial risk.

### B. Notifier Impact on Claims

- Claims reported by third parties (CNF) have significantly higher average incurred costs compared to those reported by policyholders (PH).
- Third-party claims often involve legal disputes, delays, or higher liability exposure.

### C. Impact of Notification Period

- No clear linear relationship was observed between notification period and incurred claim costs.
- Some of the most expensive claims have longer notification periods.
- Encouraging quicker notifications may help prevent cost escalation.

### D. Weather Impact on Claims

- Accidents in "wet" weather conditions tend to have higher incurred costs.
- Wet weather increases the severity of accidents, leading to higher costs.

### E. Third-Party Involvement by Region

- Regions such as Yorkshire and Wales show the highest third-party involvement.
- These regions also incur the highest average claim costs.
- Region-specific adjustments in pricing and risk mitigation strategies are recommended.

## 3. Methodology

### A. Data Preprocessing

- Cleaned the dataset to handle missing data.
- Identified key features such as third-party involvement, weather conditions, and incurred costs.

### B. Exploratory Data Analysis (EDA)

- Conducted EDA to identify key patterns and relationships in the data.
- Used visualizations like bar charts and scatter plots to explore the impact of various factors on incurred claim costs.

### C. Key Factor Analysis

- Focused analysis on:
  - Third-party involvement
  - Notifier type
  - Notification period
  - Weather conditions
  - Regional factors

## 4. Recommendations

### A. Region-Specific Pricing and Risk Management

- Adjust pricing models for regions with high third-party involvement and incurred costs (e.g., Yorkshire and Wales).

### B. Improve FNOL Processes

- Implement measures to encourage faster reporting of claims.
- Prioritize improvements for third-party claim notifications to reduce overall costs.

### C. Weather-Based Risk Adjustments

- Incorporate weather conditions into pricing models.
- Consider seasonal rate adjustments to mitigate losses during high-risk weather periods.

### D. Monitor High-Cost Outliers

- Investigate high-cost outlier claims.
- Identify additional risk factors and improve early detection to prevent cost escalation.

### E. Stakeholder Engagement

- Collaborate with claims, pricing, and management teams.
- Share insights and optimize processes with a focus on region-specific risks and FNOL (First Notification of Loss) improvements.

## 5. Conclusion

This analysis provides actionable insights into head-on collision claims. By addressing third-party involvement, weather conditions, and regional risk factors, the company can enhance pricing and reserving strategies. Monitoring outliers and refining claims handling processes will further reduce financial exposure.
