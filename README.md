
# Dynamic Retail Dashboard on Excel

### Overview

This project is a **Dynamic Retail Dashboard** built entirely in **Microsoft Excel**, designed to provide valuable insights and analytics for retail sales data. The dashboard helps visualize key metrics such as sales performance, profitability, shipping costs, and customer segments across various markets. It allows users to interactively filter and explore the data using slicers and dynamic charts, making it a powerful tool for decision-making in retail environments.

---

### Features

- **Interactive Dashboard**: Easily explore data using slicers to filter by customer segment, region, order priority, and product categories.
- **KPIs and Metrics**: Visualize critical KPIs such as:
  - Total Sales
  - Total Profit
  - Shipping Costs
  - Discounts
- **Dynamic Charts**: Includes five key chart types for comprehensive analysis:
  - **Sales by Region and Market**: Shows regional performance across global markets.
  - **Profitability by Product Category**: Identifies top-performing and underperforming product categories.
  - **Shipping Mode and Sales**: Compares sales and shipping costs across different shipping methods.
  - **Discount Impact on Profit**: Highlights how discounting strategies affect profitability.
  - **Order Priority and Shipping Costs**: Evaluates the relationship between order priority levels and shipping expenses.
- **Data Segmentation**: Detailed breakdown by customer segments (Consumer, Corporate, Home Office) and product categories (Technology, Furniture, Office Supplies).
- **Responsive Design**: The dashboard automatically adjusts charts and figures based on filters, providing real-time insights with a user-friendly interface.

---

### Dataset

The dataset used for this dashboard includes retail sales data with key columns such as:
- **Order ID**: Unique identifier for each order.
- **Order Date & Shipping Date**: Timeline of orders and shipping.
- **Ship Mode**: Shipping method used (Same Day, Second Class, First Class).
- **Customer Information**: Customer ID, Name, Segment, Location.
- **Product Information**: Product ID, Category, Sub-Category, Product Name.
- **Sales, Profit, Discount, Shipping Cost**: Key financial metrics to track the performance of orders.

---

### Use Cases

- **Sales Analysis**: Retail businesses can use this dashboard to identify sales trends across different markets and regions.
- **Profitability Insights**: Explore which product categories and regions are driving profits or losses.
- **Shipping Strategy Optimization**: Track shipping costs and performance across different shipping methods and prioritize cost-efficient strategies.
- **Customer Segmentation**: Analyze customer behavior by segment, region, and product preferences.

---

### How to Use

1. Download the Excel file from the repository.
2. Open the file in **Microsoft Excel** (make sure you enable macros if any are used).
3. Use the slicers to filter and explore the data interactively.
4. Analyze the charts and KPIs to gain insights and make informed decisions.

---

### Requirements

- **Microsoft Excel** (version 2016 or higher recommended for best performance with slicers and dynamic charts).
- Basic knowledge of Excel formulas, charts, and slicers is helpful.

---

To help you structure your GitHub description for the "Dynamic Retail Dashboard on Excel," here’s a proposed format based on your content. This includes objectives, steps, and conclusions:

---


## Objective

The goal of this project is to create a comprehensive dashboard that helps in analyzing retail data, tracking key performance indicators (KPIs), and identifying top and bottom performers in various dimensions. The dashboard is dynamic, allowing users to interact with the data for deeper insights.

### Key Objectives:
1. Track and visualize key KPIs: Total Sales, Total Profit, Quantity Sold, Number of Orders, and Profit Margin.
2. Conduct detailed analysis of sales and profitability across different product categories and regions.
3. Identify top and bottom-performing products, subcategories, and customers.
4. Highlight sales trends over time to observe year-on-year growth.

## Data Used
The dataset includes three primary tables:
1. **Orders**: Contains details such as Order ID, Order Date, Customer Info, Product Info, Sales, Profit, and Shipping Costs.
2. **People**: Represents sales regions and personnel data.
3. **Returns**: Information about returned orders for further analysis.

### Sample Columns from the Orders Table:
- Row ID
- Order ID
- Customer Name
- Segment
- Category & Sub-Category
- Sales, Profit, Discount, Shipping Cost
- Order Priority

## Key Insights Delivered
The dashboard focuses on providing answers to the following business questions:
1. **KPIs**:
    - Total Sales
    - Total Profit
    - Total Quantity
    - Number of Orders
    - Profit Margin
2. **Sales & Profit Analysis**:
    - Segment-wise sales share %
    - Sales by country
3. **Category/Sub-Category Analysis**:
    - Category-wise profit
    - Top 5 sub-categories by sales and profit
    - Bottom 5 sub-categories by sales and profit
4. **Yearly Sales Trends**:
    - Year-over-year sales trends to highlight growth patterns.
5. **Customer Insights**:
    - Return analysis for identifying trends in product returns.
    - Top and Bottom customers by sales volume.

## Steps Involved
### 1. Data Cleaning:
   - Used Excel's **Power Query Editor** to clean and transform raw data from the Orders, People, and Returns tables.
   - Performed data corrections such as adjusting formats and eliminating unnecessary columns.
   
### 2. Data Aggregation:
   - Created metrics such as total sales, profit, quantity, and order count.
   - Added a profitability metric calculated as the difference between sales and total costs.

### 3. KPI Visualization:
   - Used pivot tables to summarize KPIs such as:
      - Total Sales
      - Total Profit
      - Average Discount
      - Total Orders
      - Profitability
   - Custom symbols were used for each KPI for clear visualization.
   
### 4. Dashboard Creation:
   - Built interactive charts and graphs to visualize the data, including bar charts, line graphs, and pie charts for category-wise and country-wise breakdowns.
   - Added filters and slicers to make the dashboard dynamic, allowing for interaction with the data at various levels of granularity.

### 5. Additional Features:
   - **Return Analysis**: Identified returned orders by analyzing the Returns table and linking it with the Orders data.
   - **Customer Analysis**: Highlighted top and bottom customers based on sales volume.

## Conclusion
The **Dynamic Retail Dashboard** is a powerful tool that provides retailers with a clear view of their operational performance. The use of Excel's advanced features like Power Query and pivot tables ensures that data is efficiently processed and displayed in a way that is easy to understand. This dashboard allows businesses to:
- Monitor key performance indicators in real-time.
- Drill down into specific categories, segments, or customers.
- Track return rates and analyze their impact on profitability.
- Identify high-potential customers and areas of improvement for low-performing ones.
