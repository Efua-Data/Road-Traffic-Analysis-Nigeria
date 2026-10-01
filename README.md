# Road-Traffic-Analysis-Nigeria
Exploratory Analysis of Road Traffic Data in Nigeria 

# Road Traffic Crash Analysis in Nigeria (2021–2023)

## Project Overview

This project analyses road traffic crashes in Nigeria between 2021 and 2023 using national road transport data. The analysis examines crash frequency, casualties, contributing factors, vehicle involvement, gender distribution of injuries and fatalities, temporal patterns, and the geographic distribution of crashes across Nigerian states.

Road traffic crashes represent a significant public health and development challenge, particularly in low- and middle-income countries. In Nigeria, factors such as rapid urbanisation, population growth, increasing vehicle ownership, human behaviour, vehicle conditions, and infrastructure challenges contribute to road safety risks.

## Objectives

- Identify patterns and trends in road traffic crashes from 2021–2023.
- Determine states with particularly high crash volumes.
- Examine major contributing factors to crashes.
- Analyse crash patterns by vehicle type and gender.
- Explore temporal patterns across years and quarters.
- Visualise the geographic distribution of crashes.
- Develop an interactive dashboard to communicate key findings.

## Data

The analysis used secondary data from official Nigerian road transport records covering **2021–2023**, sourced from the **Federal Road Safety Corps (FRSC)** and the **National Bureau of Statistics (NBS)**.

The dataset contains quarterly records across Nigerian states, including:

- Total crash cases and casualties
- Causes of road traffic crashes
- Vehicle types and categories involved
- Gender-based injury and fatality information
- Geographic boundary data for Nigerian states

The data was provided across multiple Excel sheets. Considerable preprocessing was required, including data cleaning, standardisation of state names, handling missing values, and aggregation across years and quarters.

## Tools and Technologies

The project was developed primarily using **Python** and included:

- **Pandas** – data cleaning, transformation, aggregation, and exploratory analysis
- **NumPy** – numerical operations
- **Matplotlib** – data visualisation
- **Plotly** – interactive visualisations
- **GeoPandas** – geospatial analysis and mapping
- **Streamlit** – development of an interactive analytical dashboard

## Methodology

1. **Data Integration and Cleaning** – Multiple datasets were combined, cleaned, and standardised to create an analysis-ready dataset.
2. **Exploratory Data Analysis** – Crash frequencies, casualties, causes, vehicle types, gender distributions, and temporal patterns were examined.
3. **Trend and Comparative Analysis** – Crash patterns were compared across years, quarters, and Nigerian states.
4. **Spatial Analysis** – Geographic data was combined with crash statistics to identify areas with higher crash volumes and produce hotspot maps.
5. **Data Visualisation** – Charts, graphs, and maps were developed to communicate patterns and trends clearly.
6. **Interactive Dashboard** – A Streamlit dashboard was developed to allow users to explore the findings using interactive filters, charts, and maps.

## Key Findings

- **FCT recorded the highest number of crash cases**, with **4,627 cases**, followed by Ogun and Nasarawa, identifying these areas as major crash hotspots.
- **2022 recorded the highest number of crashes** during the study period, suggesting important temporal patterns that may be associated with factors such as travel behaviour, weather conditions, or economic activity.
- A total of **126,618 casualties** were recorded across the three-year period.
- **Human-related factors were identified as dominant contributors to crashes**, reinforcing the importance of driver behaviour in road safety.
- Commercial and private vehicles accounted for a large proportion of recorded crashes.
- **Adult males experienced substantially higher injury and fatality rates than females**, highlighting the importance of targeted road safety interventions.

## Societal Impact

The findings provide useful evidence for organisations involved in road safety, public health, urban planning, transportation, and policymaking.

The analysis can support:

- Targeted road safety campaigns in high-risk areas
- Improved enforcement of traffic regulations
- Public education addressing risky driving behaviours
- Infrastructure improvements in crash hotspots
- Evidence-based allocation of road safety resources
- Better understanding of vulnerable population groups

Reducing road traffic crashes has potential benefits beyond preventing deaths and injuries, including reducing healthcare costs, improving productivity, and contributing to safer communities.

## Key Learning Outcomes

Working with real-world road safety data provided practical experience in the complete data analysis workflow, from data cleaning and integration through to visualisation and dashboard development.

The project demonstrated the importance of:

- Thorough data cleaning and validation
- Combining multiple datasets for meaningful analysis
- Using visualisation to communicate complex findings
- Applying geospatial techniques to understand location-based patterns
- Developing interactive tools for non-technical users
- Using data science to address real-world societal challenges

## Conclusion

This project demonstrates how data analytics can be applied to understand road traffic crashes and generate actionable insights. By examining **where, when, and why crashes occur**, the analysis provides an evidence-based foundation for understanding road safety challenges in Nigeria.

The project also highlights the broader value of data science in addressing public safety and development challenges through data-driven decision-making.
