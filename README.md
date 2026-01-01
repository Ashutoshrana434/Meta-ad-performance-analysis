# Meta Ad Performance Analysis Dashboard

## 📊 Project Overview

This project focuses on building a **comprehensive Power BI dashboard** to analyze advertising performance across **Meta platforms (Facebook & Instagram)**. The primary objective is to provide actionable insights into campaign effectiveness, audience behavior, and budget utilization across the full marketing funnel.

By tracking key performance indicators (KPIs), the dashboard enables marketing teams and stakeholders to make **data-driven decisions** to improve engagement, optimize ad spend, and enhance conversion efficiency.

---

## 🚀 Live Dashboard

You can view and interact with the live dashboard here:

**[Link to the Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNGU1NGRkMDQtMTgyMy00ZGVjLWIzNmYtNjRmMTEzYzdmYjBkIiwidCI6ImFkODQwZTUyLTUzZDEtNDNiZS1hZmY1LWRlMDgzNDE0NjZkMSJ9)**

<img width="1540" height="880" alt="image" src="https://github.com/user-attachments/assets/aaaf8a27-21b3-46d0-9eba-63fa8765f053" />

---

## 🎯 Business Requirements

The core objective was to design a **dynamic performance tracking dashboard** for paid advertising campaigns on Meta platforms. Key requirements included:

* Tracking campaign reach, engagement, and conversions.
* Measuring funnel performance from impressions to purchases.
* Comparing performance across platforms (Facebook vs Instagram).
* Analyzing audience demographics by **age, gender, and geography**.
* Identifying high-performing ad formats and optimal engagement timings.
* Providing actionable insights for **budget optimization and ROI improvement**.

---

## 💾 Dataset

The analysis is based on structured advertising performance data modeled after Meta Ads platforms.

**Key Tables Used:**

* `ad_events` – Event-level data (impressions, clicks, shares, comments, purchases)
* `ads` – Ad creative and targeting information
* `campaigns` – Campaign-level budget and duration data
* `users` – Audience demographics and interests

📄 Detailed dataset definitions and field explanations are provided in:

* **Business Requirements Document (BRD)**
* **Domain Knowledge Document**

---

## 🛠️ Tools Used

* **Microsoft Power BI:**
  Used for data cleaning (Power Query), data modeling, DAX calculations, and interactive dashboard creation.
* **DAX (Data Analysis Expressions):**
  Used to compute KPIs such as CTR, Engagement Rate, Conversion Rate, Purchase Rate, and Budget Metrics.
* **Data Modeling:**
  Star schema design with `ad_events` as the fact table and supporting dimension tables.

---

## ⚙️ Project Methodology

The project followed a structured, end-to-end analytics workflow:

1. **Requirement Gathering:** Defined business objectives, KPIs, and reporting expectations.
2. **Data Cleaning & Transformation:** Cleaned and standardized event-level data using Power Query.
3. **Data Modeling:** Built a star schema connecting ads, campaigns, users, and events.
4. **DAX Calculations:** Developed measures for funnel metrics and performance ratios.
5. **Dashboard Development:** Designed multiple analytical views in Power BI, including:

   * **Overview Dashboard:** High-level KPIs and funnel metrics
   * **Audience Analysis:** Gender, age group, and geographic performance
   * **Time-Based Trends:** Hourly, weekly, and monthly engagement patterns
   * **Ad Type Analysis:** Performance comparison across Image, Video, Stories, and Carousel ads
6. **Insights Generation:** Interpreted results to derive optimization recommendations.

---

## 📈 Key Insights

The dashboard uncovered several important insights:

* **Strong Awareness & Engagement:**
  CTR (~11.7%) and Engagement Rate (~13.5%) are significantly above industry benchmarks, indicating effective creatives and targeting.
* **Funnel Drop-Off:**
  Purchase Rate (~0.6%) is relatively low, highlighting leakage between engagement and conversion stages.
* **Audience Performance:**
  Females aged **18–30** contribute the highest engagement levels.
* **Geographic Trends:**
  India and Brazil drive high engagement volume, while Germany and the UK show higher-value conversion potential.
* **Ad Format Performance:**
  **Video and Stories ads** outperform Image and Carousel formats across CTR, engagement, and conversion rates.
* **Optimal Timing:**
  Engagement peaks during **afternoon and evening hours**, suggesting optimal ad delivery windows.

---

## ✅ Business Recommendations

Based on the analysis:

* Improve landing page experience and retargeting strategies to boost conversions.
* Shift more budget toward **Video and Story ads**.
* Focus targeting on high-performing demographics and geographies.
* Schedule ads during peak engagement hours for better ROI.
* Segment strategies for high-volume vs high-value regions.

---

## 👤 Author

**Ashutosh Rana**

---
