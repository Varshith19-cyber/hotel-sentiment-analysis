📊 Hotel Review Sentiment Analysis – Gen AI Project

This project analyzes hotel reviews and predicts whether the sentiment is Positive or Negative using Machine Learning and Gen-AI techniques.
The system processes text reviews, performs sentiment classification, and displays results through a simple and user-friendly Flask web application.

🚀 Features

Predicts sentiment of hotel reviews (Positive / Negative)

Clean UI with Flask frontend

Text preprocessing and TF-IDF vectorization

Trained ML model for real-time predictions

Easy to deploy and extend

Includes complete notebook with model training

📂 Project Structure
project-folder/
│── app.py
│── README.md
│
├── static/
│    └── style.css
│
├── templates/
│    ├── index.html
│    └── result.html
│
├── dataset/
│    └── hotel_reviews.csv
│
└── notebook/
     └── hotel_sentiment.ipynb

🧠 Technologies Used

Python

Flask

Scikit-learn

Pandas

NumPy

NLTK

Matplotlib / Seaborn

🧹 Text Preprocessing

The review text goes through:

Lowercasing

Stopword removal

Lemmatization

Removing punctuation & numbers

TF-IDF vectorization

⚙️ How to Run the Project
1. Install Dependencies
pip install -r requirements.txt

2. Run the Application
python app.py

3. Open in Browser

Go to:

http://127.0.0.1:5000/

🧪 Model Training

The model is trained inside the Jupyter Notebook:

notebook/hotel_sentiment.ipynb


Steps include:

Data Cleaning

Exploratory Data Analysis

TF-IDF Vectorization

Model Training & Testing

Accuracy Comparison

🌱 Future Enhancements

Multilingual sentiment detection

Deep learning & transformer-based models (BERT, GPT)

Aspect-based sentiment analysis

Real-time dashboard

Mobile app integration
