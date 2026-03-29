# 📊 Sync or Sink — Student Performance Analysis

is a data-driven project that explores how data can determine success or failure. By analyzing and visualizing datasets, the project aims to reveal hidden insights, support strategic decisions, and help teams stay in sync with their objectives.


## 🗂️ Project Overview

**Sync or Sink** is a business intelligence project built with **Microsoft Power BI** that dives deep into student performance data. The project transforms raw academic data into meaningful visualizations and KPIs, helping educators and administrators identify trends, track student progress, and pinpoint areas that need attention.

---

## 🌟 Data Model — Star Schema

The project is built on a well-structured **Star Schema** to ensure optimal performance and clean relationships between tables.

```
                          Dim_Student
                               |
Dim_StudyBehavior ── Fact_StudentPerformance ── Dim_AIUsage
```

| Table | Type | Description |
|-------|------|-------------|
| `Fact_StudentPerformance` | Fact Table | Core table containing assignment scores, final score, improvement rate, last exam score, pass status, performance category, and study hours |
| `Dim_Student` | Dimension | Student details (student_id, age, gender, grade_level) |
| `Dim_StudyBehavior` | Dimension | Student behavior data (attendance, class participation, sleep hours, social media hours, study consistency index, study hours per day, tutoring hours) |
| `Dim_AIUsage` | Dimension | AI-related usage metrics (ai_dependency_score, ai_ethics_score, and more) |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Data modeling, DAX measures & visualizations |
| **Star Schema** | Data warehouse design pattern |
| **DAX** | Custom measures and calculated columns |

---

## 📈 Key Features

- ✅ Clean **Star Schema** data model with proper relationships
- ✅ Interactive dashboards for performance tracking
- ✅ KPIs for grades, pass rates, and subject performance
- ✅ Time-based analysis using Date dimension
- ✅ Drill-through capabilities for detailed student insights

---

## 🚀 Getting Started

### Prerequisites
- Microsoft Power BI Desktop (latest version)

### Steps
1. Clone this repository
   ```bash
   git clone https://github.com/mahmoudtarek10/Sync_or_Sink.git
   ```
2. Open the `.pbix` file in **Power BI Desktop**
3. Explore the data model under the **Model View**
4. Interact with the dashboards in **Report View**

---

## 👥 Team
Mahmoud Tarek Hassan (Leader)

Fares Hesham Mahmoud

Shahd Hassan Ahmed  

Salma Mohamed Elhwary  

shahd Mohamed Elnahas 

---

## 📄 License

This project is for educational purposes only.

# INSTRUCTOR:
Eng: Kareem Bakly
