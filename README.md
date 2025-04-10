![](https://www.agenciaeplus.com.br/wp-content/uploads/2018/06/ecommercebrasil.jpg)
# Brazil-e-commerce-analyst
This project is a collaborative effort by junior data analysts to analyze the e-commerce performance of Olist, a Brazilian online platform. Our goal is to leverage data analytics to provide insights into customer behavior and sales performance.

# Project Overview
In this data sprint, we utilized two primary datasets:

- E-Commerce Order Data: Contains details about 100,000 orders, including sales performance metrics, product information, and customer reviews.
- Marketing Funnel Data: Includes data on acquisition channels, conversion rates, and campaign performance, critical for understanding sales effectiveness.

# Deliverables
- Comprehensive analysis of sales performance.
- Dashboards visualizing key sales metrics and trends.
- Presentation summarizing insights and recommendations for improving sales strategies.

# Tools Used 
- Data cleaning and processing with Python.
- Data visualization using Power BI.

# Dataset
<p style = "text-align:justify">The dataset includes 100,000 orders from Olist, described by various variables such as order ID, order item ID, product ID, seller ID, shipping limit date, price, freight value, and quantity. These variables provide insights into sales performance, customer behavior, and shipping logistics within the Brazilian e-commerce market.

Olist is a Brazilian e-commerce platform that connects small and medium businesses with consumers, facilitating online sales across diverse product categories. This dataset enables analysis of market trends and operational efficiencies, helping businesses optimize their performance.</p>

| Column Name         | Data Type   | Description                                                      |
|---------------------|-------------|------------------------------------------------------------------|
| `order_id`          | Object      | Unique identifier for each order.                               |
| `order_item_id`     | Integer     | Unique identifier for each item within an order.                |
| `product_id`        | Object      | Unique identifier for each product.                             |
| `seller_id`         | Object      | Unique identifier for the seller of the product.                |
| `shipping_limit_date` | DateTime  | The date by which the order should be shipped.                  |
| `price`             | Float       | Price of the product (in Brazilian Real).                       |
| `freight_value`     | Float       | Shipping cost associated with the order item.                   |
| `quantity`          | Integer     | Quantity of the product ordered.                                |
