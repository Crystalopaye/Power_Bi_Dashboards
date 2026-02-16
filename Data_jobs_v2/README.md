# Data Jobs Dashboard V2 w/ Power Bi
---

![Dashboard Page 1](/images/project_2_page1.png)

## Introduction
### From Static Views to Dynamic Insights
My first dashboard, **Data Jobs Dashboard 1.0**, provided a solid foundation for exploring job market trends. It answered key questions like: **What's the trend of jobs in 2024? What is the highest paying role? How large is your salary for data jobs?** With core visuals and tabular views, it established the essential metrics—job counts, median salaries, and role comparisons.

**Data Jobs Dashboard 2.0** builds on this foundation by consolidating insights into a single, streamlined interface. Rather than navigating multiple views, users can now explore critical market trends and compensation data all in one place—with enhanced interactivity and a cleaner layout.

**What's New in Version 2.0?**
- **Unified Dashboard** – All key metrics (job count, median salary, skills, geography) on one screen
- **Dynamic Filtering** – Global slicers for job title and country let users tailor the view instantly
- **Skills Analysis** – Added "Top Skills in Data" with job count percentages for skill demand insights
- **Geospatial View** – Interactive map showing job distribution across continents
- **Improved Salary Benchmarking** – Clear side-by-side comparison of top-paying roles with yearly and hourly rates

This evolution transforms raw data into an interactive exploration tool, enabling faster, more intuitive access to the insights that matter most for job seekers, employers, and market analysts.


## Technical Skills Showcased
### Data Modeling & Calculations
- DAX measures for median yearly/hourly salary
- Implicit measures for job count and skills-per-job
- Job percent calculations for skill demand
- Dynamic measures responding to slicer selections

### Data Transformation (Power Query)
- Job title and country name standardization
- Skill parsing and column transformation
- Geospatial data preparation

### Visualization & Dashboard Design
- KPI cards with formatted metrics
- Bar charts for top skills and salary comparisons
- Azure Maps integration for global job distribution
- Side-by-side yearly/hourly salary visuals
- Text-based skill lists and job categories

### Interactivity & User Experience
- Global slicers for job title and country
- Cross-filtering between charts
- Bookmark setup for view toggling
- Drill-through data structure

### Geospatial Analytics
- Continent-level job concentration mapping
- Map-based geographic filtering
- Bing Maps geocoding integration

### Performance Optimization
- Efficient data modeling for 479K records
- Optimized DAX for fast slicer response
- Visual-level filters for focused charts

### End-to-End Reporting
- Single-page consolidated dashboard
- Intuitive layout with logical grouping
- Responsive scaling across devices


## Dashboard Overview

![Dashboard Page 1](/images/project_2_page1.png)

**Data Jobs Dashboard 2.0** is a single-page interactive tool for exploring the global data job market. It consolidates key metrics, skill demand, geographic distribution, and salary benchmarks into one streamlined interface.

**Key Metrics at a Glance**
- 479K total job postings
- 4.8 average skills per job
- $113K median yearly salary | $48 median hourly salary
- Global filters for Job Title and Country

**Core Insights**
- Top Skills – Python, SQL, AWS, Azure, Tableau, and more with job percent breakdowns
- Job Geography – Interactive map showing job concentration across North America, Europe, Asia, Africa, and South America
- Top-Paying Roles – Side-by-side comparison of yearly and hourly salaries for roles like Data Engineer, Data Scientist, Machine Learning Engineer, and others

Built For
Job seekers, employers, and market analysts needing fast, interactive access to data job trends and compensation insights.


## Conclusion
Data Jobs Dashboard 2.0 delivers a streamlined single-page tool for exploring the global data job market. Building on Version 1.0, it consolidates job counts, skills analysis, geographic distribution, and salary benchmarks into one interactive view with global slicers and cross-filtering. Users can quickly identify top skills (Python, SQL, AWS), highest-paying roles, and regional job concentrations across continents. The dashboard empowers job seekers, employers, and analysts to benchmark compensation, track skill demand, and understand geographic trends. Key technical skills demonstrated include DAX measures, Power Query transformations, geospatial mapping, and performance optimization for large datasets. Future enhancements could include time-series forecasting and company-level filtering. Overall, this project transforms raw data into an intuitive decision-making tool with advanced Power BI capabilities.