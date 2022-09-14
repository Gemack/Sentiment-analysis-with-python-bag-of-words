## SENTIMENT ANALYSIS USING  BAG OF WORDS, SIKIT LEARN TFIDFVECTORIZER 

using the Tfidfvectorizer in Sklearn this model classsify reviews in a book review into two category.
Good or bad.

The TFIDFVECTORIZER which is used in building this model is an algorithm that tranform text into numbers
which can be fitted into a machine learning model.

This model was trained on a book review in json format sourced from kaggle.
alot of preprocessing was done to convert the json file into a desirable pandas dataframe for analysis
and model building. The Data had to be trim to make it balance and prevent bias, various Machine learning
model was used but the best of them was the SVM.

