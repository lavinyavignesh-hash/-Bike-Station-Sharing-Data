# 🚲 Bike-Station System Performance Analysis

## 📌 Project Overview
Public bike-sharing systems generate continuous, real-time data from hundreds of stations across multiple cities.  
This project analyzes bike station data to evaluate **availability, utilization, and operational performance** using **Power BI**, transforming raw data into actionable urban mobility insights.

---

## 🎯 Objective
- Analyze bike availability and station utilization across cities
- Identify full and empty stations indicating demand–supply imbalance
- Compare station performance contract-wise (city-wise)
- Support data-driven decisions for bike redistribution and capacity planning

---

## 📂 Data Source
- **Source:** Public bike-sharing dataset from GitHub  
- **Type:** Real-time station-level data  
- **Coverage:** Multiple cities (contract names)

---

## 🧱 Dataset Attributes
Key fields used in the analysis:
- Station ID  
- Station Name  
- Address  
- Contract Name (City)  
- Latitude & Longitude  
- Available Bikes  
- Available Bike Stands  
- Station Status  
- Last Update Timestamp  

---

## 🛠 Tools & Technologies
- **Power BI** – Data modeling, DAX, and dashboarding  
- **Power Query** – Data cleaning and transformation  
- **DAX** – KPI calculations and performance metrics  

---

## 🔄 Data Pre-Processing
- Removed duplicate records and handled missing values
- Standardized column formats and renamed fields
- Split location fields into latitude and longitude
- Converted data types and rounded geographic values
- Created **Fact and Dimension tables** using a star schema
- Derived calculated columns for station status (Available / Empty / Full)

---

## 📐 Data Modeling
- **Fact Table:** Bike availability metrics
- **Dimension Tables:** Station, Contract (City), Date
- Relationships built using **Station ID** and **Contract Name**

---

## 📊 Key Metrics (DAX)
- Total Stations  
- Total Available Bikes  
- Total Available Stands  
- Average Bikes per Station  
- Full Stations Count  
- Empty Stations Count  
- Station Utilization Percentage  

---

## 🔍 Key Findings
- **Total Stations:** 1,028  
- **Contract Regions:** 25  
- **Available Bikes:** 5,961  
- **Available Stands:** ~10,000  
- **Average Bikes per Station:** 5.8  
- **Full Stations:** 210  
- **Empty Stations:** 381  

---

## 📈 Dashboard Highlights
- City-wise station distribution
- Available bikes by contract name
- Full vs empty station analysis
- Most frequently empty or full stations
- Station utilization comparison across cities
- Interactive KPIs, bar charts, line charts, and maps

---

## 🧠 Insights
- Significant variation in station utilization across cities
- High number of empty stations indicates peak-demand pressure
- Full stations suggest overcapacity or low usage in some areas
- Highlights the need for improved bike redistribution strategies

---

## 🧭 Business Value
This analysis supports:
- Operational efficiency improvements  
- Better bike redistribution planning  
- Capacity optimization across cities  
- Enhanced user experience in urban mobility systems  

---

## 🚀 Conclusion
The project demonstrates end-to-end data analytics capabilities, from data cleaning and modeling to DAX-driven insights and dashboard storytelling, applied to a real-world urban transportation problem.

---

## 👤 Author
**Lavinya V**  
*Aspiring Data Analyst | Power BI | Data Analytics*
