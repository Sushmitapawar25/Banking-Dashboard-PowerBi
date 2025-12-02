# 🏦 Banking Analytics Dashboard  
*An end-to-end data analytics project using Python, SQL, and Power BI.*

---

## 📌 Project Overview  
This project analyzes banking customer behavior and loan performance using a complete analytics workflow.  

I performed data cleaning and EDA using **Python**, validated and analyzed data using **SQL**, and built an interactive **Power BI dashboard** for decision-making.  

The dashboard helps banking teams understand:  
- Customer demographics  
- Loan trends  
- Approval vs. rejection patterns  
- Income vs. loan behavior  
- Risk insights (safe vs risky customers)

---

## 🛠 Tech Stack  
| Step | Technology |
|------|-----------|
| Data Cleaning | Python (Pandas, NumPy) |
| Exploratory Data Analysis | Python (Matplotlib, Seaborn) |
| Database | MySQL / SQL Server |
| Data Validation & Analytics | SQL |
| Visualization | Power BI |
| Modeling (optional) | DAX Measures |

---

## 📂 Folder Structure  
Banking-Dashboard/
│
├── data/
│ ├── banking_raw.csv
│ ├── banking_cleaned.csv
│
├── python/
│ ├── EDA.ipynb
│ ├── data_cleaning.py
│
├── sql/
│ ├── schema.sql
│ ├── cleaning_queries.sql
│ ├── analysis_queries.sql
│
├── powerbi/
│ ├── Banking_Dashboard.pbix
│ ├── dashboard_screenshots/
│
└── README.md

---

## 🔍 Project Workflow  
### **1️⃣ Data Cleaning (Python)**  
- Removed missing / inconsistent values  
- Fixed data types  
- Encoded categorical columns  
- Derived new fields (Loan-to-Income Ratio, Risk Category)  
- Exported cleaned dataset for SQL  

### **2️⃣ Data Storage & Analysis (SQL)**  
- Loaded cleaned dataset into MySQL  
- Created database schema  
- Performed SQL analysis:  
  - Loan approval rate  
  - Average income by education  
  - Customers by region  
  - Loan amount by marital status  
  - Risk segmentation  
  - Loan purpose distribution  

### **3️⃣ Dashboard Development (Power BI)**  
- Connected SQL database to Power BI  
- Created multi-page dashboard containing:  
  - KPI Cards  
  - Donut charts  
  - Stacked bar charts  
  - Line charts  
  - Matrix table  
- Added slicers for dynamic filtering  
- Applied formatting for clean UI  

---

## 📊 Dashboard Pages  

### 🏠 **1. Home Page**
- Total Customers  
- Total Loan Amount  
- Loan Approval %  
- Income Distribution  
- Gender Split  
- Loan by Education  

### 💳 **2. Loan Insights Page**
- Loan Status (Approved vs Rejected)  
- Average Loan Amount by Education  
- Loan Purpose  
- Income vs Loan Comparison  
- Risk Category  

### 👤 **3. Customer Demographics Page**
- Age Group Distribution  
- Marital Status  
- Region-wise Customers  
- Education Level  

---

## 📈 Key Business Insights  
✔ Graduates contribute to the highest loan amounts.  
✔ Married applicants show lower default risk.  
✔ Male customers apply for more loans than female.  
✔ Urban and semi-urban regions have higher loan approval.  
✔ Customers aged **25–35** are the most active in banking.  

---

## 💡 What This Project Demonstrates  
- Ability to work on **real-world end-to-end analytics projects**  
- Strong skills in **Python, SQL, and Power BI**  
- Data cleaning, preparation, and visualization  
- Ability to explain business insights to stakeholders  
- Designing professional dashboards  

---


