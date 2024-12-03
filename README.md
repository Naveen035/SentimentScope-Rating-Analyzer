# SentimentScope: Rating Analyzer

## 📌 Project Overview  
**SentimentScope: Rating Analyzer** is a machine learning-based application designed to predict the sentiment of user reviews. Using Natural Language Processing (NLP) techniques and a deep learning model, the application classifies reviews into one of five categories:
- **1 - Very Bad** 😡  
- **2 - Bad** 😠  
- **3 - Average** 😐  
- **4 - Good** 😊  
- **5 - Excellent** 🌟  

The project leverages a robust dataset of 15,000+ reviews and provides an intuitive, interactive interface for predicting sentiments.

---

## 🚀 Features  
- **Accurate Sentiment Prediction:** Classifies reviews into a 5-point sentiment scale.  
- **Interactive UI:** Built using Streamlit, with emojis and background colors for an engaging experience.  
- **Large Dataset Training:** Model trained on a dataset of over 15,000 reviews to ensure high accuracy.  
- **Customizable:** Easily adaptable for other review-based datasets or domains.  
- **Real-Time Predictions:** Instantly get the sentiment rating for any review text entered.  

---

## 🛠️ Tech Stack  
- **Languages & Tools:** Python, TensorFlow, Streamlit, NLTK, Scikit-learn  
- **Libraries:**  
  - `pandas` and `numpy` for data manipulation  
  - `nltk` for text preprocessing  
  - `TensorFlow` for building and training the RNN model  
  - `Streamlit` for creating an interactive user interface  

---

## 📂 Project Structure  
```plaintext
SentimentScope/
├── app.py                # Streamlit application file
├── tokenizer.pkl         # Pre-trained tokenizer for processing text
├── your_model.h5         # Trained deep learning model
├── requirements.txt      # Dependencies for the project
├── data/
│   └── reviews.csv       # Dataset used for training the model
└── README.md             # Project documentation

