#  Amazon Prime Content Analysis Dashboard

##  Project Overview

This repository features an interactive dashboard created to analyze the content library of **Amazon Prime Video**.  
It provides key insights into the distribution, performance, and trends of movies and TV shows to better understand the platform’s content strategy and viewer engagement.

<details>
<summary><strong> View Project Details</strong></summary>

###  Project Objective
To visualize and analyze key metrics that drive strategic content planning and marketing decisions for a streaming platform.

###  Key Insights & Visualizations
- **Content Type Breakdown:** Ratio of Movies vs. TV Shows  
- **Genre Popularity:** Distribution of titles across genres  
- **Release Year Trends:** Growth and shifts in release patterns  
- **Global Reach:** Content production by country  
- **Ratings Analysis:** Content rating distribution

###  Tools & Technologies
- Power BI

###  Data Source
The analysis is based on a publicly available dataset of Amazon Prime Movies and TV Shows.
- [Amazon Prime Movies and TV Shows Data Set on Kaggle](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows/data)
- Fields: title, director, cast, country, release_year, rating, duration, listed_in (genre).

</details>


# 🚗 BMW Car Sales Classification Dashboard: Driving Performance Analysis

## 🎯 Project Overview

This interactive dashboard was developed to provide a comprehensive, data-driven analysis of BMW vehicle sales performance, focusing on classifying sales into **“High”** or **“Low”** volume categories.  
The primary objective is to equip sales managers and strategists with powerful, flexible tools to optimize inventory, pricing, and regional market focus.

<details>
<summary><strong>📖 View Project Details</strong></summary>

## 📊 Key Performance Indicators (KPIs)

The dashboard provides immediate visibility into the overall scale and health of the sales operation:

- **Total Revenue:** $19.01 Trillion  
- **Total Sales Volume:** 253.38 Million units  
- **Average Selling Price:** $75,035 USD  
- **Average Mileage:** 100,307 KM  

## 🔍 Core Analytical Capabilities: Flexible, Segmented Visualizations

The dashboard utilizes advanced **Field Parameters** to allow users to fully customize the analysis within core visualizations, drastically speeding up root cause and comparative analysis.

### 1. Dynamic Measures (X-Axis Selection)

Users can select the quantitative measure displayed on the X-axis of key charts, allowing them to compare the same dimension across different financial and operational metrics.

**Measures Available for X-Axis & Purpose**
- **Total Revenue:** Financial comparison of total sales value  
- **Total Sales Volume:** Operational comparison of units sold  
- **Average Price (USD):** Strategic comparison of average selling price  
- **Average Mileage (KM):** Operational comparison of average vehicle use/condition  

### 2. Dynamic Dimensions (Y-Axis / Category Selection)

Users can select the categorical dimension used to group and segment data on the Y-axis, enabling deep dives into product features, market performance, and sales outcomes.

**Dimensions Available for Y-Axis & Purpose**
- **Model:** Compare performance across BMW product lines (e.g., X3 vs. 5 Series)  
- **Region:** Benchmark performance across global markets  
- **Fuel_Type:** Assess the impact of engine type (Petrol, Diesel, Hybrid, Electric)  
- **Color:** Identify customer preferences and inventory bottlenecks based on color  
- **Sales_Classification:** Analyze the factors driving “High” versus “Low” performance  
- **Transmission:** Segment performance by Manual vs. Automatic transmission  

## 🛠️ Tools Used
- **Visualization Platform:** Power BI  
- **Modeling Language:** DAX (Data Analysis Expressions) for creating robust measures and Field Parameters that enable dynamic functionality  

## 📂 Data Source
- **Dataset:** BMW_Car_Sales_Classification.csv  
- **Source:** [BMW Car Sales Dataset on Kaggle](https://www.kaggle.com/datasets/sumedh1507/bmw-car-sales-dataset)

</details>


#  Global Airline Operations & Passenger Insights Dashboard (2022)

##  Project Overview

This interactive dashboard was developed to deliver a comprehensive, data-driven analysis of global airline operations and passenger travel patterns.  
The primary objective is to equip aviation stakeholders, analysts, and decision-makers with flexible, interactive tools to assess operational performance, identify reliability challenges, and understand passenger demographics at a global scale.

<details>
<summary><strong> View Project Details</strong></summary>

##  Key Performance Indicators (KPIs)

The dashboard provides immediate visibility into the overall scale and health of global airline operations:

- **Total Customers:** 98.62K  
- **Countries Covered:** 235  
- **Nationalities Represented:** 240  
- **Cancellation Rate:** 33.40%  
- **Delay Rate:** 33.29%  
- **On-Time Rate:** 33.31%  

##  Core Analytical Capabilities: Dynamic & Flexible Insights

The dashboard leverages advanced **Field Parameters** and **DAX logic** to enable users to dynamically explore multiple analytical perspectives within a limited visual footprint.

### 1. Dynamic Metrics (Y-Axis Selection)

Users can select the quantitative metric displayed on the Y-axis, allowing the same visual to answer different operational and demographic questions.

**Metrics Available & Purpose**
- **Average Age:** Analyze passenger demographic trends  
- **Total Flights:** Measure operational scale and activity  
- **Cancellation Rate (%):** Evaluate service disruptions  
- **Delay Rate (%):** Assess punctuality challenges  
- **On-Time Rate (%):** Monitor operational reliability  

### 2. Dynamic Dimensions (X-Axis Selection)

Users can dynamically change how data is grouped on the X-axis to compare performance across key categorical dimensions.

**Dimensions Available & Purpose**
- **Continent:** Compare regional performance and reliability  
- **Gender:** Analyze passenger distribution by gender  

##  Dynamic Top-N Airport Ranking

A Top-N airport analysis is implemented using a **Numeric Range Parameter (1–20)** and a custom DAX measure.

- **Interactive Slider:** Instantly adjusts rankings from Top 5 to Top 20 airports  
- **Design Choice:** Airport Name placed on the Y-axis for readability of long international names  
- **Insight Value:** Identifies high-impact airports and global operational hubs  

##  Regional Reliability Analysis

A 100% stacked bar chart visualizes Flight Status composition by continent, normalizing values to allow fair comparisons across regions of different sizes.

**Key Insight:**  
Across all continents, flight outcomes are split almost evenly (~33% On-Time, Delayed, Cancelled), indicating a systemic global reliability challenge in 2022 rather than isolated regional issues.

##  Passenger Demographics

**Gender Distribution**
- **Male:** 50.29%  
- **Female:** 49.71%  

**Passenger ID by Flight Status**
- Breakdown of passenger volumes associated with each flight outcome  

##  Tools Used
- **Visualization Platform:** Power BI  
- **Modeling Language:** DAX (Field Parameters, Top-N logic, dynamic measures)  

##  Data Source
- **Dataset:** Airline Dataset  
- **Source:** [Airline Dataset on Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/airline-dataset)  

</details>

![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/23176512e1d4c5dd26398aefae71c6c496f747cd/Dashboard.PNG)
