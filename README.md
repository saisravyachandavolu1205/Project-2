# Project-2
This project aimed to develop predictive models for identifying ‘Bad Buys’ (i.e., vehicles that result in a financial loss) from auction data using logistic regression. The dataset included detailed attributes about vehicle specifications, pricing, and auction information.

** Objective**
To build and evaluate logistic regression models that can classify whether a car purchase would be a “Bad Buy,” helping Carvana reduce financial risks in its acquisition process.

** Dataset**
The dataset consisted of:
Vehicle details (make, model, age, odometer)
Auction info (buyer ID, purchase date, sale location)
Purchase pricing & damage details

** Data Preparation & Transformation**
Cleaned the dataset by removing or transforming irrelevant/missing values
Created new interaction terms for key features
Applied feature selection to reduce overfitting

** Models Developed**
Three logistic regression models were built and compared:

** Model 1: Baseline**
Included all available features
Accuracy: 89.70%
McFadden’s R²: 0.1787
Issue: Overfitting due to too many variables

** Model 2: Feature Selection Model**
Included only statistically significant variables
Accuracy: 87.69%
McFadden’s R²: 0.0464
Issue: Underfitting due to limited features

** Model 3: Optimized Model**
Combined feature selection with key interaction terms
Accuracy: 87.77%
McFadden’s R²: 0.0619
Result: Best trade-off between accuracy and generalizability

** Model Evaluation**
All models were evaluated using:
Accuracy
McFadden’s R²
Overfitting/Underfitting assessment
Model interpretability and risk trade-offs

**  Recommendations**
Use Regularization (LASSO, Ridge) to further reduce overfitting
Explore advanced models like Random Forest and XGBoost for potentially higher predictive power
Add more data to improve robustness
Apply feature engineering with polynomial terms and domain knowledge

** Technologies Used**
Python (assumed)
Pandas / NumPy for data wrangling
Scikit-learn / StatsModels for logistic regression and metrics
Jupyter Notebook for experimentation and visualization (assumed)
Matplotlib / Seaborn for plotting results (if used)

