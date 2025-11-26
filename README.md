# 🏡 Airbnb Market Analysis Dashboard – README
## 📌 Project Objective

Analyze Airbnb pricing patterns, monthly trends, geographical distribution, and listing availability to understand market behavior. The goal is to identify pricing drivers, high-value areas, seasonal variations, and how bedroom count impacts both price and supply.

## 📂 Dataset Overview

The dataset contains property-level information including:

Zipcodes & Geographic Coordinates

Monthly Calendar Prices

Bedroom Count & Listing Count

Property Attributes (Beds, Bedrooms, etc.)

## 📅 Period Covered: Full yearly cycle (Monthly calendar data)

## ❓ Key Questions (KPIs)
## 💰 Pricing Insights

Which zipcodes have the highest average listing price?

How does the average calendar price change month to month?

What is the price variation by bedroom count?

## 🏘️ Supply Insights

Which bedroom category has the highest number of listings?

How does listing count shift across bedroom sizes?

## 🌍 Geographical Insights

Which neighborhoods show the strongest pricing clusters?

How does price vary geographically on the map?

## 🔧 Process
### 1. Data Cleaning

- Standardized zipcode formats
- Validated price values and removed outliers
- Converted month names & dates into usable formats
- Ensured bedroom counts and numeric fields were clean and consistent
- Removed null values

### 2. Data Analysis

- Calculated average prices by zipcode, month, and bedroom count
- Computed bedroom-wise listing volumes
- Visualized geographic pricing using Mapbox
- Identified trends in price fluctuations throughout the year

### 3. Dashboard Development

#### Created a multi-visual dashboard featuring:
- Bar Chart – Avg Price Per Zipcode
- Map Visualization – Geo-pricing by location
- Line Chart – Monthly price trend
- Bar Chart – Avg Price vs Bedroom Count
- Horizontal Bar Chart – Listing Count per Bedroom
- Filters include month, zipcode, and property attributes (optional).

## 📊 Dashboard Preview

![Airbnb_dashboard.png](https://github.com/ShadQm/Airbnb_Excel_Tableau_Project/blob/main/Airbnb_dashboard.png)

- Avg Price Per Zipcode – Shows price clusters with 98109 and 98105 as top performers
- Map View – Highlights geographical differences in Seattle area pricing
- Avg Price Per Month – Shows seasonality, peaking around June–August
- Avg Price by Bedroom – 5-bedroom units have highest avg price
- Listing Count by Bedroom – 1-bedroom units dominate total listing supply

## 🔍 Key Insights
### ✅ Pricing Patterns

- 98109 leads with the highest price (~162).
- 98103 and 98107 are among the most affordable zipcodes.
- Prices peak mid-year (June–August) reflecting seasonal travel.

### 🏠 Bedroom Analysis

- 5-bedroom properties show the highest average price (~890).
- 1-bedroom units hold the highest inventory count (1.4M listings).
- Studio/0-bed units have moderate pricing but lower supply.

### 🌍 Geographical Trends

- High-value listings cluster in key central zipcodes.
- Peripheral zipcodes display more moderate pricing.

## 🧠 Final Conclusion

Airbnb prices in this region show strong geographic clustering and clear seasonal trends. Larger homes yield significantly higher revenue potential, while 1-bedroom units dominate the market supply.

Understanding zipcode-level pricing and monthly trends is crucial for:

Hosts optimizing listing prices
Investors identifying profitable neighborhoods
Analysts studying seasonal and geographic influences

The dashboard provides a high-level yet actionable view of pricing behavior and supply distribution across the Airbnb market.
