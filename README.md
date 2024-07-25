May, 2024
# 🩺 Implementing a Model to Predict Hospital Readmission from Diabetes Diagnosis 
This model utilizes several features of diabetes diagnosis to predict levels in patients’ hospital readmissions. The target of this paper is to analyze whether these diabetes diagnosis variables hold association in forecasting hospital readmission using decision tree classifiers, logistic regression, and discriminant analysis algorithms.  

With machine learning, we hope to alleviate hospital operation costs by choosing which combination of measures of diabetes diagnosis will result in readmission. The length of the dataset (a decade) will provide us with enough observations to accurately predict readmission results. Ultimately, the goal of this analysis is to help companies within the healthcare industry to better allocate resources to strategically reduce the immense costs of hospital readmissions currently compromising company efficiency. 

## Contents... 
Distribution of Diagnosis  
Cleansing, Pre-Processing & Transformation Overview	  
Dropping Bad & Missing Data	  
Creating New Features	 
Encoding Categorical Variables  
Technology & Analysis  
Logistic Regression Classification  
Decision Tree Classification  
Descriptive Statistics  
Discriminant Analysis Algorithm  
Business Insights	 
 
## Descriptions of “Hospital Readmission” Variables
The dataset titled, Predicting Hospital Readmissions has been retrieved from the data science online platform Kaggle, containing historical data for 10 years of patient information. This data consists of both numerical and categorical variables, as well as calculated variables.  
## Numerical Variables…    
"time_in_hospital" - days (from 1 to 14)  
"n_procedures" - number of procedures performed during the hospital stay  
"n_lab_procedures" - number of laboratory procedures performed during the hospital stay  
"n_medications" - number of medications administered during the hospital stay  
"n_outpatient" - number of outpatient visits in the year before a hospital stay  
"n_inpatient" - number of inpatient visits in the year before the hospital stay  
"n_emergency" - number of visits to the emergency room in the year before the hospital stay  
## Categorical Variables…  
"age" - age bracket of the patient  
"medical_specialty" - the specialty of the admitting physician  
"diag_1" - primary diagnosis (Circulatory, Respiratory, Digestive, etc.)  
"diag_2" - secondary diagnosis  
"diag_3" - additional secondary diagnosis  
"glucose_test" - whether the glucose serum came out as high (> 200), normal, or not performed  
"A1Ctest" - whether the A1C level of the patient came out as high (> 7%), normal, or not performed  
"change" - whether there was a change in the diabetes medication ('yes' or 'no')  
"diabetes_med" - whether a diabetes medication was prescribed ('yes' or 'no')  
"readmitted" - if the patient was readmitted at the hospital ('yes' or 'no')  
## Calculated Variables…  
"average_time_in_hospital" - average length of hospital stay (days)  
"average_#_of _procedures" - average number of procedures 


