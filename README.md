# Sentiment Analysis on Movie Reviews
This project aims to perform sentiment analysis on movie reviews using two machine learning models: Naive Bayes and Support Vector Machine (SVM). Sentiment analysis involves determining the sentiment expressed in a piece of text, which can be positive, negative, or neutral. In this case, we focus on movie reviews to classify them into positive or negative sentiments.
# Dataset Information
The dataset is expected to be a csv file of type "id","sentiment","review" where the "id" is a unique integer identifying the review, sentiment is either 1 (positive) or 0 (negative).The dataset contains 25000 datapoints.
# Requirements
There are some general library requirements for the project and some which are specific to individual methods. The general requirements are as follows.

pandas 

numpy

scikit-learn

scipy

Nltk

To install the necessary libraries, you can use the following command:

pip install scikit-learn nltk

# Installing
Clone the repository

https://github.com/AmalenduR841/Classification-Task.git

Navigate to the project directory.

Open your preferred Python environment (Jupyter Notebook, Spyder, etc.) and open the sentiment_analysis.ipynb file.
Execute the code cells in the notebook sequentially. This will train the Naive Bayes and SVM models and perform sentiment analysis on movie reviews.

# Workflow 
## Data Preparation

### The dataset is loaded and preprocessed to remove any irrelevant information.

Removed the punctuations from the reviews.

Removed stopwords.

Handled the contractions in the reviews.

Lemmatization is done to tokenize the reviews.

## Feature Extraction

## Model Building and Evaluation

Naive Bayes Model

SVM model

Evaluated the model's performance.


