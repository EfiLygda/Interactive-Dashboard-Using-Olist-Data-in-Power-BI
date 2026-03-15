# Interactive E-commerce Dashboard in Power BI

This project presents an interactive Power BI dashboard built using the Brazilian e-commerce Olist dataset. The goal of the dashboard is to analyze sales performance, customer behavior and delivery efficiency.

The dashboard enables stakeholders to explore key business metrics such as revenue, order volume, customer satisfaction, and logistics performance through interactive visualizations.

![](./Demos/9.%20Demo.gif)


## Tools Used

The tools used in this project include: `Power BI`, `DAX (Data Analysis Expressions)`, `Data modeling`, `Data visualization`

## Dataset 

The dataset contains information about: `customers`, `orders`, `payments`, `products`, `sellers`, `reviews`, `geolocation`, `leads`

The available tables are connected to analyze the full e-commerce process from purchase to delivery and customer feedback.

![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F2473556%2F23a7d4d8cd99e36e32e57303eb804fff%2Fdb-schema.png?generation=1714391550829633&alt=media)

> [!NOTE] 
> This repository uses the data available at [Kaggle](https://www.kaggle.com/datasets/terencicp/e-commerce-dataset-by-olist-as-an-sqlite-database).


## Business Questions

The dashboard was designed to answer the following business questions:

```
Summary
What is the total revenue and number of orders over time? Is the platform growing over time?
Total Revenue: $15.6M
Total Orders: 99.44K
The marketplace experienced consistent growth, suggesting increasing customer demand and platform adoption.

How successful are orders from placement to completion?
~98% of orders are completed, Operational efficiency appears very high

How satisfied are customers based on review ratings?
Average Review Score: 4.09 / 5 ⭐
Customers generally report positive experiences

Which product categories generate the most revenue?
Top revenue-generating categories:
Health & Beauty – $1.43M
Watches & Gifts – $1.29M
Bed, Bath & Table – $1.24M
Sports & Leisure – $1.13M
Computers & Accessories – $1.04M
Lifestyle and personal products dominate revenue, suggesting consumer demand in everyday-use categories.

Which regions generate the most revenue?
Top revenue regions:
São Paulo (largest contributor)
Rio de Janeiro
Minas Gerais
Rio Grande do Sul
Paraná

Sales are heavily concentrated in Brazil’s most economically active states, especially São Paulo.
```



## Dashboard Pages

### Summary

This page provides a high-level summary of business performance, in order to quickly understand overall company performance and sales growth over time.

![](./Demos/1.%20Summary%20Tab.gif)

#### Overall Business Performance

The marketplace shows strong overall sales activity with high order completion and steady revenue growth over time.
```
Total Revenue: $15.6M
Total Customers: 96.1K
Total Orders: 99.44K
Cancellation Rate: 0.63% (very low)
```
📌 Insight:
A low cancellation rate and high number of completed orders indicate efficient order fulfillment and customer reliability.

#### Revenue Trend

The Revenue Trending chart shows:

Revenue steadily increasing from 2017 to 2018

Growth accelerated through late 2017 and early 2018

Peak revenue months approach ~$1.1M–$1.2M

A sharp drop at the end is noted as incomplete data for the latest month (Sept 2018).

📌 Insight:
The marketplace experienced consistent growth, suggesting increasing customer demand and platform adoption.

#### Order Fulfillment Performance

Order status distribution:

Status	Orders
Completed	97.59K
Cancelled	0.63K
Processing	0.62K
Unavailable	0.61K
Pending	0.01K

📌 Insight:

~98% of orders are completed

Operational efficiency appears very high

#### Customer Satisfaction

Average Review Score: 4.09 / 5 ⭐

📌 Insight:
Customers generally report positive experiences, indicating good service, product quality, or delivery performance.

#### Most Profitable Product Categories

Top revenue-generating categories:

Health & Beauty – $1.43M

Watches & Gifts – $1.29M

Bed, Bath & Table – $1.24M

Sports & Leisure – $1.13M

Computers & Accessories – $1.04M

📌 Insight:
Lifestyle and personal products dominate revenue, suggesting consumer demand in everyday-use categories.

#### Most Profitable States

Top revenue regions:

São Paulo (largest contributor)

Rio de Janeiro

Minas Gerais

Rio Grande do Sul

Paraná

📌 Insight:
Sales are heavily concentrated in Brazil’s most economically active states, especially São Paulo.


#### Overall Conclusion

The marketplace shows:

Strong revenue growth

High order completion rate

Low cancellations

Good customer satisfaction

Revenue concentrated in key product categories and major Brazilian states

➡️ This suggests a healthy and efficiently operating e-commerce marketplace with strong demand and reliable fulfillment.


### Customer & Sales Details

![](./Demos/2.%20Customer%20&%20Service%20Details.gif)


### Product Details

![](./Demos/3.%20Product%20Details.gif)


### Map

![](./Demos/4.%20Map.gif)

### Tooltips

#### Category

![](./Demos/5.%20Category%20Tooltip.PNG)


#### Orders

![](./Demos/6.%20Orders%20Tooltip.PNG)


#### Review Score

![](./Demos/7.%20Review%20Score%20Tooltip.PNG)

### Colorset

![](./Demos/8.%20Colour%20Sets.PNG)
