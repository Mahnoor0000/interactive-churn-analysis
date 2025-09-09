# Churn Analysis with Interactive Plotly Dashboards

##  Overview
This project explores **customer churn** using an interactive and visual-first approach. Instead of just static plots, it leverages **Plotly** to build dashboards that allow filtering, switching features, and exploring customer behavior in detail.  

The notebook contains:
- **Exploratory Data Analysis (EDA)**
- **Feature engineering** (`BalanceToSalary` ratio)
- **Interactive visualizations** to understand churn patterns  



---

##  Main Plotly Dashboards

### 1️ Balance vs Salary Scatter (with churn filter)
An interactive scatter plot:
- **X-axis:** Estimated Salary  
- **Y-axis:** Account Balance  
- **Color-coded:** Retained vs Churned customers  
- **Hover tooltips:** Geography, Gender, Age, Products, Activity status  
- **Dropdown filter:** View *All*, *Retained*, or *Churned* customers  

👉 This helps visualize whether balance and salary distributions differ between churned and retained customers.

---

### 2️ Feature Comparison by Churn (Box Plot with dropdown)
An interactive box plot that compares **different features** across churn status:
- **X-axis:** Customer status (*Retained* vs *Churned*)  
- **Y-axis:** Selectable feature (Credit Score, Age, Tenure, Balance, Number of Products, Estimated Salary, or Balance-to-Salary ratio)  
- **Dropdown menu:** Switch feature dynamically  

👉 This allows quick comparisons of feature distributions and highlights which factors might influence churn.

---


**Insight:**  
- Churned customers have slightly lower **Credit Scores**.  
- Churn is more frequent in middle-aged groups (~35–45).  
- Customers with **2+ products** are less likely to churn, showing loyalty effect.
