# 🚗 Automobile Sales Analysis Project  
**SQL & Excel Data Analytics Project**

---

## 📊 Overview  
The **Automobile Sales Analysis Project** leverages **SQL** and **Microsoft Excel** to extract, analyze, and visualize key insights from automobile sales data.  
It focuses on understanding overall sales trends, customer behavior, and product category performance.  
This project demonstrates how data querying and Excel dashboards can together deliver **data-driven business insights** for decision-making.

---

## 🎯 Key Features  
- **SQL-Based Data Analysis** – Used SQL queries to calculate KPIs such as total revenue, total products sold, and average order value.  
- **Sales Trend Analysis** – Explored monthly and yearly sales performance using SQL time-based grouping.  
- **Customer Insights** – Identified top 5 customers contributing to maximum sales volume.  
- **Category Performance** – Analyzed percentage sales by product category and deal size.  
- **Excel Dashboard** – Built an interactive Excel dashboard with charts and pivot tables for visualization.

---

## 🛠️ Tools & Technologies  

| Tool / Technology | Purpose |
|--------------------|----------|
| **SQL (MS SQL Server)** | Data querying and KPI calculation |
| **Microsoft Excel (.xlsm)** | Dashboard design and visualization |
| **Pivot Tables & Charts** | Sales and customer trend analysis |
| **Automobile Sales Dataset** | Source data for analysis |

---

## 🧠 SQL Queries Used  

| Metric | Description | SQL Query |
|---------|--------------|------------|
| **Total Revenue** | Calculates overall revenue | `SELECT SUM(TOTAL_PRICE) AS TOTAL_REVENUE FROM sales_data;` |
| **Total Orders** | Distinct orders processed | `SELECT COUNT(DISTINCT ORDER_ID) AS TOTAL_ORDERS_SOLD FROM sales_data;` |
| **Total Products Sold** | Number of units sold | `SELECT SUM(QUANTITY) AS TOTAL_PRODUCT_SOLD FROM sales_data;` |
| **Monthly Trend** | Orders per month | `SELECT DATEPART(MONTH, ORDERDATE), COUNT(DISTINCT ORDER_ID) FROM sales_data GROUP BY DATEPART(MONTH, ORDERDATE);` |
| **Top 5 Customers** | Highest product purchases | `SELECT TOP 5 CUSTOMERNAME, SUM(QUANTITY) FROM sales_data GROUP BY CUSTOMERNAME ORDER BY SUM(QUANTITY) DESC;` |

---

## 📈 Insights Highlight  
- **Total Revenue:** ₹ *calculated via SQL query*  
- **Top Product Category:** *Clasic cars*  
- **Top 5 Customers:** Identified based on total quantity sold  
- **Monthly Sales Trend:** Consistent increase during festive months  
- **Deal Size Performance:** Medium and large deals contributed most to revenue  


---

## 🧩 File Information  

| File Name | Description |
|------------|-------------|
| `Automobile Sales Report.docx` | Contains SQL queries and KPI documentation |
| `Automobile sales.xlsm` | Excel workbook with dashboard and dataset |
| `Automobile_Sales_Chart.png` | Dashboard visualization image |

---

## 💡 Objective  
To demonstrate the use of **SQL for backend data analysis** and **Excel for visualization**, providing meaningful insights into automobile sales performance.

---

## 🚀 How to Use  
1. Open the `.xlsm` file in **Microsoft Excel**.  
2. Enable macros when prompted.  
3. Explore the dashboard visuals and pivot charts.  
4. Review SQL queries from the `.docx` file.  
5. Run SQL queries in your database to reproduce key metrics.

---

## 🖼️ Dashboard Preview  
<img width="1311" height="700" alt="ASP dashboard" src="https://github.com/user-attachments/assets/c2ed3b8b-ba52-414e-b7ca-7b8d9c80ad18" />


---

## 📬 Contact  
**Author:** Hanumesh S K  
📧 **Email:** [hanumeshkumbar060@gmail.com](mailto:hanumeshkumbar060@gmail.com)  
💼 **LinkedIn:** [linkedin.com/in/hanumesha-s-k-9a62ba289](https://linkedin.com/in/hanumesha-s-k-9a62ba289)

---

## 🏁 Conclusion  
This project highlights the power of combining **SQL for analytics** and **Excel for business visualization**.  
It demonstrates strong **data handling, query design, and dashboard creation** skills — an essential part of any data analyst or business intelligence portfolio.

⭐ *If you found this project helpful, don’t forget to star the repository!*


