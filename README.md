# 📊 Sales Analytics Database Project (MySQL + Superset BI)

This project is a complete **Sales Analytics system** using **MySQL** for database design and **Apache Superset** for business intelligence dashboards. It simulates a real-world sales operation, offering SQL practice, advanced analytics, and visual reporting through dashboards.

---

## 📁 Project Structure

.
├── sales_table_create.sql # SQL script to create schema and tables
├── Sales_analysis_project.sql # SQL analysis queries, views, triggers, functions
├── Sales Store Procedure.sql # Stored procedures and data insertion
├── convert_file_csv.py # Python script to export data to CSV


---

## 🧱 Database Schema

- `customers`: Customer details, segments, location  
- `products`: Product catalog with category, pricing, stock  
- `sales_reps`: Sales personnel with regions and commission rates  
- `orders`: Order transactions with date, delivery, and revenue  
- `order_details`: Line items for each order (product, quantity, pricing)

---

## 🔑 Key Features

- ✅ Complete database schema with foreign keys and sample data  
- 📊 10+ business analysis queries (profit, trend, segmentation)  
- ⚙️ Stored procedures (`Getsalesummery`) and custom functions  
- 🎯 Triggers for stock updates on order  
- 🚀 Indexes for performance optimization  
- 🧪 15+ interview-style SQL exercises  
- 📈 Superset dashboard with MySQL integration

---

## 🚀 Getting Started

### Requirements

- MySQL Server  
- Python 3.x  
- Apache Superset  
- Python packages: `mysql-connector-python`

### Setup Instructions

1. **Create the database and tables**  
   Run: `sales_table_create.sql`

2. **Insert sample data and stored procedures**  
   Run: `Sales Store Procedure.sql`

3. **Run analysis queries, views, and triggers**  
   Run: `Sales_analysis_project.sql`

---

## 📦 CSV Export (Optional)

To export SQL table to CSV:

```bash
python convert_file_csv.py

📊 Superset BI Integration:
Connect Superset to MySQL

URI: mysql://root:root@localhost:3306/sales_analytics

Import tables as datasets

Create visualizations

Daywise and Monthwise Sales

Category-wise Sales

Top Selling Products

Regional Revenue

Sales Rep Performance

Profit Margins

Build dashboard

Combine charts into an interactive dashboard

Apply filters, dropdowns, and time ranges

💡 Highlight Queries:
📦 Inventory vs Sales
🛒 Monthly Sales Trend
💰 Profit Margin by Product
🌍 Geographic Revenue Analysis
🧍 Customer Lifetime Value
📈 Growth & Performance Dashboards
