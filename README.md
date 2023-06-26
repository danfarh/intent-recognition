# Intent Recognition
This project is an intent recognition system that uses Natural Language Processing (NLP) techniques to identify the intent of a user's input. The system takes user input in the form of text and classifies it into one of several pre-defined categories, or "intents". The intents can be used to trigger specific actions, such as querying a database or providing a response to the user.

## Dataset
The dataset used for this project is the Hamrah Aval questions dataset, which is about 6,113 questions in Farsi language, with 21 pre-defined intents

## Approach
The project will use a machine learning approach to translate text between Persian and English. The following steps will be taken:

- Data Preparation: The dataset will be preprocessed and cleaned to remove any noise and irrelevant information.
- Feature Extraction: The text data will be transformed into a numerical representation using word embeddings.
- Model Development: A transformer-based sequence-to-sequence model with attention will be developed and trained on the features extracted from the text data.
- Model Evaluation: The model will be evaluated on a test set to measure its accuracy and other performance metrics.

## Requirements
- Python
- Pandas
- Numpy
- Tensorflow
- Keras
