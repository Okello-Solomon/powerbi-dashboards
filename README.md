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
