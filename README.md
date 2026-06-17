# 1. Employee Performance & Workforce Analytics Dashboard

## Project Overview

This interactive Power BI dashboard provides a data-driven analysis of employee performance, attrition, satisfaction, and workforce stability using the INX Future Inc. Employee Performance dataset. The project aims to help HR leaders and decision-makers identify key factors affecting productivity, retention, employee engagement, and organizational performance.

The dashboard delivers actionable insights into performance bottlenecks, attrition risk, promotion gaps, and workplace satisfaction through interactive visual analytics and workforce segmentation. INX Future Inc. has a workforce of 1,200 employees across 6 departments, with an average employee age of 36.92 years and 11.33 years of work experience.

The analysis highlights emerging organizational challenges related to employee retention, promotion stagnation, and maintaining high-performing talent, all of which directly impact productivity, service delivery, and client satisfaction.

<details>
<summary><strong> View Project Details</strong></summary>
  
## Workforce Structure & Demographic Insights
The analysis shows that most employees at INX Future Inc. are within the 30-40 years age group, indicating a mature and experienced workforce. Employees at this stage typically prioritize career growth, promotion opportunities, work-life balance, job stability, and recognition, making employee engagement a key driver of performance and retention.

### Key Performance Indicators (KPIs)
The dashboard provides an immediate snapshot of workforce scale, employee stability, and organizational health:
-	Total Employees: 1,200
-	Departments: 6
-	Average Employee Age: 36.92 Years
-	Average Distance from Home: 9.17 KM
-	Average Hourly Rate: 65.98
-	Average Work Experience: 11.33 Years
-	Attrition Rate: 14.83%
-	Average Training Time: 2.79 Hrs
  
These KPIs dynamically respond to dashboard slicers and segmentation filters.

### Employee Performance Distribution (Donut Chart)
The employee performance analysis indicates that the majority of employees at INX Future Inc. are performing at a high level. Most employees fall under the Excellent performance category, accounting for approximately 72.83% of the workforce. Employees rated as Good represent about 16.17%, while 11.00% achieved the highest rating of Outstanding.

### Employee Attrition Analysis (100% Stacked Bar Chart)
Employee attrition highlights a key organizational risk. The “Good” performance group shows the highest attrition rate (18.56%), followed by "Excellent" (14.19%) and "Outstanding" (13.64%).
Although "Excellent" employees have a lower attrition rate, they account for the highest number of exits due to their large workforce share, indicating a notable loss of core talent.
Overall, the pattern suggests retention challenges among mid-level performers and the need to protect high-performing employees critical to productivity and service delivery.

### Environment Satisfaction & Performance Relationship (Heatmap)
The analysis reveals a strong relationship between workplace environment satisfaction and employee performance. Employees with High environment satisfaction recorded 310 “Excellent” and 54 “Outstanding” ratings, while those with Very High satisfaction recorded 307 “Excellent” and 51 “Outstanding” ratings.

In contrast, employees with Low satisfaction recorded only 127 “Excellent” ratings but a much higher number of “Good” ratings (90), while Medium satisfaction employees recorded 130 “Excellent” and 98 “Good” ratings. This suggests that higher workplace satisfaction is strongly associated with better employee performance outcomes.

### Employee Count by Performance Rating and Attrition (Clustered Column Chart)
This chart compares employee retention and attrition across performance levels.

Excellent performers had 750 stayed and 124 left, with an attrition rate of 14.19%, representing the highest number of total exits and a key loss of high-value talent.
Good performers recorded the highest attrition rate at 18.56%, with 158 stayed and 36 left, indicating higher disengagement in this group.

Outstanding performers showed the lowest attrition rate of 13.64%, with 114 stayed and 18 left, reflecting stronger retention among top performers.
Overall, attrition is more concentrated among mid and high performers rather than low performance groups, suggesting retention challenges are driven more by engagement and career growth factors than performance ability.

### Employee Count by Department and Performance Rating (100% Stacked Bar Chart)
This 100% stacked bar chart analyzes the distribution of employee performance ratings across departments, showing the proportion of employees classified as Excellent, Good, and Outstanding within each department.

**Key Insights**

-	Development recorded one of the strongest performance profiles, with 84.21% Excellent (304 employees) and 12.19% Outstanding (44 employees), while only 3.6% Good (13 employees). 
-	Data Science had the highest concentration of Excellent performers, with 85% Excellent (17 employees), 10% Outstanding (2 employees), and only 5% Good (1 employee). 
-	Sales showed greater performance variation, with 67.29% Excellent (251 employees), 23.32% Good (87 employees), and 9.38% Outstanding (35 employees), indicating a larger mid-performing workforce. 
-	Research & Development maintained a strong performance structure with 68.22% Excellent (234 employees) and 11.95% Outstanding (41 employees), though 19.83% (68 employees) remained in the Good category. 
-	Human Resource demonstrated relatively balanced performance levels, with 70.37% Excellent (38 employees), 18.52% Good (10 employees), and 11.11% Outstanding (6 employees). 
-	Finance recorded the weakest performance composition, with the lowest proportion of Excellent performers at 61.22% (30 employees) and the highest Good performer share at 30.61% (15 employees).
-	
**Strategic Insight**
 	
The chart shows that most departments are dominated by Excellent performers, indicating a generally high-performing workforce. However, departments such as Sales and Finance exhibit larger concentrations of “Good” performers, suggesting opportunities for targeted training, employee engagement, and performance development initiatives.


### Dynamic Dashboard Capabilities (Clustered Bar Chart)
The dashboard incorporates advanced Field Parameters, interactive filtering, and DAX-driven analytics to enable flexible workforce exploration without duplicating visuals.

#### Dynamic Metrics (X-Axis Selection)
Users can dynamically switch between multiple workforce metrics:
-	Total Employees
-	Attrition Rate
-	Average Employee Age
-	Average Hourly Rate
-	Average Work Experience
-	Average Training Frequency
-	Average Years Since Last Promotion
-	Average Years With Current Manager

#### Dynamic Dimensions (Y-Axis Selection)
Users can instantly segment analysis across:
-	Department
-	Job Role
-	Attrition Status
-	Gender
-	Marital Status
-	Education Background
-	Job Satisfaction
-	Environment Satisfaction
-	Work-Life Balance
-	Business Travel Frequency
This enables multidimensional workforce analysis within a compact dashboard layout.

### A histogram Employee Age Distribution (Histogram)
The histogram shows the age distribution of employees at INX Future Inc., ranging from 18 to 60 years. Most employees fall within the 30-40 age group, with an average age of around 36-37, indicating a predominantly mid-career workforce.

The distribution is slightly right-skewed, meaning there are fewer older employees as age increases.

## Technical Stack
-	**Visualization Platform:** Power BI Desktop
-	**Modeling & Analytics:** DAX (Field Parameters, Dynamic KPIs, Attrition Measures)
-	**Data Transformation:** Power Query
-	**Analytical Techniques:** Workforce Segmentation, Attrition Analysis, Satisfaction Correlation Analysis, Dynamic Filtering & Drilldowns
  
## Data Source
The analysis is based on the INX Future Inc. Employee Performance Dataset.

**Source:** (INX Future Inc. Employee Performance Dataset)[http://data.iabac.org/exam/p2/data/INX_Future_Inc_Employee_Performance_CDS_Project2_Data_V1.8.xls] 

</details>

![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/ee653adeca312a46767460be8af61616734b05d8/Employee%20Performance%20Analysis/Dashboard%201..png)


![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/bc96abba27c3a9d7da5044da06763b8f1958df74/Employee%20Performance%20Analysis/Dashboard%202..png)

#  2. Amazon Prime Content Analysis Dashboard

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


#  3. BMW Car Sales Classification Dashboard: Driving Performance Analysis

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


#  4. Global Airline Operations & Passenger Insights Dashboard (2022)

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



# 5. Superstore Performance & Profitability Dashboard



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



 # 6. Paris 2024 Olympic Performance Analytics Dashboard

 
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



 # 7. International COVID-19 Surveillance Dashboard
 
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



# 8. Telecom Customer Churn Analysis Dashboard

## **Project Overview:** 
This project focuses on analyzing customer churn in a California-based telecommunications company during Q2 2022. The primary objective is to understand customer behavior, identify key factors influencing churn, and generate actionable insights to support data-driven decision-making and business intelligence reporting.

<details>
<summary><strong> View Project Details</strong></summary>

### **KPI Snapshot**
- Total Customers: 7,043

- Churn Rate: 26.54%

- Retention Rate: 73.46%

- Total Revenue Generated: $170.97M

- Revenue Lost to Churn: $29.48M

- Total Referrals: 110K

- Average Customer Age: 46.51 years

- Cities Covered: 1,106


#### **Key Financial Insight**
More than $29M in revenue has already been lost due to churn, representing a significant leakage risk that requires structured intervention.
Churn is not simply a volume issue, it is a high-value revenue erosion problem.

### **Deep-Dive Analytical Insights**

#### **Customer Status & Revenue Exposure**

##### **Customer Distribution**
- Stayed: 67.02% (37.76K)
- Churned: 26.54% (14.95K)
- Joined: 6.45% (3.63K)
##### **Revenue Contribution by Status**
- Active customers: $105M
- Churned customers: $23M in sunk charges
This confirms that churn directly impacts revenue sustainability.

#### **High-Risk Behavioral Drivers**
##### **Payment Method Risk**
The highest churn concentration occurs among:
- Bank Withdrawal users; 10.6K churned
- More than 3x higher churn compared to Credit Card users
**This suggests:**
- Payment friction
- Lower behavioral commitment
- Weak auto-renewal retention structure

#### **Contract Vulnerability**
Using contract segmentation: 
- Month-to-Month contracts show the highest churn volatility
- One-Year and Two-Year commitments demonstrate stronger retention
Customers without long-term commitment are significantly more likely to leave.

#### **Demographic Profile**
- Male: 50.48%
- Female: 49.52%
Churn is not gender-driven.
- 51.7% Unmarried
Unmarried customers show higher mobility and churn sensitivity.

#### **Service-Level Churn & Retention Analysis**
A central component of this dashboard is the Churn & Retention Matrix by Service Subscription Status, which compares churn behavior between customers who subscribed to specific services (“Yes”) and those who did not (“No”).
This analysis does not reflect time-based decline.
Instead, it highlights behavioral differences between subscribers and non-subscribers.
Across nearly all services, a consistent pattern emerges:
Customers who subscribe to additional value-added services exhibit lower churn rates than those who do not.

##### **High-Impact Service Associations**
**Online Security**
- No: 41.77% churn
- Yes: 14.61% churn
This represents the strongest difference observed. Customers without online security churn at nearly three times the rate of subscribers, indicating a strong association between security services and customer stability.

**Premium Tech Support**
- No: 41.64% churn
- Yes: 15.17% churn
Subscribers to technical support services demonstrate significantly lower churn, reinforcing the importance of reliability and direct assistance.

**Device Protection Plan**
- No: 39.13% churn
- Yes: 22.50% churn
Customers who safeguard their devices show noticeably lower churn, suggesting higher engagement and stronger service attachment.

##### Moderate Service Associations
**Online Backup**
- No: 39.93% churn
- Yes: 21.53% churn
Backup services show a meaningful difference in churn behavior, indicating stronger retention among subscribers.

##### **Moderate-to-Low Impact Services**
**Streaming Movies, Music, and TV**
•	Non-subscribers: 33.68% churn
•	Subscribers: 29.95% churn
Entertainment services are associated with modestly lower churn, though the gap is smaller compared to security and support services.

##### **Minimal Differentiation** 
Unlimited Data
•	No: 32.90% churn
•	Yes: 31.65% churn
The difference is marginal, suggesting unlimited data may be perceived as a baseline expectation rather than a strong retention differentiator.

#### **Service Impact Hierarchy**
1. Security & Technical Support; Strongest association with lower churn
2.	Backup & Protection; Moderate association
3.	Entertainment Add-ons; Incremental improvement
4.	Unlimited Data; Minimal differentiation
This provides clear direction for churn mitigation strategy and service bundling optimization.

### **Dashboard Features & Advanced Modeling**

**Dynamic Axis Exploration (Field Parameters) **

Users can dynamically toggle:

**X-Axis Metrics**
- Total Charges
- Total Revenue
- Customer Counts
- Refunds

**Y-Axis Dimensions**

- Payment Method
- Gender
- Internet Type
- Contract
- City
- Marital Status
- Offer Type
This enables multi-dimensional exploratory analysis without duplicating visuals.

#### **Dynamic X-Axis (Financial & Volume Metrics)**
The X-axis can be swapped to compare Customer Status (Stayed, Churned, Joined) against various financial and behavioral benchmarks:
- **Total Charges ($105M vs $23M): ** Quantifies the "Sunk Revenue" from churned customers compared to the active base.
- **Total Revenue: ** Tracks overall financial health and the $29.48M total revenue lost.
- **Total Customer: ** Visualizes the volume split (e.g., 26.54% Churn Rate).
- **Total Dependents: ** Analyzes household "stickiness"; accounts with more dependents typically show lower churn.
- **Total Refunds: ** Identifies a "Red Flag" correlation between service dissatisfaction and attrition.

#### **Interactive Segmentation (Slicers)**
•	**Customer Status: ** Churned / Joined / Stayed
•	**Contract: ** Month-to-Month / One-Year / Two-Year
•	**Internet Type: ** Fiber Optic / Cable / DSL
•	**Gender: ** Male / Female
All visuals update dynamically.

#### **Technical Stack**
- Visualization Platform: Power BI Desktop
- Modeling Language: DAX
- DISTINCTCOUNT
- CALCULATE
- DIVIDE
- Context-aware measures
- Field Parameters
- Data Transformation: Power Query

#### **Data Source**
[Telecom Customer Churn Dataset]( https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics)

</details>

![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/eb8ff9578b2495973b42d6e9aa86da6b76cb83c9/Telecom%20Customer%20Churn%20Analysis%20Dashboard.png)


# 9. Supply Chain Analysis Dashboard

## Project Overview
This interactive Power BI dashboard provides a deep-dive, data-driven analysis of the supply chain operations for a Fashion and Beauty startup. It moves beyond basic logistics tracking to uncover the critical relationships between manufacturing efficiency, transportation costs, and product profitability.
The primary objective is to empower supply chain managers and stakeholders with dynamic tools to monitor inventory velocity, evaluate supplier reliability, optimize regional distribution hubs, and maintain high-quality standards across a diverse portfolio of makeup products.
<details> <summary><strong>View Project Details</strong></summary>

## Key Performance Indicators (KPIs)
The dashboard provides an immediate snapshot of the operational health and financial scale of the startup:
-	**Total Revenue:** $577.60K
-	**Total Cost:** $58.21K
-	**Gross Profit:** $519.40K
-	**Profit Margin:** 89.92%
-	**Inventory Turnover:** 965.02
-	**Defect Rate:** 0.06%
-	**Avg Shipping Time:** 5.75 Days
These KPIs reflect a high-margin business model with rapid stock movement, where products are sold and replaced nearly 965 times within the period.

## Core Analytical Capabilities
The dashboard uses Power BI Field Parameters and advanced DAX calculations to provide flexible analysis without duplicating visuals. Users can dynamically pivot the report to explore different perspectives of operational performance.

#### Dynamic Metrics (X-Axis Selection)
Users can toggle the bar charts and trends between 9 distinct quantitative measures:
-	**Financials:** Total Revenue, Total Cost, Gross Profit, Profit Margin %.
-	**Operations:** Total Units Produced, Total Units Sold , Total Order Quantity.
-	**Efficiency:** Inventory Turnover and Defect Rate %.
  
#### Dynamic Dimensions (Y-Axis Selection)
The data can be dynamically grouped and analyzed by:
-	**Product & Customer:** Product Type (Skincare, Haircare, Cosmetics) or Customer Demographics.
-	**Logistics:**  Location (Cities), Shipping Carriers, Routes, or Transportation Modes.
  
### Advanced Business Analytics

#### Pareto Analysis - Revenue by Location (80/20 Rule)
This analysis identifies the geographical hubs driving the majority of the company's financial success.
-	The "Vital Few": Mumbai, Kolkata, and Chennai account for about 80% of total revenue, indicating these hubs are the most critical for resource allocation.
#### Logistics & Shipping Distribution
A dedicated histogram analyzes the distribution of SKU shipping durations:
-	While the average shipping time is 5.75 days, a significant cluster of products (33 SKUs) falls into the 8–10 day range.
-	This identifies specific shipping lanes or carriers that require efficiency improvements to meet the startup's speed-to-market goals.
-	Only a small portion of shipments fall into the fastest delivery window
### Revenue Segmentation
-	**Product Type Donut:** Skincare is the dominant revenue engine, contributing 41.83% ($241.63K) of total earnings.
-	**Route Treemap:** Route A is the primary logistics artery, moving $253.20K in value, followed by Route B and C.
  
### User Control & Slicers
A comprehensive slicer panel allows users to filter the entire experience by:
-	**Customer Demographic:** Gender demographics (Female, Male, Non-binary, Unknown).
-	**Supplier Name:** Detailed tracking by Supplier (Supplier 1, 2, 3, 4, 5)
  
### Tools & Technical Stack
-	**Visualization Platform:** Power BI Desktop
-	**Modeling & Analytics:** DAX (Field Parameters, Pareto Calculations, Inventory Velocity Logic).
-	**Data Transformation:** Power Query (Data cleaning, normalization of 24 supply chain features).
  
### Data Source
**Source:** [Supply Chain Analysis Dataset on Kaggle]( https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis/data)
</details>

![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/81edb9b366974a443999e537e5f20862a49fe7ba/Supply%20Chain%20Analysis%20Dashboard.png)

# 10. UK Rail Operations & Revenue Dashboard

## Project Overview
This interactive Power BI dashboard provides a comprehensive analysis of railway operations, revenue performance, and service reliability using UK National Rail journey data.

The project moves beyond simple trip counts and revenue totals to uncover the key drivers of operational efficiency, customer demand, and financial performance. It integrates both business (revenue, pricing) and operational (delays, cancellations, refunds) perspectives into a single analytical solution.

The goal is to support better decision-making in pricing, scheduling, and operational efficiency.

<details> <summary><strong>View Project Details</strong></summary>
  
## Key Performance Indicators (KPIs)
-	Total Journeys: 31,653 
-	Total Revenue: £741,921 
-	Average Ticket Price: £23.44 
-	On-Time Journeys: 27,481 
-	Delays: 2,292 
-	Cancellations: 1,880 
-	On-Time Rate: 86.82% 
-	Refund Rate: 3.53% 
-	Departure Stations: 12
  
**Insight:**

The rail system demonstrates strong reliability, with nearly 87% of journeys on time, though 13.18% of trips (4,172 journeys) experience disruptions, impacting both revenue and customer satisfaction.

## Core Visual Analysis & Insights
### 1. Revenue Distribution by Payment Method (Treemap)
- Credit Card: £469,511 (63.3%) 
- Contactless: £219,444 (29.6%) 
- Debit Card: £52,966 (7.1%) 
**Insight:** 
Credit card payments dominate revenue, contributing nearly two-thirds of total income, indicating strong reliance on digital payment channels.

### 2. Revenue by Ticket Type (Donut Chart)
-	Advance: £309,274 (41.69%) 
-	Off-Peak: £223,338 (30.10%) 
-	Anytime: £209,309 (28.21%)
  
**Insight:**

Advance tickets generate the highest share of revenue primarily due to their strong demand and high purchase volume, while Anytime tickets despite having higher prices contribute less overall because they are used less frequently. This pattern highlights a clear trade-off between volume and pricing, where revenue is driven more by the frequency of purchases rather than premium pricing alone, suggesting that demand plays a more critical role than price in maximizing total revenue.
### 3. Refund Rate by Journey Status (100% Stacked Column Chart)
**Cancelled Journeys**
-	Refund: 69.57% 
-	No Refund: 30.43% 
**Delayed Journeys**
-	Refund: 76.18% 
-	No Refund: 23.82%
  
**Insight:**
 	
Most disrupted journeys lead to refund requests, with delays triggering an even higher refund rate (76%) than cancellations (70%). This suggests that passengers are more sensitive to prolonged inconvenience and uncertainty caused by delays than outright cancellations, highlighting that maintaining punctuality is critical not just for operations but also for minimizing revenue loss and preserving customer satisfaction.
### 4. Trip Distribution by Station (Clustered Bar Chart)
•	Interactive axis allows switching between: 
o	Departure Stations 
o	Arrival Destinations 
**Insight:**
A small number of stations dominate total traffic, indicating that demand is heavily concentrated in key transport hubs.

### 5. Journey Status Distribution (Pie Chart)
-	On-Time: 27,481 (86.82%) 
-	Delayed: 2,292 (7.24%) 
-	Cancelled: 1,880 (5.94%)
  
**Insight:**

The system performs well overall; however, about 1 in every 8 journeys is disrupted, which becomes significant when considered at scale.

### 6. Revenue Breakdown Matrix (Ticket Type × Class × Payment Method)

**Insight:**
The revenue breakdown matrix helps identify high-performing combinations such as Advance tickets purchased in Standard class using Credit Card, while also highlighting low-performing segments that may require targeted optimization to improve overall revenue performance.

### 7. Journey Status by Day of Week (100% Stacked Column Chart)

The “Journey Status by Day of Week” 100% stacked column chart is used to understand how performance varies across different days of the week by comparing the proportions of on-time, delayed, and cancelled journeys. It helps reveal which specific days experience more disruptions either in the form of delays or cancellations compared to others. This insight is useful for operational planning because it allows the rail operator to identify high-risk days and adjust train schedules, maintenance activities, or staffing levels accordingly. It also supports better workforce allocation by ensuring more staff are available on days when disruptions are more likely to occur, ultimately improving service reliability and customer experience.

### 8. Hourly Departure Frequency by Day (Matrix / Heatmap)
The Hourly Departure Frequency by Day heatmap shows clear peak travel periods in the morning (6-9 AM) and evening (4-7 PM), indicating heavy commuter activity during typical work start and end times. In contrast, there is significantly lower activity during midday and late-night hours. Overall, this pattern reflects a strong commuter-driven demand structure, where travel is concentrated around daily work schedules rather than being evenly distributed throughout the day.

### 9. Interactivity & Features
The dashboard is designed for flexible, user-driven analysis:

-	**Slicers:** 
The dashboard is designed to support flexible, user-driven analysis through interactive features. It includes slicers for ticket type and ticket class, allowing users to filter and segment the data based on these two categories.

-	**Dynamic Filtering:**
All visuals update dynamically based on the selected filters, ensuring that insights reflect the user’s choices in real time.

-	**Drill-down Capabilities:**
In addition, the dashboard provides drill-down capabilities, enabling users to move from high-level summaries to more detailed breakdowns for deeper analysis.

## Tools & Technologies
**Visualization:** Power BI Desktop 
**Data Modeling:** DAX (KPIs, ratios, calculated columns) 
**Data Preparation:** Power Query 
**Visualization Techniques:**
-	KPI Cards 
-	Heatmaps 
-	Scatter Plots 
-	Matrix Tables with Conditional Formatting
  
## Data Source: [UK Train Rides]( https://mavenanalytics.io/data-playground/uk-train-rides)

</details>

![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/0895391804b221a71c9743b5821387c16a1b98dc/UK%20Train%20Rides/Dashboard%20Page%201.png)


![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/e0b845e705f2439a8e7aaf39617fd26514c92e5a/UK%20Train%20Rides/Dashboard%20Page%202.png)


#  11. Interactive Formula 1 Decision Analysis Dashboard
## Project Overview
This project analyzes Formula 1 telemetry and race management data to explore the factors influencing next-lap pit decisions (PitNextLap). Using interactive Power BI visualizations, the dashboard examines how tire degradation, lap progression, race conditions, and seasonal trends impact pit timing across multiple F1 seasons.
The dataset contains over 439,000 telemetry records covering multiple circuits, drivers, tire compounds, and racing seasons, enabling large-scale exploratory analysis and predictive modeling.

<details>
<summary><strong> View Project Details</strong></summary>
  
## Executive Summary & High-Level KPIs
The dashboard begins with a high-level overview of the telemetry environment and operational race metrics.
  
## KPI
-	Total Laps Analyzed: 439,140
-	Unique Grand Prix Events: 26 circuits
-	Driver Pool: 887 unique driver profiles
-	Global Average Lap Time: 90.95 seconds
-	Average Tyre Life: 14.16 laps
-	Average Laps per Stint: 1.79
-	Current Pit Stop Rate: 14%
-	Pit Next Lap Rate: 20%
  
These metrics provide the baseline operational context for understanding tire behavior, race progression, and pit timing dynamics across the dataset.
## Pit Stop vs No Pit Stop Distribution (Donut Chart)
  
**Distribution Overview**

-	No Pit Stop: 351,759 laps (80.1%)
-	Pit Stop: 87,381 laps (19.9%)
-	Total Records: 439,140 rows
  
The dataset exhibits a strong class imbalance, with pit-entry scenarios occurring significantly less frequently than normal racing laps.

## Next-Lap Pit Decisions by Tire Compound (Treemap)
This section explores how pit decisions vary across different tire compounds and how tire durability influences race strategy.
**Tire Compound Distribution**
-	HARD Compound: 55,851 pit stops (63.9%)
-	MEDIUM Compound: 21,353 pit stops (24.4%)
-	SOFT Compound: 7,496 pit stops (8.6%)
-	INTERMEDIATE Compound: 2,647 pit stops (3.1%)
  
**Key Insights**

HARD tires dominate pit stops (63.9%) due to long stints and higher degradation over time. MEDIUMs (24.4%) support balanced race strategies, while SOFTs (8.6%) are used for short, aggressive stints. INTERMEDIATEs (3.1%) appear mainly in wet conditions.
Overall, pit behavior is driven by tire durability, degradation, and weather conditions.

## Next-Lap Pit Decisions Over Race Progression (Line Graph)
This visualization tracks the frequency of upcoming pit decisions across race laps using Lap Number.

**Visualization Parameters**
-	X-Axis: Lap Number
-	Y-Axis: Pit Next Lap Count
  
The chart reveals clear strategic pit windows concentrated around specific race phases.

**Key Insights**

Pit stops are concentrated in specific lap windows, mainly mid-race when tire degradation and strategy shifts occur. Early laps (1-5) see minimal stops, while late-race pits decline due to limited time gains.
Smaller spikes outside these windows are driven by safety cars, weather changes, and race incidents that temporarily reshape strategy.

## Pit Decisions vs Tyre Life (Scatter Plot)
This scatter visualization examines the relationship between tire age (TyreLife) and next-lap pit decisions.
**Visualization Parameters**
-	X-Axis: Tyre Life
-	Y-Axis: Pit Next Lap Count
  
**Key Insights**

Pit stops peak between 10-25 laps of tire life, which represents the optimal strategic window. Very fresh tires show minimal pit activity, while very old tires see declining pit density due to performance limits.
Overall, tire degradation is a key driver of pit timing decisions.

## Seasonal Pit Decision Trends (Donut Chart)
This section analyzes how pit decision activity varies across different Formula 1 seasons.
Seasonal Distribution
-	2024: 37,538 pit stops (42.96%)
-	2025: 26,418 pit stops (30.23%)
-	2022: 22,117 pit stops (25.31%)
-	2023: 1,308 pit stops (1.50%)
  
**Key Insights**

2024 records the highest pit decision activity, while 2023 shows unusually low pit stop counts.
Overall, seasonal differences reflect changes in tire behavior, race conditions, and team strategy execution.

## Pit Decisions Over Laps by Season (Area Chart)
This area chart visualizes how pit-entry behavior evolves throughout race distance across multiple seasons.
**Visualization Parameters**
-	X-Axis: Lap Number
-	Y-Axis: Pit Next Lap Count
-	Legend: Season (2022-2025)
  
**Key Insights**

Pit windows stay consistent across seasons, with peaks clustering around similar lap ranges driven by tire degradation. Smaller variations are mainly due to race interruptions and changing conditions.
Overall, pit timing patterns are stable but slightly influenced by seasonal and race-specific factors.
## Data Source
The analysis is based on a publicly available Kaggle Playground Series dataset inspired by Formula 1 strategy data.
**Source:** [F1 Strategy Playground Series Dataset on Kaggle]( https://www.kaggle.com/competitions/playground-series-s6e5/data)

</details>

![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/7d0ae045e51f02e9db9b4bb25ffe2cb4189f783b/Formula%201%20Pit%20Stop%20Dashboard/Dashboard%201.png)


![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/7d0ae045e51f02e9db9b4bb25ffe2cb4189f783b/Formula%201%20Pit%20Stop%20Dashboard/Dashboard%202.png)


# 12. Spotify Tracks Analysis Dashboard

![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/6fb8d800e9fec76b7d0362e68eda0edb37b5a82b/Spotify%20Tracks%20Dashboard/Dashboard%201.png)

![image alt](https://github.com/Okello-Solomon/powerbi-dashboards/blob/6fb8d800e9fec76b7d0362e68eda0edb37b5a82b/Spotify%20Tracks%20Dashboard/Dashboard%202.png)
