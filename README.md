# RFM_CustomerSegmentation
RFM Analysis and Customer Segmentation-Online Retail Store

## Project Overview
This project involves an RFM (Recency, Frequency, Monetary) analysis for an online retail shop where most customers are wholesalers.<br/> The goal is to segment customers based on purchasing behaviors to provide actionable insights for targeted marketing and customer retention strategies.

### Question to answer
1. How are customers distributed across different RFM segments (e.g., Loyal, Potential Loyal, Dormant, Critical, Inactive)?
2. How do Recency, Frequency, and Monetary values correlate with each other within the segments? (e.g., loyal customer segment)
3. What strategies can be implemented to increase customer retention and spending?
   
### Brief Background
**Why RFM is conducted?**
It was traditionally done to categorize customers according to 3 characteristics:
1. Recency(R)- Amount of elapsed time(e.g days) since the last purchase
2. Frequency(F)- Count of purchases made during some period (e.g., last 1 year)
3. Monetary(M)- Total amount of purchase made during some time period( e.g., last 1 year)<br/>
💡 The key idea is that customers who rank highly in the above characteristics are more likely to be repeat buyers.

## Insights from the analysis
### Customer Segmentation
The total number of customers analyzed is 4,760.<br/>
**Distribution of Customers:**
* **Loyal:** 1,699 customers (35.7%)
* **Potential Loyal:** 1,375 customers (28.9%)
* **Dormant:** 515 customers (10.8%)
* **Critical:** 390 customers (8.2%)
* **Inactive:** 393 customers (8.3%)<br/>

**Distribution of Revenue** <br/>
| RFM Customer Segment  | Total Revenue | Average Order Value | Revenue % |
| :--- | :---| :--- | :--- |
|Loyal |	6,972,427.41	|21.40	|84.22 |
|Potential Loyal |	998,309.74|17.64 |12.06 |
|Dormant  | 176,486.28	| 16.38	|2.13 |
|Critical  | 88,362.68 | 16.43	|1.07 |
|Inactive	| 4,2933.310	|13.92	|0.52 |
|Total	| 8,278,519.42	| NaN | 100.00 |

Discovered that *Loyal Customers* contributed to **Total Revenue** by *84%* and had *$4.2M* more in revenue and *$4.25* higher **AOV**. <br/>

### Relationship of the Metrics (Correlation) Among Loyal Customers
1. **R vs F:** Strong negative correlation of *-0.096* (compared to R Vs M).<br/>
**Interpretation:** Customers with a high frequency of purchases tend to have lower recency scores. The frequent buyers are also the most engaged with recent purchases.<br/>
2. **R vs M:** Weak negative correlation of *-0.100*.<br/>
**Interpretation:** Customers who have spent more money tend to have slightly lower recency scores and are therefore somewhat likely to have made recent purchases. This indicates that the most valuable customers are still actively engaged with the business.<br/>
3. **F vs M:** Moderate positive correlation of *0.335*.<br/>
**Interpretation:** Customers who purchase frequently tend to spend more money, however, there is a mix of some buying frequently but with smaller spending.

## Recommendations
1. **Customer Retention:** Keeping the frequent buyers engaged, should be a priority since they are also likely to be recent purchasers.<br/>
2. **Enhance Loyalty Programs:**  The focus on the Loyal segment to offer personalized and exclusive offers e.g., free delivery up to a certain purchase. <br/>
3. **Target the Potential Loyal Customer Segment:** Campaigns to engage the **28.9%** to move them to the Loyal Customer segment. Strategies could be offering incentives like discounts or even discounts on repeat purchases within a short timeframe to boost their recency score and frequency scores and in turn boost the revenue for the score. <br/>
4. **Targeted Marketing to Inactive customers:** Address the Dormant and Inactive segments with special offers, personalized messages, or reactivation packages. The personalized messages could remind them of the value of the products and the services the Store offers which sets them apart from the competitors. <br/>
5. **Monitor and Adapt:** Continuously monitor the effectiveness of the strategies and adjust based on customer behaviour and trends. Additionally, reassess the segments and monitor the shifts in customer behaviour to make timely interventions. For example, if a customer has frequently and recently called customer service, there might be a likelihood of them not purchasing frequently or stopping altogether. <br/>

    
**💡The recommendation** is to focus on 2 strategies: *Re-engage* high spenders who may not be spending as frequently and *targeting the "Potential Loyal Customer segment"* to convert to Loyal customers and increase their recency of purchases.
