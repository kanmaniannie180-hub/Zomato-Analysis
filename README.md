# Zomato-Analysis


---

🍴 Restaurant Performance & Insights Dashboard

An interactive Power BI dashboard analyzing global restaurant data.
It provides insights on restaurant distribution, cuisines, ratings, and presence across countries, cities, and localities.
The project helps decision-makers in the food & beverage industry identify trends, top cuisines, and areas for improvement 🌍🍲📊.


---

📌 1. Project Overview

This project focuses on building a Restaurant Analysis Dashboard using Power BI.
It transforms raw restaurant data into actionable insights by visualizing:

🌍 Restaurant presence across countries & cities

🍜 Cuisines diversity

⭐ Customer ratings distribution

🚚 Service models (online delivery, table booking)



---

❓ 2. Problem Statement

The analysis aims to answer:

🏙 Which countries, cities & localities have the highest restaurant presence?

🍲 What are the top cuisines, and how do they perform across regions?

⭐ How do ratings vary across cuisines & restaurants?

📦 Which service models (online delivery, table booking) dominate?

📊 How can Zomato or restaurants use this to boost performance?



---

📂 3. Dataset

Source: Zomato dataset (CSV/Excel)

Records: ~9,500+ restaurants 📑

Fields:
🏷 Restaurant ID | 🍽 Name | 🌍 Country | 🏙 City | 📍 Locality | 🍲 Cuisines | ⭐ Rating | 🎨 Rating Color | 🚚 Online Delivery | 📅 Table Booking | 💰 Avg. Cost for Two | 💱 Currency

Preprocessing Steps:
✅ Removed duplicates & null values
✅ Standardized cost across currencies 💱
✅ Derived calculated columns like Rating Text (Excellent, Very Good, Good, etc.)



---

🔄 4. Analysis Workflow

⿡ Data Cleaning & Preparation 🧹

Removed duplicates, handled nulls, fixed data types

Created columns: Rating Text, Service Availability


⿢ Transformation & Calculations (DAX) 🧮

Measures:
🍽 Restaurant Count
🍜 Distinct Cuisines
🏙 Presence in City/Locality
⭐ Average Rating


⿣ Exploratory Analysis 🔍

Map 🌍 → Country-wise restaurant presence

Donut & Bar Charts 📊 → Rating distribution

Cuisine vs Ratings analysis 🍲⭐


⿤ Insights Derived 💡

Found countries with highest restaurant count

Identified diverse cuisines served

Rating trends (more “Good” than “Excellent”)



---

📊 5. Key Metrics & KPIs

🏢 Restaurant Count – Total restaurants

🍲 Distinct Cuisines – Variety across countries

📍 Presence in City/Locality – Market reach

⭐ Average Rating – Customer perception

🚚📅 Service Availability – Online delivery & booking trends



---

📈 6. Dashboards & Visuals

The dashboard includes:

📌 KPI Cards → Restaurant Count, Distinct Cuisines, Localities

🍩 Donut Chart → Distribution by Ratings

🌍 Map → Country-wise restaurant spread

📊 Bar Charts →

Cuisines Count by Rating

Restaurant Count by Country




---

💡 7. Results & Insights

🇮🇳 India = highest restaurant count

⭐ Most restaurants are rated “Good” or “Average”

🌐 Few cuisines dominate (North Indian, Chinese)

🏙 Untapped localities = expansion opportunities



---

🚀 8. Future Improvements

📆 Add trend analysis of ratings over time

💰 Compare average cost for two across regions

🤖 Predictive modeling for success factors

🔗 API integration for real-time updates



---

🖥 9. Usage Instructions

⿡ Download the .pbix file from the repo  
⿢ Open in Power BI Desktop  
⿣ Check dataset (CSV/Excel) path is correct  
⿤ Use slicers (Country, Cuisines, Ratings, etc.)  
⿥ Explore Page 1 (Overview) & Page 2 (Detailed Insights)


---


📷 Dashboard Preview

<img width="1292" height="741" alt="image" src="https://github.com/user-attachments/assets/34299fea-74bd-4874-9d5d-ea223eaebee7" />
<img width="1327" height="747" alt="image" src="https://github.com/user-attachments/assets/1b3acd0a-c162-43a2-a631-1b02c61204f5" />

---



