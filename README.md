# SUV-Purchase-Prediction

In this project, I predict whether a customer will purchase an SUV using **Logistic Regression** in Python.

##  Overview
In this project, I explore a real-world classification problem: **Will a customer buy an SUV based on their Age, Gender, and Estimated Salary?**  
Using Logistic Regression, I build a predictive model, evaluate its performance, and interpret insights into purchasing behaviour.  

## Dataset
The dataset contains basic demographic and purchase information.  

**Columns**
- `Age` — Customer age (in years)  
- `Gender` — Male/Female  
- `EstimatedSalary` — Annual salary (numeric)  
- `Purchased` — Target variable: 1 = purchased, 0 = did not purchase  

##  Objectives
- To train a Logistic Regression model to predict SUV purchases.  
- To evaluate performance using Accuracy, Precision, Recall, F1-score, ROC-AUC, and Confusion Matrix.  
- To explore how Age and Salary influence purchase probability.  
- To consider the ethical use of demographic features like Gender.

    ## ⚙️ Methods
1. **Data Pre-processing**
   - Handle missing values  
   - Encode categorical variables (`Gender`)  
   - Scale `Age` and `EstimatedSalary`  

2. **Modelling**
   - Logistic Regression (scikit-learn)  
   - Stratified train/test split  

3. **Evaluation**
   - Accuracy, Precision, Recall, F1-score  
   - ROC-AUC and Confusion Matrix  
   - Threshold tuning for better balance  

4. **Interpretation**
   - Inspect coefficients for feature importance  
   - Visualise decision boundaries and probability curves

   ## Technologies Used
- Python (pandas, numpy, scikit-learn, matplotlib)
- Jupyter Notebook for exploration
- GitHub for version control and collaboration

  ## Responsible AI
- Gender is included for demonstration only.
- Consider testing the model without sensitive attributes.
- This project is for educational purposes only, but also suitable for real-world decision-making in finance, hiring, or similar contexts.

## References
- Hosmer & Lemeshow, Applied Logistic Regression
- scikit-learn documentation
- General resources on model interpretability and ROC analysis
-  Kaggle 
