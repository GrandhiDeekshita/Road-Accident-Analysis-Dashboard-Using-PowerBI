📊 Road Accident Analysis Dashboard

A Power BI Project for Accident Insights, Trends & Risk Analysis

This project provides a detailed analysis of road accidents across different states, years, vehicle types, and severity levels. The dashboard helps identify accident trends, high-risk zones, and factors influencing fatalities and casualties.

🚀 Project Overview

This Power BI dashboard analyzes national road accident data to uncover:

Accident severity distribution

Yearly trends in accidents, fatalities & casualties

Vehicle involvement patterns

Location-wise accident hotspots

Time-of-day accident severity

Monthly casualties

Fatality rate vs target

State-wise filtering for deeper insights

It is designed to support decision-making related to road safety, traffic planning, and risk reduction strategies.

📂 Key Features
✔️ 1. KPI Highlights

Total Accidents

Total Casualties

Total Fatalities

Total Vehicles Involved

Max Year in Dataset

✔️ 2. Accident Trend Analysis

A multi-line trend chart showing:

Accident counts

Fatalities

Casualties (year-wise)

✔️ 3. Vehicle Involvement by Location & City

Compares vehicle involvement across locations (Straight Road, Curve, Bridge, Intersection)

Across major cities (Ahmedabad, Bangalore, Chennai)

✔️ 4. Casualties by Month

Identifies months with highest casualties

✔️ 5. Casualties by Vehicle Type & Fatalities Count

Heatmap visualization to identify patterns between vehicles and fatal accident counts

✔️ 6. Accidents by Severity & Time of Day

Compares fatal, serious, and minor accidents across time slots

✔️ 7. Fatality Rate vs Target

KPI card showing actual fatality rate vs targeted value

✔️ 8. Interactive Filters

State Name slicer

Year Range slicer

All visuals update dynamically

🛠️ Tools Used

Power BI Desktop

Power Query (Data Cleaning & Transformation)

DAX (Measures & Calculations)

Excel / CSV (Source Dataset)

📁 Dataset

The dataset includes:

Accident severity

Number of casualties

Number of fatalities

Number of vehicles involved

State name

City name

Accident location type

Year and Month



📈 DAX Measures Used
Total Accidents = COUNT(accident_prediction_india[Accident_Severity])

Total Casualties = SUM(accident_prediction_india[Number_of_Casualties])

Total Fatalities = SUM(accident_prediction_india[Number_of_Fatalities])

Total Vehicles Involved = SUM(accident_prediction_india[Number_of_Vehicles_Involved])


🎯 Insights Summary

Some major insights from the dashboard:

Increasing trend in accidents & casualties between 2018–2022

Intersections and curves show higher vehicle involvement

March, January, and April have the highest casualties

Fatal accidents increase significantly during late-night hours

Fatality rate exceeded the target value
🖼️ Dashboard Preview
<img width="1329" height="740" alt="Screenshot 2025-12-09 184000" src="https://github.com/user-attachments/assets/4bd890a0-d9fa-4320-90ee-4875aa2b31ec" />


📌 How to Use

Clone this repository

Open Road_Accident_Analysis.pbix in Power BI

Load dataset if required

Interact with filters to explore insights

📬 Contact

If you have questions or suggestions, feel free to reach out!

Deekshita Grandhi
📧 deekshithagrandhi@gmail.com
💼https://www.linkedin.com/in/grandhi-deekshita-7a0940251/
