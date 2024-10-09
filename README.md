# Capstone_Project
MI/AL Capstone Project.
The Silent Epidemic: Diabetes Prediction and Analysis
Diabetes is often referred to as a silent epidemic, affecting millions worldwide without showing immediate symptoms. This dataset provides an opportunity to delve into the factors that contribute to diabetes and potentially predict its occurrence. If you find this notebook useful, please consider upvoting it.


we have used Random forest modle to predict the Diabetes.

The Data set 
"diabetes_prediction_dataset.csv" is attached and was avaialbe in KAaagle.


the following columns are present in the Data set.
gender,age,hypertension,heart_disease,smoking_history,bmi,HbA1c_level,blood_glucose_level,diabetes


After Data load we have clean up the data to remove duplicates and 

Data Analysis 
We did extensive Data Analysis 
Age,
Geneder, 
smoking history.


Data Preperation.
we removed all the duplicates that were present in the data.
Also conversion of the non Integer data elements as integer

A corelation Matrix was also generated.

Then the Data was Split inot test and training  data and 
The analysis employed a Random Forest classifier to predict diabetes based on various health indicators and lifestyle factors. The model was trained and evaluated on a dataset of 100,000 records, and Hyperparameter tuning was performed to optimize the model's performance.

The model achieved an accuracy of approximately 95.1%, with precision of 0.98 for class 0 (non-diabetic) and 0.69 for class 1 (diabetic). It was also able to recall 96% of non-diabetic cases and 81% of diabetic cases correctly. The relatively high accuracy and balanced performance on both classes indicate that the model is well-tuned and robust.

Feature importance analysis highlighted HbA1c_level and blood_glucose_level as the most critical factors in predicting Diabetes. Age and BMI also showed significant importance. However, some features, such as smoking history and gender, had minimal or no impact on the model's predictions.
