# Email_Sms_Spam_Detector
End to End Spam Email Detector Project 

![Screenshot (45)](https://user-images.githubusercontent.com/90169527/155844474-78a75e63-09df-4ce6-9171-1c051383585c.png)

# About:
In this Project I have created the sms spam classifier using NLP.

## Files:
Full Notebook : https://github.com/Siddhantjad/Email_Sms_Spam_Detector/blob/main/spam_prediction.ipynb

# Process:
### Data Cleaning
* Handling Missing values
* Renaming columns
* Removing duplicated entries

### Data Pre-Processing
* Tokenization was done on text column.
* Lower case converted all text.
* Removed special characters.
* Stemming was done.
* Removed stopwords and punctuation

# Model Building:
Machine algo need the numerical data to learn it cannot directly learn from alphabetical data so,  transformed the text into vectors with TF-IDF.
Trained Data on different ML algorithms.

Different ML models with accuracy and precision:

![Screenshot (47)](https://user-images.githubusercontent.com/90169527/155844844-4c526b7e-83fa-40a8-84e4-faee54b5e531.png)

# Conclusion :
Of all Classifier tested, The RandomForestClassifier was selected for prediction and Deployment.
