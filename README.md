#  **Predicting Student Depression**


**Project Overview**


This notebook explores a dataset focused on student depression to better understand what factors contribute to mental health challenges in academic settings. I started by loading the data from an online CSV and checking for class imbalance in the target variable (Depression). I also visualized how depression was distributed based on key features like sleep duration, dietary habits, and financial or academic pressure. The goal was to identify which students might be at higher risk and why.


**Methods & Results**

After the exploratory analysis, I built two predictive models: logistic regression and gradient boosting. The logistic regression model was helpful for interpretation, especially using its coefficients and odds ratios to understand the effect size of each feature. For example, suicidal thoughts and high financial stress were clearly associated with higher odds of depression. I also used a confusion matrix and classification report to evaluate performance.
To improve prediction, I trained a Gradient Boosting Classifier and tuned the hyperparameters using GridSearchCV. This model gave slightly better predictive power and helped identify key feature importances. I also ran an interaction analysis to explore how combinations of risk factors (like financial stress and academic pressure) increased depression likelihood more than any one feature on its own.


**Key Outputs**
-	Cleaned and prepared student depression dataset
-	Visualizations exploring key lifestyle and academic factors
-	Logistic regression model with odds ratio interpretation and coefficients
-	Gradient boosting model with improved recall
-	Feature interactions, confusion matrices, and classification reports


**Conclusion**

Overall, this notebook walks through data cleaning, EDA, modeling, and interpretation in a way that balances the technical world with true, societal meaning – especially for institutions looking to support students before they risk dropping out.
