# Urban-Mobility-Intelligence-Dashboard
Interactive Tableau dashboard analyzing 9M+ NYC Taxi trips using Python, feature engineering, geospatial analytics, demand forecasting insights, and revenue intelligence.# Urban Mobility Intelligence Dashboard

## Project Overview

The Urban Mobility Intelligence Dashboard is an end-to-end analytics project built using Python and Tableau to analyze over 9 million New York City taxi trips.

The objective of this project is to uncover patterns in transportation demand, revenue generation, passenger behavior, tipping trends, and operational efficiency across New York City. The project demonstrates a complete analytics workflow including data cleaning, feature engineering, exploratory analysis, and interactive dashboard development.

The final solution consists of four interconnected Tableau dashboards that enable users to drill down into specific locations, time periods, boroughs, and trip characteristics through interactive cross-filtering actions.

## Business Problem

Urban transportation systems generate massive volumes of trip-level data every day. Understanding where demand occurs, which locations generate the most revenue, when congestion is highest, and how customer behavior changes across time can help transportation operators improve service quality and optimize resource allocation.

This project aims to answer questions such as:

* Which zones generate the highest revenue?
* What are the busiest pickup hours?
* How does demand vary between weekdays and weekends?
* Which areas experience the highest congestion?
* How does trip distance affect fare generation?
* How do tipping behaviors vary across locations?
* What payment methods generate the most revenue?

---

## Dataset

Source: NYC Taxi & Limousine Commission (TLC)

Data Used:

* January 2024 Yellow Taxi Trip Data
* February 2024 Yellow Taxi Trip Data
* March 2024 Yellow Taxi Trip Data
* NYC Taxi Zone Lookup Dataset

Total Records Analyzed:

* 9+ Million Taxi Trips

---

## Data Cleaning

Data cleaning was performed using Python (Pandas).

Cleaning steps included:

* Removed trips with invalid fare amounts
* Retained fare amounts between $2.50 and $500
* Retained trip distances between 0.1 and 100 miles
* Removed trips with unrealistic durations
* Filtered invalid pickup and dropoff zones
* Removed records containing null location IDs
* Removed invalid passenger count records
* Standardized date and time fields

---

## Feature Engineering

Additional analytical features were created to support business insights.

### Time-Based Features

* Trip Duration (Minutes)
* Hour of Day
* Day of Week
* Month
* Quarter
* Year
* Weekend Indicator
* Peak Hour Indicator

### Revenue Features

* Revenue per Mile
* Revenue per Trip

### Operational Features

* Average Speed (MPH)
* Congestion Classification

### Customer Behavior Features

* Tip Percentage
* Airport Trip Indicator

---

## Dashboard Architecture

The project contains four interactive dashboards.

### 1. Geographic Insights Dashboard

Purpose:

Analyze revenue generation and trip demand across NYC zones.

Visualizations:

* Revenue Map
* Trip Density Map
* Top Revenue Generating Zones
* Borough Revenue Trend

Key Insights:

* Identifies high-performing revenue zones
* Highlights geographic demand concentration
* Compares borough-level revenue trends

---

### 2. Demand Analytics Dashboard

Purpose:

Understand temporal demand patterns and rider behavior.

Visualizations:

* Hourly Demand Distribution
* Weekday vs Weekend Demand Comparison
* Demand Heatmap
* Peak Hour Analysis

Key Insights:

* Peak demand occurs during commuting hours
* Weekday demand significantly exceeds weekend demand
* Demand patterns vary by hour and day

---

### 3. Revenue & Customer Behavior Dashboard

Purpose:

Evaluate fare generation and customer payment behavior.

Visualizations:

* Fare vs Distance Analysis
* Revenue by Zone
* Revenue by Rate Code
* Tip Behavior by Zone
* Revenue by Payment Type

Key Insights:

* Airport routes generate substantial revenue
* Credit card transactions dominate revenue streams
* Tipping behavior varies significantly across locations

---

### 4. Operational Efficiency Dashboard

Purpose:

Analyze transportation efficiency and congestion patterns.

Visualizations:

* Revenue per Hour by Zone
* Average Speed by Hour
* Passenger Analysis
* Dispute Rate Trend

Key Insights:

* Congestion peaks during daytime operating hours
* Certain zones generate higher revenue efficiency
* Passenger count influences average fare values

---

## Interactive Features

The dashboards are connected through Tableau dashboard actions.

Source Sheets:

* Revenue Map
* Hourly Demand
* Fare vs Distance
* Revenue per Hour by Zone

Functionality:

Selecting a region, hour, fare cluster, or revenue zone dynamically filters the remaining visualizations, allowing users to perform detailed exploratory analysis without changing dashboards.

This interaction creates a drill-down analytical experience similar to enterprise business intelligence applications.

---

## Tools & Technologies

### Data Processing

* Python
* Pandas
* NumPy

### Visualization

* Tableau Desktop

### Data Source

* NYC Taxi & Limousine Commission (TLC)

### Geographic Analysis

* Tableau Maps
* Taxi Zone Lookup Dataset

---

## Project Structure

---

## Business Impact

This project demonstrates the ability to:

* Process and clean large-scale datasets
* Perform feature engineering for business analytics
* Develop interactive executive dashboards
* Conduct geospatial analysis
* Identify revenue drivers and operational bottlenecks
* Translate raw transportation data into actionable business insights

The analytical workflow mirrors real-world responsibilities commonly found in Data Analyst, Business Analyst, Business Intelligence Analyst, and Data Scientist roles.


