# 🏠 Airbnb Pricing Dashboard

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Data_Analysis](https://img.shields.io/badge/Analysis-Geospatial-blue?style=for-the-badge)

## 📋 Project Overview
This project presents an interactive Tableau dashboard designed to analyze the Airbnb rental market. By visualizing pricing trends, listing distributions, and seasonal revenue, this tool provides a clear and straightforward overview of market dynamics for property owners and analysts.

## 🎯 Project Objectives
The goal was to answer practical business questions regarding the short-term rental market:
* How does the number of bedrooms impact the average rental price?
* Which specific Zipcodes command the highest prices?
* What are the seasonal revenue patterns throughout the year?
* What is the distribution of listings based on property size?

---

## 📊 Dashboard Key Features
The dashboard provides a focused view of the market through several analytical layers:

1. 💰 **Pricing Overview:** A bar chart showing the "Average Price Per Bedroom," helping to quickly benchmark rental rates.
2. 📍 **Geospatial Mapping:** A "Price Per Zipcode" map that visually highlights the most expensive and affordable areas for rentals.
3. 📈 **Seasonal Trends:** A time-series line chart ("Revenue for Year") that tracks revenue fluctuations to identify peak booking seasons.
4. 🏢 **Market Distribution:** A breakdown of "Distinct Count of Listings" to show which property sizes (1-6 bedrooms) are most common in the market.
5. 🔍 **Location Comparison:** A secondary bar chart for a precise comparison of prices across all Zipcodes.

---

## ⚙️ Technical Workflow

### 1. Data Preparation
* Processed the dataset to ensure Zipcodes and pricing data were correctly formatted for Tableau’s mapping engine.
* Filtered data to focus on relevant property sizes (e.g., 1-6 bedrooms) to maintain a clear and accurate analysis.

### 2. Data Visualization
* Built custom calculated fields in Tableau for revenue and pricing metrics.
* Designed a clean, intuitive layout with interactive filters allowing users to drill down into specific Zipcodes.

---

## 🚀 Key Insights
* **Location Value:** Identified specific Zipcodes that consistently outperform the market average.
* **Property Sizing:** Demonstrated how revenue scales with bedroom count, assisting in pricing strategies.
* **Seasonality:** Pinpointed the months with the highest revenue, enabling better planning for peak seasons.
