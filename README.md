[hospital_README.md](https://github.com/user-attachments/files/27466095/hospital_README.md)
# 🏥 Hospital Patient Analytics — SQL (PostgreSQL)

An end-to-end SQL analysis project on a hospital dataset with 7,500+ patient records. The project uncovers actionable insights around treatment costs, ICU utilisation, doctor performance, and patient diagnosis patterns — helping hospital management make data-driven operational decisions.

---

## 🔍 Problem Statement

Hospital administrators needed deeper visibility into their operations to answer critical business questions:
- Which cities are generating the highest treatment costs?
- Which doctors are contributing the most revenue?
- How is ICU capacity being utilised by high-severity patients?
- What are the most common diagnoses across different age groups?
- How do treatment costs trend across months?

---

## 📁 Dataset Overview

| Field | Details |
|---|---|
| Total Records | 7,500+ patient entries |
| Domain | Healthcare Analytics |
| Tables Used | Patients, Diagnosis, Treatment, Bed Allocation |
| Database | PostgreSQL |

---

## 🛠️ SQL Concepts Applied

| Concept | Usage |
|---|---|
| **JOINs** (INNER, LEFT) | Linking patient, diagnosis, treatment, and bed tables |
| **Aggregations** | SUM, COUNT, AVG for cost and occupancy analysis |
| **CASE Statements** | Categorising patients by severity and age group |
| **Subqueries** | Filtering high-cost treatments and ICU load |
| **Window Functions** | RANK(), ROW_NUMBER() for doctor revenue ranking and cost trends |
| **CTEs** | Breaking complex queries into readable steps |
| **GROUP BY / HAVING** | Region and doctor-level summaries with filters |

---

## 📊 Key Business Insights

- 🏙️ **Top 5 cities by treatment cost** identified — enabling targeted resource allocation
- 🛏️ **ICU occupancy analysis** revealed high-severity patient load trends — supporting capacity planning
- 👨‍⚕️ **Doctor-wise revenue ranking** built using window functions — highlighting top performers
- 📅 **Monthly cost trends** uncovered seasonal spikes in treatment expenditure
- 🔬 **Most common diagnoses by age group** identified — supporting preventive care programs

---

## 💡 Business Recommendations

1. **Allocate more resources to top-cost cities** — treatment burden is concentrated in specific regions
2. **Plan ICU capacity proactively** — high-severity patient trends are predictable by month
3. **Recognise and retain top-revenue doctors** — ranking data shows clear performance gaps
4. **Design age-specific health programs** — diagnosis patterns differ significantly across age groups
5. **Investigate monthly cost spikes** — irregular spending months need deeper root cause analysis

---

## 🗂️ Project Structure

```
hospital-patient-analytics-sql/
│
├── queries/
│   ├── top_cities_by_cost.sql
│   ├── icu_occupancy_analysis.sql
│   ├── doctor_revenue_ranking.sql
│   ├── monthly_cost_trends.sql
│   └── diagnosis_by_age_group.sql
│
├── dataset/
│   └── hospital_data.csv
│
└── README.md
```

---


---

## 👨‍💻 Author

**Rohit Yadav**
Data Analyst | Mumbai, India
📧 ry809509@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/rohit-yadav-03babb232)

