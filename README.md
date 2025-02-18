# **CRM Sales Dashboard**

## **📌 Project Overview**  
The **CRM Sales Dashboard** is an advanced analytical tool developed using **Power BI** to assess and optimize sales performance. It provides a comprehensive and interactive interface for tracking key sales metrics, revenue trends, and business insights. The dashboard is designed to empower organizations with data-driven insights for better decision-making, enabling the optimization of sales strategies and improving overall business performance.

---

## **📊 Key Features & Insights**

### **1. Sales Performance Metrics**
- 🔧 **Total Employees:** 396,000  
- 💰 **Total Revenue:** 363M  
- 🏆 **Win Rate:** 57.46%  
- **Average Deal Size:** 22.99  
- **Total Deals Closed:** 4,238  

### **2. Revenue Analysis**
- **Revenue Trend Over Time:** Analyze monthly revenue fluctuations.  
- **Revenue by Account & Regional Office:** Insights into revenue contributions by top accounts and regional offices.  
- **Top 10 Accounts by Revenue:** A ranking of the highest revenue-generating clients.  

### **3. Sales Agent Performance**
- **Total Deals by Deal Stage:** Breakdown of deals by stage: won, lost, engaged, and prospecting.  
- **Top 10 Deals Won by Sales Agent:** Performance analysis of the top-performing sales agents.  
- **Top 5 Sales Agents by Win Rate:** Ranking agents based on the highest deal closure success.  
- **Monthly Revenue vs. Deals Closed:** Analyzing the relationship between revenue and closed deals.

### **4. Sector & Product Performance**
- **Revenue by Sector:** Insights by industry sectors, such as Retail, Technology, Medical, Software, and Finance.  
- **Revenue by Product:** Breakdown of revenue across top-performing products, including **GTX Plus Pro, MG Advanced, and GTK 500**.

---

## **🚀 Dashboard Usage**

1. **Open Power BI Desktop:** Ensure that Power BI Desktop is installed.  
2. **Load the Dashboard:** Open the **.pbix** file to access the CRM Sales Dashboard.  
3. **Interactive Analysis:**  
   - Use built-in filters for customized insights.  
   - Select regional offices, sales agents, and product categories for dynamic visualizations.  
   - Analyze monthly performance through timeline filters.

---

## **📁 Project Structure**

- **Data Cleaning Notebook:** Jupyter notebook for preprocessing raw sales data.  
- **Database Connection Notebook:** Jupyter notebook for data extraction from the CRM database.  
- **Power BI Dashboard:** Interactive **.pbix** file featuring the sales dashboard.

---

## **🛠 Execution Steps**

### **Step 1: Data Cleaning**
- Open the `crm_data_cleaning.ipynb` file.  
- Run the code cells to clean the raw datasets.  
- Save the cleaned data for further use.

### **Step 2: Database Integration**
- Open the `sql_connecting_file.ipynb` file.  
- Update the database credentials in the script.  
- Run the cells to upload the cleaned data to the **MySQL database**.

### **Step 3: Data Visualization**
- Open the `crm_sales_project.pbit` file in **Power BI Desktop**.  
- Connect the template to your database.  
- Refresh the data to view the latest updates on the dashboard.

---

## **🔧 Tools & Technologies**
- **Power BI Desktop:** Advanced data visualization and dashboard creation  
- **Jupyter Notebook:** Data preprocessing and database integration  
- **Python:** Data wrangling and extraction  
- **CRM Database:** Source for sales and performance data  

