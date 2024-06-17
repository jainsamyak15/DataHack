# Samyak_Datahack

## Project Overview
- Predict the likelihood of individuals receiving the XYZ Vaccine and Seasonal Vaccine using machine learning techniques.
- Dataset contains various features related to demographics, behaviors, opinions, and health conditions of the respondents.

## Dataset
- Includes information about respondents' characteristics, such as age, education, race, income, and employment status.
- Contains features related to respondents' opinions and behaviors regarding vaccines and flu prevention.

## Methodology
1. Data Preprocessing:
  - Handled missing values using the IterativeImputer for numerical columns.
  - Encoded categorical variables using OneHotEncoder.
  - Created a preprocessing pipeline using scikit-learn's ColumnTransformer.

2. Model Selection:
  - Chose the Random Forest Classifier as the predictive model.
  - Random Forest is an ensemble learning algorithm known for its robustness and ability to handle complex relationships between features.

3. Model Training and Evaluation:
  - Trained the Random Forest model on the preprocessed data.
  - Evaluated the model's performance using the ROC AUC (Area Under the Receiver Operating Characteristic Curve) metric.
  - Achieved an ROC AUC score of 0.8539 for the XYZ Vaccine and 0.8557 for the Seasonal Vaccine, indicating good predictive performance.

4. Prediction:
  - Made predictions on the preprocessed test set.
  - Saved the predicted probabilities for each target variable in a submission file format.

## Results
- The trained model achieved a mean ROC AUC score of 0.8548, suggesting a strong ability to distinguish between individuals likely to receive the vaccines and those who are not.
- The model's performance demonstrates the effectiveness of the Random Forest Classifier in capturing the relationships between features and the target variables.
