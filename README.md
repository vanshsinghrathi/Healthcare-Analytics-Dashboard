
# 🏥 Hospital Emergency Room Performance Dashboard

<div align="center">

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-Data_Analytics_Project-blue?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Healthcare_Analytics-red?style=for-the-badge)

**An interactive Excel dashboard that transforms raw ER data into actionable insights for hospital administrators.**

[Features](#-key-features) • [KPIs](#-kpis-tracked) • [Charts](#-charts--visualizations) • [Skills Used](#-skills-demonstrated) • [Screenshots](#-dashboard-preview) • [How to Use](#-how-to-use)

</div>

---

## 📌 Project Overview


Emergency Departments operate in high-pressure environments where every second counts. This project involved building a **fully interactive Hospital Emergency Room Performance Dashboard** in **Microsoft Excel** to help healthcare administrators:

- Monitor daily patient volumes and ER efficiency
- Track operational KPIs at a glance
- Analyze patient demographics and department referral patterns
- Make data-driven decisions to improve service quality and reduce wait times

> **Purpose:** Convert raw hospital ER data into a clean, filterable, and visually rich dashboard that gives stakeholders instant visibility into performance trends.

---

## 🖼️ Dashboard Preview

![Hospital ER Dashboard](<img width="1122" height="636" alt="Screenshot 2026-06-28 001310" src="https://github.com/user-attachments/assets/a798dca8-cdda-41d2-b7b6-896a32158347" />

)
> *Hospital Emergency Room Dashboard — May 2024 view with interactive year/month slicers*

| Section | What it Shows |
|---|---|
| Top KPI Cards | Total Patients · Avg Wait Time · Satisfaction Score |
| Admission Status | Admitted vs Not Admitted with % breakdown |
| Age Distribution | Bar chart — patients grouped by age band |
| Department Referrals | Horizontal bar — which departments receive most ER transfers |
| Gender Analysis | Donut chart — Female vs Male split |
| Timeliness Tracker | Donut chart — On-Time vs Delayed patient attendance |

---

## 📊 KPIs Tracked

| KPI | Description | Visual |
|---|---|---|
| **Number of Patients** | Total ER visits per day | Card + Area Sparkline |
| **Average Wait Time** | Mean time (minutes) before a patient sees a professional | Card + Area Sparkline |
| **Patient Satisfaction Score** | Average daily rating out of 5 | Card + Area Sparkline |

Each KPI card includes an **area sparkline** to surface patterns like busy days, seasonal spikes, or dips in satisfaction — instantly, without drilling into raw data.

---

## 📈 Charts & Visualizations

### 1. Patient Admission Status
- **Type:** Horizontal Bar Chart
- **Insight:** Compares admitted vs. not-admitted patients with count and percentage
- **Sample Data:** Not Admitted — 156 (49%) · Admitted — 160 (51%)

### 2. Patient Age Distribution
- **Type:** Clustered Column Chart
- **Insight:** Groups patients into 8 age bands (0–9, 10–19, ..., 70–79) to reveal which age groups use the ER most
- **Sample Peak:** Age group 0–9 with 28 patients

### 3. Gender Analysis
- **Type:** Donut Chart
- **Insight:** Shows the male-female split of ER visitors
- **Sample Data:** Female 47% · Male 53%

### 4. Patients Attended Within Time
- **Type:** Donut Chart
- **Insight:** Tracks the percentage of patients seen within the 30-minute target
- **Sample Data:** On-Time 52% · Delayed 48%

### 5. Department Referrals
- **Type:** Horizontal Bar Chart (sorted descending)
- **Insight:** Identifies which departments receive the highest referral volume from the ER
- **Top Referrals:** None (83) · General Practice (31) · Orthopedics (16)

---

## 🔧 Interactive Features

| Feature | Description |
|---|---|
| **Year Slicer** | Toggle between 2023 and 2024 data instantly |
| **Month Slicer** | Filter by any month (Jan–Dec) — all charts update dynamically |
| **Sparklines** | Mini area charts embedded in KPI cards to show daily trends |
| **Dynamic Labels** | All chart values and percentages update automatically on filter change |

---

## 💡 Skills Demonstrated

### Excel Techniques
- ✅ Pivot Tables & Pivot Charts — for aggregating and summarising raw data
- ✅ COUNTIFS / AVERAGEIFS / SUMIFS — for dynamic KPI calculations
- ✅ Slicers linked to multiple Pivot Tables — for seamless filtering
- ✅ Sparklines (Area type) — embedded trend indicators in KPI cards
- ✅ Conditional Formatting — to highlight key values
- ✅ Named Ranges — for clean and maintainable formulas
- ✅ Chart Formatting — custom colors, labels, and layout for a professional look
- ✅ Dashboard Layout Design — structured, readable, and print-ready

### Analytical Skills
- ✅ KPI identification and requirement gathering
- ✅ Data cleaning and transformation
- ✅ Patient flow and operational efficiency analysis
- ✅ Demographic segmentation (age, gender)
- ✅ Time-based filtering and trend identification

---

## 📁 Project Structure

```
Hospital-ER-Dashboard/
│
├── 📊 Hospital_ER_Dashboard.xlsx      # Main Excel workbook
│   ├── Raw Data Sheet                 # Original dataset
│   ├── Working Sheet                  # Cleaned + calculated data
│   ├── Pivot Tables Sheet             # All pivot aggregations
│   └── Dashboard Sheet                # Final interactive dashboard
│
├── 📸 Screenshots/
│   ├── dashboard_overview.png         # Full dashboard view
│   ├── kpi_requirements.png           # KPI spec reference
│   ├── charts_requirements.png        # Charts spec reference
│   └── project_purpose.png            # Project brief
│
└── 📄 README.md                       # This file
```

---

## 🗂️ Dataset Details

| Field | Description |
|---|---|
| Patient ID | Unique identifier per visit |
| Date | Date of ER visit |
| Patient Age | Age of the patient |
| Patient Gender | Male / Female |
| Wait Time (mins) | Time from arrival to first contact |
| Satisfaction Score | Rating given by patient (1–5 scale) |
| Admission Status | Admitted / Not Admitted |
| Department Referral | Department the patient was referred to |
| Attended Within Time | Whether the patient was seen within 30 mins |

---

## 🚀 How to Use

1. **Download** the `Hospital_ER_Dashboard.xlsx` file
2. **Open** in Microsoft Excel (2016 or later recommended)
3. **Enable editing** if prompted — slicers and pivot charts require this
4. Use the **Year buttons** (2023 / 2024) at the top right to switch between years
5. Click any **Month** in the left panel to filter all charts and KPIs for that month
6. All KPI cards, charts, and percentages will **update automatically**

> 💡 Tip: Click on any chart element to see the underlying pivot table it draws from.

---

## 📋 Requirements

| Tool | Version |
|---|---|
| Microsoft Excel | 2016 or later |
| Operating System | Windows / macOS |
| Macros Required | No |
| External Add-ins | None |

---

## 🎯 Business Impact

This dashboard enables hospital management to:

- **Reduce wait times** by identifying peak hours and high-traffic age groups
- **Improve resource allocation** by knowing which departments need more ER support
- **Track satisfaction trends** and investigate months where scores dropped
- **Monitor admission efficiency** to balance bed availability and triage decisions
- **Present performance reports** to stakeholders without manual data preparation

---

## 👤 Author

**Vansh**
- 🎓 B.Voc. Software Development Student
- 📊 Aspiring Data Analyst
- 🛠️ Skills: Excel · SQL · Python · Data Visualization

---

## 📬 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vansh-rathi-04b485355)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vanshsinghrathi)

---

## 🏷️ Tags

`Excel` `Dashboard` `Healthcare Analytics` `Data Visualization` `KPIs` `Pivot Tables` `Hospital ER` `Business Intelligence` `Data Analytics` `Portfolio Project`

---

<div align="center">

⭐ If you found this project helpful, please consider giving it a star!

*Built with 💙 using Microsoft Excel*

</div>
