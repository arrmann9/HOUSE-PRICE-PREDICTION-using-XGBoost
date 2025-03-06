# HOUSE-PRICE-PREDICTION-using-XGBoost

This project implements a House Price Prediction Model using XGBoost Regressor. The model is trained on the California Housing Dataset to predict house prices based on key housing and demographic features.

**Dataset**
The dataset contains housing-related parameters such as: 
Median Income, House Age, Average Rooms, Population, Latitude, Longitude, etc.
Target Variable: Price (Median house value in a district)

**Technologies Used**
* Python
* NumPy, Pandas
* Scikit-learn (Train-Test Split, Metrics, Correlation Analysis)
* Matplotlib, Seaborn (Data Visualization)
* XGBoost (Extreme Gradient Boosting Regressor)

  **{Why Use XGBoost?**
* Handles large datasets efficiently and is optimized for speed and performance.
* Uses boosted decision trees to improve prediction accuracy by reducing errors.
* Provides feature importance analysis, helping to identify the most influential variables.
* Includes regularization techniques to prevent overfitting and maintain model generalization.**}**
  
**Project Workflow**
* Load the dataset and convert it into a DataFrame.
* Perform exploratory data analysis (EDA), check for missing values, and analyze feature relationships.
* Split the dataset into training (80%) and testing (20%) sets.
* Train the XGBoost Regressor on the training data.
* Evaluate the model using R² Score and Mean Absolute Error (MAE).
* Visualize predictions with scatter plots.

  **{Why Evaluate with R² Score & MAE?**
* R² Score measures how well the model explains variance in house prices. A higher R² indicates better performance.
* Mean Absolute Error (MAE) shows the average absolute difference between actual and predicted prices. A lower MAE indicates better accuracy.**}**
  
**Model Performance:**

  **Training Accuracy**
* R² Score: 0.9436 (94.36% variance explained)
* MAE: 0.1933
  
  **Testing Accuracy**
* R² Score: 0.8338 (83.38% variance explained)
* MAE: 0.3108
  
**Observations:**
* The model performs well on training data and generalizes effectively to test data.
* The R² score of 0.83 on test data indicates strong predictive power.
* Further hyperparameter tuning may improve performance.
  
**Installation & Usage**
* Install Dependencies:
*pip install numpy pandas scikit-learn matplotlib seaborn xgboost*

**Future Improvements**
* Perform hyperparameter tuning to optimize model performance.
* Experiment with other ML models such as Random Forest and Linear Regression.
* Deploy the model as a web application.
  
**Author: Arman Ahmad**
[Connect with me on LinkedIn: www.linkedin.com/in/armanahmad16]

