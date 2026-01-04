🏨 AtliQ Hotels Data Analysis Project

Revenue • Occupancy • Business Performance Insights

<p align="center"> <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue" /> <img src="https://img.shields.io/badge/Pandas-Data%20Wrangling-green" /> <img src="https://img.shields.io/badge/Jupyter-Notebook-orange" /> <img src="https://img.shields.io/badge/Status-Completed-success" /> </p>
📌 Project Overview

This project focuses on analyzing hotel revenue, occupancy rates, and overall business performance for AtliQ Hotels using real-world booking data.

🎯 Goal:
To generate actionable insights that help management:

Improve pricing strategies

Optimize capacity utilization

Drive revenue growth

🧭 Quick Navigation

🎯 Business Objectives

🛠️ Tools & Technologies

📂 Dataset Information

🔍 Project Workflow

📊 Key Insights

📈 Visualizations

🚀 How to Run

⭐ Key Takeaways

🎯 Business Objectives

✔ Analyze occupancy percentage across room categories and cities
✔ Identify revenue trends by city, hotel, month, and booking platform
✔ Compare weekday vs weekend performance
✔ Detect data quality issues (invalid entries, missing values, outliers)
✔ Enable data-driven decision making for hotel operations

🛠️ Tools & Technologies
Tool	Purpose
🐍 Python	Core data analysis
🧮 Pandas	Data cleaning & transformation
📊 Matplotlib	Visualizations
📓 Jupyter Notebook	Interactive analysis
📁 CSV Files	Raw datasets
📂 Dataset Information

The project uses five structured datasets:

Dataset	Description
dim_date.csv	Date, month, weekday/weekend info
dim_hotels.csv	Hotel properties & city mapping
dim_rooms.csv	Room categories & room class
fact_bookings.csv	Booking-level transactional data
fact_aggregated_bookings.csv	Capacity & aggregated bookings
🔍 Project Workflow
1️⃣ Data Import & Exploration

Loaded datasets using Pandas

Explored schema, shape, and distributions

Analyzed booking platforms, room types & cities

2️⃣ Data Cleaning

❌ Removed invalid guest records

📉 Handled outliers using statistical thresholds

🧩 Treated missing values using median where applicable

🚫 Filtered bookings exceeding capacity

3️⃣ Data Transformation

🧮 Created occupancy percentage (occ_pct)

🔗 Merged multiple datasets

📆 Converted date columns for time-series analysis

4️⃣ Insights Generation

📊 Average occupancy by room category

🏙️ City-wise occupancy performance

📅 Weekday vs weekend comparison

💰 Monthly & city-level revenue trends

🌐 Revenue contribution by booking platform

📊 Key Insights

✨ Certain cities consistently show higher occupancy rates
✨ Weekends outperform weekdays in occupancy
✨ Premium room categories generate higher revenue
✨ Few booking platforms contribute most of the revenue

📈 Visualizations

📌 (Screenshots recommended — add inside /images folder)

📊 Bar charts → Occupancy & revenue comparison

🥧 Pie chart → Revenue share by booking platform

📈 Trend charts → Monthly & city-wise performancetie
