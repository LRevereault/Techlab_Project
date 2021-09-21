# Techlab_Project

For this notebook we have drawn some inspirations from the following notebooks:

NLP with Disaster Tweets - EDA, Cleaning and BERT.ipynb
Disaster NLP: Keras BERT using TFHub

Disaster Tweets Evaluation with NLP .ipynb

## Problem/Challenge to be solved:

This project is based on a kaggle competition (www.kaggle.com/c/nlp-getting-started) aiming at analysing tweets and determining if they are related to a disaster or not. To perform this analysis, we were provided three datasets: train.csv, test.csv and sample_submission.csv. Using Natural Language Processing (NLP) we aim at analysing the tweets and predicting their context. Please not that the aim of this notebook is not to provide state-of-the-art model. NLP is a new topic for all of us, so the objective of this notebook and our project is to experiment with different approaches to Natural Language Processing and gain some experience.

## Project approach:

As a fist step, our team will make exploratory data analysis, in order to identify the trends in the data which might be useful to create new features, clean the tweets from unnecessary elements.

Second step will be to clean the data, create additional columns with features. Then, we will tokenize the tweets (and their parts). This will serve as an input into the neural networks and ML classification models.

As a third step, we will train and evaluate several ML learning models and two neural networks. For the top-performing ML models we will tune the hyperparameters. Afterwards, we will re-evaluate the best models (for which we tuned the parameters), compare their performance and choose the best model.

As a final step, we will execute the best model on the test set and save the predictions in the submission file.
