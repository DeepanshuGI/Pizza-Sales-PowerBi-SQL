<!-- Project Header -->
<p align="center">
  <img src="images/pizza_logo.png" alt="Pizza Sales Analysis" width="200"/>
</p>

<h1 align="center">Pizza Sales Analysis Dashboard</h1>

<p align="center">
  <a href="#"><img alt="Power BI" src="https://img.shields.io/badge/Built%20With-Power%20BI-blue"></a>
  <a href="#"><img alt="SQL" src="https://img.shields.io/badge/Backend-SQL-lightgrey"></a>
  <a href="#"><img alt="Status" src="https://img.shields.io/badge/Status-Active-success"></a>
</p>

<p align="center">
  This project provides an <b>interactive dashboard</b> and <b>SQL-based analysis</b> for Pizza Sales.  
  It helps track KPIs, analyze trends, and identify top-selling products.
</p>

<hr/>

<h2>📦 Repository Contents</h2>

<ul>
  <li><code>Pizza Sales Report.pbix</code> — Power BI dashboard file</li>
  <li><code>pizza_sales.csv</code> — Raw dataset used for analysis</li>
  <li><code>pizza_sales_excel_file.xlsx</code> — Excel version of the dataset</li>
  <li><code>PIZZA SALES SQL QUERIES.docx</code> — SQL queries for key KPIs & insights</li>
  <li><code>images/</code> — Exported charts & dashboard preview</li>
</ul>

<h2>🧭 Project Overview</h2>

<p>
This project analyzes pizza sales performance using SQL and Power BI.  
Key performance indicators (KPIs) such as Total Revenue, Average Order Value, and Top Pizzas by Sales are tracked to help improve business decision-making.
</p>

<h2>✨ Key Insights</h2>

<ul>
  <li>Total Revenue & Orders over time</li>
  <li>Top & bottom 5 pizzas by sales and quantity</li>
  <li>Sales breakdown by category and size</li>
  <li>Monthly and daily order trends</li>
  <li>Average pizzas per order</li>
</ul>

<h2>📸 Dashboard Preview</h2>

<p align="center">
  <img src="images/pizza_dashboard.png" alt="Pizza Sales Dashboard" width="800"/><br/>
  <em>Interactive Power BI Dashboard for Pizza Sales</em>
</p>

<h2>🛠️ Tools & Technologies</h2>

<ul>
  <li><b>Power BI</b> — Data visualization & KPI reporting</li>
  <li><b>SQL</b> — Data extraction & analysis (queries included)</li>
  <li><b>Excel/CSV</b> — Data storage & transformation</li>
</ul>

<h2>🚀 How to Run</h2>

<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/&lt;your-username&gt;/pizza-sales-dashboard.git</code></pre>
  </li>
  <li>Open <code>Pizza Sales Report.pbix</code> in Power BI Desktop</li>
  <li>Review SQL queries in <code>PIZZA SALES SQL QUERIES.docx</code></li>
  <li>Explore datasets (<code>pizza_sales.csv</code> or <code>pizza_sales_excel_file.xlsx</code>)</li>
</ol>

<h2>📈 Sample SQL Queries</h2>

<pre><code>
-- Total Revenue
SELECT SUM(total_price) AS Total_Revenue FROM pizza_sales;

-- Average Order Value
SELECT (SUM(total_price) / COUNT(DISTINCT order_id)) AS Avg_Order_Value FROM pizza_sales;
</code></pre>

<h2>📌 Future Enhancements</h2>

<ul>
  <li>Automate dashboard refresh with SQL database connection</li>
  <li>Integrate Python for predictive sales analysis</li>
  <li>Deploy dashboard to Power BI Service</li>
</ul>

<h2>👤 Author</h2>

<p>
<strong>Your Name</strong><br/>
<a href="mailto:your.email@example.com">your.email@example.com</a> · 
<a href="https://www.linkedin.com/in/your-link">LinkedIn</a> · 
<a href="https://github.com/your-username">GitHub</a>
</p>

<hr/>

<p align="center">
  <sub>© {YEAR} Your Name. For educational and portfolio purposes.</sub>
</p>
