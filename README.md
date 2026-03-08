# Automated-Emerging-Cyber-Threat-Identification-and-Profiting-based-on-Natural-Language-Processing

Automated Cyberbullying Detection using NLP

This project is a Cyberbullying Detection System that analyzes tweets and identifies cyberbullying content using Natural Language Processing (NLP) and Machine Learning techniques.
The system provides a Graphical User Interface (GUI) built with Tkinter to make the workflow interactive and easy to use.

Project Features

Upload and analyze cyberbullying tweet datasets

Text preprocessing and cleaning

Sentiment analysis of tweets

Named Entity Recognition (NER)

Part-of-Speech (POS) tagging

Topic modeling visualization

Feature extraction using Bag-of-Words

Machine learning classification models

Performance comparison between models

Technologies Used

Programming Language

Python

Libraries and Frameworks

NumPy

pandas

NLTK

spaCy

TextBlob

Gensim

scikit-learn

matplotlib

seaborn

Dataset

The project uses a Cyberbullying Tweets Dataset containing tweets and their corresponding cyberbullying categories.

Example dataset fields:

tweet_text	cyberbullying_type
"I hate you"	gender
"You are stupid"	religion
"Stop insulting people"	age

Dataset file example:

cyberbullying_tweets.csv
Installation

Clone the repository:

git clone https://github.com/yourusername/cyberbullying-detection-nlp.git
cd cyberbullying-detection-nlp

Install required Python libraries:

pip install numpy pandas matplotlib seaborn scikit-learn nltk spacy gensim textblob tqdm

Download required NLP models:

python -m nltk.downloader punkt
python -m nltk.downloader stopwords
python -m spacy download en_core_web_sm
Running the Project

Run the main Python script:

python cyberbullying_detection_nlp.py

A GUI window will open with multiple processing options.

Execution Workflow

Upload Cyberbullying Tweets Dataset

Dataset Pre-processing

Sentiment Analysis

Named Entity Recognition (NER)

POS Tagging

Topic Modeling Visualization

Feature Extraction

Logistic Regression Algorithm

Decision Tree Algorithm

Random Forest Algorithm

Comparison of Models

Machine Learning Models Used

The system trains and evaluates three classification models:

Logistic Regression

Decision Tree

Random Forest

Evaluation metrics include:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

ROC Curve

Example Results
Model	Accuracy
Logistic Regression	~0.89
Decision Tree	~0.86
Random Forest	~0.91

Random Forest typically achieves the best performance.
