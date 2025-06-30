# revolutionizing-liver-care-predicting-liver-cirrhosi-using-advanced-machine-learning-techiniques
Cirrhosis Stage Prediction Using Machine Learning
This repository contains the implementation of a machine learning project aimed at predicting the stage of cirrhosis based on clinical features. The dataset, sourced from here: https://www.kaggle.com/datasets/fedesoriano/cirrhosis-prediction-dataset

Project Overview
Cirrhosis is a liver disease characterized by abnormal liver function due to chronic liver damage. Effective prediction of cirrhosis stages can aid in better management and treatment strategies for patients. This project utilizes Logistic Regression, K-Nearest Neighbors (KNN), and Random Forest classifiers to model and predict the stages of cirrhosis from clinical data.

Dataset Description
The following data contains the information collected from the Mayo Clinic trial in primary biliary cirrhosis (PBC) of the liver conducted between 1974 and 1984. A description of the clinical background for the trial and the covariates recorded here is in Chapter 0, especially Section 0.2 of Fleming and Harrington, Counting Processes and Survival Analysis, Wiley, 1991. A more extended discussion can be found in Dickson, et al., Hepatology 10:1-7 (1989) and in Markus, et al., N Eng J of Med 320:1709-13 (1989). A total of 424 PBC patients, referred to Mayo Clinic during that ten-year interval, met eligibility criteria for the randomized placebo-controlled trial of the drug D-penicillamine. The first 312 cases in the dataset participated in the randomized trial and contain largely complete data. The additional 112 cases did not participate in the clinical trial but consented to have basic measurements recorded and to be followed for survival. Six of those cases were lost to follow-up shortly after diagnosis, so the data here are on an additional 106 cases as well as the 312 randomized participants. Attribute Information

ID: unique identifier
N_Days: number of days between registration and the earlier of death, transplantation, or study analysis time in July 1986
Status: status of the patient C (censored), CL (censored due to liver tx), or D (death)
Drug: type of drug D-penicillamine or placebo
Age: age in [days]
Sex: M (male) or F (female)
Ascites: presence of ascites N (No) or Y (Yes)
Hepatomegaly: presence of hepatomegaly N (No) or Y (Yes)
Spiders: presence of spiders N (No) or Y (Yes)
Edema: presence of edema N (no edema and no diuretic therapy for edema), S (edema present without diuretics, or edema resolved by diuretics), or Y (edema despite diuretic therapy)
Bilirubin: serum bilirubin in [mg/dl]
Cholesterol: serum cholesterol in [mg/dl]
Albumin: albumin in [gm/dl]
Copper: urine copper in [ug/day]
Alk_Phos: alkaline phosphatase in [U/liter]
SGOT: SGOT in [U/ml]
Triglycerides: triglicerides in [mg/dl]
Platelets: platelets per cubic [ml/1000]
Prothrombin: prothrombin time in seconds [s]
Stage: histologic stage of disease (1, 2, 3, or 4)
Key Steps in the Analysis
Data Preprocessing: Cleaning missing values, encoding categorical variables, and scaling numerical features.
Exploratory Data Analysis: Visualizing distributions and relationships between features.
Predictive Modeling: Implementing Logistic Regression, KNN, and Random Forest to predict the cirrhosis stage.
Model Evaluation: Assessing models based on accuracy and using confusion matrices for detailed performance analysis.
Result Visualization: Comparing the performance of different models visually.
Contribution
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.
