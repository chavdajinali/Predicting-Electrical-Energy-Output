
# Predicting-Electrical-Energy-Output
Combined Cycle Power Plant (Machine Learning Project)

# Project Overview
This project focuses on predicting the electrical energy output (PE) of a Combined Cycle Power Plant using machine learning models. The goal is to improve efficiency, optimize operations, and reduce operational costs.

# Objectives
	•	Predict energy output using environmental factors
	•	Compare different machine learning models
	•	Analyze the impact of different feature combinations
	•	Identify the best-performing model

# Dataset Information
The dataset contains 9568 hourly observations collected from power plant sensors.

# Features:
	•	AT(Ambient Temperature)
	• 	AP(Ambient Pressure)
	• 	RH(Relative Humidity)
	• 	V(Exhaust Vacuum)
	• 	PE(Energy Output (Target Variable))

# Data Preprocessing
	•	Checked for missing values
	•	Verified feature ranges
	•	No categorical variables (all numeric data)
	•	Train-test split:
	  •	80% Training
	  •	20% Testing
    
# Models Used
# 1. Linear Regression
	•	Simple baseline model
	•	Assumes linear relationships

# 2. Random Forest Regressor
	•	Ensemble model (multiple decision trees)
	•	Captures non-linear relationships
	•	Hyperparameters tested:
	•	n_estimators = 50
	•	n_estimators = 100

  # Evaluation Metrics
	•	RMSE (Root Mean Squared Error) → Lower is better
	•	R² Score → Closer to 1 is better

  # Feature Sets Tested
	•	All Features → AT, AP, RH, V
	•	Without RH → AT, AP, V
	•	Without AP → AT, RH, V
	•	Only AT & V

# Results
<img width="995" height="591" alt="Screenshot 2026-04-02 at 11 18 45 AM" src="https://github.com/user-attachments/assets/a781b323-edea-48a5-8b45-07903de063ef" />

# Conclusion
The Random Forest model provides the most accurate and stable predictions for energy output. Using all input features improves performance, making the model suitable for real-world power plant optimization.

# Tech Stack
	•	Python
	•	Pandas
	•	NumPy
	•	Scikit-learn
	•	Matplotlib

# How to Run
 	 ## Install dependencies
		pip install pandas numpy scikit-learn matplotlib
	## Run Jupyter Notebook
		jupyter notebook

# Explanation Video
https://youtu.be/aqTIdmaRATY
