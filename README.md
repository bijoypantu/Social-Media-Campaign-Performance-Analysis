<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,28&height=220&section=header&text=📱%20Social%20Media%20Campaign&fontSize=42&fontColor=ffffff&fontAlignY=35&desc=Performance%20Analysis%20%7C%20SQL%20%2B%20Tableau&descSize=20&descAlignY=55&animation=fadeIn" width="100%"/>

<br/>

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-27AE60?style=for-the-badge)
![RWFD](https://img.shields.io/badge/Challenge-RWFD%20S04D01-e6377a?style=for-the-badge)

</div>

---

## 📌 Project Overview

This project analyzes **synthetic social media campaign data** to evaluate platform and campaign performance across key metrics — reach, engagement, conversions, cost, and revenue. The goal is to identify which platforms and campaigns deliver the best ROI, and what factors drive performance.

The analysis was completed as part of the **Real World Fake Data (RWFD) S04D01** challenge, and the final Tableau dashboard is published on Tableau Public.

---

## 🗂️ Repository Structure

```
Social-Media-Campaign-Performance-Analysis/
│
├── 📁 data/
│   ├── 📁 raw/                    ← Original, untouched source dataset
│   └── 📁 cleaned/                ← Processed & analysis-ready data
│
├── 📁 sql/                        ← SQL scripts for cleaning & KPI calculation
│
├── 📁 dashboard/
│   └── 📊 Social_Media_Campaign_Performance.twbx
│
├── 📁 assets/                     ← Icons, images & dashboard screenshots
│
└── 📄 README.md
```

---

## 🎯 Objectives

- 📊 Evaluate **platform performance** across reach, engagement, conversions & revenue
- 💰 Calculate key KPIs — **Conversion Rate, CTR, CPC, and ROI** — at campaign & platform level
- 🔍 Compare **spend vs. revenue** to identify the most ROI-efficient platforms
- 🧩 Analyze performance drivers — **audience mix, boosted content & sentiment correlation**
- 📈 Build a clean, interactive **Tableau dashboard** for business stakeholders

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|:-----|:--------|
| ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | Data cleaning, validation & KPI computation |
| ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) | Interactive dashboard & data storytelling |

---

## 🔍 Methodology

### 1️⃣ Data Cleaning & Validation (SQL)
- Cleaned and validated synthetic social media campaign dataset
- Handled nulls, duplicates, and standardized categorical fields (platform names, campaign types)
- Ensured data integrity before KPI computation

### 2️⃣ KPI Computation (SQL)
Calculated the following metrics at both **campaign level** and **platform level**:

| KPI | Formula |
|:----|:--------|
| **Conversion Rate** | `Conversions / Clicks × 100` |
| **CTR** (Click-Through Rate) | `Clicks / Impressions × 100` |
| **CPC** (Cost Per Click) | `Total Spend / Clicks` |
| **ROI** (Return on Investment) | `(Revenue - Spend) / Spend × 100` |

### 3️⃣ Tableau Dashboard
Built a two-page interactive dashboard:
- **Overview** — High-level performance across platforms and campaigns
- **Performance Drivers** — Deep-dive into audience mix, boosted content, and sentiment correlation

---

## 🎨 Dashboard Color Palette

<div align="center">

| Color | Role | Hex |
|:------|:-----|:----|
| 🩷 Pink | Primary / Brand | `#e6377a` |
| 🟢 Green | Positive / Growth | `#43aa8b` |
| 🔴 Red | Negative / Loss | `#ff6b6b` |
| 🔵 Teal | Headings / Labels | `#3f9aa8` |

</div>

---

## 📊 Dashboard Preview

### Overview
[![Overview](https://github.com/bijoypantu/Social-Media-Campaign-Performance-Analysis/raw/main/Icons%20&%20Images/Overview.png?raw=true)](https://public.tableau.com/app/profile/bijoy.pantu/viz/SocialMediaCampaignPerformanceRWFDS04D01/Overview)

### Performance Drivers
[![Performance Drivers](https://github.com/bijoypantu/Social-Media-Campaign-Performance-Analysis/raw/main/Icons%20&%20Images/Performance%20Drivers.png?raw=true)](https://public.tableau.com/app/profile/bijoy.pantu/viz/SocialMediaCampaignPerformanceRWFDS04D01/Overview)

---

## 💡 Key Insights

| 💡 Finding | 📝 Detail |
|:----------|:---------|
| 🏆 Top ROI Platform | Identified the platform returning the highest revenue per dollar spent |
| 📉 Underperformers | Campaigns with high spend but low conversion rate flagged for review |
| 🚀 Boosted Content | Boosted posts showed significantly higher CTR vs. organic content |
| 😊 Sentiment Impact | Positive sentiment correlated with higher conversion rates |
| 👥 Audience Mix | Certain audience segments drove disproportionate revenue share |

---

## 🖱️ How to Use the Dashboard

- Navigate between **Overview** and **Performance Drivers** tabs
- **Hover** over charts to reveal detailed tooltips
- Click the **ⓘ info** buttons for contextual explanations
- Use the **month filter** to track campaign performance over time

---

## 🚀 How to Explore This Project

**Option 1 — View Live on Tableau Public (Recommended)**

[![View Dashboard](https://img.shields.io/badge/🚀%20View%20Live%20Dashboard-Tableau%20Public-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/bijoy.pantu/viz/SocialMediaCampaignPerformanceRWFDS04D01/Overview)

**Option 2 — Open Locally in Tableau Desktop**
```
1. Clone or download this repository
2. Open  dashboard/Social_Media_Campaign_Performance.twbx  in Tableau Desktop
3. Explore the interactive dashboard locally
```

**Option 3 — Reproduce the Analysis via SQL**
```
1. Load data/raw/  into your SQL environment (MySQL / PostgreSQL)
2. Run sql/  scripts in order — cleaning first, then KPI calculation
3. Cleaned output will match  data/cleaned/
```

---

## 📬 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Bijoy%20Pantu-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bijoypantu/)
[![Tableau](https://img.shields.io/badge/Tableau-Public-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/bijoy.pantu/vizzes)
[![GitHub](https://img.shields.io/badge/GitHub-bijoypantu-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bijoypantu)
[![Gmail](https://img.shields.io/badge/Gmail-bijoypantu176-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bijoypantu176@gmail.com)

</div>

---

<div align="center">

*"Data beats opinions. ROI beats assumptions."* 📊

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,28&height=120&section=footer" width="100%"/>

</div>