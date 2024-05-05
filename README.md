# Energy-prediction-project-

# 1) Project Overview:
-This project aims to model the energy production of a combined-cycle power plant based on various ambient and operational variables.
-The dataset consists of 9568 observations collected over six years, with features including temperature, exhaust vacuum, ambient pressure, relative humidity, and energy production.

# 2) Data Preprocessing:
-Checked for missing values (none found).
-Examined data statistics to understand the distribution and variability of each feature.
-Identified and handled outliers using the interquartile range method.
-Visualized pairwise relationships between features and energy production using pair plots and a correlation heatmap.

# 3) Modeling:
-Utilized multiple regression techniques to predict energy production.
-Split the dataset into training and testing sets (80/20 split).
-Trained a Linear Regression model and evaluated its performance using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).
-Employed K-Nearest Neighbors (KNN) Regression and optimized hyperparameters using GridSearchCV.
-Explored decision tree-based models including Decision Tree Regressor, Bagging Regressor, Random Forest Regressor, and AdaBoost Regressor.
-Evaluated the performance of XGBoost and Support Vector Machine (SVM) regressors.

# 4) Results:
-Linear Regression achieved an accuracy score of approximately 92.83%.
-KNN Regression with 6 neighbors obtained an accuracy of around 92.85%.
-Decision Tree, Bagging, Random Forest, and XGBoost achieved accuracies of approximately 96.03%, 96.14%, 96.14%, and 95.07% respectively.
-SVM Regression yielded a lower accuracy of around 34.87%.

# 5) Conclusion:
-The project successfully modeled energy production based on ambient and operational variables using various regression techniques.
-Decision tree-based ensemble methods demonstrated superior performance compared to linear and instance-based models.
-The choice of model can be based on computational efficiency and the desired level of interpretability.

# 6) Future Improvements:
-Explore additional feature engineering techniques to enhance model performance.
-Investigate advanced machine learning algorithms and ensemble methods.
-Conduct further experimentation with hyperparameter tuning to optimize model performance.
