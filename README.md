# **Advertising Data Prediction using LightGBM**

## **Project Description**  
This project focuses on building a machine learning model to predict advertising effectiveness using the LightGBM Regressor. The goal is to analyze various features from the advertising dataset and develop a predictive model to estimate outcomes like sales based on these features.

## **Table of Contents**:
1. [Project Overview](#project-overview)
2. [Datasets](#datasets)
3. [Methodology](#methodology)
4. [Results and Insights](#results-and-insights)
5. [Technologies Used](#technologies-used)
6. [How to Run the Project](#how-to-run-the-project)
7. [Conclusion](#conclusion)

## **Project Overview**  
The goal of this project is to predict the sales or effectiveness of advertising based on key features from an advertising dataset. The LightGBM Regressor is used for this purpose, with hyperparameter tuning applied to improve model accuracy.

## **Datasets**  
- **Advertising Dataset**: Contains features related to advertising efforts such as TV, radio, newspaper, and corresponding sales data.

## **Methodology**  
1. **Data Cleaning and Preprocessing**: Addressed missing values and standardized the dataset for better model performance.
2. **Feature Engineering**: Created new features to improve model accuracy.
3. **Model Selection**: Applied LightGBM Regressor as the primary model for predictions.
4. **Hyperparameter Tuning**: Tuned model hyperparameters to optimize performance.
5. **Model Evaluation**: Used metrics such as Mean Squared Error (MSE) to evaluate model performance.

## **Results and Insights**  
- **Final Model Performance**: The LightGBM Regressor achieved an MSE of 0.87, indicating a good fit to the data.
- **Feature Importance**: TV advertising had the highest impact on sales, followed by radio and newspaper.

## **Technologies Used**  
- Python (Pandas, NumPy, LightGBM)
- Machine Learning (LightGBM Regressor)
- Data Visualization (Matplotlib, Seaborn)

## **How to Run the Project**  
1. Clone the repository.
2. Install the required libraries using the provided `requirements.txt`.
3. Open and run the Jupyter Notebook to explore the analysis.

## **Conclusion**  
The project demonstrates the use of the LightGBM Regressor in predicting advertising effectiveness. The final model provides valuable insights into which advertising channels contribute most to sales, with TV being the dominant feature.
