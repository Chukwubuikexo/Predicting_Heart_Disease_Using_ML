# Predicting_Heart_Disease_Using_ML
    "This projects aims to utilize various Python-based machine learning and data science libraries to build a machine learning model capable of predicting if a patient has heart disease or not based on their medical attributes
    
  # Data Source - 
  "The Cleavland data from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/heart+Disease\n",
  
    "# Data Features\n",
    "1. age - age in years\n",
    "2. sex - (1 = male; 0 = female)\n",
    "3. cp - chest pain type\n",
    "    0: Typical angina: chest pain related decrease blood supply to the heart\n",
    "    1: Atypical angina: chest pain not related to heart\n",
    "    2: Non-anginal pain: typically esophageal spasms (non heart related)\n",
    "    3: Asymptomatic: chest pain not showing signs of disease\n",
    "4. trestbps - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern\n",
    "5. chol - serum cholestoral in mg/dl\n",
    "    serum = LDL + HDL + .2 * triglycerides\n",
    "    above 200 is cause for concern\n",
    "6. fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)\n",
    "    '>126' mg/dL signals diabetes\n",
    "7. restecg - resting electrocardiographic results\n",
    "    0: Nothing to note\n",
    "    1: ST-T Wave abnormality\n",
    "       can range from mild symptoms to severe problems\n",
    "       signals non-normal heart beat\n",
    "    2: Possible or definite left ventricular hypertrophy\n",
    "        Enlarged heart's main pumping chamber\n",
    "8. thalach - maximum heart rate achieved\n",
    "9. exang - exercise induced angina (1 = yes; 0 = no)\n",
    "10. oldpeak - ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more\n",
    "11. slope - the slope of the peak exercise ST segment\n",
    "    0: Upsloping: better heart rate with excercise (uncommon)\n",
    "    1: Flatsloping: minimal change (typical healthy heart)\n",
    "    2: Downslopins: signs of unhealthy heart\n",
    "12. ca - number of major vessels (0-3) colored by flourosopy\n",
    "    colored vessel means the doctor can see the blood passing through\n",
    "    the more blood movement the better (no clots)\n",
    "13. thal - thalium stress result\n",
    "    1,3: normal\n",
    "    6: fixed defect: used to be defect but ok now\n",
    "    7: reversable defect: no proper blood movement when excercising\n",
    "14. target - have disease or not (1=yes, 0=no) (= the predicted attribute)\n",
    "\n",
  
  Goal 
    "95% - 100% Accuracy of the model\n"
  
