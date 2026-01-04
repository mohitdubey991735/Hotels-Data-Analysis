🏨 AtliQ Hotels Data Analysis Project

Revenue • Occupancy • Business Performance Insights

👋 Introduction

This is an end-to-end data analysis project built using Python to analyze hotel booking data for AtliQ Hotels.

The project simulates a real business problem where management wants to understand:

Why revenue is fluctuating

Which cities and room types perform best

How occupancy changes across time

🎯 What Problem Does This Project Solve?

Hotel management struggles with:

Inconsistent occupancy rates

Uneven revenue across cities

Poor visibility into booking behavior

📌 This project converts raw booking data into meaningful business insights.

🧠 What You Will Learn From This Project

✔ How to clean messy real-world data
✔ How to calculate occupancy & revenue metrics
✔ How to merge multiple datasets
✔ How to answer real business questions using data
✔ How to present insights visually

🛠️ Tools & Technologies Used
Tool	Purpose
Python	Core programming
Pandas	Data cleaning & transformation
Matplotlib	Data visualization
Jupyter Notebook	Interactive analysis
CSV Files	Raw datasets
📂 Dataset Overview (Simple Explanation)

This project uses 5 datasets:

File Name	What It Contains
dim_date.csv	Date, month, weekday/weekend info
dim_hotels.csv	Hotel names & cities
dim_rooms.csv	Room category details
fact_bookings.csv	Individual booking records
fact_aggregated_bookings.csv	Capacity & total bookings
🧩 Step-by-Step Project Explanation
🔹 Step 1: Data Import & Exploration

Goal: Understand what data looks like before analysis

✔ Loaded all CSV files using Pandas
✔ Checked shape, columns, data types
✔ Explored:

Booking platforms

Room categories

City distribution

📌 This step helps identify data quality issues early.

🔹 Step 2: Data Cleaning

Goal: Remove incorrect and misleading data

✔ Removed bookings with invalid guest count
✔ Detected and handled revenue outliers
✔ Filled missing values using median where appropriate
✔ Removed records where bookings exceeded capacity

📌 Clean data = reliable insights

🔹 Step 3: Data Transformation

Goal: Create useful business metrics

✔ Created Occupancy Percentage (occ_pct)
✔ Merged booking, hotel, room, and date datasets
✔ Converted date columns for time-based analysis

📌 This step prepares data for analysis.

🔹 Step 4: Business Insights Generation

Questions Answered:

✔ What is the average occupancy by room category?
✔ Which cities have the highest occupancy?
✔ Do weekends perform better than weekdays?
✔ How does revenue change month-by-month?
✔ Which booking platforms generate the most revenue?

📌 This is where raw data becomes business value.

📊 Key Insights (Simple & Clear)

✔ Weekends show higher occupancy than weekdays
✔ Premium room categories generate more revenue
✔ Certain cities consistently outperform others
✔ A small number of booking platforms contribute most revenue

📈 Visualizations Included

✔ Bar charts for occupancy comparison
✔ Pie chart for revenue by booking platform
✔ Trend charts for monthly revenue

📌 (Visuals make insights easy to understand for non-technical stakeholders.)
