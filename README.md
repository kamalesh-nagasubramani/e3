EXPT NO:3 Regression and Optimization (Multi Linear and Polynomial regression)

DATE: 04.02.2026


SCENARIO 1 – MULTILINEAR REGRESSION

Problem Statement

Predict student academic performance based on academic, behavioral, and lifestyle factors.

Dataset (Kaggle – Public) https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

Target Variable

· Final Exam Score (Average of Math, Reading, Writing)

Input Features

· Study hours per day

· Attendance percentage

· Parental education level (encoded)

· Test preparation course (encoded)

· Sleep hours


 TASKS (Multilinear Regression)

1. Import required Python libraries.

2. Load the student performance dataset.

3. Perform data preprocessing and encoding of categorical features.

4. Select multiple input features and compute the target variable.

5. Handle missing values using suitable imputation.

6. Apply feature scaling.

7. Split the dataset into training and testing sets.

8. Train a Multilinear Regression model.

9. Predict student performance for test data.

10. Evaluate performance using:

· MSE

· RMSE

· R² Score

11. Analyze regression coefficients to interpret feature influence.

12. Optimize the model using:

· Feature elimination

· Ridge and Lasso regularization


Visualization

· Predicted vs Actual exam scores

· Coefficient magnitude comparison

· Residual distribution plot


SCENARIO 2 – POLYNOMIAL REGRESSION

Problem Statement

Predict vehicle fuel efficiency based on engine characteristics where the relationship is non-linear.

Dataset (Kaggle – Public) https://www.kaggle.com/datasets/uciml/autompg-dataset

Target Variable

· Miles Per Gallon (MPG)

Input Feature

· Engine Horsepower

 TASKS (Polynomial Regression)

1. Import required Python libraries.

2. Load and clean the Auto MPG dataset.

3. Select horsepower as the independent variable.

4. Handle missing values.

5. Generate polynomial features for degrees 2, 3, and 4.

6. Apply feature scaling.

7. Split the dataset into training and testing sets.

8. Train Polynomial Regression models with different degrees.

9. Predict fuel efficiency values.

10. Evaluate each model using:

o MSE

o RMSE

o R² Score

11. Compare model performance across polynomial degrees.

12. Apply Ridge regression to control overfitting.


Visualization

· Polynomial curve fitting for different degrees

· Training vs Testing error comparison

· Overfitting and underfitting demonstration


SUBMISSION REQUIREMENTS

· Python code (with student roll numbers)

· Screenshot of code

· Screenshot of outputs and graphs

· GitHub repository link


