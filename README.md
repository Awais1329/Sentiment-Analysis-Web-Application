Sentiment Analysis Web Application

A Sentiment Analysis Web Application developed using Natural Language Processing (NLP) and Machine Learning to classify text as Positive or Negative. The application provides an easy-to-use web interface built with Streamlit, allowing users to analyze individual text inputs or upload files containing multiple text entries for batch sentiment analysis.

The machine learning model is trained on the IMDB Movie Reviews Dataset using TF-IDF (Term Frequency–Inverse Document Frequency) for text feature extraction and Logistic Regression for sentiment classification. Before prediction, the input text undergoes preprocessing steps such as text cleaning, lowercasing, punctuation removal, stop-word removal, and tokenization to improve prediction accuracy.

Features
Analyze the sentiment of a single text or sentence.
Upload a CSV or text file for batch sentiment analysis.
Automatically predicts whether each text is Positive or Negative.
Displays sentiment predictions in an easy-to-read format.
Fast and interactive web interface built with Streamlit.
Machine Learning model trained using the IMDB movie review dataset.
How It Works
Users enter text manually or upload a file containing multiple text records.
The application preprocesses the text using NLP techniques.
TF-IDF converts the processed text into numerical feature vectors.
The trained Logistic Regression model predicts the sentiment of each text.
Results are displayed instantly, showing whether the sentiment is Positive or Negative.
Technologies Used
Python
Streamlit
Scikit-learn
Pandas
NumPy
Natural Language Processing (NLP)
TF-IDF Vectorization
Logistic Regression
Project Outcome

This project demonstrates the practical application of Machine Learning and Natural Language Processing by building a real-world sentiment analysis system. It enables users to efficiently analyze customer reviews, feedback, or any text data through both single-text prediction and batch file analysis, making it suitable for various business and research applications.
