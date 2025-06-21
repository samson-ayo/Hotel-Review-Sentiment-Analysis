# samson-project

📌 Project Overview

This project focuses on applying text mining and sentiment analysis techniques to analyze thousands of customer feedback from 30 different hotels and restaurants across India. The objective is to extract meaningful insights about customer satisfaction and classify their reviews into positive, negative, or neutral sentiments.
Two supervised machine learning models — Naive Bayes and Random Forest — were implemented to predict the sentiment based on the textual content of the reviews.

🎯 Objectives

Extract insights from raw textual reviews using text mining
Preprocess and clean review data (stopword removal, stemming, tokenization)
Convert unstructured text into structured features using TF-IDF
Classify sentiment into positive, neutral, or negative
Train and evaluate models using Naive Bayes and Random Forest

🛠️ Tools & Technologies

| Tool/Library             | Purpose                           |
| ------------------------ | --------------------------------- |
| **Python**               | Core programming language         |
| **NLTK / spaCy**         | Text preprocessing & tokenization |
| **Scikit-learn**         | Model building & evaluation       |
| **Pandas / NumPy**       | Data handling                     |
| **Matplotlib / Seaborn** | Data visualization                |

⚙️ Workflow Summary

Data Collection: Raw reviews from 30 hotels/restaurants

Text Preprocessing:
Lowercasing
Stopword removal
Tokenization
Lemmatization/Stemming
Feature Engineering:
Bag of Words and TF-IDF Vectorization

Modeling:
Train Naive Bayes and Random Forest classifiers
Evaluate performance with accuracy, precision, recall, and F1-score

Sentiment Classification:
Predict whether each review is positive, neutral, or negative

🧠 Model Evaluation

| Model         | Accuracy | Precision | Recall | F1-Score |
| ------------- | -------- | --------- | ------ | -------- |
| Naive Bayes   | 0.98%    | 0.99%     | 1.00%  | 0.99%    |
| Random Forest | 1.00%    | 1.00%     | 1.00%  | 1.00%    |

📊 Example Use Case

A restaurant owner can use this model to:
Automatically tag new customer reviews
Track trends in positive or negative feedback over time
Identify specific areas (e.g., service, food, ambience) causing dissatisfaction

🚀 Future Improvements

Use deep learning models (e.g., BERT, LSTM) for better context understanding
Expand to multilingual review analysis
Integrate into a dashboard or web application for real-time insights
Perform aspect-based sentiment analysis (e.g., sentiment on food vs service)
