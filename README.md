# Opinion-Mining-PR
An Exploratory Data Analysis based project to reflect public opinion related to common mental health problems such as anxiety, depression, OCD, schizophrenia, PTSD etc. through time-series analysis from collected twitter data.
# Analyzer Model Description and Results
 - **DataSet:** Data are collected from Twitter using snscrape. The focused mental health concerns are: anxiety, depression, eating disorder, OCD, schizophrenia, stress and drug abuse. In total, 32,525 tweets have been collected which have been posted on Twitter from November,2020 to November,2021.
- **Data Annotation :** Data have been annotated using Valance Aware Dictionary for Sentiment Reasoning (Vader). This tool analyses textual data and returns a dictionary of scores referring to the intensity of positivity, negativity, neutralism, and the compound score of the three. Thus we have annotated the collected data in three classes: positive, negative and neutral.
- **Model:** Recurrent Neural Network with LSTM Architecture
- **Results**
| |Precision|Recall |F1 score|Accuracy|
|----|----|----|----|----|
Train|94.1|95.2|94.7|95|
Test|85|85|85|85.1|

