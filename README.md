# Hotels-Data-Analysis
End-to-end data analysis project using Python to analyze hotel revenue, occupancy trends, and business performance insights.
🏨 AtliQ Hotels Data Analysis Project
📌 Project Overview

This project focuses on analyzing hotel revenue, occupancy rates, and overall business performance for AtliQ Hotels using real-world booking data.
The goal is to derive actionable insights that can help management improve pricing strategy, capacity utilization, and revenue growth.

🎯 Business Objectives

Analyze occupancy percentage across room categories and cities

Identify revenue trends by city, hotel, month, and booking platform

Compare weekday vs weekend performance

Detect data issues such as invalid entries, missing values, and outliers

Support data-driven decision making for hotel operations

🛠️ Tools & Technologies

Python

Pandas

Matplotlib

Jupyter Notebook

CSV Datasets

📂 Dataset Information

The analysis uses the following datasets:

dim_date.csv – Date and day-type details

dim_hotels.csv – Hotel properties and city information

dim_rooms.csv – Room categories and room classes

fact_bookings.csv – Detailed booking-level data

fact_aggregated_bookings.csv – Aggregated capacity and booking data

🔍 Project Workflow
1️⃣ Data Import & Exploration

Loaded all datasets using Pandas

Explored data structure, unique values, and distributions

Analyzed booking platforms, room categories, and city-wise hotels

2️⃣ Data Cleaning

Removed invalid guest records

Handled outliers in revenue columns using statistical methods

Treated missing values using median where appropriate

Filtered records where bookings exceeded capacity

3️⃣ Data Transformation

Created occupancy percentage (occ_pct) column

Merged multiple datasets for enriched analysis

Converted date fields for time-based analysis

4️⃣ Insights Generation

Average occupancy rate by room category

City-wise occupancy analysis

Weekday vs weekend occupancy comparison

Monthly and city-wise revenue analysis

Revenue distribution by booking platform

📊 Key Insights

Certain cities consistently show higher occupancy rates

Weekends generally perform better than weekdays

Premium room categories generate higher revenue

A small number of booking platforms contribute to a large share of revenue

📈 Visualizations Included

Bar charts for occupancy and revenue analysis

Pie chart showing revenue share by booking platform

Trend analysis across months and citie
