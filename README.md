🎬 Movie Review Sentiment Analyzer

This project is a simple web application that predicts whether a given movie review is positive or negative. It is built using Python, Streamlit, and Machine Learning.

📌 Features

Interactive Streamlit web interface

Text preprocessing (stopwords removal, lowercasing, cleaning HTML/URLs/special characters)

TF-IDF vectorizer for feature extraction

Logistic Regression model for sentiment classification

Displays prediction with confidence scores

🛠️ Tech Stack

Python

Streamlit

Scikit-learn

NLTK

Joblib

🚀 How to Run

Clone this repository:

git clone https://github.com/yourusername/movie-sentiment-analyzer.git
cd movie-sentiment-analyzer


Install dependencies:

pip install -r requirements.txt


Make sure the model files are present in the project folder:

tfidf_vectorizer.joblib

logreg_sentiment_model.joblib

Run the app:

streamlit run app.py

📊 Example Output

Input: “The movie was fantastic and thrilling!”
→ ✅ Positive (Confidence ~95%)

Input: “Worst movie ever, waste of time.”
→ ❌ Negative (Confidence ~92%)

📈 Future Improvements

Support for multiple languages

Use of deep learning models (LSTM, BERT)

Deploy on cloud (Streamlit Cloud / Heroku / AWS)

Add neutral sentiment detection