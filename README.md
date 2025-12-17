# Website Evaluation Using Opinion Mining

## Project Overview
This project implements a **sentiment-driven website evaluation system** using **Natural Language Processing (NLP)** and a **deep learning–based Recurrent Neural Network (LSTM)**. The system analyzes user opinions in the form of reviews or comments and evaluates website quality based on sentiment classification.

The objective is to automatically extract insights from textual feedback and classify sentiments into **Positive, Neutral, and Negative** categories.

---

## Repository Overview
The project follows an end-to-end opinion mining pipeline, including data ingestion, text preprocessing, deep learning–based modeling, and result visualization.

---

## Problem Statement
User-generated content such as reviews and comments provides valuable insights into website quality. However, manual analysis is time-consuming and error-prone.  
This project applies **deep learning–based sentiment analysis** to automate website evaluation by learning contextual and sequential patterns in text data.

---

## Features
- Web scraping or dataset-based ingestion of user reviews
- Text cleaning and preprocessing
- Tokenization and sequence padding
- LSTM-based deep learning model for sentiment classification
- Visualization of sentiment distribution and model performance

---

## Workflow

### 1. Data Loading and Cleaning
- Removed irrelevant or unused columns
- Dropped null or inconsistent entries
- Generated sentiment labels (Positive, Neutral, Negative) from numerical ratings

### 2. Text Preprocessing
- Converted text to lowercase
- Removed punctuation and special characters
- Eliminated stopwords
- Tokenized text
- Applied padding to ensure uniform input length

### 3. Deep Learning Model
- Used an LSTM-based Recurrent Neural Network to capture sequential dependencies in text

**Model Architecture:**


---

## Results
- Achieved **92.87% accuracy** on sentiment classification
- Successfully captured long-term dependencies in review text
- Outperformed traditional machine learning approaches for raw text analysis

---

## Tools and Technologies
- **Programming Language:** Python
- **Libraries:** TensorFlow / Keras, Pandas, NumPy, NLTK
- **Visualization:** Matplotlib, Seaborn
- **Model:** LSTM-based Recurrent Neural Network
- **Platform:** Google Colab

---

## Key Learnings
- Practical application of NLP preprocessing techniques
- Understanding sequence modeling using LSTM networks
- Importance of text representation for sentiment analysis
- Visualizing and interpreting deep learning model performance

---

## Future Improvements
- Experiment with GRU and BiLSTM architectures
- Introduce attention mechanisms
- Explore transformer-based models such as BERT
- Deploy the system as an API or interactive dashboard

---

## Author
**Sambit Sahoo**  
Machine Learning | Deep Learning | NLP
