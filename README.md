# Easy-ML Documentation

## Overview
Easy-ML is a user-friendly machine learning library that provides easy-to-use implementations of popular algorithms. This documentation covers the setup instructions, file structure, CSV format requirements, model explanations, metrics, and future enhancements.

## Supported Models
1. **XGBoost**  
   XGBoost is an optimized distributed gradient boosting library designed to be highly efficient, flexible, and portable.
   - **Features**: Handles missing data, supports multiple languages, and built-in cross-validation.

2. **Random Forest**  
   Random Forest is an ensemble learning method that constructs multiple decision trees during training and merges them to improve accuracy.
   - **Features**: Reduces overfitting, handles large datasets, and provides feature importance.

3. **Linear Regression**  
   A simple algorithm that models the relationship between a dependent variable and one or more independent variables.
   - **Features**: Easy to implement, interpretable results, and gives overall trend.

4. **Elastic Net**  
   Combines L1 (Lasso) and L2 (Ridge) regularization techniques to enhance model performance in the presence of correlated features.
   - **Features**: Tackle multicollinearity, sparse solutions, and flexibility in penalty formulation.

5. **Decision Tree**  
   A non-parametric supervised learning method used for classification and regression.
   - **Features**: Easy to interpret, handles categorical data efficiently, and requires little data preprocessing.

## Setup Instructions
1. Clone the repository:
   ```
   git clone https://github.com/MarkSun04HX/Easy-ML.git
   ```
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
3. Run your first model:
   ```
   python example.py
   ```

## File Structure
- `models/` - Directory containing model implementations.
- `data/` - Directory for storing input CSV files.
- `requirements.txt` - File listing required packages.
- `example.py` - An example script to demonstrate usage.

## CSV Format Requirements
- The CSV files should contain headers and should be structured with one row for each observation.
- Ensure that all feature names are clearly defined and consistent with the model requirements.

## Metrics Explanation
- **Accuracy**: The ratio of correctly predicted observations to total observations.
- **Precision**: The ratio of correctly predicted positive observations to the total predicted positives.
- **Recall (Sensitivity)**: The ratio of correctly predicted positive observations to all actual positives.
- **F1 Score**: The weighted average of Precision and Recall.

## Future Enhancements
- Addition of more algorithms (e.g., Support Vector Machines, Neural Networks).
- Improvement of documentation for each model's parameters and tuning.
- Implementation of automated hyperparameter tuning methods.

---  
This documentation is designed to assist users in understanding and utilizing the Easy-ML library effectively.