# up221-foodaccess
## Group Name: Food Access in LA County
### Group Assignment 1

## Introduction:
We plan to explore the relationship between food insecurity and adult health outcomes in Los Angeles County. Food insecure areas do not exist randomly throughout the [county of Los Angeles](https://storymaps.arcgis.com/stories/4ef7d78c52ec4b29a6073ffdc6809e83), and are often correlated with race and income levels (U.S. Department of Health and Human Services, n.d.). Food insecurity has been shown to be associated with cardiovascular disease, possibly through a circular association, where some studies suggest that cardiovascular medical cost could result in being food insecure (Chang et al., 2022). Given this association, it is important to investigate how these variables are distributed across Los Angeles County to delineate areas that are most affected or neighborhoods that could benefit from an intervention. Our research aims to understand the impact of government policy such as EBT access on adult cardiovascular health in the County of Los Angeles. Our primary research question is: does food insecurity spatially associate with adult cardiovascular disease in Los Angeles County and if so, what is the association?

## Spatial Scope:
Our project focuses on the county of Los Angeles because of our existing knowledge of the area's policies and the availability of data. The list of food resources in California is a snapshot of 2020 whereas the EBT acceptance data runs from 2017 - 2023 and the heart disease prevalence data is from 2013 - 2014. Understanding spatiality is important for our project because cardiovascular disease is among the top ten leading causes of death in Los Angeles (Los Angeles County Department of Public Health, 2019). Discerning which census tracts are most affected by risk factors and adverse health outcomes may help inform policy and intervention programs.

## Data Sources:
We plan to use a dataset from USC's Neighborhood Data for Social Change resource on EBT acceptance rates across LA county by census tract. This dataset from 2021 includes geocodes for each census tract, the total population of each tract, how many businesses accept EBT in each tract, and the rate of EBT acceptance in each tract.

A second dataset that we will use is the Prevalence of Adult Heart Disease from 2013-2014. Data for this dataset came from the California Health Interview Survey Neighborhood Edition and the dataset provides the prevalence of respondents who were 18 years and older and were ever diagnosed with heart disease. The prevalence of heart disease is provided by zip code.

An additional dataset we may use is the Food Resources in California dataset from the LA city controller. This dataset contains a list of food resources including food banks, pantries, etc, as well as the address and contact information of each of these resources.

## Include datasource with links

[https://map.myneighborhooddata.org/](https://map.myneighborhooddata.org/) - USC Neighborhood Change
Variable(s): EBT Acceptance Rate in LA County by Census Tract 2021
[https://map.myneighborhooddata.org/](https://map.myneighborhooddata.org/) - USC Neighborhood Change
Variable(s): Coronary heart disease prevalence in LA County by Census Tract 2020
[https://www.census.gov/programs-surveys/acs/data.html](https://www.census.gov/programs-surveys/acs/data.html) - American Community Survey
Variables(s): Demographics (race, ethnicity, sex, age) and socioeconomics (income, employment, housing) in LA County by Census Tract 2016-2020

## Analysis and Visualizations:
In this analysis, we intend to explore the spatial distribution of food access as measured by EBT acceptance rate. We also will explore the spatial distribution of heart disease prevalence. Our analysis will result in a map with differing layers, including food access and heart disease so we can determine areas of Los Angeles county that are affected by both variables and help understand any interaction between the two variables.

In order to understand the association between food insecurity and cardiovascular disease, we will perform a spatial regression analysis and map the regression results across LA County. We will analyze the spatial distribution of the regression to identify areas where the association is stronger or weaker. We will use our demographic and socioeconomic variables in our regression to better understand this relationship.

## Conclusion:
From our research, we hope to gain a better understanding of how EBT access is spatially correlated with adult heart disease. Exploring spatial correlations may provide insight into which specific areas of LA are more at risk for heart disease or which tracts could benefit the most from interventions.

## References:
Chang, R., Javed, Z., Taha, M., Yahya, T., Valero-Elizondo, J., Brandt, E. J., ... & Nasir, K. (2022). Food insecurity and cardiovascular disease: Current trends and future directions. American Journal of Preventive Cardiology, 9, 100303.

Food insecurity. Food Insecurity - Healthy People 2030. (n.d.). [https://health.gov/healthypeople/priority-areas/social-determinants-health/literature-summaries/food-insecurity#:~:text=Food%20insecurity%20may%20be%20long%20term%20or%20temporary.&text=It%20may%20be%20influenced%20by,race%2Fethnicity%2C%20and%20disability.] 

Patterns in mortality in Los Angeles County, 2008-2017. Los Angeles County Department of Public Health. Office of Health Assessment and Epidemiology. December 2019.

