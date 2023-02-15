# SOEN 6111 BigData Project - Team 33

### *Project Title:*   Water Treatment Plant Data Analysis
#### *Project Members:* 
- Ronak Patel (40221814)
- Rutvik Jakasaniya (40220251)
- Harsh Mithaiwala (40221295)
- Ravleen Kaur (40221236)
#### *Riipen Project Link:* https://app.riipen.com/projects/vO16Y9zE/

## Project Description

The Objective of the project is to analyze water treatment data in order to identify trends, patterns, and potential issues with the water treatment process, and make data-driven recommendations for improving the efficiency and effectiveness of the treatment system.

The data set includes a variety of parameters such as: 
- *pH:* This is a measure of the acidity or alkalinity of the water, with a range from 0 to 14.
- *Chlorine:* Chlorine is a disinfectant used to kill bacteria and other microorganisms in water.
- *Turbidity:* This measures the amount of suspended particles in the water, which can be caused by clay, silt, algae, or other organic matter.
- *Total Dissolved Solids:* This measures the amount of dissolved solids such as salts and minerals present in the water.
- *Hardness:* This measures how much calcium and magnesium are present in the water.
- *Alkalinity:* This measures how much alkaline material such as bicarbonates and carbonates are present in the water.
- *Aluminum:* Aluminium in water is a form of dissolved aluminum, which is the result of aluminum ions being released into the water from natural sources such as rocks and soil.
- *Chemical Dosages (Chlorine, Alum, Lime(Pre), Lime(Post))*: This feature is a measure of the number of chemicals used to treat water.

## Research Questions

*1.* Based on the raw water features, such as pH, turbidity, hardness, What Chemical Dosages will be needed to make it safe for human consumption or agricultural purposes?

>We will be using pH, chlorine, hardness, alkalinity, and aluminium as main features and planning to predict the amount of chemical dosage for chlorine and alum. To achieve this, we will be using multiple linear regression, decision trees, and random forest and XGBoost algorithms and we will compare the results.

*2.* How do the levels of Total Dissolved Solids, Turbidity, and hardness, in water change over a specified period, and is there any indication of recurring patterns or trends in the data?
>Our initial analysis will involve examining measures of central tendency and dispersion. We will then utilise scatter plots and correlation analysis to identify any underlying patterns in the data. To uncover seasonality, trends, and cycles, we will employ techniques such as autocorrelation, decomposition, and the moving average.

*3.* What is the degree of variability in pH measurements in high-volume water processing? Additionally, Develop the prediction model to predict the error rate of the pH level in order to make water human consumable. 
>Initially, the degree of variability of the pH levels is computed based on the raw and finished values. Subsequently, a prediction model is developed to estimate the degree of variability, while considering the volume of water that flows from the plant. SVM and Linear Regression algorithms will be used. 

*4.* What is the variation in turbidity levels in water over a specified period, and is there any indication of increased variability during the snow melting season?
>According to the research, there exists a direct proportionality between the degree of turbidity and the volume of snow melt and rainwater passing through the rock formations. Therefore, correlation analysis will be conducted to explore this intriguing pattern.

## Evaluation Metrics
The performance of each algorithm will be evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), Mean Squared Error (MSE), and R-squared (R2) metrics.
