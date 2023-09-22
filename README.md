# heart_failure_clinical_records_dataset
The "Heart Failure Clinical Records Dataset" is a dataset that contains clinical and medical features of individuals who have experienced heart failure, as well as information about whether or not they survived. Analyzing this dataset can provide valuable insights into factors that may contribute to heart failure and could aid in the development of predictive models to identify individuals at risk.

Dataset Information
The dataset contains the following features:

-age: Age of the individual (years).
-anaemia: Whether the individual has anemia (0: No, 1: Yes).
-creatinine_phosphokinase: Level of creatinine phosphokinase in the blood (mcg/L).
-diabetes: Whether the individual has diabetes (0: No, 1: Yes).
-ejection_fraction: Percentage of blood leaving the heart at each contraction (%).
-high_blood_pressure: Whether the individual has high blood pressure (0: No, 1: Yes).
-platelets: Platelets in the blood (kiloplatelets/mL).
-serum_creatinine: Level of serum creatinine in the blood (mg/dL).
-serum_sodium: Level of serum sodium in the blood (mEq/L).
-sex: Gender of the individual (0: Female, 1: Male).
-smoking: Whether the individual is a smoker (0: No, 1: Yes).
-time: Follow-up period (days).
-DEATH_EVENT: Whether the individual experienced a death event during the follow-up period (0: No, 1: Yes).

Analysis
The main analysis of the Heart Failure Clinical Records Dataset is documented in a Jupyter notebook named Heart_Failure_Analysis.ipynb. The notebook covers exploratory data analysis, feature preprocessing, model development, and evaluation of the predictive model.

Dependencies
The analysis uses common Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-Learn. Ensure you have these dependencies installed in your Python environment to run the analysis successfully.

Models-
-Logistic Regression with eli5
-hyper perameter LR
-Decision Tree Classifier
-Random Forest Classifier
-lime
-SHAP
