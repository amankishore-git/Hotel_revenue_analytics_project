# 🏨 AtliQ Grands - Hospitality Data Analytics

## 📝 Problem Statement
AtliQ Grands, a prominent luxury and business hotel chain in India, has been losing its market share and revenue over the past few months. This decline is primarily due to strategic moves from competitors and ineffective decision-making in management. 

To regain their market share and revenue, the Managing Director of AtliQ Grands decided to incorporate "Business and Data Intelligence" into their operations. However, the company lacks an in-house data analytics team. As a result, the revenue management team hired a data analyst to derive actionable insights from their historical data.

## 🎯 Objective
To build an interactive Power BI dashboard that provides the revenue management team with key insights into hotel performance, helping them make data-driven pricing and operational decisions to increase revenue and regain market share.

## 🛠️ Tech Stack & Skills
- **Tool:** Power BI
- **Data Cleaning & Transformation:** Power Query
- **Calculations & Metrics:** DAX (Data Analysis Expressions)
- **Data Modeling:** Star Schema (Fact and Dimension Tables)
- **Concepts:** Revenue Management, Dynamic Pricing, Hospitality Domain Knowledge

## 📊 Key Metrics (KPIs) Created
During the project, I translated business requirements into mathematical formulas using DAX. Key metrics include:
- **RevPAR (Revenue Per Available Room):** Assesses the hotel's ability to fill its available rooms at an average rate.
- **ADR (Average Daily Rate):** Measures the average rental income per paid occupied room.
- **Occupancy %:** The percentage of available rooms that are occupied over a specific period.
- **Realization %:** The percentage of successfully checked-out bookings over the total number of bookings.
- **DSRN, DBRN, DURN:** Daily Sellable Room Nights, Daily Booked Room Nights, and Daily Utilized Room Nights.

## 🗄️ Data Modeling
- Followed the **Star Schema** approach to optimize the model for analytical querying.
- Established relationships between the central Fact table (`fact_bookings`) and various Dimension tables (`dim_date`, `dim_hotels`, `dim_rooms`).

## 💡 Key Insights Generated
- **Weekend vs. Weekday Performance:** Occupancy rates and RevPAR show distinct trends based on the day of the week, indicating the need for dynamic weekend pricing strategies.
- **City-wise Revenue:** Mumbai generates the highest total revenue, while cities like Delhi and Bangalore experience varying realization percentages.
- **Booking Platforms:** "MakeYourTrip" and "LogTrip" perform differently in terms of realization percentage. Direct offline bookings have a noticeably different ADR compared to online travel agencies (OTAs).
- **Room Categories:** Elite and Premium rooms contribute significantly to the revenue, but their occupancy heavily fluctuates during off-peak seasons.

## 📸 Dashboard Snapshot
*(Delete this text and drag & drop an image of your Power BI dashboard here)*

## 🌐 Live Dashboard
[Click here to interact with the Live Power BI Dashboard](PK)

## 🤝 Credits
This project was completed as part of the End-to-End Data Analytics course provided by **Codebasics** (instructed by Dhaval Patel & Hemanand Vadivel).
