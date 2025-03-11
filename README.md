Methodology
To predict student performance, we follow these steps:

Data Collection:

We use student data containing Study Hours, Previous Scores, and Final Exam Scores.
Data Preprocessing:

Check for missing values and remove them if needed.
Separate the data into input features (Study Hours, Previous Scores) and target variable (Final Exam Score).
Data Splitting:

Split the data into Training (80%) and Testing (20%) to train the model.
Model Training:

Use Linear Regression to create a model that learns from training data.
Model Evaluation:

Predict the scores on test data.
Measure accuracy using Mean Absolute Error (MAE) and Mean Squared Error (MSE).
Live Prediction:

Take user input for Study Hours and Previous Score.
Predict the expected Final Exam Score using the trained model.
Visualization:

Display a scatter plot to show the relation between Study Hours and Final Exam Score.
Add a regression line to understand the trend.

Output
Example Input:
Enter study hours: 8.5  
Enter previous score: 70

Example Prediction Output:
Predicted Final Exam Score: 75.23  
Performance Metrics:
Model Performance: MAE = 6.2, MSE = 8.9  

Graph Output:
A scatter plot of Study Hours vs Final Exam Score.
A red regression line indicating the trend.
