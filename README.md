# 📊 Sales Insights Dashboard  

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" alt="Pandas" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="NumPy" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" alt="Matplotlib" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" width="40" height="40"/>
  <img src="https://img.icons8.com/color/48/000000/ms-excel.png" alt="Excel" width="40" height="40"/>
</p>  

An interactive **data analysis project** that uncovers key business insights from an **E-commerce dataset** using **Python, Excel, and SQL**. The project simulates a **Business Analyst / Data Analyst workflow** — from data cleaning and exploration to building an interactive dashboard for decision-making.  

---

## 📌 Project Overview
The goal of this project is to help businesses track sales performance, identify customer behavior patterns, and recommend strategies for growth.  

Key objectives:  
- Clean and preprocess raw transactional sales data  
- Perform **exploratory data analysis (EDA)** using Python (pandas, matplotlib, seaborn)  
- Build **KPI-driven dashboards** in Excel for interactive insights  
- Write **SQL queries** for deeper business insights
- Apply **RFM analysis** for customer segmentation  

---

## 🗂 Dataset
- **Name:** Online Retail Dataset  
- **Size:** ~500,000 rows  
- **Fields:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country
- **Original Dataset (Raw):** [UCI Machine Learning Repository – Online Retail](https://archive.ics.uci.edu/ml/datasets/online+retail)  
- **Cleaned Dataset (CSV):** [View on Kaggle](https://www.kaggle.com/datasets/navvyaa/online-retail-dataset-cleaned-csv)  

The cleaned dataset removes nulls, canceled orders, and formatting issues, and is used in this analysis.  

---

## 🔍 Key Insights
- **Top Countries by Revenue (excluding UK)** – Identified the most profitable regions  
- **Monthly Revenue Trends** – Clear seasonality in sales behavior  
- **Top Products** – Most demanded products by sales quantity  
- **Order Frequency per Customer** – Customer engagement and loyalty analysis  
- **Customer Segmentation (RFM Analysis)** –  
   - 🟢 Loyal Customers – High frequency & high monetary value  
   - 🟡 At-Risk Customers – Long recency, low frequency  
   - 🔵 Big Spenders – High monetary, moderate frequency  
   - 🔴 Churned Customers – No recent activity  
- **KPI Summary** – Total Revenue, Unique Customers, Total Orders, and Time Period covered  

---

## 📊 RFM Analysis
We performed **Recency, Frequency, Monetary (RFM) analysis** to segment customers based on purchasing behavior.  

- **Recency (R):** Days since last purchase  
- **Frequency (F):** Number of orders per customer  
- **Monetary (M):** Total spend by customer  

👉 [Download RFM Analysis Results (CSV)](analysis/rfm_analysis.csv)  
  

---

## 📊 Dashboard (Excel)
Designed an **interactive Excel dashboard** with slicers and visualizations:  
- Bar chart for top-selling products  
- Line chart for monthly revenue trends  
- Pie chart for customer segments  
- Order frequency analysis per customer  
- KPI cards for Revenue, Customers, Orders, and Period  

---

## 🛠 Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **Excel:** Pivot Tables, Slicers, Interactive Charts  
- **SQL (MySQL):** Querying cleaned dataset for business insights  
- **Other:** GitHub for version control  

---

## 🚀 How to Run
1. Clone this repository  
```bash
   git clone https://github.com/navvvyyaa/Sales-Insights-Dashboard.git
   cd Sales-Insights-Dashboard
```
2. Install dependencies
```bash
   pip install -r requirements.txt
```
3. Open the notebook
```bash
   jupyter notebook Sales_Insights.ipynb
```
4. Open **Sales_Insights_Dashboard.xlsx** in Excel for the dashboard  
5. Run SQL queries in **Sales_Insights_Analysis.sql** using MySQL Workbench  

---

## 📜 SQL Analysis
A set of SQL queries is included in `Sales_Insights_Analysis.sql` to extract meaningful insights such as:  
- Top 10 countries by revenue  
- Monthly sales growth trends  
- Most frequently purchased products  
- Customer segmentation and loyalty patterns  

(You can run these queries on the cleaned dataset imported into MySQL)  

---

## 📝 Future Improvements
- Automating dashboard refresh with Power BI / Tableau  
- Expanding SQL queries for deeper business insights  
- Predictive analytics using ML models
- Deploying dashboard for business users

---

## 👩‍💻 Author
**Navya Bagga**  
- LinkedIn: [linkedin.com/in/navvvyyaa](https://linkedin.com/in/navvvyyaa)  
- Email: navyabagga18@gmail.com  

---

✨ This project showcases my ability to work with **real-world datasets**, extract **business insights**, perform **RFM segmentation** and present findings effectively through **dashboards, SQL queries, and reports**.
