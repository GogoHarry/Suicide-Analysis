# Global Suicide Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Analysis and Visualization](#data-analysis-and-visualization)
- [Key Results and Findings](#key-results-and-findings)
- [Recommendations](#recommendations)
- [Data Limitation](#data-limitations)

### Project Overview

HealthStat Analytics lacks insights into global suicide patterns, considering demographics, economic factors, and generational trends. This project aims to address this by exploring and visualizing a complex suicide dataset using Tableau to uncover patterns, correlations, and trends. These insights will inform evidence-based public health strategies and interventions.

![image](https://github.com/GogoHarry/Suicide-Analysis/assets/82883963/c62d084c-8892-420f-b70c-ff483d7607f7)


### Data Source

The primary dataset used for this analysis is the global suicide Data.csv file, obtained from Kaggle, containing detailed information on global suicide rates between 1987 and 2016.
Data Import: I Connected Tableau to the chosen data source (CSV).
Data Exploration: I familiarized myself with the data by examining variable names, data types, and value ranges.

### Tools
- Tableau - Data analysis and creating reports


### Data Cleaning and Preparation

In the initial data preparation phase, we performed the following tasks:

Missing Values: Checked for missing data points and determined how to handle them.

Data Formatting: I ensured consistent data formats for the dates by changing the year data type from a number to a Date.

Calculated Fields:  I created new calculated fields in Tableau to derive additional insights, such as:


* Coefficient of GDP & Suicide number

![image](https://github.com/GogoHarry/Suicide-Analysis/assets/82883963/3ba677e8-9378-4491-b52d-eacacff81b64)


* Coefficient of Population & GDP

![image](https://github.com/GogoHarry/Suicide-Analysis/assets/82883963/324ecb53-0f24-4548-994e-c1adf35d06bf)


* Coefficient of Population & Suicide number

![image](https://github.com/GogoHarry/Suicide-Analysis/assets/82883963/1ada5798-8400-4ad5-857e-465c358f047c)


### Exploratory Data Analysis (EDA)

EDA involved exploring the suicide data to answer key questions, such as:

1. What is the Overall Suicide Number?

  ![image](https://github.com/GogoHarry/Suicide-Analysis/assets/82883963/b573bf5b-01a3-472a-b10b-fbe15d4beb09)


2. How do suicide rates vary across countries and demographic groups?

  ![Suicide Rate per Country](https://github.com/GogoHarry/Suicide-Analysis/assets/82883963/36b1847b-9c79-439b-af5a-da6491db3616)


3. Are there notable trends in suicide rates based on age and gender?

  ![Suicide by AgeGroup](https://github.com/GogoHarry/Suicide-Analysis/assets/82883963/77839aa5-25cd-4e64-ae1a-a1b6a4d769f8)   ![Suicide Rate by Gender](https://github.com/GogoHarry/Suicide-Analysis/assets/82883963/b00e090b-bf81-4fbe-873a-0cb817274b12)

  
4. What is the correlation between economic indicators (GDP) and suicide rates?

  ![GDP   Suicide](https://github.com/GogoHarry/Suicide-Analysis/assets/82883963/8dc7d20a-4464-4a67-8c8b-fddb7812da85)

  
5. How has the suicide rate changed over time in different countries?

  ![Prediction of Suicide Rate](https://github.com/GogoHarry/Suicide-Analysis/assets/82883963/2c3ab914-3200-4092-a073-c0b4ef659656)
  

6. Can we identify countries or regions with particularly high or low suicide rates?

  ![Country with Highest](https://github.com/GogoHarry/Suicide-Analysis/assets/82883963/1dc26ee5-28f9-4c06-a995-7a06a2b143ab)



### Data Analysis and Visualization

Filtering: I filtered the data by specific countries, regions, Sex, age groups, etc.

Visualizations: I then created the visualizations using Tableau's drag-and-drop interface. For the project, I utilized;
- World Map: Color-coded map to show global suicide rate distribution.
- Bar Charts: Compare suicide rates by country, gender, or age group.
- Line Charts: Analyze trends in suicide rates over time.
- Scatter Plots: Explore correlations between suicide rates and other factors.

* Building Charts
    * Build Chart
    * Format
        * Remove Lines & Grids
        * Clean up Axis & Headers
        * Coloring
        * Tooltip

Dashboard Creation: I organized key visualizations into a cohesive dashboard to tell a compelling story about the global suicide rates.
* Building Dashboard Steps
    * Build Container Structure
    * Put all Charts together
    * Format
        * Distributed the content "evenly"
        * Formated the colors and sizes, etc
        * Fitted it into "Entire View"
        * Add Legends
        * Add Spaces (Inner/Outer Padding)

  ![Suicide Analysis Dashboard](https://github.com/GogoHarry/Suicide-Analysis/assets/82883963/f16c09a2-15d6-4b47-bb6f-58dfec535c40)


### Key Results and Findings

- High National Suicide Burden: Our analysis revealed a concerning overall number of suicides at 6,748,240. Notably, the Russian Federation had the highest number of suicides (1,209,742), highlighting a specific area for potential intervention strategies.

- Vulnerable Age Groups:  Individuals between 35-54 and 55-74 years old exhibited the highest suicide rates, suggesting a need for targeted prevention efforts within these age demographics.

- Temporal Trends: Interestingly, the data shows the highest number of suicides occurred in 1999, followed by a decrease in 2016.  Further investigation is needed to understand the factors influencing this historical trend.

- Limited GDP Correlation: The analysis suggests a non-linear relationship between "gdp_for_year" and "suicides_no."  This indicates that Gross Domestic Product (GDP) alone may not be a significant explanatory factor for suicide rates in the data set analyzed.

### Recommendations
Given the high suicide burden and the identification of vulnerable age groups, I recommend a multifaceted approach to suicide prevention that goes beyond economic factors. This approach should include:

- Strengthening mental health services: Increased access to mental health care and support programs specifically tailored to the needs of middle-aged adults.
- Social support initiatives: Programs promoting social connection and reducing isolation among middle-aged populations.
- Targeted interventions in high-risk regions: Developing and implementing suicide prevention strategies specifically designed for the Russian Federation, considering its unique cultural and social context.
- Further research: Investigating the non-linear relationship between GDP and suicide rates to understand the complex interplay of economic factors with social, cultural, and psychological determinants of suicide.

By implementing these recommendations, we can work towards creating a more comprehensive and effective approach to suicide prevention that addresses the specific needs of individuals and communities most at risk.

### Data Limitations

- Under-reporting: Suicide is a sensitive topic and may be under-reported due to stigma, cultural beliefs, or legal restrictions. This can lead to an underestimation of the true suicide rate in some countries.
- Lack of Contextual Data: Suicide data alone might not provide the whole picture. Factors like mental health services, economic conditions, or social support can influence suicide rates. Without this context, it's difficult to understand the root causes and develop comprehensive prevention strategies.
- Data Availability: Reliable suicide data may not be available for all countries, especially low- and middle-income countries. This limits the scope of global analysis. Hence our data does not include suicide data on all countries of the World

Despite these limitations, our analysis uncovers clear patterns and trends in suicide rates across Nations. This provides a strong foundation for further research and targeted interventions to address this global public health concern. While the data may not be entirely comprehensive, the identified patterns offer valuable insights that can guide efforts to reduce suicide rates worldwide. By acknowledging these limitations and continuing to improve data collection methods, we can work towards creating a more accurate picture of the global suicide burden and develop more effective prevention strategies for all countries.
