# 📱 Power BI Dashboard: Mobile Sales Analytics

## 🧭 Overview
This dashboard provides a comprehensive analysis of mobile phone sales transactions, customer behavior, and brand performance. It is designed to help sales teams, product managers, and analysts gain insights into top-performing models, customer preferences, and regional sales trends.

---
### Dashboard Link : C:\Users\abhis\OneDrive\Documents\moblie_data.pbix



## 📂 Dataset Description

| Column Name         | Description |
|---------------------|-------------|
| `Transaction ID`    | Unique identifier for each transaction |
| `Day`, `Month`, `Year`, `Day Name` | Date components of the transaction |
| `Brand`             | Mobile brand (e.g., Samsung, Apple) |
| `Units Sold`        | Number of units sold per transaction |
| `Price Per Unit`    | Selling price per unit |
| `Customer Name`     | Name of the customer |
| `Customer Age`      | Age of the customer |
| `City`              | City where the transaction occurred |
| `Payment Method`    | Mode of payment (e.g., Credit Card, UPI) |
| `Customer Ratings`  | Rating given by the customer |
| `Mobile Model`      | Specific model of the mobile phone |

---

## 📊 Dashboard Features

### 🔹 Slicers
- **Mobile Model**
- **Payment Method**
- **Brand**

### 🔹 KPI Cards
- **💰 Total Profit** → `(Units Sold × Price Per Unit) - Cost` *(if cost is available or assumed)*
- **📦 Total Units Sold** → `SUM(Units Sold)`
- **🛒 Total Sales** → `SUM(Units Sold × Price Per Unit)`
- **📈 Average Sale Price** → `AVERAGE(Price Per Unit)`

### 🔹 Visuals
- **🗺️ Map: City-wise Sales & Profit**
  - Shows geographic distribution of sales and profit
- **📊 Matrix: Brand vs Total Sales**
  - Cross-tab view of brand performance
- **📍 Region-wise Transaction Summary**
  - Aggregated metrics by city or region
- **🏆 Top 3 Selling Mobile Models**
  - Based on total units sold
- **⭐ Ratings Distribution**
  - Customer satisfaction status
- **💸 Top & Least Profitable Models**
  - Ranked by profit
- **👤 Top Customers by Profit & Sales**
  - Based on total purchase value
- **📉 Least Performing Transactions**
  - Transactions with lowest sales or profit

### 🔁 Time Intelligence
- **📅 MTD (Month-to-Date) Total Sales**
- **📅 MTD Profit**
  - Automatically updates based on selected month

---

## 🔧 Interactivity & Features
- **📑 Bookmarks**: Predefined views for quick navigation
- **🔄 Refresh Button**: Ensures latest data is loaded
- **🔍 Cross-Check Capability**: Drill-through enabled to validate KPIs with raw transaction data

---

## 👥 Intended Audience
- Sales & Marketing Teams
- Product Managers
- Business Analysts
- Retail Operations

---

## 🚀 How to Use

1. Open the dashboard in Power BI Desktop or Service.
2. Use slicers to filter by brand, model, or payment method.
3. Review KPI cards for high-level metrics.
4. Explore visuals to identify trends and top performers.
5. Use bookmarks to switch between views.
6. Click on cities or models to drill into detailed data.
7. Refresh the dashboard to load the latest transactions.

---

## 📎 Notes
- Ensure data is refreshed regularly to maintain accuracy.
- Sensitive customer information should be anonymized before sharing externally.
- Ratings and profit calculations may require assumptions if cost data is unavailable.

---

## 📬 Contact
For questions, feedback, or collaboration, please reach out to:

**Dashboard Owner**: Abhishek kumar 
**Email**: abhisheksingh782795@gmail.com
**Team**: Data Analytics / Sales Intelligence

