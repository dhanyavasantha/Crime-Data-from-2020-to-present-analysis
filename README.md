# Crime-Data-from-2020-to-present-analysis

# Crime Data from 2020 to Present Analysis  

## Project Overview  
This project analyzes crime data from Los Angeles (2020 - Present) to identify trends, patterns, and geographical distributions. The objective is to examine how crime rates were impacted by COVID-19, analyze crime categories, and determine high-crime locations using statistical and geospatial analysis.  

## Objectives  
1. **Temporal Analysis:** Identify monthly and yearly crime trends before, during, and after COVID-19.  
2. **Crime Category Analysis:** Determine how specific crime types (property crimes, violent crimes) changed over time.  
3. **Geospatial Analysis:** Detect high-crime neighborhoods and analyze how geographical factors influenced crime patterns.  

## Dataset  
- **Source:** [Data.gov - Los Angeles Crime Data](https://catalog.data.gov/dataset/crime-data-from-2020-to-present)  
- **Description:** The dataset includes incident details, crime types, locations, victim demographics, and timestamps.  
- **Data Types:** Nominal, Ordinal, Interval, Ratio  

| Feature | Description |
|---------|------------|
| Date Reported | When the crime was reported |
| Date Occurred | When the crime occurred |
| Crime Code | Type of crime committed |
| Area Name | Los Angeles region where the crime took place |
| Victim Age/Sex | Demographic details of the victim |
| Weapon Used | Details on the type of weapon used |
| Location Coordinates | Crime location (Latitude, Longitude) |

## Key Research Questions & Findings  

### 1. How did crime trends change before and after COVID-19?  
Crime rates dropped during 2020-2021 due to lockdowns but surged in 2022-2023 post-pandemic.  

**Key Observations:**  
- Monthly crime trends showed a significant dip during lockdown periods.  
- Crime levels increased again after restrictions were lifted.  
- The peak crime months were identified as June to September each year.  

### 2. What are the most common crimes committed in Los Angeles?  
**Top 3 Most Reported Crimes:**  
- Robbery  
- Assault with Deadly Weapon  
- Theft & Burglary  

**Crime Category Analysis:**  
- Property crimes remained consistent throughout the years.  
- Violent crimes had spikes in 2023, especially aggravated assaults and robberies.  
- Weapon-related crimes increased post-pandemic.  

### 3. Which locations in Los Angeles have the highest crime rates?  
**Top High-Crime Areas:**  
- Central LA – Highest crime rate in the city.  
- Van Nuys & South LA – Significant hotspots.  
- Downtown & Hollywood – Frequent theft & violent incidents.  

**Geospatial Analysis:**  
- Hexbin plots revealed clusters of high crime concentration in specific areas.  
- Crime incidents were more frequent near highways, public transport stations, and commercial areas.  

## Methods & Tools  

### Tools Used  
| Technology | Purpose |
|------------|---------|
| Python | Data Cleaning, Trend Analysis, Visualization |
| R | Statistical Analysis, Advanced Visualization |
| GIS Tools | Mapping Crime Locations |
| SQL | Querying and Storing Crime Data |

### Libraries Used  

**Python**  
- Pandas - Data Cleaning & Preprocessing  
- Matplotlib & Seaborn - Data Visualization  
- Geopandas - Crime Location Mapping  

**R Language**  
- ggplot2 - Advanced Data Visualization  
- tidyr & dplyr - Data Manipulation  

**SQL**  
- Used to query and store crime data in a relational database.  

## Future Scope  
- Expand analysis to include predictive crime modeling.  
- Integrate machine learning models to detect crime patterns.  
- Use real-time crime data streaming for live analytics.  

## Author  
**Name:** Dhanya Sri Vasantha  
