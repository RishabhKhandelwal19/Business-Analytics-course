# Business-Analytics-course
This is my minor project for the course: Business Analytics from SmartKnower. 
# Wine-Quality-Predictions
Predicting the Quality of Red Wine using Machine Learning Algorithms for Regression Analysis, Data Visualizations and Data Analysis.
# Content
Input variables (based on physicochemical tests):
1 - fixed acidity 
2 - volatile acidity 
3 - citric acid 
4 - residual sugar 
5 - chlorides 
6 - free sulfur dioxide 
7 - total sulfur dioxide 
8 - density 
9 - pH 
10 - sulphates 
11 - alcohol 
Output variable (based on sensory data): 
12 - quality (score between 0 and 10) 
# Tips
As suggested in the question aside from only using regression modelling to set an arbitrary cutoff for your dependent variable (wine quality) at e.g. 6 or higher getting classified as 'good/1' and the remainder as 'poor/0'. This allows you to practice with hyper parameter tuning on e.g. decision tree algorithms looking at the ROC curve and the AUC value. Without doing any kind of feature engineering or overfitting you should be able to get an AUC of .88 (without even using random forest algorithm)
