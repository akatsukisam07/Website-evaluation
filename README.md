Website Evaluation Using Opinion Mining

A sentiment-driven system that evaluates websites using NLP and a Recurrent Neural Network (LSTM-based model).

Overview

This project performs website quality evaluation using opinion mining.
It extracts user reviews/comments, cleans the text, vectorizes the text, and classifies sentiment (Positive, Neutral, Negative) using a deep learning–based RNN model (LSTM).

Features

Web scraping / dataset ingestion

Text cleaning & preprocessing

Tokenization + padding

Deep learning model (Embedding + LSTM)

Visualizations: sentiment distribution, word cloud, accuracy/loss curves


Tech Stack


Language: Python

Libraries: TensorFlow/Keras, Pandas, NumPy, NLTK, Matplotlib, Seaborn

Model: LSTM-based Recurrent Neural Network

Platform: Google Colab


Workflow

1. Data Loading & Cleaning

Removed unnecessary columns

Dropped null values

Created sentiment labels from ratings (Positive, Neutral, Negative)


2. Text Preprocessing

Lowercasing

Removing punctuation

Stopword removal

Tokenization

Padding sequences


3. Deep Learning Model (LSTM)

Architecture used:

Embedding → LSTM → Dense → Output Layer



Results

LSTM model achieved 92.87% accuracy 

Captures long-term dependencies in review text

Performs significantly better than classical ML models for raw text

<img width="310" height="288" alt="image" src="https://github.com/user-attachments/assets/55273cfb-6483-43ea-965b-59df48d8e312" />



Conclusion

This project demonstrates how deep learning (LSTM) can be applied for opinion mining and website evaluation.
The pipeline is flexible and can be expanded to support more complex architectures.


Future Improvements

Use GRU / BiLSTM

Add attention mechanism

Try transformer models (BERT)

Deploy as an API / dashboard

Author

Sambit Sahoo
