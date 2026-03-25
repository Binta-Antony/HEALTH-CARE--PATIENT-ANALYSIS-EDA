# 🏥 Healthcare Patient Analysis - EDA

## 📊 Project Overview
This project performs an in-depth **Exploratory Data Analysis (EDA)** on healthcare patient data to uncover patterns, trends, and insights related to patient care, hospital operations, and financial performance.

The analysis focuses on understanding key factors such as **medical conditions, hospital stay duration, billing amounts, and resource utilization** to support data-driven decision-making.

---

## 🎯 Objectives
- Analyze patient data to identify meaningful patterns  
- Understand factors affecting hospital stay duration  
- Explore relationships between medical conditions and billing  
- Evaluate hospital performance and resource usage  
- Generate actionable insights for healthcare improvement  

---

## 🧾 Dataset
The dataset includes information such as:
- Patient demographics (Age, Gender)  
- Medical conditions  
- Admission & discharge dates  
- Hospital and doctor details  
- Insurance provider  
- Billing amount  
- Test results  

📌 *Dataset source: Kaggle (Healthcare Dataset)*

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔍 Data Analysis Process

### 1. Data Exploration
- Checked dataset structure and data types  
- Identified missing values and duplicates  
- Reviewed statistical summaries  

### 2. Data Preprocessing
- Converted date columns to datetime format  
- Created new features:
  - **Stay Duration** (Discharge - Admission)
  - **Revenue per Day**
- Handled inconsistent data  

### 3. Feature Engineering
- Created age groups using `pd.cut()`  
- Extracted time-based features (month, season)  

### 4. Exploratory Data Analysis
- Univariate analysis (distributions)  
- Bivariate analysis (relationships)  
- Correlation analysis  

---

## 📈 Key Insights
- Certain medical conditions lead to longer hospital stays  
- Higher stay duration is directly linked to increased billing  
- Insurance providers show variations in total revenue contribution  
- Seasonal trends impact admission rates  
- Abnormal test results are associated with longer recovery periods  

---

## 📊 Visualizations
- Bar charts (billing by condition)  
- Heatmaps (stay duration vs age group & condition)  
- Line plots (yearly trends)  
- Scatter plots (relationships between variables)  

---

## 💡 Business Implications
- Optimize hospital resource allocation  
- Improve partnerships with insurance providers  
- Focus on high-cost medical conditions  
- Enhance patient care strategies based on data insights  

---

## 🚀 Future Improvements
- Apply machine learning models for prediction  
- Use real-time healthcare data  
- Build interactive dashboards (Power BI / Tableau)  

---

## 📌 Conclusion
This project demonstrates how **EDA transforms raw healthcare data into meaningful insights**, helping hospitals improve operational efficiency and patient outcomes.

---

## 👩‍💻 Author
**Binta Antony**  
MSc Data Science, AI & Digital Business  
