# ✈️ Airline Route Profitability & Performance Analysis

## 📌 Project Overview
This project focuses on analyzing airline route profitability using SQL and Power BI. The objective is to help airline management identify profitable routes, cost inefficiencies, demand patterns, and occupancy performance to support data-driven decision making.

The analysis is based on operational, financial, and passenger data for multiple airline routes.

---

## 🎯 Business Objective
- Identify most profitable airline routes
- Analyze revenue vs operational cost
- Measure seat occupancy efficiency
- Understand monthly and seasonal profit trends
- Compare route performance by aircraft type and route code

---

## 🗂 Dataset Description

**File:** `AirlineRoutesData.csv`

| Column Name | Description |
|-------------|-------------|
| FlightID | Unique identifier for each flight |
| RouteCode | Route identifier (e.g., BLR-DEL) |
| Origin | Departure airport |
| Destination | Arrival airport |
| FlightDate | Date of flight |
| FlightDurationMins | Flight duration in minutes |
| AircraftType | Aircraft used for the flight |
| SeatsAvailable | Total seats available |
| SeatsSold | Number of seats sold |
| Revenue | Total ticket revenue |
| OperationalCost | Total cost to operate the flight |

---

## 🛠 Tools & Technologies Used
- **SQL** – Data analysis & aggregation
- **Power BI** – Data modeling & visualization
- **Excel / CSV** – Data source
- **DAX** – Measures & calculations

---

## 🧮 Key Calculations (DAX Measures)
- Total Revenue
- Total Cost
- Total Profit
- Average Profit
- Occupancy Rate (%)
- Monthly Profit
- Revenue & Cost per Route

*All measures are stored in a dedicated Measures table following best practices.*

---

## 📊 Dashboard Features

### Dashboard Title:
**🛫 Route Profitability & Performance Dashboard**

### Key Visuals:
- 📊 **Bar Chart:** Top 10 most profitable routes
- 🗺 **Map:** Origin–Destination route visualization
- 📈 **Line Chart:** Monthly profit trend
- 🎯 **Gauge/Donut:** Average occupancy rate
- 📊 **Stacked Column Chart:** Revenue vs Cost by route

### Interactive Slicers:
- Aircraft Type
- Flight Month
- Route Code

---

## 📈 Key Business Insights
- The airline generates strong overall profit with efficient cost management.
- Average occupancy rate (~63%) shows unused seat capacity across routes.
- A small number of routes contribute the majority of total profit.
- Some high-revenue routes have high operational costs, reducing margins.
- Clear seasonal trends affect monthly profitability.
- Aircraft type plays a critical role in route performance.

---

## 📂 Project Structure
```
📁 Airline-Route-Profitability-Analysis
│
├── AirlineRoutesData.csv
├── SkyRoutesAnalysis.sql
├── RouteProfitDashboard.pbix
├── RouteInsights.txt
└── README.md
```

---

## 🚀 How to Use the Project
1. Load `AirlineRoutesData.csv` into SQL / Power BI
2. Run SQL queries from `SkyRoutesAnalysis.sql`
3. Open `RouteProfitDashboard.pbix` in Power BI Desktop
4. Use slicers to explore insights interactively

---

## 📌 Conclusion
This project demonstrates how SQL + Power BI can be used to transform raw airline data into actionable business insights. The dashboard enables stakeholders to optimize routes, improve occupancy, manage costs, and maximize profitability.

---

## 👤 Author
**JATIN KUMAR**  
Aspiring Data Analyst | Power BI | SQL | Business Intelligence

---

## 📫 Contact
Feel free to connect with me for feedback, collaboration, or opportunities!

---

## 📝 License
This project is open-source and available for educational purposes.

---

**⭐ If you found this project helpful, please give it a star!**
