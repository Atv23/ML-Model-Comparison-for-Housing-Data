# Machine Learning Models for Housing Price Prediction

## Overview
This repository contains the work for CSC3831's Machine Learning assignment, focusing on predicting housing prices. The project entails a comprehensive analysis of housing data, including data exploration, preprocessing, feature selection, and the development of multiple machine learning models to forecast median house values.

## Project Structure
- `Data Exploration`: Analyzed the dataset through descriptive statistics, visualization (histograms, scatter plots, correlation matrix), and identified missing values.
- `Preprocessing`: Addressed missing data, detected and treated outliers, engineered features, and encoded categorical variables. Explored dimensionality reduction techniques.
- `Feature Selection`: Identified key predictors of median house value using correlation analysis, Random Forest feature importance, and checked for multicollinearity.
- `Feature Normalization`: Normalized selected features to ensure equal contribution to the predictive models.
- `Machine Learning Models`: Developed and evaluated three distinct models:
  - **Linear Regression**: A baseline model for linear relationships.
  - **Decision Tree Regressor**: Captures non-linear relationships and feature interactions.
  - **Random Forest Regressor**: An ensemble method that improves robustness and handles complex data well.

### Data Exploration and Preprocessing
- Initial analysis revealed critical insights into the distribution and relationships within the data, guiding feature selection and preprocessing steps.
- Preprocessing efforts focused on ensuring data quality and relevance, including handling missing values, outlier treatment, and feature transformation for model readiness.

### Feature Selection and Normalization
- `Feature Selection`: Prioritized `median_income` and `housing_median_age` based on their correlation and importance scores. Excluded features with high multicollinearity.
- `Normalization`: Implemented to enhance model performance and ensure balanced feature influence.

### Machine Learning Implementation
1. **Linear Regression**:
   - Rationale: Simple and efficient for linearly correlated data.
   - Performance Evaluation: Used validation data to assess fit and guide adjustments.
2. **Decision Tree Regressor**:
   - Rationale: Ability to model complex, non-linear relationships and feature interactions.
   - Hyperparameter Tuning: Employed techniques like GridSearchCV for optimization.
3. **Random Forest Regressor**:
   - Rationale: Offers improved accuracy through ensemble learning, handling data complexity effectively.
   - Hyperparameter Tuning: Adjusted parameters such as `n_estimators` and `max_depth` for optimal performance.

### Comparative Analysis and Conclusions
- Conducted a detailed comparison of the models based on predictive ability and analysis metrics, highlighting the pros and cons of each approach.
- Concluded on the efficacy of each model and the impact of feature selection and preprocessing techniques on model performance.

## Running the Project
- Ensure all dependencies are installed. Refer to `requirements.txt` for a detailed list.
- Execute the Jupyter Notebook (`MachineLearningStart-1.ipynb`) to replicate the analysis and model development process.

## Conclusions
- The project demonstrates the effectiveness of various machine learning models in predicting housing prices, with an emphasis on the importance of thorough data preparation.
- Insights into feature relevance and model performance provide a strong foundation for further exploration and optimization.

## Acknowledgments
- Special thanks to the CSC3831 instructors and TAs for providing the dataset and guidance.
- Utilized Python libraries: Pandas for data manipulation, Matplotlib and Seaborn for visualization, and Scikit-learn for machine learning modeling.
