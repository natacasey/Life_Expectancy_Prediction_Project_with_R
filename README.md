# Life Expectancy Prediction Project with R

![picture](https://github.com/natacasey/Life_Expectancy_Prediction_Project_with_R/blob/master/_assets/life_expectancy_pic%20(1).jpg)

## Project description

Relying on the [data](https://www.kaggle.com/kumarajarshi/life-expectancy-who) put together by WHO and the United Nations, this project examined the hypotheses about the relationships between such factors as education, BMI, population density, expenditure on health, alcohol consumption and the variable life expectancy with the help of multiple regression analysis. 
Assumptions of Multiple Linear Regression models were tested. 

## Development:
Programming langauge - R. 

## Details 

Assumption of Independence and assumption of normality of residuals’ distribution were violated for the first regression model.

![violations](https://github.com/natacasey/Life_Expectancy_Prediction_Project_with_R/blob/master/_assets/violations.PNG)

After performing some research on the possible causes of the independence violation, the decision to test the hypotheses including the data for only one year was made. 

## Final model

![final model](https://github.com/natacasey/Life_Expectancy_Prediction_Project_with_R/blob/master/_assets/final_model.PNG)

The two factors that seem to have a significant positive relationship with life expectancy are “Schooling” which belongs to the social factor, and “BMI” which is associated with the health factor. 
The variables could be used for predictions of life expectancy with the help of the model. 

## Project limitations and considerations for the future

- The project has some limitations. Even though it provides results for effects of BMI and Schooling, it doesn’t explain other factors that could be influencing life expectancy. 
Considering performing the analyses of other variables from the data set can allow for discovery of additional factors influencing life expectancy.

- Incorrect data points present in the data set and missing values significantly reduced the amount of observations available thus reducing the possibility of accounting for all of the information for the variables. Finding the original data set and verifying the values would help with substituting the incorrect values of the secondary data set analyzed in the project.

- The project only covered the values for the year of 2014. There are 15 more years which the project hasn’t analyzed.Further analysis of the rest of the years and comparison of the results could help with confirming or questioning the validity of the results obtained so far, or identifying the trends of effects on life expectancy over the given time frame.

- Looking at different ranges of BMI separately could help with getting a clearer picture of the findings and more possible reasons for explanation of the results of this project.


















