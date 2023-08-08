# FGAUII-BigData
This repository is used to fulfill the assignment for the second session of FGAUII-BigData Training.
On this repository, I would like to introduce my exercise project of machine learning to predict stroke on patients.
Data were collected from Kaggle. Consist of id, gender, age	hypertension,	heart_disease,	ever_married,	work_type,	Residence_type,	avg_glucose_level,	bmi, and	smoking_status.
I used Logictic Regression and Decision Tree algorithm to determine which model could predict with great score.

Part of the code that I share is the steps of Data Preparation where we need to prepare the data before processing it.
Since column BMI has several missing values which could resulting in bias, we need to make sure that the data either being replaced or add new values based on several techniques.

On this project, I use mean techniques, where we find the mean value of column BMI and replace the missing values with the mean values.
