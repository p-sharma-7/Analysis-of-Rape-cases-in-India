# Analysis-of-Rape-cases-in-India
A comprehensive data analysis project examining trends, patterns, and insights into rape cases across India using National Crime Records Bureau (NCRB) data.

## 📝 Description

This repository contains a systematic analysis of rape cases reported in India, featuring:

- **Data Preparation Pipeline**: Cleaning, transformation, and quality checks
- **Comprehensive Profiling**: Automated analysis of dataset characteristics
- **Exploratory Data Analysis**: Spatial-temporal patterns and statistical insights
- **Visual Analytics**: Interactive charts and geospatial mappings

Key focus areas include:
- Temporal trends (2001-2020)
- State/UT-wise comparisons
- Case disposition rates
- Demographic patterns of survivors
- Legal process efficiency analysis

## 📊 Dataset Sources

1. [State/UT, City and Age Group-wise Victims of Incest Rape, Other Rape and Total Rape Cases (Sec. 376 IPC) during 2001](https://www.data.gov.in/resource/stateutcity-age-group-wise-victims-incest-rape-other-rape-and-total-rape-cases-during-2001)
2. [State & UT-wise Victims of Rape (also Incest Rape Cases) under Different Age-Groups During 2002](https://www.data.gov.in/resource/stateut-city-and-age-group-wise-victims-incest-rape-other-rape-and-rape-cases-total-cases)
4. [State & UT-wise Victims of Rape (also Incest Rape Cases) under Different Age-Groups During 2003](https://www.data.gov.in/resource/stateut-city-and-age-group-wise-victims-incest-rape-other-rape-and-total-rape-cases-total)
5. [State & UT-wise Victims of Rape (also Incest Rape Cases) under Different Age-Groups During 2009](https://www.data.gov.in/resource/stateut-city-and-age-group-wise-victims-incest-rape-other-rape-and-total-rape-cases-sec-0)
6. [State & UT-wise Victims of Rape (also Incest Rape Cases) under Different Age-Groups During 2015](https://www.data.gov.in/resource/state-ut-wise-victims-rape-also-incest-rape-cases-under-different-age-groups-during-2015)
7. [State/UT/City and Age Group-Wise Victims of Incest Rape, Other Rape and Total Rape Cases Cases during 2005](https://www.data.gov.in/resource/stateutcity-and-age-group-wise-victims-incest-rape-other-rape-and-total-rape-cases-cases-0)
8. [State/UT/City and Age Group-Wise Victims of Incest Rape, Other Rape and Total Rape Cases Cases during 2006](https://www.data.gov.in/resource/stateutcity-and-age-group-wise-victims-incest-rape-other-rape-and-total-rape-cases-cases)
9. [State/UT/ City and Age Group-wise Victims of Incest Rape, Other Rape and Total Rape Cases Total Cases during 2004](https://www.data.gov.in/resource/stateut-city-and-age-group-wise-victims-incest-rape-other-rape-and-total-rape-cases-total)
10. [State/UT, City and Age Group-wise Victims of Incest Rape, Other Rape and Total Rape Cases (Sec. 376 IPC) during 2007](https://www.data.gov.in/resource/stateut-city-and-age-group-wise-victims-incest-rape-other-rape-and-total-rape-cases-sec-3)
11. [State/UT, City and Age Group-wise Victims of Incest Rape, Other Rape and Total Rape Cases (Sec. 376 IPC) during 2008](https://www.data.gov.in/resource/stateut-city-and-age-group-wise-victims-incest-rape-other-rape-and-total-rape-cases-sec)
12. [State/UT, City and Age Group-wise Victims of Incest Rape, Other Rape and Total Rape Cases (Sec. 376 IPC) during 2010](https://www.data.gov.in/resource/stateut-city-and-age-group-wise-victims-incest-rape-other-rape-and-total-rape-cases-sec-1)
13. [State/UT, City and Age Group-wise Victims of Incest Rape, Other Rape and Total Rape Cases (Sec. 376 IPC) during 2011](https://www.data.gov.in/resource/stateut-city-and-age-group-wise-victims-incest-rape-other-rape-and-total-rape-cases-sec-2)
14. [State & UT-Wise Victims of Rape Cases (Incest, Other and Total) under different Age Groups during 2013](https://www.data.gov.in/resource/state-ut-wise-victims-rape-cases-incest-other-and-total-under-different-age-groups-during)
15. [State & UT-wise Victims of Rape (also Incest Rape Cases) under Different Age-Groups During 2015](https://www.data.gov.in/resource/state-ut-wise-victims-rape-also-incest-rape-cases-under-different-age-groups-during-2015)
16. [State/UT-wise Details of Cases Registered, Cases Charge-sheeted and Cases in which Trials were Completed under Rape from 2018 to 2022](https://up.data.gov.in/resource/stateut-wise-details-cases-registered-cases-charge-sheeted-and-cases-which-trials-were)

*Note: Actual dataset files are maintained in the `Datasets/` directory*

## 🚀 Usage

1. **Data Preparation**:
- Execute `Data_Preparation_and_Data_profiling_of_Rape_cases_in_India.ipynb`
- Performs:
  - Missing value imputation
  - Feature engineering
  - Automated data profiling
  - Temporal alignment of records

2. **Exploratory Analysis**:
- Run `EDA_of_Rape_cases_in_India.ipynb`
- Includes:
  - Time-series decomposition
  - Spatial autocorrelation analysis
  - Conviction rate modeling
  - Comparative analysis with socioeconomic factors

## 🔍 Key Features

- **Automated Data Profiling**: Comprehensive quality reports with statistics
- **Geospatial Visualization**: Heatmaps of case distribution
- **Legal Process Analysis**: Timeline analysis from FIR to judgment
- **Statistical Modeling**: Regression analysis of contributing factor

## Visualizations: 
*Yearly trend of total rape cases in India from 2001 to 2013*
![image](https://github.com/user-attachments/assets/f51615f3-ad96-4746-93d1-1dc620a6c2fc)

*Percentage Changes in total rape cases over year*<br>
![image](https://github.com/user-attachments/assets/64490fc5-7b82-45a5-a61f-2d7aa3dc8b1c)

*Statewise intensity of Rape cases reported in India from 2001 to 2022*
![image](https://github.com/user-attachments/assets/49934a98-81ee-4a45-96ba-733413b50d97)

Age-wise Distribution
![image](https://github.com/user-attachments/assets/b2ab5bc0-90f0-4104-bf85-b01e99433d25)
![image](https://github.com/user-attachments/assets/39954612-be19-4d92-a336-e0b2b9ef8191)
![image](https://github.com/user-attachments/assets/0d56d56d-3d3c-44da-857d-3027c38e79fa)
![image](https://github.com/user-attachments/assets/e8f39074-5e14-4ec0-906f-9b8721e2209f)
![image](https://github.com/user-attachments/assets/b2f82d60-231b-4ef2-b17e-214b07f90920)
![image](https://github.com/user-attachments/assets/75efad68-3427-46b1-9b86-d8c24ce8cb1b)
![image](https://github.com/user-attachments/assets/bbbd2fe5-a4f5-4222-907a-915d61e51c9d)
![image](https://github.com/user-attachments/assets/16e5d477-0c8e-47fc-bbf3-03fdc9973d79)






## Conclusion
---------------
This analysis visualizes and compares rape cases across Indian states, breaking down the data by age groups and case types (incest, other, total). The findings highlight significant state-wise and age-wise disparities, with many victims being minors. These insights emphasize the urgent need for targeted prevention, policy action, and support services to address and reduce sexual violence in India.

## Key Insights
---------------

### 📈 Temporal Trends
- While overall trends show fluctuations, consistent patterns emerge in the **age distribution of victims**.
- The age group **below 18** shows significant numbers across various categories, indicating a persistent **vulnerability** within this demographic.

### 🗺️ Geographic Distribution
- **Four states**—**Rajasthan, Madhya Pradesh, Uttar Pradesh**, and **Maharashtra**—consistently report the **highest number of cases** over the years.

### 🧮 Data Quality Considerations
- **Inconsistent column names** and **missing data** across different years limit the scope of analysis and the reliability of long-term trends.
- Further **data cleaning and standardization** are crucial to extract more robust conclusions.
- Future analyses could benefit from incorporating **demographic and socioeconomic factors** to provide richer insights.

### 🔍 Incest vs. Other Rape Cases
- Analyzing the **ratio and normalized percentages** of incestuous versus other rape cases can provide important insights.
- Rising or falling trends in these metrics may reflect **changes in societal norms** or **reporting patterns**.
- It's crucial to examine the **specific context of each state** when interpreting these results.

### 📊 Age-wise Distribution
1. Across the years, the **age group below 18** consistently shows a **high percentage** in the categories of incest, other, and total rape cases.
2. **Incest rape cases involving minors** are approximately **50%** of total incest cases.
3. **More than 50%** of total rape cases belong to the **18–30 year** age category.
4. **Focused and tailored interventions** are necessary for these vulnerable demographics.

## 📈 Future Work

- Predictive modeling of case outcomes
- Natural language processing of FIR narratives
- Interactive dashboard development
- Policy impact analysis of 2013 legal reforms

*Note: Actual findings may vary based on latest data updates*
*Disclaimer: Contains sensitive content. Strictly for academic/research purposes.*

