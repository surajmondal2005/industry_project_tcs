# Retail Sales Performance Analysis

## 📌 Objective
The objective of this project is to analyze retail sales data to identify trends, understand customer behavior, and build an interactive dashboard for business insights.

## 🛠️ Tools & Technologies Used
- Python (Pandas, NumPy, Scikit-learn)
- Power BI
- Jupyter Notebook

## 📊 Data Preprocessing
- Removed duplicate records  
- Handled missing values using forward fill  
- Standardized column names  
- Converted date column into datetime format  

## ⚙️ Feature Engineering
- Created Month, Day, Quarter from date  
- Created Age Groups for demographic analysis  
- Calculated Total Amount (Quantity × Price per Unit)  

## 🤖 Machine Learning
K-Means Clustering was used to segment customers based on:
- Quantity purchased  
- Total transaction value  

### Segments Identified:
- Cluster 0 → Low-value customers  
- Cluster 1 → Medium-value customers  
- Cluster 2 → High-value customers  

## 📈 Dashboard (Power BI)
The interactive dashboard includes:
- Sales Trend (monthly performance)
- Sales by Product Category
- Sales by Gender
- Customer Segmentation (clusters)
- Key KPIs (Total Sales, Average Sales, Total Quantity)

## 🔍 Key Insights
- Electronics category generates the highest revenue  
- Sales show variation across months indicating seasonal trends  
- Female customers contribute slightly more than male customers  
- Majority of customers fall in mid-value spending segment  
- High-value customers identified using clustering  

## 📁 Files Included
- industry_project.py → Python preprocessing and ML code  
- final_sales_data.csv → Cleaned dataset used in dashboard  
- industryproject.ipynb → Jupyter notebook (optional)  
- Power BI Dashboard (.pbix)  

## 🚀 Future Scope
- Implement real-time data integration  
- Use advanced ML models for prediction  
- Build recommendation systems for customers  
- Deploy dashboard on cloud platforms  
