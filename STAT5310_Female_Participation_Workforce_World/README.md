![project_image](https://github.com/sonalgan/Data-Science-Projects/assets/57640393/125de8a4-57a8-4956-9cd6-658054a0aa87)


# Female Participation in Workforce in World - README

This repository contains the project files for the "Female Participation in Workforce in World" project, which aimed to analyze the factors influencing female participation in the workforce worldwide using Multiple Linear Regression (MLR) implemented in R. The project was conducted as part of the STAT5310 course on Data Science.

## Folder Structure

- `Data Science Projects`
  - `STAT5310_Female_Participation_Workforce_World`
    - `report.rmd`: The R Markdown file containing the code, analysis, and visualizations for the project.
    - `final_project.pdf`: The final report summarizing the project findings and conclusions.

## Project Description

The "Female Participation in Workforce in World" project focused on studying the disparity between male and female workforce participation across different countries. The objective was to identify the socio-economic factors that influence the percentage of employed women using Multiple Linear Regression (MLR) techniques. The project was implemented using R programming language.

## Data and Analysis

The project utilized data from the World Bank database, specifically focusing on 11 development indicators related to female employment and other predictor variables across 217 countries for the year 2019. The data was preprocessed to handle missing values and simplify variable names. The MLR model was then built using the selected predictors to analyze the relationship with the percentage of employed women.

## Analysis Highlights

The regression analysis revealed the following insights:

- The intercept of the regression model was -6.87, indicating a negative impact on the average percentage of employed women in the given year.
- The variable "RatioMaletoFemale" showed a positive correlation with the response variable. An increase in the male-to-female labor force participation ratio led to an increase in the percentage of employed women.
- Another significant predictor was "ContrFamWorkers," which positively influenced the response variable. An increase in the number of contributing family workers in a household increased the chances of female employment.
- Surprisingly, variables such as "Industry" and "FertilityRate" had a low impact on the response variable.

## Conclusion

The project findings suggest that a healthy ratio of male-to-female labor force participation and a higher number of contributing family workers in households positively influence the percentage of employed women. The analysis provides insights into the factors affecting female workforce participation and highlights areas for further research and intervention.

## References

1. [GenderData.WorldBank](https://genderdata.worldbank.org/data-stories/flfp-data-story/#:~:text=The%20global%20labor%20force%20participation,business%20expansion%20or%20career%20progression)
2. [OurWorldInData - Female Labor Supply](https://ourworldindata.org/female-labor-supply)
3. [Kaggle Dataset - Female Employment vs Socioeconomic Factors](https://www.kaggle.com/datasets/mdmuhtasimbillah/female-employment-vs-socioeconimic-factors)
4. [World Development Indicators - World Bank](https://databank.worldbank.org/source/world-development-indicators/Type/TABLE/preview/on#)

For more detailed analysis and findings, please refer to the R Markdown file (`report.rmd`) and the final report (`final_project.pdf`) included in this repository.

For any questions or further information, please contact [Sonal Ganvir] at [sonalgan2000@gmail.com].
