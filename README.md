# HR Analytics Dashboard & Attrition Analysis

## 📌 Project Overview
This project aims to develop a dynamic **HR Analytics Dashboard** to support data-driven HR decisions. The analysis focuses on employee **demographics**, **departmental structures**, **income trends**, and especially **attrition patterns** to guide actionable strategies for improving **employee retention** and **organizational planning**.

---

## 🛠️ Tools & Technologies
- **Microsoft Excel**: Data cleaning and summary statistics  
- **Power BI**: Interactive dashboards with slicers and visuals  

---

## 📁 Data Source
- **File**: `HR ANALYTICS.xlsx`  [download](https://github.com/user-attachments/files/20454088/HR.ANALYTICS.xlsx)
- **PowerBI** `HR ANALYTICS.pbix` [download]

- **Records**: 1,470 employee entries  
- **Features**: Age, Gender, Department, Education, Monthly Income, Job Role, Attrition, etc.

---

## 🧹 Data Cleaning & Preparation
- Removed duplicates and standardized column headers
- Filled missing values (`Education`, `Previous Year Rating`) using **mode**
- Grouped age into bands: `18–25`, `26–35`, `36–45`, `46–60`
- Created new Measures:
  - **Attrition Rate** = `(Attrition Count / Total Employees) × 100`
  - **Active Employees** = `Total Employees - Attrition`
  - **Total Monthly Income** = `SUM(DATA[Monthly Income])`
- Standardized categorical variables
- Verified numerical columns for outliers and inconsistencies

---

## 📊 Exploratory Data Analysis (EDA)

### 👥 Workforce Metrics
- **Total Employees**: 1,470  
- **Attrition**: 237  
- **Active Employees**: 1,233  
- **Attrition Rate**: 16.1%

### 🧬 Demographics
- **Gender**:  
  - Male: 882 (60%)  
  - Female: 588 (40%)
- **Departments**:  
  - R&D: 961  
  - Sales: 446  
  - HR: 63
- **Age Bands**:  
  - 25-34: 554  
  - 35-44: 505  
  - 45-54: 245  
  - Under 25: 97
  - Over 55: 69
- **Marital Status**:  
  - Single: 470  
  - Married: 673  
  - Divorced: 327
- **Job Roles**: 9 unique roles (e.g., Sales Executive, Research Scientist)
- **Education Levels**: Mostly Bachelor’s and Master’s degrees

### 💰 Income & Compensation
- **Monthly Income**:  
  - Highest for **Managers**  
  - Lowest for **Sales Executives** and **Lab Technicians**
- **Monthly Rate**:  
  - Generally consistent across roles, suggesting standard pay scales

---

## 📈 Key Insights & Analysis

### 🔍 Attrition Drivers
- Highest attrition in:
  - **Age Group**: 25–34  
  - **Department**: Sales
- Strongly associated with:
  - **Single marital status**
  - **Lower income**
  - **Shorter tenure**
  - **No awards or unmet KPIs**

### 🧠 Department & Education Trends
- **Sales & R&D** show highest volume and attrition levels
- Employees in **Life Sciences** and **Medical** fields are most common

### 💼 Job Role & Pay Analysis
- **Managers** earn the most  
- **Sales Executives** and **Lab Technicians** show lower pay and higher attrition

---

## 🧩 Interactive Dashboard Features
![Screenshot 2025-05-18 132115](https://github.com/user-attachments/assets/4d4696ec-5410-43f2-a61d-32ceb95db442)


**Power BI Slicers** enable drill-downs by:
- **Education Field** (e.g., Life Sciences, Marketing)
- **Department** (Sales, R&D, HR)

---

## ✅ Recommendations

### 1. Retention Strategy for Sales & R&D
- Conduct exit interviews  
- Review manager effectiveness and workload balance

### 2. Support for 25–36 Age Group
- Create mentorship programs  
- Provide clear career growth paths

### 3. Review Low-Income Roles
- Benchmark salaries  
- Reevaluate increment policies for high-attrition roles

### 4. Engage Single Employees
- Promote social activities and support groups  
- Encourage work-life balance

### 5. Use Dashboards for Targeted Decisions
- Filter insights using **Education Field**, **Department**, and **Job Role**

---

## ⚠️ Limitations
- No qualitative feedback (e.g., exit interviews, job satisfaction surveys)
- No time-based data (e.g., salary history, training impact)
- Dataset is static—no real-time updates or events
- External factors (e.g., economic conditions, family events) not considered

---

## 📌 Conclusion
The overall **attrition rate is 16.1%**, highest among **Sales employees** and those aged **25–36**. Factors like **low income**, **short tenure**, and **lack of rewards** contribute significantly. Targeted **retention strategies**, improved **engagement initiatives**, and **compensation reviews** are essential for reducing attrition. The **interactive dashboard** empowers HR teams to derive actionable insights and tailor interventions effectively.

---

## 📁 Additional Assets (Optional)
- 📊 Power BI Dashboard (with slicers by Department, Education, Job Role)  

---

> 📬 *Feel free to reach out if you’d like help building the Power BI dashboard, Python scripts, or a presentation deck!*
