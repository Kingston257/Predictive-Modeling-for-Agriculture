# Sowing Success: How Machine Learning Helps Farmers Select the Best Crops

![Farmer on a field](farmer_in_a_field.jpg)
<br>

Measuring essential soil metrics such as nitrogen, phosphorous, potassium levels, and pH value is an important aspect of assessing soil condition. However, it can be an expensive and time-consuming process, which can cause farmers to prioritize which metrics to measure based on their budget constraints.

Farmers have various options when it comes to deciding which crop to plant each season. Their primary objective is to maximize the yield of their crops, taking into account different factors. One crucial factor that affects crop growth is the condition of the soil in the field, which can be assessed by measuring basic elements such as nitrogen and potassium levels. Each crop has an ideal soil condition that ensures optimal growth and maximum yield.

## The Dataset
A farmer reached out to you as a machine learning expert for assistance in selecting the best crop for his field. They've provided you with a dataset called [Soil Measures](soil_measures.csv), which contains:

- `"N"`: Nitrogen content ratio in the soil
- `"P"`: Phosphorous content ratio in the soil
- `"K"`: Potassium content ratio in the soil
- `"pH"` value of the soil
- `"crop"`: categorical values that contain various crops (target variable).

Each row in this dataset represents various measures of the soil in a particular field. Based on these measurements, the crop specified in the `"crop"` column is the optimal choice for that field.  

## Objective
In this project, you will build multi-class classification models to predict the type of `"crop"` and identify the single most importance feature for predictive performance.

## Project Activity
Notebook [View Code](notebook.ipynb)
- Supervised Machine Learning using Logistic Regression
- Feature Selection

## Key Insights
According to the provided dataset,
- The best feature for modeling predictive performance of the soil is 'K' (Potassium content ratio in the soil).
- Its accuracy score is about 0.28.

## Credits
Project and notebook environment were provided by [DataCamp](datacamp.com) 
