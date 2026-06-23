# PowerCo Customer Churn Analysis & Retention Strategy

### A Data-Driven Customer Retention Strategy for PowerCo

## Project Overview

Customer retention is a critical business challenge, as acquiring new customers is often more expensive than retaining existing ones. This project analyzes customer behavior, identifies key drivers of churn, evaluates the impact of pricing on customer decisions, and proposes data-driven retention strategies.

Using exploratory data analysis, feature engineering, statistical testing, and predictive modeling, the project aims to answer an important business question:

> **Which customers are most likely to churn, what factors influence their decisions, and how can the business reduce revenue loss through targeted retention efforts?**

---

## Business Problem

PowerCo, an energy provider, is experiencing customer churn and wants to understand the factors contributing to customer attrition.

The project focuses on:

* Understanding customer characteristics associated with churn.
* Investigating whether price sensitivity significantly affects churn.
* Identifying high-value and high-risk customer segments.
* Estimating potential revenue at risk.
* Building predictive models to identify customers likely to churn.
* Providing actionable business recommendations for customer retention.

---

## Objectives

* Perform comprehensive exploratory data analysis.
* Engineer meaningful business and behavioral features.
* Conduct statistical hypothesis testing.
* Analyze customer segments and churn patterns.
* Build and evaluate machine learning models for churn prediction.
* Estimate business impact and revenue at risk.
* Develop practical retention strategies.

---

## Data Overview

This project utilizes customer and pricing data provided as part of the PowerCo Customer Churn Analysis case study. The objective is to investigate customer attrition patterns, evaluate the impact of pricing changes on churn, and develop data-driven retention strategies.

The two primary datasets used are:

* `client_data`: Contains customer account information, including churn status, sales channel, consumption metrics, contract details, product subscriptions, and profitability indicators.
* `price_data`: Contains historical electricity and gas pricing records used to assess price fluctuations and customer price sensitivity over time.

The datasets were cleaned, merged, and transformed to create an analytical base table for customer behavior analysis. Additional business-oriented features were engineered to support customer segmentation, statistical testing, churn prediction, and customer value analytics.

The final analysis focuses on identifying churn drivers, quantifying revenue at risk, profiling high-value customers, and recommending targeted retention strategies to improve customer lifetime value and reduce attrition.

---

## Key Analysis Performed

* **Data Cleaning & Preparation** – Handled missing values, corrected data types, and prepared the data for analysis.
* **Exploratory Data Analysis (EDA)** – Examined customer behavior, churn patterns, revenue trends, and segment characteristics.
* **Feature Engineering** – Created business-focused features related to customer value, consumption, and profitability.
* **Statistical Analysis** – Conducted hypothesis testing and price sensitivity analysis to validate key business assumptions.
* **Customer Segmentation** – Identified high-value, high-risk, and revenue-critical customer groups.
* **Predictive Modeling** – Built and evaluated machine learning models to predict customer churn.
* **Business Impact Assessment** – Estimated revenue at risk and developed data-driven retention recommendations.

---

## Tools & Technologies

* **Python:** Pandas, NumPy, Matplotlib, Seaborn, SciPy, Scikit-learn

* **Analytical Techniques:** Data Cleaning, EDA, Feature Engineering, Statistical Testing, Customer Segmentation, Predictive Modeling, Business Analytics

---

## Insights

**Price Is NOT the Primary Churn Driver**
* Off-peak price difference between churned and retained customers is <0.05% — statistically insignificant. Price changes over 2015 show no meaningful association with churn.

**Early-Tenure Customers Are the Highest-Risk Segment**
* Customers in their 1st–3rd year churn at 15.3%, more than double the rate of 5–10 year customers (7.3%). 

**PowerCo Is Losing Its Best Customers**
* Churned customers have 23% higher average net margin (£228 vs £185) and cluster in the highest-margin quartile (10.9% churn rate).

**Low Consumption = Low Stickiness**
* Churned customers consume 53% less electricity annually than retained customers (78,862 vs 167,867 kWh). 

**Multi-Product Bundling Is a Protective Moat**
* Customers with a gas add-on churn at 8.2% vs 10.1% for electricity-only customers. 
* Gas bundlers represent a 19% lower churn risk.

**Contract Proximity Is a Known Vulnerability**
* Contract end date proximity is the 4th most important predictor in the Random Forest model (8.9% importance).

**Sales Channel Quality Varies Significantly**
* Channel A acquires 46% of the customer base but drives a 12.1% churn rate vs 5.6% for Channel C.

**£324K Net Margin Is Lost Annually — Immediate Action Required**
* The 1,419 churned customers represent £324,046 in net margin.  

---

## Recommendations

**High-Risk Segment Retention:** 
  * The first 3 years represent the single most vital timeframe for PowerCo to invest in customer retention.
  * Implement specialized onboarding, predictive triggers, and year 1–3 pricing strategies to mitigate early-tenure churn.

**High-Value Churn Alert:** 
  * Competitors are successfully targeting PowerCo's most profitable Small and Medium Enterprises (SMEs).
  * Requires immediate, priority retention strategies to protect top-tier revenue accounts from competitive poaching.

**Low Stickiness in Low Consumers:** 
  * Low-consumption SMEs are less embedded in PowerCo's infrastructure, making them easier for competitors to poach.
  * It highlights the need for specialized engagement for smaller consumers who lack natural operational stickiness.

**Massive Cross-Sell Opportunity:**
  * 82% of the current customer base is electricity-only, representing a major untapped retention lever.
  * Recommends aggressive gas cross-selling to build a protective barrier around single-product accounts.

**Proactive Defense:** 
  * Requires PowerCo to overhaul its renewal timeline and beat competitors to the customer conversation.

**Channel Performance Gap:**
  * The high churn suggests poor onboarding quality or a customer-fit mismatch within the dominant acquisition channel.
  * Demands an immediate operational audit of Channel A to align acquisition incentives with long-term retention.

**High-ROI Opportunity:**
  * A targeted retention program achieving a modest 30% save rate would recoup approximately £97K annually.
  * Retaining these high-risk customers comes at a mere fraction of standard Customer Acquisition Costs (CAC).

---

## Business Impact

The project extends beyond predictive analytics by focusing on business outcomes.

The analysis helps:

* Identify customers with elevated churn risk.
* Estimate revenue exposure.
* Prioritize high-value customer retention.
* Support targeted marketing and customer engagement initiatives.
* Enable data-driven decision making for customer lifecycle management.

---

## Skills Demonstrated

This project demonstrates practical experience in:

* Data cleaning and preprocessing
* Business-oriented exploratory analysis
* Statistical hypothesis testing
* Feature engineering
* Machine learning for classification
* Customer segmentation
* Revenue and retention analytics
* Business storytelling
* Data-driven decision making

---

## Conclusion

Customer churn is a multifaceted business problem that requires a combination of analytical, statistical, and strategic approaches. This project demonstrates how data can be leveraged to understand customer behavior, quantify business risk, and support evidence-based retention strategies that contribute to long-term customer value and sustainable business growth.
