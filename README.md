# DiabetesReadmissionPrediction
Models to predict diabetes readmission and important factors affecting the same.

1.	Simple EDA to check the population what is the percentage of readmissions.
2.	Plot the target value against important columns to understand if these columns really have a bearing on the re-admission column.
3.	Use association rules, against the re-admission column to understand what prominent rules work for “>30” “<30” days.
4.	Run a logistic regression, to understand what features contribute to the model. Also predict the event re-admission.
5.	Classify the data using a Decision Tree Classifier to get the important features and a classification of re-admission

# Data: https://archive.ics.uci.edu/ml/datasets/Diabetes+130US+hospitals+for+years+1999-2008# 

# To run the code:

1. Run DiabetesAnalysis to generate a basket for association rule mining. Refer - basket_diab.csv for basket created.
2. Run AssociationRulesDiab R file giving the csv created above as input.
3. Run Logisticregression in python environment.
4. Run ClassifierDiabetes in python environment.

# Recommendation & Business Solution:
•	Using Association Rules could conclude that inpatient visits, discharge disposition and admission type were 
strong predictors of readmission. It was found that the number of laboratory tests and discharge disposition together 
predict whether the patient will be readmitted shortly after being discharged from the hospital (i.e. <30 days) 
or after a longer period of time (i.e. >30 days).

•	Using Logistic Regression , the important features identified was discharge deposition - 
Discharged/transferred to home under care of Home IV provider, Neonate discharged to another hospital for neonatal aftercare,
Admission Source - Transfer from critial access hospital, Transfer from critial access hospital,Sick Baby, Accuracy – 52%.

•	Used Decision Tree Classifier features that were important here number of readmissions with 44% accuracy.

