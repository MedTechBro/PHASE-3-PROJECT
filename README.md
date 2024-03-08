SEASONAL FLU VACCINE CLASSIFICATION PROJECT


Safaricom, through their m-tiba subsidiary wants to understand the leading factors in determining whether people would take the seasonal flu vaccine in order to put in the right strategies for their public efforts and vaccination campaigns to educate the public, raise awareness while maximizing vaccine intake.
My objective is to build a classifier to predict seasonal flu vaccination status using data they shared on their behaviours, oponions and demographic characteristics.



DATA UNDERSTANDING AND CLEANING.


The data was obtained from the National 2009 H1N1 Flu Survey. 
People were unterviewed through phone calls.
My target in this project will be seasonal_flu and predictors will be people's opinions, hevaviours and demographic features.

The variables with the highest number of null values were dropped.

Numerical variables with few null values were replaced with the median while categorical variables with the mode.

The predictors include:
'behavioral_large_gatherings', 'behavioral_face_mask', 'behavioral_wash_hands', 'opinion_seas_vacc_effective', 'opinion_seas_sick_from_vacc', 'education', 'age_group', 'seasonal_vaccine', 'chronic_med_condition', 'health_worker', 'doctor_recc_seasonal', 'behavioral_antiviral_meds', 'opinion_seas_risk'


DATA ANALYSIS AND VISUALIZATION


Distribution of our target variable.

![alt text](image.png)

Relationship between seasonal_vaccine and various attributes:

![alt text](image-1.png)

Correlation between seasonal_vaccine and the predictors.

![alt text](image-2.png)

From the analysis, we can conclude the following:

1. People with chronic health conditions.
2. Health worker profession.
3. Belief that the vaccine is efficacious.
4. Reccomendation on the seasonal flu vaccine uptake by a doctor.
5. Awareness of the risks associated with the seasonal flu.
6. People over 65 years
7. People who wear facemasks and wash hands are more likely to take the seasonal flu vaccine