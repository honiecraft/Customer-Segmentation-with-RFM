# [Python] Customer Segmentation with RFM Analysis
This project aims to provide a robust implementation of **RFM** (Recency, Frequency, Monetary) analysis using the **Python** programming language to **Segment customers**. RFM analysis is a valuable tool in _marketing and customer relationship management_, helping businesses gain insights into _customer behavior_ and make informed decisions.

## About
**SuperStore** Company is a global **retail** company. So the company has a lot of customers. On the occasion of Christmas and New Year, the Marketing department wants to **run marketing campaigns** to thank _customers who have supported the company_ over the past time. As well as exploit _customers with the potential to become loyal_ customers.

> **Objective**\
> Using the **RFM model and Python programming** to build a **segmentation** evaluation implementation to apply an appropriate marketing campaign for each customer group.

## RFM Analysis
RFM Analysis is used to understand and **segment customers based on their buying behavior**. RFM stands for recency, frequency, and monetary value, which are three key metrics that provide information about customer engagement, loyalty, and value to a business.

### What is RFM Analysis?
RFM analysis involves evaluating three key aspects of customer transactions:

- **Recency (R):** How recently did the customer make a purchase?
- **Frequency (F):** How often does the customer make a purchase?
- **Monetary Value (M):** What is the monetary value of the customer's purchases?
  
![image](https://github.com/user-attachments/assets/4dfd98c1-df8d-4b9a-95c2-055a8c515c67)

By analyzing these factors, businesses can segment their customers into meaningful groups, allowing for targeted marketing strategies and personalized engagement.

### How to Implement RFM Analysis for Customer Segmentation?
Implementing RFM analysis is a systematic process that involves several key steps:
- **Step 1: Collect Data**\
  Gather customer transactional data. This would include key details such as purchase dates, frequency of purchases, and total spending by customers.
- **Step 2: Set RFM Metrics** \
  Define your criteria for Recency (what time frame to consider), Frequency (the period over which you measure the number of purchases), and Monetary value (define the total spending period), based on your business model and industry standards.
- **Step 3: Score Customers** \
Assign scores to customers based on your defined RFM metrics. This is typically done on a scale of 1 to 5, with 5 being the highest and 1 being the lowest.
- **Step 4: Segment Customers** \
Assess the importance of each RFM variable depending on the nature of your business. Then, segment your customers into groups based on their RFM scores.
- **Step 5: Craft Marketing Strategies** \
Develop customized marketing strategies for each defined segment. Tailor your approach to the specific needs and behaviors of each group.

## Dataset
The dataset is located in file `ecommerce retail.xlsx` and having 2 sheet: 

**1. Sheet "ecommerce retail"**\
This is a transnational dataset that contains all the transactions occurring between **01/12/2010** and **09/12/2011** for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
- **InvoiceNo:** Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'C', it indicates a cancellation.
- **StockCode:** Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- **Description:** Product (item) name. Nominal.
- **Quantity:** The quantities of each product (item) per transaction. Numeric.
- **InvoiceDate:** Invoice Date and time. Numeric, the day and time when each transaction was generated.
- **UnitPrice:** Unit price. Numeric, Product price per unit in sterling.
- **CustomerID:** Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- **Country:** Country name. Nominal, the name of the country where each customer resides.

 **2. Sheet "Segmentation"**\
 This sheet includes information about 11 customer Segments and the RFM score corresponding to each group.

## Key Features
### 1. Data Preprocessing
Clean and preprocess transactional data to ensure accurate RFM analysis.
Handle missing values, outliers, and other data-cleaning tasks.
### 2. RFM Calculation
Compute Recency, Frequency, and Monetary values for each customer based on their transaction history.
Easily customize the time frame for recency calculation.
### 3. Segmentation
Utilize RFM scores to segment customers into different groups.
Explore and analyze customer segments to identify high-value and at-risk segments.
### 4. Visualization
Generate insightful visualizations, such as heatmaps and scatter plots, to visually represent RFM segments.
Customize visualizations to meet the specific needs of analysis.
### 5. Interpretation and Insights
Interpret the results of RFM analysis to derive actionable insights for marketing strategies.
Understand customer behavior and tailor marketing efforts to specific segments.
