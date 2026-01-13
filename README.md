# TTC Subway Delays Analysis (2020–2024)

## Overview
This project analyzes subway delay incidents across Toronto’s TTC network from 2020 to 2024. Using public transit data, the analysis explores temporal patterns, primary causes of delays, station-level disruptions, and the broader impact of passenger-related incidents on service reliability.

The project combines exploratory data analysis, visualization, and predictive modeling to surface actionable insights about where and why delays occur.

---

## Project Objectives
- Identify trends in subway delay frequency and duration over time  
- Understand the dominant causes of delays and how they interact  
- Analyze station-level and time-based patterns of disruption  
- Explore whether delay causes can be predicted using temporal features  

---

## Data Sources
- **TTC Subway Delay Data (2020–2024)**  
  Sourced from the City of Toronto Open Data Portal

The raw data was cleaned and standardized to resolve inconsistent station names, timestamps, and delay codes. Delay causes were grouped into broader categories to support meaningful analysis.

---

## Methodology

### Data Preparation
- Cleaned and standardized delay records  
- Resolved extensive station name inconsistencies  
- Categorized delay causes into passenger-related, system-related, and fire/weather-related groups  

### Exploratory Analysis
- Temporal analysis of delay frequency and duration  
- Station-level aggregation to identify high-impact locations  
- Cause-based breakdowns to examine compounding disruptions  

### Predictive Modeling
- Built a Random Forest classification model to predict delay cause categories  
- Used temporal features (hour of day, day of week) and delay duration  
- Evaluated model performance across delay categories  

---

## Key Findings
- Passenger-related incidents account for the majority of subway delays and total delay minutes  
- Major transfer stations experience disproportionately high disruption  
- Total delay impact peaks during evening and late-night hours due to incident frequency  
- Passenger behavior, alarms, and track-level incidents often co-occur, amplifying service disruption  

---

## How to Explore
- **Read the full report:**  
  `report/TTC_Subway_Delays_Report.pdf`
- **View the analysis code:**  
  `notebook/TTC_Subway_Delays_Analysis.ipynb`

---

## Notes
This project was completed as part of the UofT SCS Foundations of Data Science course.