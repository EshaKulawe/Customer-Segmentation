# Customer-Segmentation

The purpose of this project is to conduct a Customer Segmentation Analysis for an Automobile bike Company. Customer segmentation is a useful technique that helps us better understand our customers and meet their diverse needs. Nearly every business that offers goods or services keeps track of customer purchases. The results of the analysis can be converted into marketing efforts to boost sales since this kind of data can be utilized to carry out customer segmentation. RFM analysis is one of the most popular methods since it enables us to develop customized special offers that increase sales and decrease customer attrition.

Recency, Frequency, Monetary Value, or RFM, is a method of segmenting customers according to their past transactions.
- Recency: Days since last purchase/order of the client;
- Frequency: Total number of purchases the customer were made;
- Monetary Value: Total money the customer spent per order.

The traditional RFM approach can be used to segment customers by giving them ratings ranging from 1 to 4. To construct RFM value classes for our clients, the individual score numbers are combined into a single column to determine the final RFM score.

### Tools
- Python: It was used for data cleaning and exploratory data analysis.
- Power BI: The visualization tool was needed to explore data further and create charts, graphs, and visualizations to come up with a Sales Dashboard for Customer Segmenatation for the automobile bike company.

### Data Source
- used the excel file raw_data.xlsx

### Data Cleaning
- Used the pandas library to clean the different sheets present in original sheet.
- Checked for duplicates, missing values and discrepancies in the data and improved the data reliability by removing duplicates, handling null values and correcting the discrepancies.

### Power BI Report
![Sales](https://github.com/user-attachments/assets/7fdf69af-3e87-4f9d-b3ed-450752f630b2)
![CS](https://github.com/user-attachments/assets/2e281fab-9941-4273-9805-e8b19f52c8ba)

### EDA
- Demographic Insights:
  - Gender: Female customers have made slightly more bike-related purchases than male customers in the past three years.
  - Age Groups:
    Most customers, both old and new, belong to the age group of 40-49.
    The 20-29 and 50-59 age groups dominate among new customers, whereas 20-39 age brackets are the majority among old customers.

- Wealth Segmentation:
  - The majority of customers fall under the "Mass Customer" category across all age groups for both old and new customers.
  - The second largest group is "High Net Worth," with "Affluent Customers" having a noticeable presence in the 40-49 age group.

- Purchasing Patterns:
  - Customers who purchased recently generate significantly more revenue than those who haven't purchased for a long time.
  - Frequent buyers such as "VIP Customers" and "Very Loyal" segments are associated with higher monetary contributions.
 
- Customer Segmentation:
  - The segmentation divides customers into 11 groups based on RFM (Recency, Frequency, Monetary) scores. Key groups include:
     - VIP Customers (highest contribution and loyalty).
     - Very Loyal (Frequent buyers with significant contributions slightly less than VIPs).
     - Becoming Loyal (Customers transitioning to high loyalty and are frequent purchasers with moderate recency and monetary contributions).
     - Recent Customers (Recent purchasers with average frequency and high monetary values).
     - Potential Customers (Moderate recency and frequency with high monetary value).
     - Late Bloomers (Long intervals between purchases but significant monetary contributions when they do buy).
     - Losing Customers (Declining frequency and monetary contributions with low recency).
     - High Risk Customers (Irregular purchasing patterns and low monetary contributions).
     - Almost Lost Customers (Minimal engagement and contribution).
     - Evasive Customers (Rarely engage, contributing very little revenue).
     - Lost Customers (No recent purchases and negligible contributions).

- RFM Analysis Scatter Plot insights:
  - Recency vs Monetary:
     - Customers who purchased recently (recency between 0-50 days) generate the highest revenue.
     - A gradual decline in revenue is observed for customers with recency between 50-200 days, and minimal revenue is seen for customers with recency beyond 200 days.
     - Customers in the "High Net Worth" segment dominate recent purchases, contributing significantly to monetary value.

  - Frequency vs Monetary:
     - Customers classified as "VIP Customers" and "Very Loyal" have higher recency and frequency contributions.
     - Lower frequency customers, such as those in the "Almost Lost" and "Lost Customers" segments, show a sharp decline in monetary contributions.
   
### Strategy Recommendations for Customer Retention
- For VIP customers, the company could provide early access to new products or personalized offers and rewards to maintain their engagement.
- Region specific campaigns could be conducted to boost customer engagement.
- Conducting surveys to understand customer preference and taking measures on that basis.
- For customers with low RFM values, the company could start re-engagement campaigns with attractive discounts and targeted promotions and also send reminders or follow-ups highlighting new products or services.





