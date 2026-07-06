# Project 4 - Sales Performance Dashboard | Power BI

## 📌 Project Overview

This project focuses on building an interactive Sales Performance Dashboard using Microsoft Power BI. The dashboard transforms raw e-commerce transaction data into meaningful business insights through interactive visualizations, KPI tracking, and data storytelling.

The objective was not only to visualize the data but also to follow best practices of executive dashboard design, enabling decision-makers to identify trends, monitor business performance, and make informed decisions.

---

## 🎯 Objectives

- Analyze overall sales performance
- Monitor key business KPIs
- Identify top-performing products
- Evaluate customer acquisition channels
- Analyze payment method preferences
- Track order status distribution
- Measure coupon usage
- Present actionable business recommendations

---

## 🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel

---

## 📂 Dataset Information

The dashboard uses the cleaned e-commerce dataset prepared during Project 1.

The dataset contains:

- Order ID
- Order Date
- Customer ID
- Product
- Quantity
- Unit Price
- Total Price
- Order Status
- Payment Method
- Referral Source
- Coupon Code

---

# 📈 Dashboard Features

### Executive KPI Cards

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Average Quantity per Order

---

### Interactive Filters

- Year
- Product
- Order Status
- Payment Method
- Referral Source
- Coupon Code

---

### Visualizations

- Revenue Trend Analysis
- Revenue by Product
- Order Status Distribution
- Payment Method Analysis
- Referral Source Performance
- Coupon Usage
- Monthly Revenue Heatmap
- Top 5 Products by Quantity
- Business Insights & Recommendations

---

# 📊 Key Business Insights

- Total Revenue reached **$1.26M** across **1,200 orders**.
- Printers generated the highest revenue, followed closely by Laptops.
- Instagram was the strongest customer acquisition channel.
- Payment methods were evenly distributed, indicating flexible customer preferences.
- Average Order Value remained above **$1K**, demonstrating high-value transactions.

---

# 💡 Business Recommendations

- Prioritize inventory for Printers and Laptops.
- Increase marketing investment on Instagram.
- Maintain multiple payment options.
- Promote larger basket sizes through targeted campaigns.

---

# 🧮 Important DAX Measures

```DAX
Total Revenue =
SUM('Dataset'[TotalPrice])
```

```DAX
Total Orders =
COUNT('Dataset'[OrderID])
```

```DAX
Total Customers =
DISTINCTCOUNT('Dataset'[CustomerID])
```

```DAX
Average Order Value =
DIVIDE([Total Revenue],[Total Orders])
```

```DAX
Average Quantity / Order =
AVERAGE('Dataset'[Quantity])
```

---

# 📌 Dashboard Design Principles

The dashboard was designed following professional Business Intelligence practices:

- Executive-friendly layout
- Minimal chart clutter
- Interactive slicers
- Consistent color palette
- KPI-first storytelling
- Actionable business insights
- Clean and responsive visual hierarchy

---

# 🚀 Learning Outcomes

Through this project I learned:

- Data modeling in Power BI
- Interactive dashboard development
- DAX calculations
- KPI design
- Business storytelling
- Executive dashboard layout
- Interactive filtering
- Insight generation
- Data visualization best practices
