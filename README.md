# Olist-E-commerce-Dashboard

## 1. Project Overview

### Context

Olist is an e-commerce platform that connects small and medium-sized businesses to customers. The platform operates as a marketplace, where merchants can list their products and services and customers can browse and purchase them online. 


### Goal

- **Sales dashboard:** to provide a detailed and timely overview of key sales metrics, facilitating informed decision-making and tactical adjustments.
- **Customer Insights:** to provide a comprehensive view of customer metrics and behavior, enabling data-driven marketing strategies and campaign optimization.
- **Logistics & Delivery Insights:**  to provide a detailed and actionable view of delivery performance metrics , enabling efficient management of logistics and operational processes.


## 2. Dataset Structure

The dataset has information of  orders from 2017 to 2018(August) made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers.

This dataset can be found [here](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/code). 

## 3. Sales Dashboard Insights Summary

**Sales Performance**

![Image](https://github.com/user-attachments/assets/97ab0b4e-1af8-425f-ba57-bf646045c2ec)

- **Trend Analysis**: Evaluate how Total Orders and Gross Revenue have changed compared to previous month. This helps identify growth trends or declines in sales performance.
- **Day of Week**: Identify which days have the highest and lowest Total Orders and Gross Revenue. This can help optimize staffing, promotional efforts, and inventory levels for peak days.
- **Months **: Determine peak shopping hours. This can assist in scheduling promotions and improving website performance during high-demand months.

**Customer Behavior**

- **Average Order Value (AOV)**: Analyze how AOV change over time. A rising AOV suggests that customers are spending more per transaction, while a declining AOV could indicate reduced spending or promotions affecting spending behavior. Consider strategies to boost AOV, such as bundling products, offering discounts on higher-value orders, or implementing loyalty programs.
- **Payment Method**: Analyze the distribution of payment types. If a particular payment method dominates, consider enhancing support and promotions for less popular methods to improve their adoption.


  ## 4. Logistics & Delivery Dashboard Insights Summary

![Image](https://github.com/user-attachments/assets/7166249d-93d5-4d71-9672-8078de77f191)


**Delivery Performance**

- **On-time vs. Late Delivery Rate**: Determine the percentage of on-time deliveries versus late deliveries. This helps assess overall delivery performance and identify areas needing improvement.

**Delivery Time Analysis**

- **Delivery Time Distribution**: Analyze the distribution of delivery times to understand how long it typically takes to deliver orders. Identify any patterns that could indicate operational inefficiencies.
- **Avg Review Score & Total Orders based on delivery days Distribution**:

**On-time vs. Late Delivery Analysis**

- **On-time vs. Late Delivery by Stage**: Examine average times for different stages (approval, processing, shipping) and their impact on on-time and late deliveries. This helps identify issues in the entire delivery process.
- **On-time vs. Late Delivery by Product Category**: Identify which product categories have higher on-time and late delivery rates. This can reveal if certain categories face more logistical challenges (e.g., packaging, handling) or delays.

**Regional Delivery Performance**

- **State Analysis**: Review delivery metrics by state to identify regional performance differences. This helps pinpoint areas with higher or lower delivery performance and adjust strategies accordingly. For regions with higher late delivery rates, enhance logistical support, improve local partnerships, or optimize delivery routes.


## 5. Customer Dashboard Insights Summary

![Image](https://github.com/user-attachments/assets/6729c0d0-edca-4e14-9024-eced7131a275)

**Customer Segmentation**

- **Total vs. Repeat Customers %**: Analyze the proportion of repeat customers. A higher proportion of repeat customers may indicate strong customer loyalty and successful retention strategies. 
**Customer Behavior** 

**Revenue Insights**

- **Average Revenue & Order Value per Customer**: Compare the average revenue per customer for new versus repeat customers. This helps identify which group generates more revenue and informs strategies to increase revenue from both groups.

**Customer Satisfaction**

- **Review Score Distribution**: Assess the overall distribution of review scores to gauge general customer satisfaction. Identify if most reviews are positive, negative, or neutral, and investigate common themes in reviews.


## 6. Appendix

### Technical Process

The technical process included:

- Cleaning(have exlcuded 2016 data as it only had Aug & Sept Data), preparing and exploring the data in Microsoft Excel(Power Query)
- Calculating metrics in DAX
- Building dashboards in PowerBI


  ### Sales Dashboard Key Metrics

The sales dashboard focuses on the following key metrics:

- **Total Order Value**: The total  revenue generated from all the orders placed.
- **Total Revenue**: The total amount of money generated from sales.
- **Average Order Value (AOV)**: The average amount spent per transaction.
- **Total Products Sold**: The total number of items purchased .
- **Year to Date Growth %**: The percentage of revenue increase comapred to last year to current year.

### Logistics & Delivery Dashboard Key Metrics

- **Total Orders**: The total number of orders placed by customers within a specified period.
- **Average Delivery Time**: The average amount of time taken from when an order is placed to when it is delivered to the customer.
- - **No of delayed Orders**: The number of orders that are  not successfully fulfilled and shipped within the promised time frame.
- **Total Shipping Cost**: The total cost required to ship all the products.
- **Late Delivery Rate**: The percentage of orders that are delivered after the estimated delivery date.


### Customer Insights Dashboard Key Metrics

The customer dashboard focuses on the following key metrics:

- **Total Customers**: The total number of unique individuals who have made at least one purchase from your e-commerce store within a specified period.
- **Order per Customer**: The number of unique individuals who made their first purchase within a specific time frame.
- **Repeat Customer Rate**: The percentage of customers who make more than one purchase within a specified period.
- **Revenue per Customer**: The average revenue generated from each customer over a specified period. It reflects how much value each customer brings to your business.
- **Total Repeat Customer**: The total number of customers who made more than one purchase within a specific period.
- **Average Review Score**: The average rating given by customers on their purchases,  on a scale from 1 to 5 stars.




