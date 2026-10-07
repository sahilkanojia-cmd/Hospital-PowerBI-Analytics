# 🏥 Hospital Power BI Analytics

## 📌 Project Overview

This project presents an interactive **Hospital Analytics Dashboard built using Microsoft Power BI**.

The objective of the project is to analyze hospital admissions, patient demographics, departmental performance, clinical operations, patient satisfaction, readmissions, billing, insurance coverage, and revenue trends.

The project uses a structured healthcare dataset containing **6 interconnected tables** and demonstrates data modeling, KPI development, DAX-based analysis, and interactive dashboard design.

---

## 🛠️ Tools & Technologies

* **Power BI**
* **Microsoft Excel**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Data Visualization**

---

## 🗂️ Dataset Structure

The dataset contains 6 tables:

### Fact Tables

* `Fact_Admissions`
* `Fact_Billing`

### Dimension Tables

* `Dim_Patient`
* `Dim_Doctor`
* `Dim_Department`
* `Dim_Date`

The model follows a **star-schema approach**, connecting admission and billing information with patient, doctor, department, and date dimensions.

---

## 📊 Dashboard Pages

### 1. Executive Overview

Provides a high-level view of hospital performance, including:

* Total Admissions
* Total Revenue
* Average Length of Stay
* Patient Satisfaction
* 30-Day Readmission Rate
* Admissions by Department
* Top Diagnoses
* Monthly Revenue Trends
* Revenue by Admission Type

### 2. Clinical & Operations

Analyzes:

* Admissions by Age Group and Gender
* Department Performance
* Monthly and Daily Admission Patterns
* Top Diagnoses
* Doctor Experience vs Patient Satisfaction
* Operational KPIs

### 3. Financials

Analyzes:

* Revenue trends
* Monthly revenue changes
* Revenue breakdown
* Insurance vs Patient Payable
* Revenue by Insurance Provider
* Top Doctors by Revenue
* Payment performance

---

## 🔑 Key Insights

* The hospital recorded **14,000 admissions** with approximately **₹109.94 Cr in total billing**.
* **Oncology generated the highest revenue at approximately ₹33.28 Cr**, making it the largest revenue-generating department.
* **General Medicine recorded the highest number of admissions with 2,798 cases**.
* Oncology had the highest average length of stay at approximately **10.18 days**.
* Oncology also recorded the highest 30-day readmission rate at approximately **19.12%**, indicating a potential area for clinical and operational improvement.
* Approximately **22% of bills were either pending or partially paid**, highlighting an opportunity to improve payment collection.
* Hospital revenue decreased by approximately **2.34% from 2024 to 2025**.
* Overall patient satisfaction was approximately **3.96/5**.

---

## 📈 Business Recommendations

Based on the analysis:

1. Investigate the high readmission rate in Oncology and identify potential causes.
2. Review patient-flow and bed utilization in departments with longer average stays.
3. Improve follow-up processes for pending and partially paid bills.
4. Monitor the decline in year-over-year revenue and identify the factors driving the decrease.
5. Continue monitoring patient satisfaction across departments to identify service-quality improvement opportunities.

---

## 🎯 Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Data Modeling
* Star Schema Design
* Power Query
* DAX
* KPI Development
* Healthcare Analytics
* Financial Analytics
* Interactive Dashboard Design
* Business Insight Generation
* Data Storytelling

---

## 📁 Repository Structure

```text
Hospital-PowerBI-Analytics/
│
├── README.md
│
├── Data/
│   └── Hospital_PowerBI_Data.xlsx
│
├── PowerBI/
│   └── Hospital_Analysis_Dashboard.pbix
│
├── Dashboard/
│   ├── Executive_Overview.png
│   ├── Clinical_Operations.png
│   └── Financials.png
│
└── Documentation/
    └── Hospital_Analytics_Project.pdf
```

---

## 👤 Author

**Sahil Kanojia**

Aspiring Data Analyst | Power BI | SQL | Excel | Python

---

⭐ If you found this project useful, feel free to explore the dashboard and analysis.

