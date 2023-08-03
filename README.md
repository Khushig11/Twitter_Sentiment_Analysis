# Twitter Sentiment Analysis
This repository contains the code and resources for a sentiment analysis project on Twitter data.
The objective of this project is to build a model that can analyze tweets and determine the sentiment expressed in each tweet, whether it is positive, negative, or neutral.


# Project Description
Twitter sentiment analysis is a natural language processing (NLP) task that involves processing and classifying tweets based on the sentiment they convey. Sentiment analysis has various applications, such as understanding public opinion, brand monitoring, and social media marketing.

The project follows the following steps:

Data Collection: Dataset from Kaggle was used.It contains tweets related to Pfizer & BioNTech vaccine.

Dataset- https://www.kaggle.com/datasets/gpreda/pfizer-vaccine-tweets 

Data Preprocessing: Cleaning and preparing the tweet data for analysis. This involves removing special characters, hashtags, mentions, and links, as well as converting text to lowercase.

Text Tokenization: Breaking down the cleaned tweets into individual words or tokens, which will be used as input to the sentiment analysis model.

Model Selection: Logistic Regression model was used for sentiment analysis.

Model Training and Evaluation: Splitting the dataset into training and testing sets, training the sentiment analysis model, and evaluating its performance using metrics such as accuracy, precision and recall.

# Requirements
To replicate and run this project, you will need the following dependencies:

-Python (version 3.x)

-Jupyter Notebook (for data exploration and analysis)

-Libraries like NumPy, Pandas, Scikit-learn, PyTorch (or other deep learning frameworks) and NLTK (for NLP preprocessing)

# Future Improvements
Implement this model using Twitter API and create a Realtime Sentiment Analyzer 
