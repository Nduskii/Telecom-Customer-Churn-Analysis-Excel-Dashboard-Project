# Telecom Customer Churn Analysis – Technical & Analytical Details

## Dataset Overview 
- Customer demographics: Age, gender, partner/dependent status  
- Services: Internet type, tech support, online security, device protection  
- Contract & Billing: Contract type, payment method, monthly charges  
- Target: Customer churn (Yes/No)


## Analytical Approach  
1. **Data Cleaning & Preparation:** Formatting, filtering, handling missing values  
2. **Segmentation Analysis:** Pivot tables to examine churn by demographics, service, and contract  
3. **Metric Calculations:** COUNTIFS and AVERAGEIFS to quantify churn percentages per segment  
4. **Interactive Dashboards:** Designed for non-technical stakeholders to explore patterns


## Dashboards

**Overview Dashboard**
- Total churn: 26%  
- 47% of churned customers left after >1 year  
- Higher average monthly charges linked to churn

**Demographics Dashboard**
- Senior citizens had higher churn rates  
- Customers without dependents or partners had higher churn  
- Gender impact: negligible

**Services Dashboard**
- Internet service:  
  - Fiber optic users: 69% churn  
  - DSL users: lower churn  
- Tech & Security:  
  - 73% of churned customers had no tech support  
  - 76% lacked online security  
  - 65% had no online backup  
  - 63% had unprotected devices  
- Contract type:  
  - Month-to-month: highest churn  
  - One-year & two-year: lower churn  
- Payment method:  
  - Electronic check: highest churn  
  - Automatic credit card: lowest churn

**Churn Factors Dashboard**
- Interactive slicers for filtering by internet type, partner, and dependent status  
- Highest risk segment: Fiber optic users lacking tech support and online security, on month-to-month contracts, paying via electronic check

---


## Suggestions to Reduce Churn

Based on the analysis, the telecom company can implement the following strategies to improve customer retention:

**Retention Campaigns:** Target high-risk segments with personalized offers  
**Product/Service Improvements:** Incentivize adoption of tech support and security services, **Improve Service Offerings for Fiber Optic Users**  
**Payment Optimization:** Encourage automated payments to reduce churn

Use dashboards to **monitor churn trends and effectiveness** of interventions


## Conclusion
This project provides valuable insights into customer churn factors, enabling targeted retention strategies. The interactive dashboards help visualize and analyze trends effectively.
