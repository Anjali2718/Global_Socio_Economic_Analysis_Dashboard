# 🌍 Global Socio-Economic Analysis Dashboard (2023)

An interactive and data-driven Power BI dashboard developed using the **WorldData2023 dataset** to analyze global economic, healthcare, demographic, environmental, and sustainability indicators.

The dashboard transforms raw worldwide socio-economic data into meaningful analytical insights using advanced Power BI techniques including **data modelling, DAX measures, AI visuals, interactive filtering, geographical analysis, and business intelligence storytelling**.

This project provides a complete BI solution for:

* country-wise comparison
* economic analysis
* sustainability insights
* healthcare evaluation
* population analysis
* executive-level reporting

---

# 📌 Short Description / Purpose

The **Global Socio-Economic Analysis Dashboard (2023)** is a comprehensive Power BI reporting solution designed to analyze worldwide socio-economic indicators across multiple countries.

The dashboard converts raw global statistical data into meaningful visual insights through:

* KPI cards
* interactive charts
* geographical maps
* decomposition trees
* key influencers
* scatter analysis
* sustainability dashboards
* advanced analytics visuals

The project helps users understand:

* GDP distribution
* population trends
* inflation patterns
* healthcare strength
* life expectancy
* CO2 emissions
* environmental sustainability
* country risk analysis

This project is useful for:

* 🌍 Economic Analysts
* 📊 Data Analysts
* 🏛️ Government Researchers
* 💼 Business Intelligence Professionals
* 🎓 Power BI Learners
* 📈 Policy & Strategy Teams

---

# 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:

* 📊 **Power BI Desktop** – Main platform used for dashboard creation and interactive reporting.

* 📂 **Power Query** – Used for data cleaning, transformation, formatting, and preprocessing.

* 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures, KPIs, averages, ratios, and analytical calculations.

* 🔗 **Star Schema Data Modeling** – Implemented using fact tables, dimension tables, and relationships for professional BI architecture.

* 🌍 **Map Visualizations** – Used for country-wise geographical analysis.

* 📈 **KPI Cards** – Used to display important global metrics and summary insights.

* 🌳 **Decomposition Tree** – Used for drill-down root cause analysis.

* 🤖 **Key Influencers Visual** – Used for AI-driven analytical insights.

* 📊 **Scatter Charts & Treemaps** – Used for correlation analysis and hierarchical contribution analysis.

* 📁 **File Formats** – `.pbix`, `.png`, `.pdf`, `.docx`

---

# 📂 Data Source

## Dataset: WorldData2023 Dataset

The dataset contains worldwide socio-economic indicators including:

* GDP Statistics
* Population Data
* Fuel Prices
* Inflation Rates
* Healthcare Expenditure
* Life Expectancy
* CO2 Emissions
* Fertility Rates
* Infant Mortality
* Forest Area Percentage
* Agricultural Land Percentage
* Population Density
* Country Metadata
* Geographic Coordinates

The data was transformed into multiple related tables to support:

* interactive reporting
* dimensional modelling
* efficient filtering
* cross-visual analytics

---

# ✨ Features / Highlights

## • Business Problem

Global socio-economic datasets contain massive amounts of raw numerical data that are difficult to analyze manually.

Important analytical questions such as:

* Which countries contribute the highest GDP?
* How does healthcare impact life expectancy?
* Which countries have high inflation rates?
* How do environmental indicators vary globally?
* Which countries show stronger sustainability performance?
* What factors influence economic stability?
* How does population density affect socio-economic conditions?

…are difficult to answer without a centralized analytical dashboard.

---

## • Goal of the Dashboard

The main objective of this dashboard is to:

* Provide a centralized BI solution for global socio-economic analysis.
* Transform raw global indicators into meaningful visual insights.
* Enable country-level comparative analysis.
* Monitor economic, healthcare, and environmental trends.
* Analyze sustainability and risk indicators.
* Perform advanced drill-down analytics.
* Build an interactive and scalable analytical reporting solution.

---

# 📊 Walkthrough of Key Visuals

# 1️⃣ Country Analysis Dashboard

This dashboard provides a high-level summary of global socio-economic conditions.

## Key KPIs:

* Total GDP
* Total Population
* Total Countries
* Average Fuel Price

## Visuals Included:

* GDP Distribution Map
* GDP vs Life Expectancy Scatter Plot
* Top 10 Countries by GDP
* Top 10 Countries by Population
* Country Slicer

## Insights:

* Economically stronger countries generally show better healthcare outcomes.
* Population concentration is heavily dominated by a few nations.
* GDP distribution varies significantly across geographical regions.
* Scatter analysis reveals correlation between economic strength and life expectancy.

---

# 2️⃣ Economic Insights Dashboard

This dashboard focuses on inflation, healthcare, and economic stability indicators.

## Key KPIs:

* Inflation Rate
* Healthcare Spending
* Fertility Rate
* Infant Mortality

## Visuals Included:

* Inflation Analysis
* Population Density Distribution
* Fuel Price vs CPI Analysis
* Healthcare Spending Analysis
* Healthcare vs Life Expectancy Scatter Plot

## Insights:

* Higher healthcare spending often improves life expectancy.
* Inflation rates vary significantly across countries.
* Population density influences healthcare and economic pressure.
* Fuel prices impact inflation trends in multiple economies.

---

# 3️⃣ Country Risk & Sustainability Dashboard

This dashboard focuses on environmental sustainability and healthcare risk analysis.

## Key KPIs:

* CO2 Emissions
* Population Density
* Healthcare Strength
* Life Expectancy

## Visuals Included:

* Top 10 Countries by CO2 Emissions
* Infant Mortality vs Life Expectancy Scatter Plot
* Forest Area vs Agricultural Land Comparison
* Healthcare Strength Distribution
* Sustainability Analysis Charts

## Insights:

* Industrialized countries contribute significantly to CO2 emissions.
* Countries with stronger healthcare systems show lower infant mortality.
* Environmental sustainability varies greatly across nations.
* Forest and agricultural land comparisons reveal resource utilization patterns.

---

# 4️⃣ Advanced Analytics Dashboard

This dashboard demonstrates advanced Power BI analytical capabilities using AI visuals.

## Visuals Included:

* Decomposition Tree
* Key Influencers Visual
* Matrix Comparison Table
* GDP Contribution Treemap

## Features:

* Drill-down analytical exploration
* AI-driven insight generation
* Dynamic filtering
* Root cause analysis
* Hierarchical contribution analysis

## Insights:

* Healthcare and environmental indicators strongly influence life expectancy.
* GDP contribution can be analyzed hierarchically by country.
* Key Influencers visual automatically identifies major impacting factors.
* Decomposition tree enables deep analytical exploration.

---

# 🧩 Data Cleaning & Transformation

Extensive data preprocessing was performed using Power Query.

## Cleaning Operations Performed:

* Handling null values
* Correcting data types
* Removing currency symbols
* Formatting percentage columns
* Cleaning GDP and fuel price values
* Standardizing country-level data
* Validating geographical coordinates
* Removing inconsistencies
* Preparing columns for analytical calculations

## Importance of Cleaning

These transformations improved:

* analytical accuracy
* visual reliability
* DAX compatibility
* map performance
* dashboard consistency

---

# 🔗 Data Modeling

The project initially started with a single-table reporting approach and later evolved into a professional **star schema model**.

## Tables Created:

### 🔷 Fact_WorldIndicators

Contains measurable numerical indicators such as:

* GDP
* Population
* Inflation
* Fuel Price
* CO2 Emissions
* Life Expectancy

### 🔷 Dim_Country

Contains descriptive country-level metadata such as:

* Country Name
* Country Code
* Capital City
* Currency Code
* Official Language

### 🔷 Dim_Geography

Contains geographical and environmental information:

* Latitude
* Longitude
* Population Density
* Forest Area %
* Agricultural Land %

### 🔷 Measure Table

A dedicated table used to organize all DAX measures professionally.

---

# 📐 Relationships

Relationships were established using:

* One-to-Many Cardinality
* Country-based filtering

This improved:

* scalability
* filtering performance
* dashboard professionalism
* analytical flexibility

---

# 🧠 DAX Measures Created

The project includes several reusable DAX measures including:

* Total GDP
* Total Population
* Total Countries
* Avg Fuel Price
* Avg Life Expectancy
* Avg CO2 Emissions
* Avg Population Density
* Avg Healthcare Strength
* Avg Inflation Rate
* Avg Fertility Rate
* Avg Infant Mortality
* Avg Tax Revenue %
* GDP Per Capita
* Avg Healthcare Spending
* Avg Unemployment Rate

These measures enabled:

* KPI calculations
* dynamic filtering
* interactive reporting
* advanced analytics

---

# 📈 Business Impact & Insights

## ✔ Improved Decision-Making

The dashboard enables users to make data-driven decisions using real-time analytical insights.

## ✔ Better Economic Understanding

Users can analyze GDP, inflation, healthcare, and sustainability indicators interactively.

## ✔ Environmental Analysis

The dashboard helps identify countries contributing heavily to CO2 emissions and environmental imbalance.

## ✔ Healthcare & Demographic Insights

Healthcare spending, infant mortality, and life expectancy analysis help evaluate country development conditions.

## ✔ Interactive Exploration

Advanced visuals such as decomposition tree and key influencers support deeper analytical exploration.

---

# 📸 Dashboard Modules Included

* Country Analysis Dashboard
* Economic Insights Dashboard
* Country Risk & Sustainability Dashboard
* Advanced Analytics Dashboard

---

# 📚 Learning Outcomes

Through this project, I learned:

* Data Cleaning using Power Query
* Star Schema Data Modeling
* DAX Measure Development
* Interactive Dashboard Design
* KPI Development
* AI Visuals in Power BI
* Analytical Storytelling
* Business Intelligence Reporting
* Advanced Visualization Techniques
* Executive-Level Dashboard Design

---

# 🚀 Conclusion

The **Global Socio-Economic Analysis Dashboard (2023)** successfully transforms raw global indicators into meaningful business intelligence insights using Power BI.

This project demonstrates strong practical skills in:

* Business Intelligence
* Data Analytics
* Dashboard Development
* Power BI
* DAX
* Data Modelling
* Data Visualization
* Analytical Thinking
* Sustainability Analytics
* AI-driven Reporting

The implementation of:

* star schema modelling
* advanced visuals
* interactive filtering
* AI analytics
* sustainability dashboards

makes this project a complete end-to-end BI solution suitable for:

* college submissions
* internship portfolios
* placement showcases
* professional demonstrations
