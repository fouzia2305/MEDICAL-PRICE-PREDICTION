# Medical Cost Prediction

## Project Overview
This project aims to develop a predictive model to estimate individual medical expenses for health insurance purposes. Using a dataset containing demographic and health-related features, the model provides insights for setting insurance premiums.

## Dataset
The dataset includes 1,337 records with the following attributes:
- **age**: Age of primary beneficiary
- **sex**: Gender of insurance contractor (female, male)
- **bmi**: Body mass index
- **children**: Number of dependents
- **smoker**: Smoking status (yes, no)
- **region**: Residential area in the US (northeast, southeast, southwest, northwest)
- **charges**: Individual medical costs billed by health insurance

## Objective
To build an accurate predictive model that estimates medical expenses based on demographic and health-related features.

## Challenges and Solutions
- **Handling Duplicates**: Identified and removed duplicate records to ensure data quality.
- **Managing Outliers**: Applied Winsorization to handle extreme values in the dataset.
- **Encoding Categorical Variables**: Used one-hot encoding to transform categorical variables into numerical format suitable for modeling.

## Model Implementation
Implemented and evaluated several regression models:
- K-Nearest Neighbors (KNN)
- Linear Regression
- Support Vector Regressor (SVR)
- Decision Tree Regressor
- Random Forest Regressor

## Performance Evaluation
Models were evaluated using Mean Absolute Error (MAE). The Random Forest Regressor achieved the lowest MAE of 2318.35, indicating the most accurate predictions.

## Results and Conclusion
The project successfully demonstrated the ability to preprocess and analyze healthcare data, and to apply machine learning techniques for real-time cost prediction. The Random Forest model provides valuable insights for setting insurance premiums.

## Visualization
Visualizations were created to explore data distributions and relationships:
- Histograms for age and BMI
- Count plots for categorical features (sex, smoker)
- Scatter plots and line plots to examine relationships between features and charges
