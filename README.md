# Algae Growth Prediction

This project explores the prediction of algae growth using various machine learning models. The goal is to evaluate model performance and determine the most effective approach for predicting algae growth in a controlled laboratory environment.

## Dataset  
The dataset used for this project is sourced from Kaggle:  
[Research on Algae Growth in the Laboratory](https://www.kaggle.com/datasets/rukenmissonnier/research-on-algae-growth-in-the-laboratory/data)  

## Project Workflow  
1. **Data Preprocessing**  
   - Load and clean the dataset  
   - Apply Min-Max normalization using `MinMaxScaler`  
   - Split data into **80% training** and **20% testing**  

2. **Model Training**  
   - Train various machine learning models to predict algae growth  
   - Models explored:    
     - Decision Tree  
     - Random Forest  
     - Support Vector Machine (SVM)  
     - Artificial Neural Networks  

3. **Feature Importance Analysis**  
   - Performed feature importance analysis to identify key factors influencing algae growth  
   - Results indicate that **only the light parameter is significant** in predicting algae growth  

4. **Model Evaluation**  
   - Evaluate model performance using:  
     - Root Mean Squared Error (RMSE)  
     - Mean Absolute Error (MAE)  
     - R-Squared (R²)  
