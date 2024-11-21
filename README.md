# ML-based-Predictive-model
An ML based model that uses regression to predict calories burned while exercising.
Methodology:
1.	Data Loading:
    1.1.	Uses the pandas library to load datasets (calories.csv and exercise.csv).
  	1.2.	Displays the first and last few rows to understand the data structure.
2.	Data Merging:
  	2.1.	Merges the two datasets on a common key (User_ID), combining exercise and calorie data.
3.	EDA Steps:
  	3.1.	Dataset Shape: Displays the number of rows and columns in the merged dataset.
	  3.2.	Data Types: Uses .info() to list features and their respective data types.
	  3.3.	Null Values: Checks for missing data to ensure data quality.
4.	Statistical Analysis and Visualization:
    4.1.	Incorporates matplotlib and seaborn for data visualization.
    4.2.	Includes plots for understanding relationships and distributions (likely scatter plots, histograms, or heatmaps).
5.	Machine Learning Component:
    5.1.	Splits data into training and testing sets (train_test_split).
    5.2.	Implements a Random Forest Regressor to predict calories burned based on exercise data.
  	5.3.  Evaluates the model's performance using metrics such as MAE, MSE, or RMSE.
