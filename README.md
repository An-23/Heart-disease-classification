This is a binary classification problem to predict if a person has Heart problems(1) or NOT(0) 

**The following are the features we'll use to predict our target variable (heart disease or no heart disease).**

*age - age in years 

*sex - (1 = male; 0 = female)

*cp - chest pain type
    0: Typical angina: chest pain related decrease blood supply to the heart, 
        1: Atypical angina: chest pain not related to heart,
            2: Non-anginal pain: typically esophageal spasms (non heart related),
                3: Asymptomatic: chest pain not showing signs of disease
    
*trestbps - resting blood pressure (in mm Hg on admission to the hospital)
    (anything above 130-140 is typically cause for concern)
    
*chol - serum cholestoral in mg/dl
    serum = LDL + HDL + .2 * triglycerides
        (above 200 is cause for concern)
    
*fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
        ('>126' mg/dL signals diabetes)
    
*restecg - resting electrocardiographic results
    0: Nothing to note,
        1: ST-T Wave abnormality
            can range from mild symptoms to severe problems
                signals non-normal heart beat,
                    2: Possible or definite left ventricular hypertrophy
                        Enlarged heart's main pumping chamber
        
*thalach - maximum heart rate achieved

*exang - exercise induced angina (1 = yes; 0 = no)

*oldpeak - ST depression induced by exercise relative to rest
        (looks at stress of heart during excercise
            unhealthy heart will stress more)
    
*slope - the slope of the peak exercise ST segment
        0: Upsloping: better heart rate with excercise (uncommon),
            1: Flatsloping: minimal change (typical healthy heart),
                2: Downslopins: signs of unhealthy heart
    
*ca - number of major vessels (0-3) colored by flourosopy
        (colored vessel means the doctor can see the blood passing through
            the more blood movement the better (no clots))
    
*thal - thalium stress result
        1,3: normal,
            6: fixed defect: used to be defect but ok now,
                7: reversable defect: no proper blood movement when excercising
    
*target - have disease or not (1=yes, 0=no) (= the predicted attribute)



Make use of different data preprocessing and cleaning techniques to improve the dataset .

Make use of Logistic Regression, KNN and RandomForestClassifier Models and use the best one out of them for our predictions.
