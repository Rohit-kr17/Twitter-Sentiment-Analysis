# Twitter-Sentiment-Analysis

This repository contains a simple Python script for performing sentiment analysis on tweets using the Hugging Face Transformers library. The script utilizes a pre-trained model to classify tweets into three sentiment categories: Negative, Neutral, and Positive.

## Installation

Before running the code, make sure you have the required libraries installed. You can install them using the following command:

(i) pip install transformers scipy
(ii) pip install scipy
(iii) pip3 install torch

# Code Explanation
The script performs sentiment analysis using a pre-trained transformer model from the Hugging Face Transformers library. Here's a breakdown of the main components of the code:

The script preprocesses the input tweet to replace user mentions and URLs with generic placeholders.
It loads a pre-trained sentiment analysis model and tokenizer.
The sentiment analysis is performed by encoding the preprocessed tweet and passing it through the model.
The script then calculates the softmax scores for each sentiment label and displays the sentiment label along with its confidence score.


