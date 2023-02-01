# Breast-Cancer-Prediction
Using Support Vector Machine to classify  whether a patient has breast cancer or not depending upon various factors.


#About Dataset
- This dataset of breast cancer patients was obtained from the 2017 November update of the SEER Program of the NCI, which provides information on population-based cancer statistics. 
- The dataset involved female patients with infiltrating duct and lobular carcinoma breast cancer (SEER primary cites recode NOS histology codes 8522/3) diagnosed in 2006-2010.
-  Patients with unknown tumour size, examined regional LNs, positive regional LNs, and patients whose survival months were less than 1 month were excluded; thus, 4024 patients were ultimately included.


# NOTE : 
- Feature Engineering is used (One Hot Encoding) preceding the train_test_split.
- GridsearchCV is used for exhaustive search over specified parameter values for an estimator.
- The confidence level attained is ≈ 90 %
