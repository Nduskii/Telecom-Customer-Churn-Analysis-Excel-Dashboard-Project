**Telecom Customer Churn Analysis – Technical & Analytical Details**

**Dataset Overview**  
- Customer demographics: Age, gender, partner/dependent status  
- Services: Internet type, tech support, online security, device protection  
- Contract & Billing: Contract type, payment method, monthly charges  
- Target: Customer churn (Yes/No)  

**Analytical Approach**  
1. **Data Cleaning & Preparation:** Formatting, filtering, handling missing values  
2. **Segmentation Analysis:** Pivot tables to examine churn by demographics, service, and contract  
3. **Metric Calculations:** COUNTIFS and AVERAGEIFS to quantify churn percentages per segment  
4. **Interactive Dashboards:** Designed for non-technical stakeholders to explore patterns

**Dashboards**
**1. Overview Dashboard**
-Displays total churn percentage (26%), with most churn occurring before the one-year mark.
-Higher average monthly charges were linked to churn.
-47% of churned customers left after staying for more than a year.
**2. Demographics Dashboard**
-Senior citizens, customers without dependents, and customers without partners had higher churn rates.
-The churn rate for males and females was almost equal, making gender a non-factor.
**3. Services Dashboard**
-Customers with internet service churned more than those without.
-Among internet users, 69% of fiber optic users churned, while DSL users had lower churn.
-73% of churned customers had no tech support, 76% lacked online security, 65% had no online backup, and 63% had unprotected devices.
-Contract type and payment method were also major churn factors:
   Month-to-month contracts had the highest churn, while one-year and two-year contracts had lower churn rates.
  Electronic check payments had the highest churn rate, while customers using automatic credit card deductions churned the least.
**4. Churn Factors Dashboard**
-Interactive slicers for internet service type, partner status, and dependent status.
-Churn was highest among fiber optic users who lacked security services, tech support, or device protection.
-Overall, customers on month-to-month contracts and those paying via electronic checks had the highest churn rates, independent of internet type.


**Suggestions to Reduce Churn**
Based on the analysis, the telecom company can implement the following strategies to improve customer retention:

**Retention Campaigns:** Target high-risk segments with personalized offers  
**Product/Service Improvements:** Incentivize adoption of tech support and security services, **Improve Service Offerings for Fiber Optic Users**  
**Payment Optimization:** Encourage automated payments to reduce churn 
Use dashboards to **monitor churn trends and effectiveness** of interventions

**Tools & Techniques Used**
**Excel Features:** Pivot tables, slicers, graphs, and dashboards.
**Formulas:** COUNTIFS, AVERAGEIFS, and other functions for data calculations.
**Data Cleaning & Transformation:** Formatting, filtering, and calculations for key metrics.

**Conclusion**
This project provides valuable insights into customer churn factors, enabling targeted retention strategies. The interactive dashboards help visualize and analyze trends effectively.
