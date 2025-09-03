# 🚗 Electric Vehicle Data Analysis Project ⚡

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellowgreen)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange)
![SciPy](https://img.shields.io/badge/SciPy-Statistics-lightgrey)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> A complete **Data Science project** on Electric Vehicles, covering **data cleaning, outlier detection, correlation analysis, recommendation systems, and hypothesis testing**.  
> The project demonstrates how **data-driven insights** can support both **customers** and **businesses** in the EV market.  

---

## 📌 Project Overview
Electric Vehicles (EVs) are transforming the automobile industry.  
This project analyzes an EV dataset to answer **real-world customer and business questions**, such as:  

- Which EVs are best for a given budget and range?  
- How do battery capacity and range correlate?  
- Are there any unusual (outlier) energy consumption patterns?  
- How can we recommend the **Top 3 EVs** to a customer?  
- Is there a significant difference in **engine power** between Tesla and Audi?  

---

## 🛠️ Tech Stack
- **Python 3.9**
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy  
- **Jupyter Notebook**  

---

## 📊 Tasks Completed

### 🔹 Task 1: EV Filtering & Grouping
- Filtered EVs by **budget ≤ 350,000 PLN** and **range ≥ 400 km**  
- Grouped by manufacturer (**Make**)  
- Calculated **average battery capacity** per manufacturer  

📈 *Result:* Tesla and Audi lead in high battery capacities within this segment.  

---

### 🔹 Task 2: Outlier Detection
- Checked **mean energy consumption [kWh/100km]** using the IQR method  
- ✅ Found **no major outliers**  

📈 *Result:* EV energy consumption data is consistent.  

---

### 🔹 Task 3: Correlation Analysis
- Scatterplot: **Battery capacity vs Range** → strong positive correlation  
- Heatmap: Correlations across power, torque, weight, and range  

📈 *Result:* Larger battery capacity → longer driving range.  

---

### 🔹 Task 4: EV Recommendation System
- Built a **rule-based recommendation system** (class-based)  
- Criteria: Price, Range, Battery  
- Returns **Top 3 EVs** with visualization  

📈 *Result:*  
- Tesla Model 3 (Long Range, Performance) → performance + range  
- Volkswagen ID.3 Pro S → budget-friendly, efficient option  

---

### 🔹 Task 5: Hypothesis Testing
- **Two-sample T-test**: Tesla vs Audi (Engine Power)  
- Result: *p = 0.117 (> 0.05)* → ❌ Fail to reject H₀  

📈 *Conclusion:* No significant difference in average engine power →  
Tesla & Audi compete equally on **engine performance**.  

---

## 📊 Key Insights
- **Battery capacity** is the strongest driver of EV range.  
- **No unusual outliers** in energy consumption.  
- **Tesla dominates performance**, but **Audi is competitive in power**.  
- **Volkswagen** offers strong **cost-efficiency**.  
- Customers should evaluate **range, charging speed, and price** — not just horsepower.  

---

## ✨ Author
👤 **Aman Kumar Yadav**  
📧 amanyadav32327@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/aman-kumar-yadav-32327) | [GitHub](https://github.com/amanyadav32327)
