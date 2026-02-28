**🚀 Machine Learning Projects**

Welcome to my Machine Learning repository! This repository contains a collection of Machine Learning projects, ranging from fundamental regression models to advanced predictive analytics. Each project includes data preprocessing, model training, evaluation, and a deployment script.

**📁 Repository Structure**

**1.Simple_Linear_Regression/: Predicting Employee Salary based on Years of Experience.**

* Salary_Data.csv           # Dataset
* Model_Creation.ipynb      # Training & Evaluation
* Salary_Model.sav          # Saved Pickle Model
* Deployment.ipynb          # User Input Interface

**2.Multiple_Linear_Regression/: Predicting Startup Profit based on R&D, Administration, and Marketing expenditures.**

* 50_Startups.csv           # Multi-feature Dataset
* Model_Creation.ipynb      # Training & One-Hot Encoding
* Profit_Model.sav          # Saved Pickle Model
* Deployment.ipynb          # Real-time Prediction

**3.Support_Vector_Machine/: Predicting Startup Profit based on R&D, Administration, and Marketing expenditures.**

*50_Startups.csv            # Multi-feature Dataset

*Model_Creation.ipynb       # Training & Hyper Parameter tuning

*Profit_Model.sav           # Saved Pickle Model

*Deployment.ipynb           # Real-time Prediction

**📊 2. Projects Overview**

**Project 1: Simple Linear Regression**

Objective: To establish a linear relationship between a single independent variable (Years of Experience) and a dependent variable (Salary).

Result: Achieved high accuracy with a clear "Best Fit Line."

**Project 2: Multiple Linear Regression (Startup Profit)**

Objective: Predict the profit of 50 startups using R&D, Administration, and Marketing expenditures.Handling 

Categories: Implemented One-Hot Encoding for the "State" column. Used drop_first=True to avoid the Dummy Variable Trap.

Evaluation: Achieved an R squared of 0.93. I use Adjusted R-squared to ensure added features (like State) truly contribute to the model.

**Project 3: Support Vector Regression (SVR)**

Model Performance: Achieved 93% Accuracy same as  Multiple Linear Regression (93%).

Hyperparameter Tuning: Tuned the $C$ parameter to 0.01 to create a "Soft Margin," which reduced overfitting and allowed the model to focus on the global trend of the startup data.

Kernel Analysis: Tested RBF and Polynomial kernels; however, due to the strictly linear nature of the 50_Startups dataset, the Linear Kernel proved most effective.
