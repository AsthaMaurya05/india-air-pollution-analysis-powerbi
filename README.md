# 🌏 India Air Quality Analysis Dashboard (Power BI)

## 📌 Project Overview
This project presents a comprehensive **Power BI dashboard for analyzing air pollution levels across India** using monitoring station data.  
The dashboard is designed to support **public health awareness**, **environmental analysis**, and **policy-level understanding** by providing clear insights into pollution severity across states, cities, and pollutants.

The project follows a structured data analytics workflow including **data cleaning, data modeling, DAX-based measures, and multi-page interactive visualization**.

---

## 📊 Dashboard Pages Overview

### 🧭 Page 1 — India Air Quality Overview
This page provides a **national-level snapshot** of air pollution trends across India.

**Key Features**
- Geographic scatter visualization showing **pollution hotspots by monitoring station**
- KPI indicators:
  - Total Active Monitoring Stations  
  - Highest Pollution Detected (Peak Value)  
  - India Average Pollution Level
- Top 10 most polluted cities
- State-wise average pollution comparison
- Interactive slicers for **State** and **Pollutant**
- Summary observations highlighting national trends

**Purpose:**  
To provide a quick and clear overview for **general public awareness and high-level decision-making**.

---

### 🧪 Page 2 — Pollutant Analysis
This page focuses on **pollutant-wise analysis** to understand how different pollutants impact air quality across regions.

**Key Features**
- City-wise and state-wise pollutant severity analysis  
- Pollutant contribution analysis using a donut chart  
- KPI indicators highlighting peak pollution severity  
- Detailed monitoring station table showing minimum, maximum, and average values  
- Interactive filtering by **State** and **Pollutant**

**Purpose:**  
To support **academic analysis, research interpretation, and environmental monitoring**.

---

### 🚨 Page 3 — Health Risk & Insights
This page translates pollution levels into **public health risk categories**.

**Key Features**
- Classification of cities into **High, Moderate, and Low health risk levels**
- State-wise health risk severity comparison
- Treemap highlighting major high-risk cities
- Filters for **State** and **Pollutant**
- Public health insights explaining the effects of pollutants such as PM2.5, PM10, CO, NO₂, and Ozone

**Purpose:**  
To emphasize the **societal and health impact** of air pollution and support awareness initiatives.

---

## 🧠 Data Modeling & Techniques Used
- Power Query for data cleaning, transformation, and preparation  
- Fact and Dimension tables (State, City) with proper relationships  
- Star-schema style data modeling  
- DAX measures for KPIs and aggregated insights  
- Interactive slicers for multi-dimensional analysis  

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **CSV / Excel data sources**
- **Data visualization best practices**

---

## 📁 Repository Structure
project_files/
└── India_Air_Quality_Dashboard.pbix

data/
└── CSV / Excel datasets used in the dashboard

screenshots/
├── page1_overview.png
├── page2_pollutant_analysis.png
└── page3_health_risk_insights.png


---

## 📦 How to Use the Project

1. Clone or download this repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Ensure the dataset files are placed in the `data` folder.
4. Click **Refresh** to load the visuals.

---

## 🎓 Learning Outcomes
Through this project, I gained practical experience in:
- Designing an end-to-end Power BI analytics solution  
- Applying data modeling concepts and DAX measures  
- Building multi-page dashboards with meaningful insights  
- Translating raw data into actionable public health information  

---

## 🤝 Contributions
Suggestions and improvements are welcome.  
This project is intended for **academic and learning purposes**.
