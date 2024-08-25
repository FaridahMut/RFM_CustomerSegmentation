# RFM_CustomerSegmentation
RFM Analysis and Customer Segmentation-Online Retail Store

## Project Overview
This project involves an RFM (Recency, Frequency, Monetary) analysis for an online retail shop where most customers are wholesalers. The goal is to segment customers based on their purchasing behaviors to provide actionable insights for targeted marketing and customer retention strategies.

### Question to answer
1. How are customers distributed across different RFM segments (e.g., Loyal, Potential Loyal, Dormant, Critical, Inactive)?
2. How do Recency, Frequency, and Monetary values correlate with each other within the the segments?(e.g., loyal customer segment)
3. What strategies can be implemented to increase customer retention and spending?
   
### Brief Background
**Why RFM is conducted?**
It was traditionally done to categorize customers according to 3 characteristics:
1. Recency(R)- Amount of elapsed time(e.g days) since the last purchase
2. Frequency(F)- Count of purchases made during some period (e.g., last 1 year)
3. Monetary(M)- Total amount of purchase made during some time period( e.g., last 1 year)
💡 The key idea is that customers who rank highly in the above characteristics are more likely to be repeat buyers.

## Insights from the analysis
### Customer Segmentation
The total number of customers analyzed is 4,760.
**Distribution of Customers:**
* Loyal: 1,699 customers (35.7%)
* Potential Loyal: 1,375 customers (28.9%)
* Dormant: 515 customers (10.8%)
* Critical: 390 customers (8.2%)
* Inactive: 393 customers (8.3%)

### Relationship of the Metrics (Correlation) Among Loyal Customers
1. R vs F: Strong negative correlation of *-0.096* (compared to R Vs M) 
**Interpretation:** Customers with high frequency of purchases tend to have lower recency scores. The frequent buyers are also the most engaged with recent purchases.
2. R vs M: Weak negative correlation of *-0.100*
**Interpretation:** Customers who have spent more money tend to have slightly lower recency scores therefore somewhat likely to have made recent purchases. This is a good indication because the most valuable customers are still actively engaged with the business.
3. F vs M: Moderate positive correlation of *0.335*
**Interpretaion:** Customers who purchase frequently tend to spend more money, however there is a mix with some buying frequently but with smaller spending.


    
