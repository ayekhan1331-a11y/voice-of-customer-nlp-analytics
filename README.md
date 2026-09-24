# voice-of-customer-nlp-analytics
Pipeline that uses NLP and sentiment analysis to convert customer support transactions into insights using the VoC analytics approach.
# Voice of Customer (VoC) Analytics using NLP & Machine Learning

## 📌 Project Overview
This project processes customer support interactions across various communication channels (Chat, Email, Phone) to automatically extract customer sentiment, evaluate satisfaction trends, and discover key drivers of operational friction using Unsupervised Topic Modeling (NMF) and Sentiment Scoring.

## 🛠️ Key Features
- **Data Preprocessing & Cleaning:** Text normalization and regex filtering for operational log data.
- **Sentiment Analysis:** Polarity scoring using VADER lexicon to categorize customer sentiment (Positive, Negative, Neutral).
- **Topic Modeling (Driver Extraction):** Matrix decomposition using TF-IDF and Non-Negative Matrix Factorization (NMF) to identify root operational issues.
- **Operational Visualization:** Channel-wise sentiment distribution graphs to assist BPO Quality Assurance workflows.

## 🧰 Tech Stack
- **Language:** Python 3.x
- **NLP & ML:** NLTK, Scikit-Learn, Transformers
- **Data Analysis & Visualization:** Pandas, NumPy, Seaborn, Matplotlib
- **Environment:** Google Colab

## 🚀 How to Run
1. Open the file `VoC_Analytics_Project.ipynb` in Google Colab.
2. Run all code cells sequentially (`Shift + Enter`).
