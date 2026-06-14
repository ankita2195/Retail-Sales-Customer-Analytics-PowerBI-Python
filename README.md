# 📊 Retail Growth & Retention Analysis: Uncovering Customer Inactivity and Revenue Opportunities | Python & Power BI

---

## Executive Summary

Analyzed retail transaction and customer data using Python and Power BI to uncover revenue patterns, customer behavior, and retention gaps. Despite stable monthly revenue (170K-180K), the business shows signs of stagnation with **91% inactive customers and 87% high-value customers disengaged**. The analysis highlights a critical retention problem and declining customer acquisition, and provides targeted strategies to improve engagement, retention, and long-term growth.

# 👉 **Live Dashboard:** [View Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZjcwNjUyZjItYjAxMy00ZGVhLWE1MjctNjgzN2E1NjUzNzViIiwidCI6ImE1ZmI3ZjgwLTIwNTEtNGE5Ny05YjEyLTZhYjIyMmQyYmQ1NSJ9)

---

## Business Problem

The business aims to:
- Understand **why growth has stalled despite stable sales**
- Identify **drivers of customer inactivity and low engagement**
- Evaluate **customer retention over time**
- Detect **decline in new customer acquisition**
- Provide **data-driven strategies to improve revenue and retention**

---

## Methodology

- Cleaned and preprocessed raw retail datasets using Python  
- Merged transaction and response datasets for unified analysis  
- Performed **Exploratory Data Analysis (EDA)** to identify trends and anomalies  
- Conducted **Time Series Analysis** to evaluate sales consistency  
- Built **RFM Segmentation** to classify customers based on value  
- Performed **Cohort Analysis** to track customer retention over time  
- Designed an **interactive Power BI dashboard** for insights and decision-making  

---

## Skills Used

- **Python:** Pandas, NumPy (data cleaning, transformation)
- **Power BI:** DAX, dashboard design, data modeling  
- **Analytics Techniques:** EDA, Time Series, RFM Analysis, Cohort Analysis  
- **Business Thinking:** Insight generation, retention strategy, growth analysis  

---

## Results & Business Recommendations

### Key Findings

- Monthly revenue is **stable (170K-180K)** despite misleading yearly trends  
- Customer growth has **stagnated post-2012**  
- **91% customers are inactive**, limiting revenue potential  
- **87% of high-value customers are disengaged**  
- Cohort analysis shows **65-75% drop after first purchase**  
- No new customer acquisition observed after 2013  

---

### Business Recommendations

Creating a data-driven dashboard provides stakeholders with visibility into customer behavior, retention, and revenue trends. This reduces dependency on manual reporting and enables faster decision-making.

The analysis revealed that **a majority of customers drop off after their first purchase**, and a significant portion of high-value customers remain inactive. Based on behavioral patterns identified through cohort and RFM analysis, improving customer retention and engagement presents the highest revenue opportunity.

According to the analysis:

- Improving customer activity and retention presents the largest opportunity to increase revenue, as a significant portion of customers are currently inactive.
- Re-engaging even high-value customers can lead to a meaningful uplift in monthly revenue.
- Reducing early-stage churn (post first purchase) can substantially improve long-term retention.  

---

### Next Steps

- Implement targeted win-back campaigns for high-value inactive customers
- Introduce post-purchase engagement flows to reduce early churn
- Launch customer acquisition campaigns to restart growth
- Continuously track KPIs using the Power BI dashboard

---

### Limitations

- Partial data for 2011 (starting mid-year) and 2015 (ending early) may distort yearly trends
- No explicit churn definition, inactivity inferred from response data
- Absence of order-level identifiers limits deeper behavioral analysis
- External factors (marketing spend, seasonality, competition) not included in dataset

---

### Repository Structure

Retail-Customer-Analytics/

│── data/
│   └── # Raw & cleaned datasets       
│── notebooks/
│   └── # Python analysis (EDA, cohort, RFM)   
│── reports/
│   └── Power BI dashboard file (.pbix)                   
│── README.md    
