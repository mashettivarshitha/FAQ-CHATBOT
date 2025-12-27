# FAQ-CHATBOT
# 🧠 Chatbot using NLTK and Scikit-Learn

Welcome to the **Chatbot Project**, a simple yet effective rule-based and NLP-powered chatbot built using Python, NLTK (Natural Language Toolkit), and Scikit-learn. This project demonstrates how to combine natural language processing and machine learning techniques to create an intelligent chatbot capable of responding to user input with relevant information.

---

## 📌 Project Overview

This chatbot performs the following key functions:

- Handles general greetings like "hi", "hello", "hey", etc.
- Responds to user queries based on similarity with a custom dataset using **TF-IDF** and **cosine similarity**.
- Applies **lemmatization**, **tokenization**, and **punctuation removal** using NLTK.
- Trained on a dataset file (`chatbot dataset.txt`) that contains various predefined responses.
- Continuously interacts with the user in a loop until the user types `"bye"`.

---

## 🧰 Technologies Used

- **Python 3**
- **NLTK** - Natural Language Toolkit for preprocessing and lemmatization
- **Scikit-learn** - TF-IDF vectorization and cosine similarity
- **NumPy** - Basic numerical operations
- **Random** - For random greeting selection
- **String & IO** - For text cleaning and handling

---

## 📂 Project Structure
-**FAQ CHATBOT**

- chatbot.py # Main chatbot implementation
- chatbot dataset.txt # Text dataset the chatbot is trained on
- requirements.txt # List of required Python packages
- README.md # Project documentation (this file)
# FAQ-CHATBOT
