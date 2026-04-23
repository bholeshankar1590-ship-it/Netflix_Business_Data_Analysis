# Netflix_Business_Data_Analysis
# 🎬 Netflix Content Strategy — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue) ![Pandas](https://img.shields.io/badge/Pandas-EDA-green) ![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview

An end-to-end Exploratory Data Analysis (EDA) of Netflix's content library to uncover trends in content production, genre performance, country-wise distribution, and release strategy — with actionable business recommendations.

---

## 📂 Dataset

| Feature | Details |
|---|---|
| **Source** | Netflix Titles Dataset (`netflix.csv`) |
| **Records** | 8,807 titles |
| **Features** | 12 columns (type, country, genre, rating, duration, etc.) |
| **Date Range** | 1925 – 2021 |

---

## 🛠️ Tech Stack

- **Python** — Pandas, NumPy
- **Visualization** — Matplotlib, Seaborn
- **Environment** — Google Colab / Jupyter Notebook

---

## 🔍 Key Insights

### 📊 Content Distribution
- Netflix catalog has a **Movies : TV Shows ratio of ~2.3:1**, but the gap is shrinking rapidly
- TV Show additions have **grown significantly post-2017**, signaling a platform strategy shift toward retention-focused content
- Content additions **peaked between 2017–2020**, reflecting Netflix's global expansion phase

### 🌍 Geographic Trends
- **USA dominates** with 2,818 titles; India is 2nd with 972 titles
- Content is **highly concentrated in ~10 countries**, which account for ~80% of the catalog
- **India and USA** lean Movie-heavy; **South Korea and Japan** are TV Show-dominant
- Significant opportunity exists in **Africa, Southeast Asia, and the Middle East**

### 🎭 Genre Analysis
- **Dramas and International Movies** are the top-performing genres
- **Stand-Up Comedy and Documentaries** rank consistently high
- Multi-genre tagging is common, improving discoverability and recommendation accuracy
- **Romantic Movies** is the least-represented genre among the top categories

### ⏱️ Duration Patterns
- Movie durations cluster tightly around **90–120 minutes** (near-normal distribution)
- TV Shows are **heavily right-skewed** — majority run for only **1–2 seasons**
- Very few shows exceed 5+ seasons, reflecting a preference for limited-series formats

### 📅 Release Timing
- Content releases **peak in Q3–Q4 (July–December)**, aligned with holiday seasons and high engagement windows
- Monthly variation is meaningful; daily variation has no strategic significance

### 🔞 Audience Targeting
- **TV-MA and TV-14 dominate** the ratings distribution (~70%+ of catalog)
- Kids and family content is significantly **underrepresented** on the platform
- Platform is primarily targeting **young adults and mature viewers**

### 🎬 Creator & Talent Insights
- No single dominant director — **long-tail distribution** across 4,500+ unique directors
- Most actors appear in only one title — content is **highly diverse in casting**
- David Attenborough is the most frequently appearing cast member

---

## 💡 Business Recommendations

1. **Invest more in TV Shows** — short series (1–3 seasons) drive binge behavior and improve user retention
2. **Expand localized content** in India, South Korea, Europe, and emerging markets for regional subscriber growth
3. **Prioritize Drama, Crime, and Thriller genres** — highest global demand across diverse audiences
4. **Develop Kids & Family content** — a large underserved segment currently missing from the catalog
5. **Maintain 90–120 min movie runtime** — proven sweet spot for viewer completion rates
6. **Release major titles in Q4 (Oct–Dec)** to align with festive season engagement spikes
7. **Reduce geographic concentration risk** — diversify production into Africa, Southeast Asia, and MENA regions
8. **Support emerging creators and regional talent** to bring fresh, culturally diverse storytelling
9. **Balance Movie vs TV Show output** — movies for discovery/acquisition, shows for long-term retention
10. **Continue multi-genre content tagging** to strengthen recommendation systems and discoverability

---

## 📈 Resume Bullet Points

> Copy-paste ready for your Data Analyst / Data Science resume

- **Performed end-to-end EDA** on 8,800+ Netflix titles using Python (Pandas, Seaborn, Matplotlib), uncovering content trends, genre patterns, and regional distribution insights
- **Identified a strategic shift** from movies to TV shows through year-wise bivariate analysis, revealing a 3x growth in TV Show additions between 2015–2020
- **Analyzed geographic content concentration**, finding that 80% of Netflix content originates from just 10 countries, and recommended expansion into underserved markets (Africa, Southeast Asia, MENA)
- **Engineered and extracted** time-based features (`year_added`, `month_added`) from raw date strings to uncover Netflix's seasonal release strategy peaking in Q3–Q4
- **Handled missing data** across 4 columns (director, cast, country, rating) using mode imputation and placeholder strategies, preserving dataset integrity for downstream analysis
- **Conducted univariate and bivariate analysis** on duration, genre, rating, and content type, producing 10+ visualizations that informed actionable business recommendations
- **Delivered 10 data-driven business recommendations** including audience diversification, content format optimization, and international market expansion strategy
- **Processed and exploded multi-valued columns** (cast, genre, country) to enable accurate frequency analysis across 200,000+ exploded records

---

