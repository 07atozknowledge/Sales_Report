# Sales_Report
Sales Report of XYZ company

# 📊 Sales Report Dashboard (Power BI)

A comprehensive Power BI dashboard for analyzing company sales performance by region, product, and time period.

## 📁 File Included
- `Sales_Report.pbix` – Power BI report file

## 📊 Key Report Pages

### 1. Sales Overview
- Total Revenue: ₹2.5 Cr
- Monthly Sales Trend
- Region-wise Revenue Contribution
- KPIs: Total Orders, Average Order Value, Total Units Sold

### 2. Product Analysis
- Top-Selling Products
- Revenue per Product Category
- Profitability by Product
- Filters: Category, Sub-category

### 3. Customer Insights
- New vs Returning Customers
- Customer Lifetime Value
- High-value customer segments

### 4. Regional Performance
- Sales Heatmap by Region
- Revenue Growth by Zone
- Regional Discount Impact

## 🧮 Measures & DAX
- `Total Sales = SUM(Sales[Amount])`
- `Avg Order Value = [Total Sales] / DISTINCTCOUNT(Sales[OrderID])`
- `Customer Count = DISTINCTCOUNT(Customers[CustomerID])`
  

## Insights and Recommendations
🔹 Revenue Trends

There is strong sales growth in Q2 and Q3 with a noticeable dip in Q4.

MoM revenue showed a 12% increase from June to July, with a decline observed from November onward.

🔹 Regional Performance

The Western Region contributed the highest revenue (35% of total).

The Eastern Region has underperformed with only 12% share, indicating potential for expansion or deeper analysis.

🔹 Product Category Analysis

The "Electronics" category accounted for over 45% of the total sales, making it the best-performing category.

"Home Appliances" had low returns despite promotions—consider re-evaluating marketing strategies or pricing.

🔹 Customer Segmentation

Top 10 customers contributed 40% of the revenue—concentration risk.

Consider diversifying the customer base or offering loyalty rewards to top customers.

🔹 Recommendations

Focus on the underperforming Eastern region with targeted campaigns.

Analyze Q4 sales drop—possible factors: supply issues, market saturation, or seasonal effects.

Push successful products like Electronics further with bundled deals or cross-selling.

Strengthen retention strategies for high-value customers and identify churn risks.

🚀 Getting Started
To explore or edit the report:

Open the Sales_Report.pbix file using Power BI Desktop.

Use the slicers to explore different regions, time frames, or categories.

Review trends and KPIs on the main dashboard for actionable insights.
