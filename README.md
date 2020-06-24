# Anemia-Prediction-among-Women-in-EAG-states-of-India
Download all the files from https://data.gov.in/catalog/annual-health-survey-clinical-anthropometric-bio-chemical-cab-survey
Total number of files are 283 of EAG states of India
Combine all the files using combine_all_csv.ipynb
Remove the child variables and select dataframe age above 15 for female and 18 for male.
Convert non numeric variables to numeric variables.
Data- Preprocessing.
Correlation the biomarkers with other variables.
Drop uncorrelated features.
Apply the Imputer to remove null values.
Then combined data divided into dataframes.
# Female_severe_anemia 
This dataframe predicts the severe anemia in pregnant women age between 15-49.
And hemoglolbin level less than or eqaul to 7.

# Female_Moderate_anemia 
Hemoglolbin level between 7.1-9.9

# Female_Mild_anemia
Hemoglolbin level between 10-10.9

In above three dataframes i applied Random Forest classifier, Logistic Regression, KNN classifier and SVM classifier. And i find the test and train accuracy and compare the models by using graph.

# Male_Female
The age group is above 17.
And the HB_level for men is less than 13 and for women HB_level is less than 12.
I applied three models on it Random Forest classifier, Logistic Regression, KNN classifier.
Calculate the accuracy for these models.

# Female_anemia
This dataframe predicts the anemia in all other women age between 15-49.
And hemoglolbin level less than 12.
I applied three models on it Random Forest classifier and Logistic Regression.
Calculate the accuracy for these models.





