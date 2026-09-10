# Boston-Housing-Price-Analysis-Prediction

> **MIT Professional Certificate in AI & Data Science**
>
> This project was completed as part of the MIT Professional Certificate in AI & Data Science program.
>
> [View the complete four-project certificate portfolio](https://github.com/users/rickhegenbart/projects/2)

README Document | Data Analysis and Machine Learning Portfolio Project
Project Description
This project uses data analysis and machine learning to explore and predict Boston housing prices. The workflow includes exploratory data analysis, feature relationship review, regression modeling, and model evaluation. The goal is to understand which housing and neighborhood variables are most related to median home values and to build a predictive model for housing price estimation.
Objective
The main objective of this project is to predict median housing values using structured housing and neighborhood data. The project also focuses on interpreting feature relationships so the model is not treated as a black box.
Analyze the relationship between housing features and median home value.
Identify important variables that influence housing prices.
Build regression models to predict housing prices.
Evaluate model performance using appropriate regression metrics.
Communicate findings in a clear, portfolio-ready format.
Dataset
The project is based on the Boston housing dataset, a historical dataset commonly used for regression practice. It contains housing and neighborhood-level variables used to predict median home value.
Feature
Description
CRIM
Per-capita crime rate by town
ZN
Proportion of residential land zoned for large lots
INDUS
Proportion of non-retail business acres
CHAS
Charles River dummy variable
NOX
Nitric oxide concentration
RM
Average number of rooms per dwelling
AGE
Proportion of older owner-occupied units
DIS
Weighted distance to employment centers
RAD
Accessibility to radial highways
TAX
Property tax rate
PTRATIO
Pupil-teacher ratio by town
LSTAT
Percentage of lower-status population
MEDV
Median value of owner-occupied homes; target variable


Ethical note: The Boston housing dataset is historically important for learning regression, but it has known ethical and fairness limitations. Any modern housing model should use current, representative, and responsibly sourced data before being used for real-world decisions.
Tools and Libraries
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook or Google Colab
Project Workflow
1. Data Loading and Review: Load the dataset, inspect rows and columns, check data types, and review the target variable.
2. Exploratory Data Analysis: Examine feature distributions, correlations, outliers, and relationships between predictor variables and housing prices.
3. Data Preparation: Handle missing values if present, separate features and target variable, split the data, and scale features when required.
4. Model Training: Train regression models such as Linear Regression, Decision Tree, Random Forest, or other suitable algorithms.
5. Model Evaluation: Evaluate model performance using metrics such as MAE, MSE, RMSE, and R-squared.
6. Interpretation: Review which features most strongly influence predicted housing prices and explain the model results clearly.
Evaluation Metrics
Mean Absolute Error (MAE): Average absolute difference between predicted and actual values.
Mean Squared Error (MSE): Average squared prediction error, giving larger errors more weight.
Root Mean Squared Error (RMSE): Square root of MSE, expressed in the same general unit as the target variable.
R-squared: Percentage of variance in the target variable explained by the model.
Results to Include
When finalized, this README can include the following project results:
Best-performing model name
Test MAE, RMSE, and R-squared values
Top predictive features
Correlation heatmap
Actual vs. predicted price plot
Residual plot or error analysis
Suggested Project Structure
boston-housing-price-analysis/
│
├── data/
│   └── BostonHousing.csv
│
├── notebooks/
│   └── boston_housing_analysis_prediction.ipynb
│
├── images/
│   ├── correlation_heatmap.png
│   ├── actual_vs_predicted.png
│   └── residual_plot.png
│
├── README.md
├── requirements.txt
└── .gitignore
How to Run the Project
Clone the repository.
Open the project folder.
Install the required packages.
Open the notebook in Jupyter Notebook or Google Colab.
Run the notebook cells from top to bottom.
Example Requirements
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
Limitations
The Boston housing dataset is historical and should not be used for real-world housing decisions without major updates.
The dataset includes variables that raise fairness and ethical concerns.
The sample size is limited compared with modern real estate datasets.
Housing markets change over time, so historical patterns may not generalize to current markets.
Additional external variables, such as interest rates, employment trends, and local market conditions, would improve a real-world model.
Future Improvements
Compare additional regression models.
Tune model hyperparameters using cross-validation.
Add feature importance visualizations.
Perform deeper residual and error analysis.
Use a newer and more representative housing dataset.
Deploy the model as a simple web app or dashboard.
Conclusion
This project demonstrates how regression modeling can be used to analyze and predict housing prices. It combines exploratory data analysis, model training, performance evaluation, and interpretation to create a complete machine learning workflow. The project is useful as a portfolio example because it shows both technical modeling skills and the ability to explain results in a practical real estate context.
