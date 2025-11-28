# **Customer Shopping Behavior – Data Analytics Project**

## **Overview**
This project provides a complete end-to-end data analytics workflow using the **Customer Shopping Behavior** dataset.  
The goal is to understand customer purchasing patterns, evaluate sales performance, analyze product categories, and identify behavior trends that influence revenue.

The project includes:
- Python-based exploratory data analysis (EDA) and data cleaning  
- SQL analysis using MySQL Server  
- An interactive Power BI dashboard  
- A final analytical report  
- A presentation created using Gamma  

---

## **Dataset**
- **Name:** Customer Shopping Behavior  
- **Source:** Online  
- **Rows:** ~3,900  
- **Columns:** 19  
- **Description:** Contains customer demographics, purchase details, subscription status, product categories, review ratings, payment information, and shipping preferences.

---

## **Tools and Technologies**
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Jupyter Notebook / VS Code**  
- **MySQL Server**  
- **Power BI Desktop**  
- **Gamma App**  
- **GitHub**  

---

## **Project Steps**

### **1. Load Data in Python**
- Imported the dataset using Pandas  
- Reviewed dataset structure, data types, and initial observations  
- Identified missing values and potential inconsistencies  

### **2. Exploratory Data Analysis (EDA)**
- Analyzed age distribution, customer segments, and purchasing behavior  
- Identified top-performing and low-performing product categories  
- Examined subscription status impact on purchase frequency  
- Analyzed relationships such as:
  - Age group vs revenue  
  - Category vs sales  
- Checked correlations between key variables (purchase amount, review rating, previous purchases)  
- Created visualizations (histograms, boxplots, bar charts, heatmaps)

### **3. Data Cleaning**
- Filled numerical missing values using **average values**  
- Filled categorical missing values using **mode** or **"Unknown"**  
- Removed duplicate records  
- Corrected inconsistent category names  
- Standardized string formatting (lowercase, trimmed spaces)  
- Converted columns to correct data types  
- Detected and handled outliers  
- Created new calculated fields (age groups, revenue indicators)

### **4. SQL Analysis (MySQL Server)**
Performed SQL queries including:
- Customer behavior analysis (new vs returning, subscription effects)  
- Sales analysis (revenue by category, average purchase amount)  
- Rating checks (top-rated categories, satisfaction scores)

SQL operations included:
- `GROUP BY`, `ORDER BY`, `HAVING`  
- Aggregations (`SUM`, `AVG`, `COUNT`)  
- Filtering (`WHERE`)  
- Joins for cross-table insights  

---

## **Power BI Dashboard**
The dashboard includes the following key visuals:

- **Percentage of customers by subscription status**  
- **Revenue by category**  
- **Sales by category**  
- **Revenue by age group**  
- **Sales by age group**  

### **Key Performance Indicators (KPIs)**
- **Number of customers:** 3.9K  
- **Average purchase amount:** $59.76  
- **Average review rating:** 3.75  

The dashboard provides clear visibility into revenue trends, customer segments, category performance, and behavior patterns.

---

## **Insights**

### **1. Subscription Behavior**
- Only **27%** of customers are subscribed.  
- Subscribed customers contribute **higher revenue** and show more frequent purchasing.

### **2. Category Performance**
- **Accessories** and **Clothing** are top revenue-generating categories.  
- Some categories have lower engagement, indicating room for targeted promotions.

### **3. Age Group Trends**
- Middle-aged customers show the **highest purchase activity and revenue contribution**.  
- Younger customers purchase more trend-based items.

### **4. Purchase Amount Patterns**
- The **average purchase amount is $59.76**.  
- Customers with higher review ratings often make **repeat purchases**.

### **5. Ratings Overview**
- The average rating of **3.75** suggests moderate customer satisfaction.

---


## **How to Run**

### **Prerequisites**
- Python 3.8+  
- MySQL Server  
- Power BI Desktop  
- Gamma account (optional)

### **Steps**
1. Clone the repository:

    git clone <your-github-repo-link>


2. Install the required Python libraries:

    pip install -r requirements.txt


3. Run the Jupyter Notebook:

    jupyter notebook


4. Load the cleaned dataset into MySQL and run the SQL scripts in the `sql/` folder.  

5. Open the Power BI file (`.pbix`) to interact with the dashboard.  

6. Review the report and presentation in the `outputs/` folder.  
