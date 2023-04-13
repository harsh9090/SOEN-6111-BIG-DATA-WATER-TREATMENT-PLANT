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

*1.* Create a predictive model that can predict the required dosage of the Chemical_Dosages_Alum chemical used in water treatment, based on the properties of the water being treated.

>We will be using pH, chlorine, hardness, alkalinity, and aluminium as main features and planning to predict the amount of chemical dosage for chlorine and alum. To achieve this, we will be using multiple linear regression, decision trees, and random forest and XGBoost algorithms and we will compare the results.

*2.* Make forecasts about the future values of Raw pH, Chlorine, Total Dissolved Solids, Hardness, and Alkalinity using time series analytic techniques in order to make decisions on seasonal changes in water treatment.
>We utilized the Prophet library to train a time-series model for our dataset. The data was transformed into the required format and the model was trained in a distributed manner across all columns. Using this trained model, we generated predictions for the future levels of PH_raw, total dissolved solids, and other water profile features for the next 365 days.


## Evaluation Metrics
The performance of each algorithm will be evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE),and Mean Squared Error (MSE) metrics.
