# Twitter Sentiment Analysis Project

## Project Images
![Before Input](Before_input.png)


## Overview
This project is a Twitter Sentiment Analysis application built using Streamlit. It predicts the sentiment (positive, negative, or neutral) of a given Twitter text using a Naive Bayes classifier trained on Twitter data.

## Project Structure
The project consists of two main files:

### app.py
  This file contains the Streamlit application code. It uses the trained Naive Bayes classifier and CountVectorizer to predict the sentiment of user input.

### twitter.py
  This file contains the code for training the Naive Bayes classifier using Twitter data. It preprocesses the data, extracts features using CountVectorizer, and saves the trained classifier and vectorizer for later use.

### Clone the repository:
  git clone https://github.com/your-username/twitter-sentiment-analysis.git

### Install dependencies:
  Python 3.x
  Streamlit
  scikit-learn
  pandas
  pip install -r requirements.txt

#### Usage
  1. Run the application using the command:
  streamlit run app.py
  Enter a Twitter text in the input area.
  Click the "Predict" button to see the predicted sentiment.
![After Input](after_input.png)
## Data Used
The Twitter data used for training is sourced from 'Twitter_Data.csv'. Ensure that the dataset is available in the project directory.
