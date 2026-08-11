# 🎬 IMDB Movie Review Sentiment Analysis using Simple RNN

A Deep Learning project that uses a **Simple Recurrent Neural Network (RNN)** to perform sentiment analysis on movie reviews.

The model is trained on the **IMDB Movie Review Dataset** and classifies a given movie review as either:

- 😊 Positive
- 😞 Negative

The trained model is integrated with a **Streamlit web application** that allows users to enter their own movie reviews and receive a sentiment prediction.

---

## 🚀 Features

- Sentiment analysis using a Simple RNN
- IMDB movie review dataset
- Pre-trained TensorFlow/Keras model
- Text preprocessing and tokenization
- Sequence padding for fixed-length input
- Real-time prediction through Streamlit
- Prediction probability/score displayed to the user
- Handles unknown words using the IMDB vocabulary

---

## 🧠 How It Works

The application follows this pipeline:

```text
User enters movie review
          ↓
Convert text to lowercase
          ↓
Tokenization
          ↓
Convert words to integer indices
          ↓
Handle unknown words
          ↓
Pad sequence to 500 words
          ↓
Simple RNN Model
          ↓
Prediction Probability
          ↓
    Probability > 0.5
       ↙          ↘
   Positive      Negative