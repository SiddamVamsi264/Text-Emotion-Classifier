# Emotion Classification from Text

This project is a **multi-class text classification pipeline** built with **TensorFlow/Keras**.  
It predicts the **emotion** expressed in a sentence, such as *joy*, *sadness*, or *anger*.

## 📌 Overview
The model takes raw sentences as input, processes them into numerical form, and outputs probabilities for each possible emotion.  
It is trained on a labeled dataset of sentences and corresponding emotion tags.

---

## 🚀 Features
- Preprocessing pipeline:
  - Tokenization of text into integer sequences
  - Padding sequences to fixed length
  - Encoding labels into one-hot vectors
- Neural network architecture:
  - Embedding layer to learn word representations
  - Dense layers for feature learning
  - Softmax output for multi-class prediction
- Train/test split for performance evaluation
- Inference pipeline for new text inputs

---

## 🛠️ Tech Stack
- **Python 3.9+**
- **TensorFlow / Keras**
- **pandas**, **numpy** for data handling
- **scikit-learn** for preprocessing utilities

---
