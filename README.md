................FINAL EXAM...............

Student: Humure Enock
ID: 27394
Identification: AUCA - IT - Software Engineering
Course: INSY 8413 | Introduction to Big Data Analytics
Faculty of Information Technology - AUCA
Lecturer: Eric Maniraguha
Sector: Health
Research Question: Can we predict workplace injury patterns?

# Workplace Injury Analysis Project

## Table of Contents
1. [Project Overview](#project-overview)
2. [Problem Statement](#problem-statement)
3. [Dataset Information](#dataset-information)
4. [Tools and Technologies](#tools-and-technologies)
5. [Project Structure](#project-structure)
6. [Methodology](#methodology)
7. [Key Findings](#key-findings)
8. [Innovation Features](#innovation-features)
9. [Business Recommendations](#business-recommendations)
10. [How to Use](#how-to-use)
11. [Screenshots](#screenshots)
12. [Conclusion](#conclusion)
13. [Acknowledgments](#acknowledgments)

## Project Overview
This project analyzes workplace injury data to identify patterns and predict which industries are most dangerous. The analysis combines Python data science techniques with Power BI visualization to create comprehensive insights for workplace safety improvement.

## Problem Statement
**Research Question:** Can we predict workplace injury patterns?

The goal is to help companies make workplaces safer by understanding injury patterns across different industries and time periods.

## Dataset Information
- **Dataset:** Workplace injury claims from 2002-2018
- **Size:** Over 32,000 records
- **Content:** Industry types, injury numbers, years, occupations
- **Source:** [injury-statistics-work-related-claims-2018.csv](https://www.stats.govt.nz/assets/Uploads/Injury-statistics/Injury-statistics-work-related-claims-2018/Download-data/injury-statistics-work-related-claims-2018-csv.csv)

## Tools and Technologies
- **Python:** Data cleaning and machine learning
- **Power BI:** Interactive dashboard creation
- **Jupyter Notebook:** Code development and analysis

## Project Structure

## Methodology

### Data Cleaning
Comprehensive data preprocessing including:
- Removed missing values
- Fixed data formats
- Created risk levels (Low, Medium, High, Critical)

**Screenshots:**
- https://github.com/EnockHumure/bigdata-injury-analysis/blob/main/sceenshots/1st%20file%20of%20the%20injury%20statics%20coloumn.png
- [sceenshots/2nd file of the data previes and analyse.png]
- [sceenshots/file 3-techenical analysis.png]
- [sceenshots/data preview file3.png]
- [sceenshots/risk analysis file4.png]
- [sceenshots/file5- cleaned data(2).png]

### Exploratory Data Analysis (EDA) 
Created comprehensive data visualizations including a complete dashboard 
and 8 individual graphs to understand data patterns.

**Key Insights:**
- Manufacturing has the most injuries (40,000+ claims)
- Injuries peaked in 2005 (262,000 total claims)
- Most injuries are in the "Critical" risk category (60%+ of cases)
- Declining trend observed in recent years (15% reduction since 2010)
- Ages 25-54 represent highest risk demographic
- Strong correlation between industry type and injury frequency

**Visualization Screenshots:**
- Combined EDA Dashboard: [sceenshots/EDA 1completion of data analytics-combination.png]
- Time Trends Line Chart: [sceenshots/graph1-eda.png]
- Risk Level Pie Chart: [sceenshots/graph2-eda.png]
- Top Industries Bar Chart: [sceenshots/graph3-eda.png]
- Correlation Heatmap: [sceenshots/graph4-eda.png]
- Top Occupations Analysis: [sceenshots/graph5-eda.png]
- Claims Distribution Histogram: [sceenshots/graph6-eda.png]
- Risk Level Box Plots: [sceenshots/graph7-eda.png]
- Scatter Plot Analysis: [sceenshots/graph8.png]

### Machine Learning
Built AI models to predict injury risks:

1. **Random Forest:** Predicts risk levels (95% accuracy)
2. **K-Means Clustering:** Groups similar industries
3. **Ensemble Model:** Combines multiple models for better predictions

**Screenshots:**
-Random Forest: [sceenshots/machine learning and it graph1.png]
-K-Means Clustering:[sceenshots/ml-graph2 .png]
-Ensemble Model:[sceenshots/ml-graph3 clustering.png]

### Power BI Dashboard
Created a 3-page interactive dashboard:

1. **Overview Page:** Key numbers and summaries
2. **Industry Analysis:** Most dangerous industries identification
3. **Risk Analysis:** Interactive filters and risk levels

**Screenshots:**
- Overview: [sceenshots/power bi overview dashboard.png]
- Industry Analysis: [sceenshots/power bi industry analysis.png]
- Risk Analysis: [sceenshots/power bi risk analysis.png]

## Key Findings

### Data Insights
- **Most Dangerous Industry:** Manufacturing
- **Peak Injury Year:** 2005 (262,000 claims)
- **Current Trend:** Injuries are decreasing over time
- **Highest Risk Age:** 25-54 years old

### AI Model Performance
- **Accuracy:** 95% correct predictions
- **Best Feature:** Claim amount predicts risk level
- **Clustering:** Found 3 clear risk groups

## Innovation Features

### Python Innovations
- Custom risk prediction function
- Ensemble model combining 3 different AI algorithms
- Automated safety recommendations

**Screenshot:** [sceenshots/inovation -py.png]

### Power BI Innovations
- Multi-page navigation
- Interactive slicers for filtering
- Industry ranking cards showing highest and lowest risk industries

**Screenshot:** [sceenshots/power bi industry analysis.png]

## Business Recommendations

### For Companies
1. **Focus on Manufacturing:** Extra safety training needed
2. **Monitor High-Risk Workers:** Ages 25-54 need attention
3. **Use Predictive Model:** Predict risks before injuries happen

### For Safety Managers
1. **Regular Risk Checks:** Use dashboard for monthly monitoring
2. **Target Training:** Focus on high-risk occupations
3. **Track Progress:** Monitor safety improvements over time

## How to Use

### Python Code
1. Open `injury-statistics.ipynb` in Jupyter Notebook
2. Run all cells to reproduce analysis

### Dashboard
1. Open `Humure Enock (final_exam) 27394.pbix` in Power BI
2. Use interactive filters to explore data

## Screenshots

### Python Results
1. **Data Cleaning:** [sceenshots/file5- cleaned data(2).png]
2. **EDA Dashboard:** [sceenshots/EDA 1completion of data analytics-combination.png]
3. **Machine Learning:** [sceenshots/machine learning and it graph1.png]
4. **Innovation:** [sceenshots/inovation -py.png]

### Power BI Results
1. **Overview Page:** [sceenshots/power bi overview dashboard.png]
2. **Industry Analysis:** [sceenshots/power bi industry analysis.png]
3. **Risk Analysis:** [sceenshots/power bi risk analysis.png]

## Conclusion

This project successfully analyzed workplace injury patterns using data science and
 visualization techniques. Key achievements include:

- Built a 95% accurate predictive model for injury risk assessment
- Identified manufacturing as the highest-risk industry requiring attention
- Created interactive dashboards for real-time safety monitoring
- Provided actionable recommendations for workplace safety improvement

The analysis shows that data-driven approaches can significantly improve workplace 
safety by enabling proactive risk management rather than reactive responses.

This project demonstrates how data analytics can contribute 
to improving workplace safety and protecting workers across different industries.

## Acknowledgments

I extend my gratitude to:

- **Eric Maniraguha**, course lecturer, for guidance and expertise throughout this project
- **AUCA Faculty of Information Technology** for providing the academic framework and resources


