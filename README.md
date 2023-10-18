# About the Project
This is a midterm project for the course CISB63 in Mt.SAC.
## Description
This project is aimed to build a chatbot who can make mental health conversation and also detect psychological stress based on the conversation.

You can find the datasets here: <br>**Mental Health Conversational Data** (https://www.kaggle.com/datasets/elvis23/mental-health-conversational-data/data)
<br>**Human Stress Prediction** (https://www.kaggle.com/datasets/cbf36c44e2c14007b6aedffc307e1f7f7c6d0b9e1e96c8895f36658842a6ece4)

With these datasets, I used different NLP techniques to build two models and finally use the models to build a chatbot. The main steps are as follows:

- Conversational Module:
    - Cleaning the Mental Health Conversational data.
    - Analyzing the preset questions and plotting word frequencies using Tokenization, Stopwords, RegEx, and Word frequency distributions.
    - Build a pipeline to create a model for conversation using Stemming, Count Vectorization, TF-IDF, Decision Tree, SVM and Naive Bayes.
    - Test the models with random questions to keep the best model.
- Stress Prediction Module:
    - Cleaning and analyzing the Human Stress Prediction data.
    - Create a WordCloud of all the text in the data.
    - Visualize Named Entities of a sample text Using spaCy.
    - Build pipelines to create two models for stress prediction using Count Vectorization, TF-IDF, Naive Bayes, and Logistic Regression.
    - Compare these models with accuracy, confusion matrix, and classification report.
- Chatbot Module:
    - Using the prediction of the two models to generate conversations for the chatbot.
    - Test the chatbot with two different situations (stress and no stress)

Please check [here](CISB63_midterm_project_Chao.ipynb) to see my project in detail.

##
