# Life Expectancy Analysis

## Overview

This repository provides a comprehensive analysis of factors influencing life expectancy across 193 countries from 2000 to 2015. The project utilizes data from the World Health Organization (WHO) and the United Nations, focusing on critical health, economic, and social indicators to derive actionable insights for policy-making and improving global life expectancy.

## 🎯 Objectives

This analysis aims to address gaps in previous research, particularly the lack of consideration for immunization coverage and the Human Development Index (HDI). By incorporating these factors, the project uses advanced regression models—mixed effects and multiple linear regression—to better understand the relationships between various determinants and life expectancy. The insights gained from this study can help countries prioritize key areas for improving the health and longevity of their populations.

## 📊 Dataset

The dataset contains 2,938 rows and 22 columns, with data spanning 193 countries over a 15-year period. Predictive variables are categorized as follows:

- **Immunization Factors:** Coverage for Hepatitis B, Polio, and Diphtheria
- **Mortality Factors:** Adult Mortality, Infant Deaths, and Under-Five Deaths
- **Economic Factors:** GDP and Percentage Expenditure
- **Social Factors:** Years of Schooling, Population Size, and Prevalence of Thinness

## Key Variables:

- **Life Expectancy**: Average lifespan in years
- **Adult Mortality**: Probability of death between the ages of 15 and 60 (per 1,000 population)
- **Alcohol Consumption**: Annual per capita alcohol consumption (liters of pure alcohol)
- **BMI**: Average Body Mass Index
- **Immunization Coverage**: Percentage coverage for Hepatitis B, Polio, and Diphtheria
- **Income Composition of Resources**: Proxy measure for income-related factors
- **Years of Schooling**: Average education level

## 🛠️ Tools and Methodologies

- **Data Cleaning**: Conducted a Data Cleaning using Power Query Editor.
- **Exploratory Data Analysis (EDA)**: Conducted in Python, with additional visualization and analysis in Power BI.
- **Visualization**: Developed an interactive Power BI dashboard to provide actionable insights and trends.
- **Correlation Analysis**: Generated a Python-based correlation matrix to evaluate relationships between key variables.

## Power BI Dashboard Features

- **Dynamic Filters**: Users can filter data by year, region, and specific indicators.
- **Custom Visuals**: Advanced Power BI visualizations offer deep insights into life expectancy trends.
- **Interactive Storytelling**: Highlights relationships between health, education, and socio-economic indicators.

## Power BI Dashboard Example

Below is the screenshot of the interactive Power BI dashboard developed for the project:

![Power BI Dashboard](https://github.com/user-attachments/assets/5d111e51-9de5-4064-b56e-c54fe5a41824)

## Python Correlation Matrix

The correlation matrix evaluates relationships between critical variables such as:
- Alcohol consumption
- Immunization rates (Hepatitis B, Polio, Diphtheria)
- HIV/AIDS prevalence
- Measles cases
- Under-Five Deaths
- Years
- Schooling
- Life Expectancy

## Correlation Matrix Heatmap

The heatmap below illustrates the relationships between key variables, such as immunization rates, life expectancy, and mortality factors:

![Correlation Matrix Heatmap](https://github.com/user-attachments/assets/408970d2-acb7-4800-9ada-f6fe7b3ab383)

## Python Libraries Used:

- seaborn
- matplotlib

## Key Questions Explored

1. Which factors significantly impact life expectancy?
2. Should countries with lower life expectancy invest more in healthcare?
3. How do infant and adult mortality rates influence life expectancy?
4. What is the relationship between lifestyle habits (e.g., alcohol consumption) and life expectancy?
5. What role does education play in determining life expectancy?
6. Do densely populated countries have lower life expectancy?
7. How does immunization coverage influence life expectancy?
   
## Acknowledgments

Data used in this analysis was collected from:

- World Health Organization (WHO)
- United Nations Data Repository

Special thanks to Deeksha Russell and Duan Wang for assistance with data collection and preparation.

## How to Use This Repository

1. Clone the repository: git clone https://github.com/username/life-expectancy-analysis.git
2. Run the Python script to generate a correlation matrix.
3. Access the Power BI dashboard for an interactive exploration of the dataset.
4. Explore the README for detailed project documentation.

## Future Scope

- Expand the analysis to include recent data for further insights.
- Explore machine learning techniques for advanced predictive modeling.
- Develop additional visualizations for enhanced storytelling.

## License

This project is licensed under the MIT License. Refer to the LICENSE file for more details.
