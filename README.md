# 📊 Sales Data Analysis Project

## 📌 Project Overview
This project focuses on analyzing a **sales dataset (`sales_csv`)** to extract meaningful business insights using **Python** and **Power BI**. The analysis involves data cleaning, manipulation, exploratory data analysis (EDA), and visualization to understand sales performance, profitability, and customer behavior.

The goal of this project is to answer key business questions such as:
- How sales and profit change over time
- Which product categories and sub-categories perform best
- How customer segments contribute to sales and quantity
- Overall performance metrics like **AOV (Average Order Value)**

---

## 🛠️ Tools & Technologies Used

### 🔹 Development & Analysis
- **VS Code**
- **Jupyter Notebook Extension**
- **Python**
  - Pandas
  - NumPy
  - Matplotlib / Seaborn

### 🔹 Visualization
- **Power BI**
  - Interactive dashboards
  - KPIs and charts for business insights

---

## 📂 Dataset
- **File Name:** `sales_csv`
- **Description:**  
  The dataset contains sales transaction records including:
  - Order Date  
  - Sales  
  - Profit  
  - Quantity  
  - Category  
  - Sub-Category  
  - Segment
  - Region

---

## 🔄 Data Analysis Workflow

### 1️⃣ Data Loading
- Imported the CSV file into Jupyter Notebook using Pandas
- Inspected data structure, data types, and summary statistics

### 2️⃣ Data Cleaning
- Handled missing (NaN) values
- Converted columns to appropriate data types
- Removed duplicate records
- Renamed and reordered columns for clarity

### 3️⃣ Data Manipulation & Feature Engineering
- Grouped data by:
  - Month
  - Category
  - Sub-Category
  - Segment
- Calculated:
  - Total Sales
  - Total Profit
  - Total Quantity
  - **AOV (Average Order Value)**

### 4️⃣ Exploratory Data Analysis (EDA)
- Analyzed trends and patterns in sales and profit
- Compared performance across categories and segments
- Studied monthly and category-wise distributions

### 5️⃣ Visualization (Power BI)
- Designed dashboards to visualize:
  - Profit by Month
  - Sales by Sub-Category
  - Sum of Quantity by Segment
  - Category-wise Sales
  - KPIs for Sales, Profit, Quantity, and AOV

---

## 📈 Key Insights Extracted

- 📅 **Profit by Month**  
  Identified monthly trends and peak profit periods.

- 🧾 **Sales by Sub-Category**  
  Determined top-performing and low-performing sub-categories.

- 👥 **Sum of Quantity by Segment**  
  Found which customer segments purchase the highest quantity.

- 🗂️ **Category-wise Sales Performance**  
  Compared total sales across different product categories.

- 📊 **Overall Business Metrics**
  - Total Sales
  - Total Profit
  - Total Quantity Sold
  - **Average Order Value (AOV)**

---

## Business Recommendations

- **Adopt a balanced category strategy:**  
  All product categories contribute almost equally to overall sales. This indicates a well-diversified portfolio, and the business should continue focusing on all categories rather than prioritizing a single one.

- **Strengthen high-profit sub-categories:**  
  *Binders* are the most profitable sub-category, followed by *Phones* and *Bookcases*. These sub-categories should be prioritized through better inventory planning, targeted promotions, and potential bundling strategies to maximize profitability.

- **Improve low-performing sub-categories:**  
  *Laptops* are identified as the least profitable sub-category. Further analysis is recommended to identify underlying issues such as pricing strategy, discounting, or cost structure, and to take corrective actions accordingly.

- **Boost sales during low-performing months:**  
  Sales performance in **April** and **July** is comparatively lower. Focused marketing campaigns, seasonal offers, or promotional strategies during these months could help improve overall sales performance.


## ❓ Questions a Data Analyst Asks Before Analysis

- What is the objective of the analysis?
- What business problem are we trying to solve?
- What does each column represent?
- What is the time range of the data?
- Are there missing or inconsistent values?
- Are there duplicate records?
- Which KPIs are important for stakeholders?

---

## ❓ Questions a Data Analyst Asks During Analysis

- Which months generate the highest and lowest profit?
- Which sub-categories contribute the most to sales?
- Which customer segment buys the highest quantity?
- Does higher sales always result in higher profit?
- How does AOV vary across segments and categories?
- Are there seasonal trends in sales or profit?
- Which categories need optimization or improvement?

---

## 📊 Dashboard & Results
The final insights are presented using **Power BI dashboards**, making the analysis interactive and easy to understand for business stakeholders.



## 🚀 Conclusion
This project demonstrates the complete **data analysis lifecycle**—from raw data to actionable insights—using **Python for data analysis** and **Power BI for visualization**. The findings help in understanding sales performance, customer behavior, and profitability trends.

---

## 📎 Future Improvements
- Implement sales forecasting models
- Perform customer-level analysis
- Add advanced DAX measures and KPIs

---

## 📬 Author
**Roshan**  
Data Analysis Enthusiast | Python | Power BI
