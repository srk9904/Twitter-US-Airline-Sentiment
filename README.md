# Twitter-US-Airline-Sentiment
 UCS2602 - Principls of Machine Learning Project
# ✈️ Airline Sentiment Analysis using Ensemble Learning

This repository contains a machine learning-based sentiment analysis project focused on classifying sentiments from airline-related tweets. It explores traditional ML models, modern ensemble methods, and embeddings like TF-IDF and FastText. The final goal is to build a robust, accurate sentiment classifier tailored for real-world short-form text data.

---

## 📌 Table of Contents
- [Project Report](#project-report)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Contributors](#contributors)

---

## 🧠 Project Overview

With the explosion of social media, particularly platforms like Twitter, real-time sentiment analysis has become crucial for businesses to understand customer feedback. This project analyzes a dataset of airline-related tweets and applies various machine learning algorithms — with a strong emphasis on ensemble learning techniques — to classify tweets as **Positive**, **Negative**, or **Neutral**.

---

## ✅ Features

- Preprocessing pipeline (cleaning, tokenization, stemming)
- Feature extraction using **TF-IDF** and **FastText**
- Classification models:
  - Logistic Regression
  - Naïve Bayes
  - Support Vector Machines (SVM)
  - Random Forest
  - Voting, Bagging, Boosting (AdaBoost, Gradient Boosting)
  - XGBoost
- Comparative performance analysis
- Deployment-ready model (optional RapidMiner / AWS / Azure)

---

## 🛠️ Tech Stack

| Component | Description |
|----------|-------------|
| Language | Python 3.x |
| ML Libraries | Scikit-learn, XGBoost, NLTK, Gensim |
| Embeddings | TF-IDF, FastText |
| Notebook | Jupyter |
| Deployment (optional) | RapidMiner / AWS / Azure |

---

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/airline-sentiment-analysis.git
cd airline-sentiment-analysis
