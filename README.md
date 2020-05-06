# Topic_Modeling-Latent_dirichlet_allocation
NLP based algorithm to classify text in a document to a particular topic using LDA.

## Overview
In this project I have built the document classification model to classify text in a document to a particular topic using Latent Dirichlet Allocation (LDA) model. The major steps during this project implementation includes - 

- Data Preprocessing - Tokenization, Stopwords removal, Stemming and Lemmatization using nltk
- Creating Bag of Words on the dataset
- Implementing TF-IDF (erm Frequency, Inverse Document Frequency) on the dataset
- Run LDA on each topic to explore the words occuring in that topic and its relative weight.
- Perform Evaluation
- Test the model on the unseen documents

### Data
The dataset we'll use is a list of over one million news headlines published over a period of 15 years. It can be loaded from the abcnews-date-text.csv file provided with the project.
