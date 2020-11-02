this repo will contain the full process of making ML model that predicts the probability of having heart failure within 10 years period.
*Task-1*

Collecting heart patients’ numerical and categorical data and do some data analysis on it to compare between them and combine the perfect dataset to use to train the machine learning model .

Columns Description 

--> data1 :

-cp : 
chest pain type .
0: Typical angina: chest pain related decrease blood supply to the heart.
1: Atypical angina: chest pain not related to heart.
2: Non-anginal pain: typically esophageal spasms (non heart related).
3: Asymptomatic: chest pain not showing signs of disease.

resting_blood_pressure : 
Normal resting blood pressure, in an adult is approximately 120 millimeters of mercury (16 kPa) 

-chol :
serum cholesterol (mg/dl)

-fbs :
Whether the fasting blood sugar level is between (100 to 120 mg/dL) which is the normal level ( 0 —> Abnormal , 1 —> Normal )

-resting_electrocardiographic_results :
It’s a non-invasive test that can detect abnormalities including arrhythmias, evidence of coronary heart disease, left ventricular hypertrophy and bundle branch blocks .
0: Nothing to note
1: ST-T Wave abnormality
can range from mild symptoms to severe problems
signals non-normal heart beat
2: Possible or definite left ventricular hypertrophy
Enlarged heart's main pumping chamber

- maximum_heart_rate_achieved :
maximum heart rate is calculated by subtracting the age from 220

-exercise_induced_angina :
Whether the patient suffers from angina during exercise in which the demand for oxygen increases ( 0 —> No , 1 —> Yes )

-oldpeak :
ST depression induced by exercise relative to rest looks at stress of heart during exercise unhealthy heart will stress more.

-slope :
the slope of the peak exercise ST segment .
0: Up sloping: better heart rate with exercise (uncommon)
1: Flat sloping: minimal change (typical healthy heart)
2: Down sloping: signs of unhealthy heart

-ca :
number of major vessels colored by fluoroscopy .
colored vessel means the doctor can see the blood passing through
the more blood movement the better (no clots)


-thal :
thallium stress result .
1,3: normal
6: fixed defect: used to be defect but ok now
7: reversible defect: no proper blood movement when exercising



--> data2 :

-anaemia :
 It’s the decrease of red blood cells or hemoglobin ( 0 —> No , 1 —> Yes )

-creatinine_phosphokinase : 
It’s the level of the CPK enzyme in the blood (mcg/L) 

-diabetes : 
Whether the patient has diabetes or no ( 0 —> No , 1 —> Yes )

-ejection_fraction :
 It’s the percentage of blood leaving the heart at each contraction

-high_blood_pressure : 
If the patient has hypertension ( 0 —> No , 1 —> Yes )

-platelets :
 Platelets in the blood (kilo platelets/mL)
 
-serum_creatinine : 
Level of serum creatinine in the blood (mg/dL)

-serum_sodium : 
Level of serum sodium in the blood (mEq/L)

-sex : 
Male or Female ( 0 —> Female , 1 —> Male )

-smoking : 
Whether the patient smokes or not ( 0 —> No , 1 —> Yes )

-time : 
Follow-up period (days)

--> data3 :

-currentSmoker : 
Whether the patient smokes or not ( 0 —> No , 1 —> Yes )

 -cigsPerDay : 
If the patient is smoker , that shows how many cigarettes he has every day 

-BPMeds : 
Whether the patient is under blood pressure medications or not 
( 0 —> No , 1 —> Yes )

-prevalentStroke : 
Whether the patient suffers from a stroke or not ( 0 —> No , 1 —> Yes )

-prevalentHyp : 
Whether the patient suffers from  hypertension or not ( 0 —> No , 1 —> Yes )

-diabetes : 
Whether the patient has diabetes or no ( 0 —> No , 1 —> Yes )

-totChol : 
serum cholesterol (mg/dl)

-sysBP : 
Systolic blood pressure, the top number, measures the force your heart exerts on the walls of your arteries each time it beats.

-diaBP : 
Diastolic blood pressure, the bottom number, measures the force your heart exerts on the walls of your arteries in between beats.

-BMI : 
BMI : body mass index
m : mass (kg)
h : height (m)
Underweight = <18.5
Normal weight = 18.5 to 24.9 
Overweight = 25 to 29.9

-heartRate : 
A normal resting heart rate for adults ranges from 60 to 100 beats per minute. Generally, a lower heart rate at rest implies more efficient heart function and better cardiovascular fitness. For example, a well-trained athlete might have a normal resting heart rate closer to 40 beats per minute.

-glucose : 
A fasting blood sugar level less than 100 mg/dL (5.6 mmol/L) is normal. 
A fasting blood sugar level from 100 to 125 mg/dL (5.6 to 6.9 mmol/L) is considered prediabetes. 
If it's 126 mg/dL (7 mmol/L) or higher on two separate tests, you have diabetes.

-TenYearCHD : 
Whether the patient will suffer from Coronary heart disease in the next 10 years or not ( 0 —> No , 1 —> Yes )

--> Missed Columns 

data1 :
No missing columns 

data2 :
No missing columns 

data3 :
“ education “ column description is missing
