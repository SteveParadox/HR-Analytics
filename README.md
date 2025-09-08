
# 📊 HR Analytics & Attrition Prediction  

## 🔎 Project Overview  
Employee retention is one of the biggest challenges for modern organizations. High attrition increases hiring costs, lowers morale, and disrupts business continuity.  

In this project, I analyzed a dataset of **2M+ employee records** to:  
- Clean and transform HR data with **Python & Pandas**.  
- Discover workforce insights through **Exploratory Data Analysis (EDA)**.  
- Predict employee **attrition probability** using **Machine Learning**.  
- Design an interactive **Power BI Dashboard** for HR leaders.  

💡 This project demonstrates how **data-driven HR analytics** can empower organizations to identify at-risk employees, optimize hiring, and improve retention.  

---

## 🗂️ Dataset
**Fields used (`export_cols`)**:  
- 👤 Employee info → Employee_ID, Full_Name, Department, Job_Title  
- 🌍 Geography → Country, Location  
- 📅 Hire info → Hire_Date, Tenure_Years, Experience_Years  
- ⭐ Performance → Performance_Rating  
- 💼 Job status → Status (Active, Resigned, Retired), Work_Mode  
- 💰 Compensation → Salary_INR, Salary_Lakhs  
- 🔮 Predictions → Attrition_Flag, Attrition_Probability  

---

## 🛠️ Workflow  

### 1. **Data Preparation (Python / Pandas)**  
- Loaded and cleaned 2M+ rows (removed nulls, handled outliers).  
- Normalized categorical values (`Status`, `Work_Mode`).  
- Engineered key features: `Tenure_Years`, `Attrition_Flag`.  

### 2. **Exploratory Data Analysis (EDA)**  
- Workforce status distribution (Active, Resigned, Retired).  
- Department headcount & salary comparisons.  
- Hiring trends over time.  
- Attrition % by department, tenure, and work mode.  

### 3. **Predictive Modeling (ML)**  
- Built **Logistic Regression & XGBoost models** to predict resignation probability.  
- Achieved robust accuracy with ensemble methods.  
- Generated `Attrition_Probability` for each employee.  

### 4. **Power BI Dashboard**  
- Designed interactive visuals for HR executives:  
  - KPIs → Total Employees, Active, Resigned, Retired, Attrition Rate.  
  - Donut chart → Status distribution.  
  - Bar chart → Department headcount.  
  - Line chart → Hiring trends (new hires vs cumulative workforce).  
  - Heatmaps → Attrition risk across tenure and department.  
  - Maps → Country-level workforce spread.  
  - Predictive Insights → Attrition probability segmentation.  

---

## 📊 Dashboard Preview  
*(Insert screenshot of Power BI dashboard here)*  

---

## 🎯 Key Insights  
- **Overall Attrition Rate:** X% of employees resigned.  
- **High-Risk Departments:** Certain functions (e.g., IT, Marketing) showed higher resignation trends.  
- **Salary Fairness Gap:** Remote employees had lower average salaries compared to on-site employees.  
- **Tenure Effect:** Employees within **1–3 years** tenure had the highest attrition risk.  
- **Performance vs Attrition:** Some high performers still had high attrition probabilities → a red flag for HR strategy.  

---

## 🚀 Business Impact  
If applied in a real organization, this project could:  
- Reduce attrition by **identifying high-risk employees early**.  
- Improve salary fairness and retention strategies.  
- Support HR leaders with **data-driven decision-making**.  
- Save significant costs in hiring, training, and lost productivity.  

---

## 🔧 Tools & Tech Stack  
- **Python** → Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Machine Learning** → Logistic Regression, XGBoost  
- **Power BI** → Interactive dashboard for storytelling  
- **SQL (optional)** → For querying and slicing workforce data  

---

## 📂 Repository Structure  
```
HR-Analytics-Attrition/
│── data/              # dataset (HR_cleaned.csv)
│── notebooks/         # Jupyter notebooks for data prep & EDA
│── models/            # ML model training scripts
│── dashboard/         # Power BI .pbix file
│── README.md          # project documentation
```

---

## 🏆 Why This Project Matters  
This project demonstrates my ability to:  
✔ Handle **large datasets (2M+ records)** efficiently.  
✔ Extract actionable **business insights** through analytics.  
✔ Apply **machine learning** to real-world HR problems.  
✔ Build executive-ready **dashboards for decision-making**.  

---

## 📬 Let’s Connect  
💼 [LinkedIn](https://www.linkedin.com/)  
💻 [GitHub](https://github.com/SteveParadox)  
✉️ fordstphn@gmail.com  

---

🔥 *“In God we trust. All others must bring data.”* – W. Edwards Deming  
