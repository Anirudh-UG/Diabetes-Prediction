# Diabetes-Prediction
A simple Diabetes Prediction System using Densely Connected Neural Networks.
The Dataset is provided in the repo.
The dataset has been cleaned.

Dataset Description:
Glucose - Fasting blood sugar
HDL - HDL or good cholesterol
Chol/HDL - Ratio of total cholesterol to good cholesterol. Desirable result is < 5
Age - All adult African Americans
Gender - 162 males, 228 females
Height - In inches
Weight - In pounds (lbs)
BMI - 703 x weight (lbs)/ [height(inches]2
Systolic BP - The upper number of blood pressure
Diastolic BP - The lower number of blood pressure
Waist/hip - Ratio is possibly a stronger risk factor for heart disease than BMI
Diabetes - Yes (60), No (330)

This data set came from Vanderbilt but the original data came from a study of rural African Americans in Virginia. I elected to delete
13 patients who were missing data. Also, the diagnosis of diabetes was based on a glycohemoglobin of greater than 7, however current
guidelines use a glycohemoglobin of 6.5 or greater to diagnose diabetes. 

I opted to create a Total Cholesterol/HDL Cholesterol ratio and a Waist to Hip ratio as both are now commonly used but were not part of the original data.

REFERENCE:
Williams JP, Saunders JT, Hunt DE, Schorling JB. Prevalence of coronary risk factors among rural blacks: A community based study. Southern Medical Journal. 1997;90:814-820


