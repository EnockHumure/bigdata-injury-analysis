##................FINAL EXAM...............

#Student: Humure Enock

**ID:** 27394

**Identification:** AUCA - IT - Software Engineering

**Course:** INSY 8413 | Introduction to Big Data Analytics

**Faculty of Information Technology - AUCA**

**Lecturer:** Eric Maniraguha

**Sector:** Health

**Research Question:** Can we predict workplace injury patterns?

## Workplace Injury Analysis Project

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
- **Git:** control version

## Project Structure

## Methodology

### Data Cleaning
Comprehensive data preprocessing including:
- Removed missing values
- Fixed data formats
- Created risk levels (Low, Medium, High, Critical)

**Screenshots:**
-<img width="1318" height="704" alt="1st file of the injury statics coloumn" src="https://github.com/user-attachments/assets/21a1b4d0-175d-4a5e-b53a-cf034793f622" />

-<img width="1324" height="701" alt="2nd file of the data previes and analyse" src="https://github.com/user-attachments/assets/5cc737c3-63d9-441d-a691-7a273e0c647c" />

-<img width="1321" height="638" alt="file 3-techenical analysis" src="https://github.com/user-attachments/assets/97a39b21-d947-4ae6-8552-e6f4d9064ede" />
-<img width="1293" height="668" alt="data preview file3" src="https://github.com/user-attachments/assets/ad0f3da1-96b4-4086-84d3-29466b03aaf4" />
-<img width="1310" height="503" alt="risk analysis file4" src="https://github.com/user-attachments/assets/9ed96baa-4958-4af3-9889-a824f9ea9f19" />
-<img width="1299" height="688" alt="file5- cleaned data(2)" src="https://github.com/user-attachments/assets/67650a63-e6dd-40d0-bf73-3478653ded09" />

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
- Combined EDA Dashboard:
- <img width="734" height="702" alt="EDA 1completion of data analytics-combination" src="https://github.com/user-attachments/assets/b35ebed2-f5f5-48f8-82d2-f8151ed0b301" />

- Time Trends Line Chart:
-  <img width="1281" height="691" alt="graph1-eda" src="https://github.com/user-attachments/assets/8959aea1-c7d0-4929-a603-53c3a0429966" />

- Risk Level Pie Chart:
- <img width="1109" height="687" alt="graph2-eda" src="https://github.com/user-attachments/assets/6266bacb-2028-4d96-b311-fce98b577158" />

- Top Industries Bar Chart:
-  <img width="1102" height="666" alt="graph3-eda" src="https://github.com/user-attachments/assets/299ecb32-d83d-499f-af97-0b86d79019d8" />
  
- Correlation Heatmap:
- <img width="1064" height="708" alt="graph4-eda" src="https://github.com/user-attachments/assets/ebb09c63-b8a7-4366-8c8c-908076b47523" />

- Top Occupations Analysis:
- <img width="1055" height="628" alt="graph5-eda" src="https://github.com/user-attachments/assets/0b5bd844-3086-4cc8-9329-db2e724fa99f" />

- Claims Distribution Histogram: <img width="1028" height="589" alt="graph6-eda" src="https://github.com/user-attachments/assets/184b9b95-dbb4-4861-af2f-85b2e60959a2" />

- Risk Level Box Plots: <img width="1037" height="622" alt="graph7-eda" src="https://github.com/user-attachments/assets/8aefe18d-c757-4cd6-9062-47318d942532" />
- Scatter Plot Analysis: <img width="1009" height="638" alt="graph8" src="https://github.com/user-attachments/assets/77a7ce6c-0541-441d-b44f-8a45aaa6daf6" />

### Machine Learning
Built AI models to predict injury risks:

1. **Random Forest:** Predicts risk levels (95% accuracy)
2. **K-Means Clustering:** Groups similar industries
3. **Ensemble Model:** Combines multiple models for better predictions

**Screenshots:**
-Random Forest: 
<img width="1262" height="653" alt="machine learning and it graph1" src="https://github.com/user-attachments/assets/682e5c31-688a-437e-99dc-cce1f1dd1993" />

-K-Means Clustering:
<img width="717" height="512" alt="ml-graph3 clustering" src="https://github.com/user-attachments/assets/20714fc1-6ff9-49cd-976b-76d21ffbb400" />

-Ensemble Model: <img width="734" height="613" alt="ml-graph2 " src="https://github.com/user-attachments/assets/f56a4eee-1f1f-4ad9-89f1-e1a574658537" />

### Power BI Dashboard
Created a 3-page interactive dashboard:

1. **Overview Page:** Key numbers and summaries
2. **Industry Analysis:** Most dangerous industries identification
3. **Risk Analysis:** Interactive filters and risk levels

**Screenshots:**
- Overview: <img width="1306" height="746" alt="power bi overview dashboard" src="https://github.com/user-attachments/assets/2906a77a-e038-4f92-ab5b-1c740a358473" />

- Industry Analysis: <img width="1324" height="753" alt="power bi industry analysis" src="https://github.com/user-attachments/assets/6fb41765-b460-454a-abc9-de11911d0a6c" />

- Risk Analysis: <img width="1323" height="766" alt="power bi risk analysis" src="https://github.com/user-attachments/assets/4b50783d-dd33-4254-b460-44b0d69629d0" />

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
<img width="1093" height="200" alt="inovation -py" src="https://github.com/user-attachments/assets/ff3a336c-0ae5-4320-b319-fc16bc8e29db" />


### Power BI Innovations
- Multi-page navigation
- Interactive slicers for filtering
- Industry ranking cards showing highest and lowest risk industries
<img width="1324" height="753" alt="power bi industry analysis" src="https://github.com/user-attachments/assets/14396b5c-24f1-4d36-a8a6-2dd370dac23d" />

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
1. **Data Cleaning:**
<img width="1299" height="688" alt="file5- cleaned data(2)" src="https://github.com/user-attachments/assets/e18ece88-ca92-4cdd-af7c-e44473f28727" />

2. **EDA Dashboard:**
  <img width="734" height="702" alt="EDA 1completion of data analytics-combination" src="https://github.com/user-attachments/assets/13b515a6-6218-4bf8-aefc-cd6862a96644" />
3. **Machine Learning:** <img width="1262" height="653" alt="machine learning and it graph1" src="https://github.com/user-attachments/assets/7fdec768-f7d1-46d6-bc4d-2d5fa7f0762d" />

4. **Innovation:** <img width="1093" height="200" alt="inovation -py" src="https://github.com/user-attachments/assets/c7376f40-b334-4bc8-bbc6-c6d5f738b5d4" />

### Power BI Results
5. **Industry Analysis:**
<img width="1324" height="753" alt="power bi industry analysis" src="https://github.com/user-attachments/assets/f936a295-1e42-4094-8899-a85150ff3ca0" />
6. **summary:**
   <img width="1215" height="670" alt="final summary" src="https://github.com/user-attachments/assets/20575e01-80da-4dfc-8262-c71c0be93430" />


   **Here you can use this link for download the dashboard of the power BI** https://drive.google.com/file/d/1ZOZl23If22oqs0FMtc_4_BRxWkkM_xkd/view?usp=sharing

**Here are the folder on my drive you can download it for the checking**
https://drive.google.com/drive/folders/1EISYa17lObBuu8cvqT9XtjvJRCPLUJSo?usp=drive_link
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


