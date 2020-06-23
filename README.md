# Anemia-Prediction-among-Women-in-EAG-states-of-India
Download all the files from https://data.gov.in/catalog/annual-health-survey-clinical-anthropometric-bio-chemical-cab-survey
Total number of files are 283 of EAG states of India
Combine all the files using combine_all_csv.ipynb
Remove the child variables and select dataframe age above 15 for female and 18 for male.
Convert non numeric variables to numeric variables.
Data- Preprocessing.
Correlation the biomarkers with other variables.
Now drop uncorrelated features.
Apply the Imputer to remove null values.
Then combined data divided into dataframes.
# Female_severe_anemia 
This dataframe predicts the severe anemia in women age between 15-49
And hemoglolbin level less than or eqaul to 7.

# Female_Moderate_anemia 
Hemoglolbin level between 7.1-9.9
Apply the Models to predict the Anemia
Calculate the train set and test accuracy 
Compare the models by using graph
Find the best Model 


