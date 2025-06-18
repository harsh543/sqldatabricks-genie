# 🛍️ Retail Sales Dataset

This dataset contains transactional retail sales records across various departments and stores. It includes purchase data, departmental breakdowns, store location details, and individual salesperson information. This is ideal for performing analytics and BI use cases such as sales trend analysis, performance dashboards, and location-based insights.

## 📊 Dataset Description

Each row in the dataset represents a single sales transaction. The schema includes:

| Column Name       | Description                                                  |
|-------------------|--------------------------------------------------------------|
| Department        | Product category or department name (e.g., Cosmetics)        |
| Manager           | Department manager overseeing the sale                       |
| Salesperson       | Staff member who completed the transaction                   |
| Transaction Type  | Type of transaction (e.g., Purchase, Return)                 |
| Sale Amount       | Total dollar value of the transaction                        |
| Sale Date         | Date when the transaction occurred                           |
| Store Number      | Unique identifier of the retail store                        |
| Country           | Country where the transaction took place                     |
| StateName         | State or region name                                         |
| City              | City and state code (e.g., Phoenix,AZ)                       |
| Zipcode           | Postal code of the store                                     |

## 🧪 Sample Data

| Department        | Manager   | Salesperson | Transaction Type | Sale Amount | Sale Date | Store Number | Country        | StateName | City            | Zipcode |
|------------------|-----------|-------------|------------------|-------------|-----------|---------------|----------------|-----------|------------------|---------|
| Mens Furnishings | BRANCH    | WEBB        | Purchase         | 48.49       | 6/1/2011  | 281a          | N/A            | (not set) |                  |         |
| Womens Shoes     | ROBBINS   | TAYLOR      | Purchase         | 14.87       | 6/1/2011  | 577a          | United States  | Alabama   | Birmingham,AL    | 35201   |
| Casual           | BURKE     | ROGERS      | Purchase         | 60.33       | 6/1/2011  | 211a          | United States  | Arizona   | Phoenix,AZ       | 85019   |
| Sportswear       | COOLEY    | GARCIA      | Purchase         | 84.84       | 6/1/2011  | 576a          | United States  | Arizona   | Mesa,AZ          | 85876   |

## 🧠 Possible Use Cases

- 📈 **Sales Trend Analysis**: Visualize department-wise or regional sales performance over time
- 🧾 **BI Dashboards**: Create dashboards in tools like Power BI, Databricks SQL, or Tableau
- 👥 **Salesperson Performance**: Evaluate individual or manager contribution to sales
- 📍 **Geospatial Analysis**: Map sales data by ZIP code or state
- 💳 **Customer Segmentation**: Classify purchasing patterns based on departments and amounts

## 📂 File Format

- Format: `.csv`, `.parquet`, or `.delta` (depending on usage)
- Encoding: UTF-8
- Delimiter: Comma (`,`)

## 📍 Getting Started

Use the dataset in Databricks, Pandas, or any data analysis platform:

# 📊 Key Business Questions for Your Sales Dashboard

## 🔹 Sales Performance Metrics

- What is the **total sales revenue by department** this month?
- Which departments have the **highest YoY or MoM growth** in sales?

## 🔹 Sales Team Performance

- Who are the **top 5 salespersons** by total sales amount?
- What is the **average sale per salesperson** by department or store?

## 🔹 Customer Behavior & Transaction Analysis

- What is the **distribution of sales amount** per transaction type?
- What is the **frequency of purchases** by department over time?

## 🔹 AI-Enhanced Insights to Ask Genie

- Which **features most influence high sales** (e.g., department, city, manager)?

## 🔹 Visual Elements to Include in the Dashboard

- **Bar charts**: Sales by Department, Sales by State  
- **Line charts**: Daily/Monthly Sales Trends  
- **Maps**: Sales by Zipcode or City  
- **Heatmaps**: Sales per Department vs State  
- **Tables**: Top 10 Salespersons / Managers / Stores  
- **KPIs**: Total Sales, Avg Sale per Transaction, Number of Transactions  



[▶️ Click here to watch the video](https://youtu.be/v4nt95KW9o0)


![Alt text](demo2.gif)
