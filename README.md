## Shopify Sales & Customer Funnel Analysis – Power BI Dashboard

A fully interactive Power BI dashboard designed to analyze Shopify’s sales performance, customer funnel behavior, retention metrics and product category insights.

This project covers the complete BI development lifecycle including data cleaning, modeling, DAX calculations, visualization building and delivering a business-ready analytical report.


#### Project Development Steps

The project follows a structured Business Intelligence workflow:

✔ Requirement Gathering / Business Understanding

✔ Data Walkthrough

✔ Data Connection

✔ Data Cleaning & Quality Check

✔ Data Modeling

✔ Data Processing

✔ DAX Calculations

✔ Dashboard Layout Planning

✔ Visualizations & Chart Development

✔ Report Formatting

✔ Insights Extraction & Validation


#### Business Requirement

The objective is to analyze Shopify sales data to uncover:

- Transaction performance & revenue trends

- Customer purchasing behavior & repeat activity

- Retention metrics such as LTV, repeat rate & purchase frequency

- Regional sales distribution across provinces & cities

- Payment gateway preferences

- Product performance across categories

The dashboard enables stakeholders to make informed decisions regarding marketing, finance and customer engagement.


#### Key Performance Indicators (KPIs)

1. Transaction Performance

- Net Sales

- Total Quantity

- Net Average Order Value

2. Customer Purchase Behavior

- Total Customers

- Single-Order Customers

- Repeat Customers

3. Retention & Value KPIs

- Lifetime Value (LTV)

- Repeat Rate

- Purchase Frequency


#### Visualization Requirements

1. Regional Overview – Province & City

- Filled Map (Province-Level) → Shows KPI distribution by province

- Bubble/Density Map (City-Level) → Shows revenue/customer concentration

- City-Level Bar Chart → Ranks top-performing cities

2. Sales Trend Over Time

- Daily Trend (Area Chart) → Displays KPI changes by date

- Hourly Trend (Bar or Line Chart) → Reveals peak activity time (0–23 hrs)

3. Payment Gateway Analysis

- Identifies most-used and least-used payment methods

- Helps understand customer checkout preferences

4. Product Type Performance

- Bar chart showing best-performing product categories

- Helps optimize product and marketing decisions

#### Dashboard Output

![Dashboard Overview](Outcomes/shopify%20analysis%20dashboard%20outcome%20image%20-%201.PNG)

![Detailed Table](Outcomes/shopify%20analysis%20dashboard%20outcome%20image%20-%202.png)


#### Project Structure

Shopify Analysis/

├── Data/

│   └── Shopify Sales Data.xlsx

├── Outcomes/

│   ├── shopify analysis dashboard outcome image - 1.png

│   └── shopify analysis dashboard outcome image - 2.png

├── Resources/

│   └── Shopify Logo.png

└── Shopify Analysis Dashboard.pbix


#### Insights Summary

📌 Sales Insights

- Certain provinces and cities contribute significantly higher revenue.

- Net Sales and AOV show noticeable trends over specific dates and hours.

- Running Shoes, Tennis Shoes and Gift Cards are among top categories.

📌 Customer Insights

- Repeat customers form a strong portion of overall revenue.

- Purchase frequency reveals strong engagement among recurring buyers.

📌 Payment Insights

- Shopify Payments dominates as the most preferred gateway.

- Gift Card and PayPal usage vary depending on region and customer type.


#### How to Use This Project

1. Download or clone the repository

2. Open the .pbix file using Power BI Desktop

3. Ensure the dataset path is correctly mapped

4. Refresh the data

5. Use the slicers to explore:

- Province

- Gateway

- KPI Selector

- Product Type


#### Dataset

The dataset is included in the project:

/Data/Shopify Sales Data.xlsx


#### Contributing

Contributions are welcome!

You may contribute by improving:

- DAX measures

- UI/UX and layout

- Additional KPIs

- More drill-through pages

- Enhanced navigation

Steps:

1. Fork the repository

2. Create a new branch

3. Commit your updates

4. Submit a pull request
