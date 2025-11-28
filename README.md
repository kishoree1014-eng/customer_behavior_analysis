# 📊 **Customer Shopping Behavior – Data Analytics Project**

## 📝 **Overview**
This project provides a complete end-to-end data analytics workflow using the **Customer Shopping Behavior** dataset.  
The main objective is to understand customer purchasing patterns, analyze sales performance, and uncover behavior trends that influence revenue.

The project includes:
- 🐍 Python-based exploratory data analysis (EDA) and data cleaning  
- 🗄️ SQL analysis using MySQL Server  
- 📊 Interactive Power BI dashboard  
- 📄 Analytical report  
- 🎤 Presentation created using Gamma  

---

## 📂 **Dataset**
- **Name:** Customer Shopping Behavior  
- **Source:** Online  
- **Rows:** ~3,900  
- **Columns:** 19  
- **Description:** Includes customer demographics, purchase attributes, subscription status, product categories, review ratings, payment types, and shipping preferences.

---

## 🛠️ **Tools and Technologies**
- 🐍 Python (Pandas, NumPy, Seaborn, Matplotlib)  
- 💻 Jupyter Notebook / VS Code  
- 🗄️ MySQL Server  
- 📊 Power BI Desktop  
- 🎨 Gamma App  
- 🌐 GitHub  

---

## 🚀 **Project Steps**

### 🔹 **1. Load Data in Python**
- Loaded dataset using Pandas  
- Checked structure, data types, missing values  
- Initial inspection of inconsistencies  

### 🔹 **2. Exploratory Data Analysis (EDA)**
- Analyzed customer age distribution and purchase behavior  
- Identified top and low-performing product categories  
- Examined subscription behavior impact  
- Explored relationships (age group vs revenue, category vs sales)  
- Checked correlations between purchase amount, reviews, and previous purchases  
- Generated visualizations (bar charts, histograms, heatmaps, boxplots)

### 🔹 **3. Data Cleaning**
- Filled numerical missing values with **averages**  
- Filled categorical missing values with **mode** or **Unknown**  
- Removed duplicates  
- Standardized text formatting  
- Corrected inconsistent category names  
- Converted columns to correct data types  
- Detected and treated outliers  
- Created new fields: age groups, revenue metrics  

### 🔹 **4. SQL Analysis (MySQL Server)**
Performed essential SQL analysis:
- Customer behavior (new vs returning, subscription patterns)  
- Sales metrics (revenue by category, avg purchase amount)  
- Rating checks (satisfaction levels, top-rated categories)

SQL operations:
- `GROUP BY`, `ORDER BY`, `HAVING`  
- Aggregations (`SUM`, `COUNT`, `AVG`)  
- Filtering with `WHERE`  
- Joins for cross-table analysis  

---

## 📊 **Power BI Dashboard**
The dashboard includes:

- 🟣 Subscription status breakdown  
- 🟦 Revenue by category  
- 🟦 Sales by category  
- 🟩 Revenue by age group  
- 🟩 Sales by age group  

### **KPIs**
- 👥 **Number of Customers:** 3.9K  
- 💰 **Average Purchase Amount:** $59.76  
- ⭐ **Average Review Rating:** 3.75  

---

## 🔍 **Insights**

### ⭐ **1. Subscription Behavior**
- Only **27%** of customers are subscribed.  
- Subscribed customers show **higher purchase frequency and revenue**.

### 📦 **2. Category Performance**
- **Accessories** and **Clothing** dominate revenue.  
- Low-performing categories offer opportunities for improvement.

### 👨‍👩‍👧 **3. Age Group Trends**
- Middle-aged customers generate **the most revenue**.  
- Younger customers prefer trend-based categories.

### 💳 **4. Purchase Amount Trends**
- Average purchase amount: **$59.76**  
- Higher-rated customers tend to be **repeat buyers**.

### ⭐ **5. Ratings Overview**
- With an average rating of **3.75**, overall satisfaction is moderate.

---


---

## ⚙️ **How to Run**

### ✅ **Prerequisites**
- Python 3.8+  
- MySQL Server  
- Power BI Desktop  
- Gamma account (optional)

### ▶️ **Steps**
1. Clone the repository:
    git clone <your-github-repo-link>


2. Install dependencies:
    pip install -r requirements.txt


3. Run the notebook:
    jupyter notebook

4. Load cleaned data into MySQL and run SQL scripts.

5. Open the `.pbix` file in Power BI to view the dashboard.

6. Review the report and Gamma presentation in the `outputs` folder.

---
