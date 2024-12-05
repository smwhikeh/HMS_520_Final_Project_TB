# HMS_520_Final_Project_TB
Final Project for HMS520 Data Analysis for (GBD 2021) Tuberculosis Estimates 1990-2021

## Team member[s]

- Sophie Whikehart and Ye Naing 

## Format we chose 

3. Analyzing a dataset that uses data wrangling and modeling tools in R

## Overall goal of project 

In our project we plan to use the Global Burden of Disease 2021 (GBD 2021) Tuberculosis Estimates 1990-2021. 
Our dataset contains mortality counts across different age groups, years and location. We would like to investigate trends in global mortality rates from tuberculosis by different 
age groups and regions from 2015 and 2020 in order to understand patterns in mortality rates. Our main questions are:

**1. How have mortality rates changed from 2015 to 2020 across different age groups?**

**2. What is the relative contribution of different risk factors to mortality in 2015 and 2020?**

**3. Do regions or age groups with higher mortality reductions show lower risk factors contribution?**

## Detailed plans and timeline 

### Detailed Plan 

**1. How have mortality rates changed from 2015 to 2020 across different age groups and regions?**

- Main goal: Assess change in mortality trends over time to identify vulnerable age groups or regions with the largest reductions or increases in mortality 

- Analysis ideas:
    
    - Calculate percentage change in mortality [`mort_2020_count_mean` vs `mort_2015_count_mean`]
    - Use data wrangling to group by age group or region and visualize trends with a bar or line chart 

- Potential outputs
    
    - Bar plot of mortality changes by age group and location
    - Insights on which age group or region have seen the most improvement / setback

**2. What is the realative contribution of different risk factors [ex - smoking, alcohol, and diabetes] to mortality in 2015 and 2020?**

- Main goal: Understand impact of individual risk factors on overall mortality and identify the most influential contributors

- Analysis ideas:

    - Normalize risk factors [`rmv_mean_smoking`, `rmv_mean_alcohol`] by total risk [`rmv_mean_all_risk`]
    - Create bar plot to visualize proportion of each risk factor's contribution 

- Potential Output 

    - Chart showing relative contributions of smoking, alcohol, and diabetes across age group or locations
    - Key findings on which risk factors to target for interventions 

**. Do regions or age groups with higher mortality reductions also show lower risk factor contributions?**

- Main goal: Explore relationship between changes in mortality and prevalence or impact of risk factors 

- Analysis ideas:

    - Correlation analysis between `mortality_change` an indiviudal risk factors [`rmv_mean_smoking`]

- Potential ouputs

    - Scatterplot of mortality change vs smoking/alcohol contributions 
    - Insight on if risk reduction efforts have contributed to improved mortality outcomes

### Timeline 

- Day 1-3 : Initial setup and data cleaning 
- Day 4-6: Mortality Trends and Risk Factor Contribution 
- Day 7-9: Correlation & Group Analysis 
- Day 10-12: Interpretation, Final Report and Presentation 