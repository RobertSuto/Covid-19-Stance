# Stance Detection for COVID-19

This project aims to understand public opinion and sentiment towards the COVID-19 pandemic through the use of Natural Language Processing (NLP) and machine learning techniques. The project analyzes a dataset of tweets related to COVID-19 and uses three different models - XGBoost, Bert, and Multinomial Naive Bayes - to classify the stance of each tweet as positive, negative, or neutral.

## Data Pre-processing

Before applying the models, the text data is pre-processed to remove unwanted characters, punctuation, and special symbols, as well as common words that do not carry significant meaning. The text is then split into individual tokens and converted into numerical features using Term Frequency-Inverse Document Frequency (TF-IDF) encoding.

## Models

Three different models are used to classify the stance of each tweet:

- XGBoost
- Bert
- Multinomial Naive Bayes

The Bert model performs the best, achieving an accuracy score of 0.9, followed by the XGBoost model with a score of 0.865 and the Multinomial Naive Bayes model with a score of 0.72. The Multinomial Naive Bayes model is used as a baseline for the other models.

## Key Findings

The analysis provides valuable insights into the public opinion on COVID-19. It is found that the most mentioned account in the dataset is that of former US President Donald Trump, likely due to false statements he made during the pandemic. The models are successful at recognizing negative tweets, but struggle with neutral tweets. The findings pave the way for further research in this field.
