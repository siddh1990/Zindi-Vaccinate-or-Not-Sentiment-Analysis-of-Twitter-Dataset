# Zindi-Vaccinate-or-Not-Sentiment-Analysis-of-Twitter-Dataset

This challenge has been posted on Zindi. Following is the URL:
https://zindi.africa/competitions/to-vaccinate-or-not-to-vaccinate
Following is the summary as provided on the competition page:
This challenge aims at developing a machine learning model to assess positive, negative, or neutral Twitter posts related to vaccinations. The solution will help the governments and other public health actors monitor public sentiments towards COVID-19 vaccinations and help improve public health policy, vaccine communication strategies, and vaccination programs worldwide.

In this challenge, we are working with text data; it is initially non-numerical and must be processed before it can be fed into a Machine Learning algorithm. For this, we use Natural Language Processing - natural language processing (NLP) is the ability of a computer program to understand human language as it is spoken and written (referred to as natural language). For this challenge, we are dealing with a branch of NLP called sentiment analysis. Sentiment analysis is a field that aims to get the emotional tone behind a body of text; this is a popular way for organisations to determine and categorise opinions about a product, service, or idea.
## Dataset
Train Dataset includes tweets, their sentiment as annoted by human and agrrement/probability of the sentiment.This dataset is further divided in training and validation datasets into 80:20 ratio in case of approach 3 as given below, and 67:33 ratio for Shallow ML and Vander Sentiment analysis.

## Methodolgy
For this challenge, follwoing three approaches has been evaluated:
1. Rule based method of Vander Sentiment Analysis
2. Shallow machine learning model employing traditional NLP
3. Finetuning of bert-base-uncased language model hosted on hugging face using keras and tensorflow libraries

## Evaluation Metrics
Original Evaluation metrics for the challenge is rmse or root mean square error. However, in this notebook, evaluation metrics has been changed to accuracy and problem type has been changed from regression to classification. 


