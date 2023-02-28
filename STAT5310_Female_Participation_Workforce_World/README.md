# A Study on Female Participation in Workforce in World

## Introduction

Half of the world's population roughly comprises of women but when compared to a country’s total workforce the male and female workers percentage is rarely similar. If you look at the developing and underdeveloped countries, it’s even more prominent. Insufficient access to education, religious superstitions, lack of adequate infrastructures are some of the reasons responsible for this discrepancy, also it goes way beyond these.  The total labor force has been considered to show the effects of multiple socioeconomic factors on the women participation in the total workforce ad percentage of female employment. The relationship between these factors can be analyzed using multiple linear regression model.

## Problem 
Our original data comes from World Bank database where they have a collection of development indicators to estimate various socio-economic factors for all nations in the world. The data was collected using the Data Bank online resource which allows users to form custom time-series data sets based on chosen filters like countries, years and development indicators. We gathered data for each of the 11 development indicators (including the employed women percentage and related predictor variables) across 217 countries for the most recent year, 2019. After performing data preprocessing like removing missing values and labeling our indicators to more simple variable names .etc , we get our final data having 187 data points (countries). There is one response variable which is the percentage of the employed women explanatory variables of predictors. Brief descriptions of these variables are given below.

**1. PerFemEmploy (Employment to population ratio (%) of women who are of age 15 or older.)** Employment to population ratio is the proportion of a country's population that is employed. Employment is defined as persons of working age who, during a short reference period, were engaged in any activity to produce goods or provide services for pay or profit, whether at work during the reference period (i.e. who worked in a job for at least one hour) or not at work due to temporary absence from a job, or to working-time arrangements. Ages 15 and older are generally considered the working-age population.

**2. FertilityRate (Fertility rate (birth per women).)** Total fertility rate represents the number of children that would be born to a woman if she were to live to the end of her childbearing years and bear children in accordance with age-specific fertility rates of the specified year.

**3. RatioMaletoFemale (Ratio of female to male labor force participation rate.)** Labor force participation rate is the proportion of the population ages 15 and older that is economically active: all people who supply labor for the production of goods and services during a specified period. Ratio of female to male labor force participation rate is calculated by dividing female labor force participation rate by male labor force participation rate and multiplying by 100.

**4. PerFemEmployers Employers, female (% of female employment).** Employers are those workers who, working on their own account or with one or a few partners, hold the type of jobs defined as a "self-employment jobs" i.e. jobs where the remuneration is directly dependent upon the profits derived from the goods and services produced), and, in this capacity, have engaged, on a continuous basis, one or more persons to work for them as employee(s).

**Agriculture (Employment in agriculture, female (% of female employment).)** Employment is defined as persons of working age who were engaged in any activity to produce goods or provide services for pay or profit, whether at work during the reference period or not at work due to temporary absence from a job, or to working-time arrangement. The agriculture sector consists of activities in agriculture, hunting, forestry and fishing, in accordance with division 1 (ISIC 2) or categories A-B (ISIC 3) or category A (ISIC 4).

**5. Industry (Employment in industry, female (% of female employment).)** The industry sector consists of mining and quarrying, manufacturing, construction, and public utilities (electricity, gas, and water), in accordance with divisions 2-5 (ISIC 2) or categories C-F (ISIC 3) or categories B-F (ISIC 4).

**6. Services (Employment in services, female (% of female employment).)** The services sector consists of wholesale and retail trade and restaurants and hotels; transport, storage, and communications; financing, insurance, real estate, and business services; and community, social, and personal services, in accordance with divisions 6-9 (ISIC 2) or categories G-Q (ISIC 3) or categories G-U (ISIC 4).

**7. Wage.Salaried (Wage and salaried workers, female (% of female employment).)** Wage and salaried workers (employees) are those workers who hold the type of jobs defined as "paid employment jobs," where the incumbents hold explicit (written or oral) or implicit employment contracts that give them a basic remuneration that is not directly dependent upon the revenue of the unit for which they work.

**8. ContrFamWorkers (Contributing family workers, female (% of female employment).)** Contributing family workers are those workers who hold "self-employment jobs" as own-account workers in a market-oriented establishment operated by a related person living in the same household.

**9. OwnAccount (Own-account female workers (% of employment).)** Own-account workers are workers who, working on their own account or with one or more partners, hold the types of jobs defined as "self-employment jobs" and have not engaged on a continuous basis any employees to work for them. Own account workers are a subcategory of "self-employed".

**10. Vulnerable (Vulnerable employment, female (% of female employment).)** Vulnerable employment is contributing family workers and own-account workers as a percentage of total employment.

## Purpose
We can apply Linear Regression Model and other statistical methods on this dataset to analyze if there are any viable relationship between the response of the variables and the predictor.
