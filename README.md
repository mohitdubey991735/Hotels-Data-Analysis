# 🏨 Project Title: AtliQ Hotels Data Analysis – Revenue & Occupancy Insights 📊

---

## Short Description

AtliQ Hotels Data Analysis is an end-to-end business analytics project built using **Python** and **Pandas** to analyze hotel booking data and uncover actionable insights related to **revenue performance, occupancy trends, and customer booking behavior**.

This project simulates a real-world hospitality analytics use case where management needs a clear understanding of **which cities, room categories, and booking platforms drive performance**, enabling better **pricing strategy, capacity planning, and revenue optimization**.

---

## Tech Stack

- **Programming Language:** Python  
- **Data Analysis & Manipulation:** Pandas  
- **Data Visualization:** Matplotlib  
- **Development Environment:** Jupyter Notebook  
- **Data Format:** CSV Files  

---

## Data Source

The analysis is performed on a structured, real-world–style dataset representing hotel operations for **AtliQ Hotels**.  
The dataset consists of multiple interconnected tables containing historical booking and operational data related to:

- **Hotel Properties:** Property name, city, and hotel category  
- **Room Details:** Room types and room classes  
- **Booking Data:** Booking platform, number of guests, revenue generated, revenue realized, and ratings  
- **Date Information:** Check-in date, month, year, weekday vs weekend classification  
- **Capacity Metrics:** Available capacity and successful bookings  

---

## Project Objectives

- Analyze **occupancy percentage** across room categories and cities  
- Identify **revenue trends** by city, hotel, month, and booking platform  
- Compare **weekday vs weekend performance**  
- Detect and handle **data quality issues** such as invalid records, missing values, and outliers  
- Enable **data-driven decision making** for hotel operations  

---

## Project Workflow

### 1. Data Import & Exploration
- Loaded multiple CSV datasets using Pandas  
- Explored dataset structure, data types, and distributions  
- Analyzed booking platforms, room categories, and city-wise hotel presence  

---

### 2. Data Cleaning
- Removed records with invalid guest counts  
- Handled revenue outliers using statistical thresholds  
- Treated missing values using median where appropriate  
- Filtered records where bookings exceeded available capacity  

---

### 3. Data Transformation
- Created **Occupancy Percentage (`occ_pct`)** metric  
- Merged booking, hotel, room, and date datasets  
- Converted date columns for time-based and monthly analysis  

---

### 4. Business Insights & Analysis
- Average occupancy rate by room category  
- City-wise occupancy performance comparison  
- Weekday vs weekend occupancy analysis  
- Monthly and city-level revenue trends  
- Revenue contribution by booking platform  

---

## Key Insights

- Certain cities consistently achieve **higher occupancy rates**  
- **Weekends outperform weekdays** in occupancy performance  
- **Premium room categories** contribute significantly higher revenue  
- A **small number of booking platforms** generate the majority of total revenue  

---

## Visualizations

The following visualizations highlight key insights derived from the analysis:

---

### 📊 Hotel Count per City
This chart shows the distribution of hotel properties across different cities.

![Hotel Count per City](img/Hotel%20count%20per%20city.png)

---

### 📅 Occupancy Analysis – June
This visualization highlights city-wise occupancy performance for the month of June.

![June Occupancy Analysis](img/In%20the%20month%20of%20June%2C%20what%20is%20the%20occupancy%20for%20different%20cities.png)

---

### 🥧 Revenue Contribution by Booking Platform
This pie chart shows how different booking platforms contribute to total revenue.

![Revenue by Booking Platform](img/a%20pie%20chart%20of%20revenue%20realized%20per%20booking%20platform.png)

---

### 📈 Bookings Data Overview
This chart provides an overview of booking trends from the dataset.

![Bookings Data Overview](img/bookings_data_in_a_datagrame.png)


## How to Run the Project

```bash
# Clone the repository
git clone https://github.com/mohitdubey991735/AtliQ-Hotels-Data-Analysis.git

# Install required libraries
pip install pandas matplotlib

# Open the Jupyter Notebook
jupyter notebook
