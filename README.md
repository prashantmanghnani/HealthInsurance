# Health Insurance Cost Prediction

## Project Overview
This project aims to predict health insurance costs based on factors such as age, BMI, smoking status, and more. By leveraging advanced regression techniques, the model identifies key drivers of insurance charges and provides actionable insights for cost management.

## Key Features
- **Machine Learning Algorithms**: Gradient Boosting, Stacking Regressor, Ridge, and Lasso Regression.
- **Feature Engineering**: Scaling, encoding categorical variables, and handling missing values.
- **Statistical Analysis**: Correlation matrix and feature importance evaluation.
- **Model Evaluation**: Achieved R² of 0.91 and MSE of 17,153,919 with the Stacking Regressor.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: Scikit-learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn
- **Tools**: Jupyter Notebook, GitHub

## Data Preparation
1. **Cleaning**: Addressed missing values and ensured data consistency.
2. **Feature Scaling**: Normalized continuous variables for improved algorithm performance.
3. **Encoding**: Converted categorical variables using one-hot encoding.

## Models and Performance
| Model                 | R² Score | MSE          | MAE      |
|-----------------------|-----------|--------------|----------|
| Gradient Boosting     | 0.90492   | 17,547,786   | 2,515.83 |
| Stacking Regressor    | 0.90708   | 17,153,919   | 2,426.68 |
| Ridge Regression      | 0.80196   | 36,550,536   | 4,312.61 |
| Lasso Regression      | 0.80233   | 36,481,737   | 4,305.17 |
| Bagging Regressor     | 0.86788   | 24,384,181   | 2,866.25 |

## Steps to Reproduce
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd health-insurance-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook to explore the dataset and train models.

## Results
- **Best Model**: Stacking Regressor
- **Key Metrics**: R² = 0.91, MSE = 17,153,919

## Future Work
- Explore additional algorithms such as Neural Networks.
- Improve feature engineering with advanced techniques.
- Expand the dataset to include more diverse factors.


## License
This project is licensed under the MIT License.

