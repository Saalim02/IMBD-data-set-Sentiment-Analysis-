# 🎬 IMDB Sentiment Analysis using Simple RNN

This project is a **Sentiment Analysis Web App** built using **TensorFlow**, **Keras**, and **Streamlit**.  
It predicts whether a movie review is **Positive** or **Negative** based on the input text.

---

## 🚀 Project Overview

The application uses a **Simple Recurrent Neural Network (Simple RNN)** trained on the **IMDB movie review dataset**.

Users can enter a custom movie review, and the app will:
- preprocess the text
- convert it into numerical format using the IMDB word index
- pass it through the trained model
- predict the sentiment as **Positive** or **Negative**

---

## 📌 Features

- Predicts sentiment of movie reviews
- Built with **TensorFlow / Keras**
- Interactive **Streamlit web app**
- Uses a pretrained **Simple RNN model**
- Displays both:
  - Sentiment label
  - Prediction confidence score

---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Pandas**
- **Scikit-learn**
- **Matplotlib**
- **Streamlit**

---

## 📂 Project Structure

```bash
simple-rnn-imdb-sentiment-analysis/
│
├── main.py
├── requirements.txt
├── runtime.txt
├── README.md
├── .gitignore
└── simple_rnn_imdb.h5
