#  1. Amazon Prime Content Analysis Dashboard

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

![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/a2538480c2a5b67707b3fc48bef55c128e566cff/Amazon%20Prime%20Videos.pbix.png)


#  2. BMW Car Sales Classification Dashboard: Driving Performance Analysis

##  Project Overview

This interactive dashboard was developed to provide a comprehensive, data-driven analysis of BMW vehicle sales performance, focusing on classifying sales into **“High”** or **“Low”** volume categories.  
The primary objective is to equip sales managers and strategists with powerful, flexible tools to optimize inventory, pricing, and regional market focus.

<details>
<summary><strong> View Project Details</strong></summary>

##  Key Performance Indicators (KPIs)

The dashboard provides immediate visibility into the overall scale and health of the sales operation:

- **Total Revenue:** $19.01 Trillion  
- **Total Sales Volume:** 253.38 Million units  
- **Average Selling Price:** $75,035 USD  
- **Average Mileage:** 100,307 KM  

##  Core Analytical Capabilities: Flexible, Segmented Visualizations

The dashboard utilizes advanced **Field Parameters** to allow users to fully customize the analysis within core visualizations, drastically speeding up root cause and comparative analysis.

###  Dynamic Measures (X-Axis Selection)

Users can select the quantitative measure displayed on the X-axis of key charts, allowing them to compare the same dimension across different financial and operational metrics.

**Measures Available for X-Axis & Purpose**
- **Total Revenue:** Financial comparison of total sales value  
- **Total Sales Volume:** Operational comparison of units sold  
- **Average Price (USD):** Strategic comparison of average selling price  
- **Average Mileage (KM):** Operational comparison of average vehicle use/condition  

###  Dynamic Dimensions (Y-Axis / Category Selection)

Users can select the categorical dimension used to group and segment data on the Y-axis, enabling deep dives into product features, market performance, and sales outcomes.

**Dimensions Available for Y-Axis & Purpose**
- **Model:** Compare performance across BMW product lines (e.g., X3 vs. 5 Series)  
- **Region:** Benchmark performance across global markets  
- **Fuel_Type:** Assess the impact of engine type (Petrol, Diesel, Hybrid, Electric)  
- **Color:** Identify customer preferences and inventory bottlenecks based on color  
- **Sales_Classification:** Analyze the factors driving “High” versus “Low” performance  
- **Transmission:** Segment performance by Manual vs. Automatic transmission  

##  Tools Used
- **Visualization Platform:** Power BI  
- **Modeling Language:** DAX (Data Analysis Expressions) for creating robust measures and Field Parameters that enable dynamic functionality  

##  Data Source
- **Dataset:** BMW_Car_Sales_Classification.csv  
- **Source:** [BMW Car Sales Dataset on Kaggle](https://www.kaggle.com/datasets/sumedh1507/bmw-car-sales-dataset)

</details>

![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/524ee74c2f7326834c631bb1629a0f78d0e6a59c/BMW%20Car%20Sales%20Dashboard..png)


#  3. Global Airline Operations & Passenger Insights Dashboard (2022)

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

###  Dynamic Metrics (Y-Axis Selection)

Users can select the quantitative metric displayed on the Y-axis, allowing the same visual to answer different operational and demographic questions.

**Metrics Available & Purpose**
- **Average Age:** Analyze passenger demographic trends  
- **Total Flights:** Measure operational scale and activity  
- **Cancellation Rate (%):** Evaluate service disruptions  
- **Delay Rate (%):** Assess punctuality challenges  
- **On-Time Rate (%):** Monitor operational reliability  

###  Dynamic Dimensions (X-Axis Selection)

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



# 4. Superstore Performance & Profitability Dashboard



## Project Overview

This interactive dashboard delivers a comprehensive, data-driven analysis of retail performance, profitability, and operational efficiency using the Superstore dataset.
It is designed to move beyond high-level sales totals and uncover the true drivers of profit, loss, and growth across products, customers, and regions.

The primary objective is to equip business stakeholders and analysts with dynamic, flexible analytical tools to identify loss-making products, evaluate regional performance, optimize discount strategies, and apply the Pareto (80/20) principle for revenue optimization.

<details> <summary><strong>View Project Details</strong></summary>

  
## Key Performance Indicators (KPIs)

The dashboard provides an immediate snapshot of the overall scale and health of Superstore operations:

- **Total Sales:** $2.30M

- **Total Profit:** $286.40K

- **Profit Margin:** 12.5%

- **Total Orders:** 5,009

- **Total Quantity Sold:** 38K

- **Active Customers:** 793

These KPIs dynamically respond to slicers for Region, Segment, and Order Year, enabling instant performance comparisons across business dimensions.

## Core Analytical Capabilities: Dynamic & Flexible Insights

The dashboard leverages Field Parameters and DAX logic to allow users to switch metrics and dimensions without duplicating visuals, maximizing analytical depth while maintaining a clean layout.

### Dynamic Metrics (X / Y-Axis Selection)

Users can toggle between multiple quantitative measures to evaluate performance from different financial perspectives:

- **Total Sales:** Measure top-line revenue scale

- **Total Profit:** Analyze bottom-line contribution

- **Total Discount:** Monitor the cost and impact of promotions

### Dynamic Dimensions (Category Selection)

Data can be dynamically grouped by:

- **Geography:** Region, State, or City

- **Product Hierarchy:** Category or Sub-Category

- **Customer Segment:** Consumer, Corporate, Home Office

This enables rapid cross-sectional analysis across markets and product lines.

## Advanced Business Analytics

### Pareto Analysis - Sub-Category Sales Contribution (80/20 Rule)

This Pareto chart analyzes Total Sales by Product Sub-Category, combining a bar chart and a cumulative percentage line to apply the Pareto Principle (80/20 rule) to retail revenue performance.

- **Bars (Primary Axis):** Represent total sales revenue generated by each product sub-category, sorted in descending order from highest to lowest.

- **Cumulative Line (Secondary Axis):** Shows the running percentage contribution of each sub-category to total sales.

#### Key Insights

A small number of sub-categories (such as Phones, Chairs, Storage, Tables, and Binders) account for a disproportionately large share of total revenue.

Approximately 20–30% of sub-categories generate nearly 80% of total sales, confirming a classic Pareto distribution in the Superstore product mix.

Beyond this point, additional sub-categories contribute incrementally smaller revenue, indicating diminishing returns.

## Regional Profitability Matrix

A high-density matrix with conditional formatting visualizes profitability by State and Product Category.

- **Green Zones:** Strong profit contributors (e.g., California, New York)

- **Red Zones:** Margin-bleeding regions (e.g., Texas, Ohio)

This view enables instant identification of geographic risk and opportunity zones.

## Top-N Customer Analysis

A Numeric Range Parameter (Top 1–20) allows users to dynamically rank customers by sales.

- **Interactive Slider:** Adjusts the Top-N threshold instantly

- **Design Choice:** Horizontal bars ensure readability of long customer names

- **Business Use:** Identifies high-value accounts for retention and targeted marketing

## Sales & Profit Trends Over Time

A dual-line chart tracks Sales vs. Profit by Year, revealing:

Revenue growth from 2014 to 2017

A widening gap between sales and profit, reinforcing the need for discount optimization and margin control

## Tools & Technical Stack

Visualization Platform: Power BI Desktop

- **Modeling & Analytics:** DAX (Field Parameters, Top-N Ranking, Pareto Logic, Time Intelligence)

- **Data Transformation:** Power Query (cleaning, normalization, date table creation)

## Data Source

**Dataset:** Sample Superstore Dataset (Retail Operations)

**Source:** [Superstore Dataset on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)  

</details>


![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/73066b52c6371268552c6462cb580233f7a54b7f/Superstore%20Performance%20Dashboard%201.PNG)



![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/a58020beb68fa5ebea0d29af93ff1e5077eba892/Superstore%20Performance%20Dashboard%202.PNG)



 # 5. Paris 2024 Olympic Performance Analytics Dashboard

 
## Project Overview

The dashboard analyzes performance, participation, and representation at the Paris 2024 Summer Olympic Games.

Using the official Paris 2024 Kaggle dataset, the dashboard goes beyond medal tables to uncover structural, organizational, and social dynamics of the Games focusing on gender parity, technical leadership, and national specialization strategies.

Paris 2024 was branded as the first gender-equal Olympics.
This project evaluates how that ambition translated from athlete quotas into coaching, officiating, and competitive outcomes.

<details> <summary><strong>View Project Details</strong></summary>

  
## Project Objective

To design a narrative-driven analytics dashboard that:

Evaluates Olympic performance beyond medal counts

Assesses gender parity across athletes, coaches, and officials

Identifies national specialization and power concentration strategies

Enables flexible, user-driven exploration through advanced DAX modeling



## Executive KPIs

At a glance, the dashboard captures the scale and complexity of the XXXIII Olympiad:

- **11,100+ Total Athletes**

- **206 Participating Countries (NOCs)**

- **198 Nationalities**

- **52 Sports**

- **28 Team Sports**

- **35 Competition Venues**

- **974 Coaches**

- **1,021 Technical Officials**

These KPIs frame the Olympics as both a global sporting event and a large-scale organizational system.

## Key Insights & Visualizations

### 1. Dynamic Analysis: The "Multi-Dimensional" Explorer
To allow for deep exploration of the Paris 2024 results, I implemented Dynamic Field Parameters. This allows the user to toggle the entire dashboard’s view instantly across different categories.

#### X-Axis:

- **Total Medals:** The core volume metric.


#### Y-Axis (Dynamic Selection): The viewer can switch the Y-Axis to analyze medal distribution by:

- **Discipline:** Which sports are most "top-heavy" with medals?

- **Gender:** Comparing participation and success rates.

- **Country:** Traditional leaderboard view.

- **Event:** Deep dive into specific competitions.

- **Medal Type:** Breakdown by Gold, Silver, and Bronze.

### 2. The Gender Parity Milestone
Paris 2024 marked a historic shift as the first Olympic Games to achieve full gender parity. My analysis explores how this balance was distributed across different nations and disciplines.

- **Metric:** Athlete Gender Ratio (%)

- **Feature:** Interactive Tooltips; Users can hover over any segment to see the precise percentage breakdown between Male and Female participants.

### 3. Distribution of Coaches by Gender
This visualization highlights a clear gender gap in technical leadership, with male coaches overwhelmingly represented (743) compared to female coaches (231), underscoring the continued underrepresentation of women in elite coaching roles.

### 4. Distribution of Technical Officials
The visualization indicates that men constitute 652 technical officials (63.86%), making up nearly two-thirds of the total, while women account for 369 officials (36.14%), representing just over one-third. This distribution highlights a noticeable gender imbalance in technical officiating roles, with male participation remaining dominant.

### 5. Total Teams by Discipline 
This chart shows the distribution of teams across selected disciplines at the Paris 2024 Olympic Summer Games.
Swimming records the highest participation (371 teams), followed by Rowing (158) and Athletics (142). Other disciplines such as Canoe Sprint, Tennis, Sailing, and Cycling Track etc show lower participation.

### 6. Total Technical Officials by Function 

This bar chart shows the distribution of technical officials across different functions at the Paris 2024 Olympic Summer Games. The data highlights that Referees make up the largest group with 640 officials, followed by Judges with 280 officials. Other roles, including Umpires (26), Jury Members (25), Line Judges (21), and Technical Officials (20), have significantly fewer personnel. Specialized roles such as Challenge Referees (5), Head Judges (2), Jury Chair (1), and Medical Delegates (1) represent a very small portion of the total.

### Power BI

DAX (Measures, Field Parameters)

Interactive Tooltips

### Data Source

The analysis is based on the Paris 2024 Olympic Dataset:

**Source:** [Paris 2024 Olympic Summer Games](https://www.kaggle.com/datasets/piterfm/paris-2024-olympic-summer-games)

</details>

![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/13e04b3759dd9dac0eefdb004036b93bf00d771a/Paris%202024%20Olympic%20Games%20Performance%20Analytics%20Dashboard.PNG)



 # 6. International COVID-19 Surveillance Dashboard
 
## Project Overview

The International COVID-19 Surveillance Dashboard is an advanced Power BI analytics solution designed to monitor, analyze, and compare the global impact of COVID-19 across 209 countries.
The dashboard converts raw surveillance data into actionable public-health insights using interactive visuals, population-normalized metrics, and dynamic analytics controls.

<details> <summary><strong> View Project Details</strong></summary>
  
### This project emphasizes:

Fair cross-country comparison through per-capita indicators

Deep exploratory analysis via Field Parameters

Clear storytelling through multi-level visual design

### Global Snapshot; Key Performance Indicators (KPIs)

**The dashboard opens with a high-level summary of the pandemic’s global status:**

- **Total Countries Monitored:** 209

- **Total Tests Conducted:** 268M

- **Total Confirmed Cases:** 19M

- **Total Recovered:** 12M (62.97% recovery rate)

- **Total Deaths:** 713K (3.72% fatality rate)

- **Active Cases:** 6M

These KPIs provide immediate situational awareness of global disease burden and outcomes.

### Visual Analytics & Insights

#### 1. Current Disease Burden

Treemap – Total Active Cases by Continent

This visual shows where COVID-19 pressure is currently concentrated:

- **North America:** ~3M active cases

- **Asia & South America:** ~1M each

- **Lower burden observed in Europe and Africa**

**Insight:** The treemap quickly identifies regions under the greatest healthcare strain.

#### 2. Case Outcome Distribution

Donut Chart; Active Cases, Recoveries, and Deaths

**Global case outcomes are distributed as:**

- **Recovered:** ~65.4%

- **Active:** ~30.7%

- **Deaths:** ~3.9%

**Insight:** While recovery dominates, a substantial proportion of active cases indicates sustained transmission risk.

#### 3. Population-Adjusted Severity Funnel

Funnel Chart; COVID-19 Intensity per 1M Population

This funnel chart provides a population-normalized view of the COVID-19 surveillance pipeline, illustrating how testing volume translates into infections and fatalities when adjusted for population size.

**Funnel Stages (Per 1M Population):**

- **Testing Intensity:** ~16.04M tests per 1M population

- **Infection Rate:** ~0.66M cases per 1M population

- **Mortality Rate:** ~0.02M deaths per 1M population

**Insight:**
The funnel highlights the attrition from testing to confirmed infection to mortality, offering a clear view of pandemic severity independent of population size. This allows users to compare true impact and health-system outcomes across regions without bias from absolute population counts.

### Population-Normalized Comparative Analysis (Per 1M Population)

To enable equitable comparisons across countries with vastly different population sizes, the dashboard uses per-1M population metrics throughout its analytical visuals.

 #### 4. Column Chart Variant 1; Broad Comparative View

Dynamic Column Chart (Multi-Level Comparison)

**X-Axis (Field Parameter):**

- **Continent**

- **Country/Region**

- **WHO Region**

**Y-Axis (Per 1M Population – Field Parameter):**

- **Infection**

- **Mortality Rate**

- **Testing Intensity**

**Purpose:**
Supports high-level global and regional comparisons, including WHO-standardized regional analysis.

#### 5. Column Chart Variant 2; Focused Country & Continent View

Dynamic Column Chart (Ranking & Precision Analysis)

**X-Axis (Field Parameter):**

- **Country/Region**

- **Continent**

**Y-Axis (Per 1M Population – Field Parameter):**

- **Infection Rate**

- **Mortality Rate**

- **Testing Intensity**

**Purpose:**
Optimized for precise country-level ranking and severity analysis, excluding WHO Region to:

Reduce aggregation bias

Improve interpretability

Clearly identify outliers

Example Insight:

San Marino (1,238) and Belgium (850) emerge as global leaders in mortality rate per 1M population, insights obscured in absolute counts.

### Advanced Interactivity & Analytics Engine

#### Field Parameters (Dynamic Analytics)

The dashboard uses Power BI Field Parameters to allow real-time switching of:

Analytical dimensions (X-axis)

Population-normalized indicators (Y-axis)

This design enables exploratory analysis without duplicating visuals, improving usability and performance.

#### Granular Filtering

Country slicer for national drill-downs

WHO Region slicer for standardized global comparisons

All visuals respond dynamically to slicer selections

#### Analytical Techniques

DAX-based 7-Day Moving Averages to smooth daily volatility and reveal underlying trends

Population-Normalized Metrics (Per 1M) for fair comparison

Spatiotemporal Mapping via Bing Maps for geographic surveillance

### Technical Stack

- **Tool:** Power BI Desktop

- **Data Modeling & Logic:** DAX

- **Interactivity: Field Parameters & Slicers

- **Mapping:** Bing Maps Integration

### Data Source

The analysis is based on a global COVID-19 surveillance dataset compiled from publicly reported health data.

**Source:** [COVID-19 Global Report Dataset](https://www.kaggle.com/datasets/imdevskp/corona-virus-report)

</details>

![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/34694cb905b17b31f6a8aae0019580b18460de67/COVID-19%20Surveillance%20Dashboard%201.PNG)



![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/70c84ca930e946864f2b46fe381b0c4f87ac050d/COVID-19%20Surveillance%20Dashboard%202.PNG)



# 7.Telecom Customer Churn Analysis Dashboard

![image alt]()

