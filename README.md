# Kaggle Project: Multi-Class Prediction of Cirrhosis Outcomes：[https://www.kaggle.com/competitions/playground-series-s3e26/data]
## Project Introdution:

The objective is to accurately forecast whether a patient has Cirrhosis, utilizing pertinent demographic details and body measurement data.

**Overview of the Dataset**: 
The dataset for this competition (both train and test) was generated from a deep learning model trained on the Cirrhosis Patient Survival Prediction dataset. Feature distributions are close to, but not exactly the same, as the original.

**Training Set**:
It consists of 20 features. **Status** is the categorical target; C (censored) indicates the patient was alive at N_Days, CL indicates the patient was alive at N_Days due to liver a transplant, and D indicates the patient was deceased at N_Days.

**Test Set**:
Test set is given, and the objective is to predict the probability of each of the three Status values, e.g., Status_C, Status_CL, Status_D.

**Stakeholders:** Kaiqi Cheng, Yimei Yang.
