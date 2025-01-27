# Prediction-of-air-quality
This project predicts relative humidity (RH) using a dataset of air quality sensor readings from an Italian city. Various models, including Random Forest and Polynomial Regression, were tested, achieving high accuracy. Hyperparameter tuning showed minimal improvement, and all features were used to enhance prediction performance.

The dataset used is from the Air Quality UCI repository, containing real-world data collected from an air quality monitoring station. Initially, the dataset is cleaned by removing missing values, converting the date and time columns to appropriate formats, and handling any outliers or invalid entries. A correlation heatmap is visualized to understand the relationships between different air quality parameters and RH.

# Model development
After preprocessing, the data is split into training and testing sets. And then different regression models were applied to predict RH. Then Standardization is used on the features for better model performance. The models' effectiveness is evaluated using the Root Mean Square Error (RMSE) metric, with each model demonstrating its ability to predict RH based on the input air quality parameters. The project highlights how machine learning models can be utilized to predict environmental variables, with Random Forest providing the best predictive performance in this case.
