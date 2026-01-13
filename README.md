# 🚦 Motor Vehicle Collisions Analysis (Power BI)

## 📌 Project Overview

This project analyzes New York City motor vehicle collision data to identify trends in collision frequency, injuries, fatalities, time patterns, locations, and contributing factors. A key focus was **data quality remediation**, transforming a high-volume but inconsistent public dataset into a reliable, decision-ready analytical model presented through an interactive Power BI dashboard.

---

## 🎯 Objectives
* Connect Power BI directly to a public-sector open data source
* Resolve critical data quality issues in a real-world dataset
* Create meaningful location logic despite missing street-level data
* Identify high-risk periods, locations, and behaviors
* Translate analytical findings into **practical policy recommendations**

---

## 🗂️ Data Quality Challenges

* Incorrect spellings and invalid entries
* High volume of missing values
* Dates stored as text
* Inconsistent text formatting

**Data completeness notes:**

* Borough: ~30% nulls
* Location fields: ~4% nulls

---

## 🛠️ Data Preparation & Modeling

* Standardized all text fields and corrected invalid values
* Converted date fields from text to date format for time-series analysis
* Replaced nulls with controlled placeholders where appropriate

### 📍 Location Logic

Due to missing street names, collisions were logically classified as:

* Intersection
* Off-Street
* Mid-Block
* Unknown

This preserved analytical value while mitigating data gaps.

---

## 📊 Dashboard Highlights

* KPI cards for collisions, injuries, fatalities, and rates
* Borough-level collision distribution
* Seasonal, monthly, and hourly trends
* Collision distribution by location type
* Leading contributing factors

---

## 🔍 Key Insights (2025)

* **85k collisions**, **50k injuries**, **225 fatalities**
* **Injury rate:** 58.0% | **Fatality rate:** 0.3%

**Geography**

* Brooklyn recorded the highest collision share, followed by Queens, Manhattan, the Bronx, and Staten Island

**Time Patterns**

* Collision peaks at **08:00** and **15:00–18:00**, aligning with commuter traffic
* Lowest collision volume observed in **February**
* Higher activity during **Spring, Summer, and Fall**

**Location Risk**

* Intersections account for the highest collision concentration
* Off-street locations follow, with minimal mid-block incidents

**Primary Causes**

* Driver distraction (leading factor)
* Failure to yield right-of-way
* Following too closely
* Improper lane usage

---

## 🏛️ Data-Driven Recommendations

Based on these findings, the analysis supports the following actions for city leadership:

* Prioritize **high-risk intersections** for safety redesigns and signal optimization
* Focus **traffic enforcement during peak commute hours**
* Strengthen **distracted-driving prevention and education**
* Improve **right-of-way compliance** through clearer signage and junction design
* Launch **seasonal safety campaigns** aligned with collision peaks
* Implement **borough-specific interventions**, starting with Brooklyn
* Improve collision **data collection standards** to reduce missing location data

---

## 📈 Impact

This project demonstrates the ability to:

* Clean and structure complex public datasets
* Apply analytical logic to incomplete data
* Deliver executive-level insights and policy-ready recommendations
* Build professional, stakeholder-focused Power BI dashboards

---

## 🔗 Live Dashboard

👉 [https://app.powerbi.com/view?r=eyJrIjoiMjEzY2I1MzAtN2YxZS00YjRlLWJjYzMtMjM0YjRhOGNlNDNiIiwidCI6ImIyMTFiMjkwLWFkNzUtNGJlNC1iZDk3LWI5Y2MxZDlmMzdlZCJ9](https://app.powerbi.com/view?r=eyJrIjoiMjEzY2I1MzAtN2YxZS00YjRlLWJjYzMtMjM0YjRhOGNlNDNiIiwidCI6ImIyMTFiMjkwLWFkNzUtNGJlNC1iZDk3LWI5Y2MxZDlmMzdlZCJ9)

---

## 🧰 Tools Used

* Power BI
* Power Query
* DAX

---

## 👤 Author

**Elijah Okpako**
Data Analyst | Power BI | SQL | Excel

---
