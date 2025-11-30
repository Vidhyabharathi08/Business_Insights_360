# Business_Insights_360

## Problem Statement:
AtliQ Hardwares is a global consumer electronics manufacturer, comparable to brands like HP and Dell. Although the company has been growing steadily worldwide, it has been facing major challenges in the Latin American market.A key reason behind these challenges is the company’s reliance on Excel files to manage large and complex datasets. While Excel is useful for basic reporting, it becomes inefficient as data volume increases. 

This leads to several issues, such as:

> Difficulty in understanding and interpreting large datasets

> Limited visualization and analytical capabilities

> Lack of scalability for enterprise-level reporting

> Reduced visibility into key business metrics

These limitations contributed to poor decision-making and significant financial losses in the Latin American region.

## Objective:
To overcome these challenges, this project aims to develop an advanced analytics solution that enhances data accessibility, improves reporting efficiency, and enables data-driven decision-making across the business.

### Data Source Overview:

Before beginning the analysis, it is essential to understand the structure of the data. The dataset consists of multiple tables categorized into:

### Dimension Tables:

Dimension tables provide descriptive and static information that gives context to the business data. Thi table contains the attributes of the fact table.

### Fact Tables:

Fact tables contain transactional, measurable data that grows over time and forms the core of the analysis.


### gdb041

### dim_customer:

Covers 27 global markets (e.g., India, USA, Spain).

Includes 75 unique customers across all markets.

Operates through two major platform types:

> Brick & Mortar – Physical retail outlets

> E-commerce – Online marketplaces (Amazon, Flipkart, etc.)

Categorized into three customer channels:

> Retail

> Direct

> Distributor

### dim_market:

> Represents 27 markets, grouped for strategic analysis.

> Divided into 7 sub-zones for better regional segmentation.

Classified into 4 primary regions:

> APAC

> EU

> NA

> LATAM

### dim_product:

Organized under major product divisions, including:

#### P & A (Peripherals & Accessories)

> Peripherals

> Accessories

#### PC (Computing Products)

> Notebook

> Desktop

#### N & S (Networking & Storage)

> Networking

> Storage

### gdb056 

#### freight_cost:

Contains market-wise transportation and logistics costs recorded by fiscal year.

#### gross_price:

Stores gross selling prices for each product, linked through product codes.

#### manufacturing_cost:

Includes yearly manufacturing costs for each product based on product code.

#### pre_invoice_deductions:

Provides annual pre-invoice deduction percentages applied to each customer.

post_invoice_deductions:

Records post-invoice deductions such as rebates, claims, and additional discounts.

### Data Model:
<img width="814" height="715" alt="Screenshot 2025-11-30 160605" src="https://github.com/user-attachments/assets/1135f89d-5c6c-45e4-b77c-54557b130222" />
In this project, we have followed Snowfall data modeling method.

##  Objective:
Developed a comprehensive analytics solution for AtliQ Hardware to optimize data analysis and generate meaningful insights for business leaders in Sales, Finance, and Marketing.

### Finance View:
<img width="1378" height="772" alt="Screenshot 2025-11-30 161414" src="https://github.com/user-attachments/assets/7212a4ca-93f0-44d3-b3d9-a8f8d2bff671" />
This Finance view provides a comprehensive snapshot of AtliQ Hardware’s financial performance. It tracks key metrics such as Net Sales, Net Profit, and Gross Margin, allowing users to analyze trends over time. The dashboard highlights performance across different products, customers, and regions, and includes a Profit & Loss breakdown for detailed insights.

### Sales View:
<img width="1383" height="766" alt="Screenshot 2025-11-30 161912" src="https://github.com/user-attachments/assets/b7776141-15a8-4f9d-9d22-89976a39e304" />
Decode customer and product performances influenced by Key metrics such as Net Sales, Gross Margin and Gross Margin Percentage ,performance matrix b/w NS and Np % for market, customers ,then explore the Break down of P & L values of Sales View such as Net Sales , Total Post Invoice Deductions , Gross Marigin.

### Marketing View:
<img width="1420" height="769" alt="Screenshot 2025-11-30 163048" src="https://github.com/user-attachments/assets/da366d65-ac44-4ef5-8215-1f691e761f39" />
This dashboard provides a clear view of category-wise performance, showing how each product segment contributes to Net Sales, Gross Margin, and Net Profit. The market performance chart highlights regions based on profitability trends, revealing strong and weak markets. A COGS vs Gross Margin donut explains how revenue is divided between cost and profit. The waterfall chart further breaks down how expenses impact overall profitability, helping identify key drivers and improvement areas.


###

Interactive Dashboard: [Click Here](https://app.powerbi.com/groups/me/reports/430f25d4-4a9c-48cc-b4fc-dbe2898aaaca/9a80cbb6959b8fa1f8b2?experience=power-bi)


### Conclusion:

AtliQ Hardware’s overall performance shows steady growth in net sales and profitability across key product categories. Customer and market analyses highlight the major revenue drivers and reveal clear opportunities for expansion. Cost and margin insights help identify areas where efficiency can be improved to boost overall profit. The dashboards together provide a strong data foundation for strategic decisions in sales, finance, and market planning.



