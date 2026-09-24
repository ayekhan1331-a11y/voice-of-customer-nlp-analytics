# voice-of-customer-nlp-analytics
Pipeline that uses NLP and sentiment analysis to convert customer support transactions into insights using the VoC analytics approach.
# Voice of Customer (VoC) Analytics & Sentiment Pipeline

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1MCP4aaESMxzGEtChVxoLCyqqYFnERDkD)

## 📌 Overview
Having spent over 4 years working in Customer Support, Quality Assurance, and BPO operations, I frequently saw how much rich customer feedback gets buried inside daily interaction logs. Standard CSAT metrics tell you *what* score a customer gave, but they rarely capture *why* customers feel the way they do.

I built this project to bridge that operational gap using Python and Natural Language Processing (NLP). The pipeline ingests real customer service interaction data (e.g., Twitter customer support tickets), automates sentiment categorization, and extracts recurring complaint drivers to help support teams act on feedback faster.

---

## 💡 What This Pipeline Does
- **Text Preprocessing & Cleaning:** Standardizes raw support text by handling lowercasing, regex filtering, and removing operational noise.
- **Sentiment Scoring (VADER):** Uses rule-based lexicon scoring to automatically evaluate ticket sentiment and group feedback into **Positive**, **Negative**, or **Neutral** buckets.
- **Unsupervised Topic Modeling (NMF):** Applies TF-IDF vectorization and Non-Negative Matrix Factorization (NMF) to uncover hidden root causes behind customer inquiries (e.g., billing glitches, app errors, service delays).
- **Operational Visualizations:** Plots sentiment distribution across support channels using Seaborn to help QA teams prioritize ticket queues.

---

## 🧰 Tools & Libraries
- **Language:** Python 3.x
- **NLP & Machine Learning:** NLTK (VADER), Scikit-Learn (TF-IDF, NMF)
- **Data Manipulation & Visualization:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Google Colab / Jupyter Notebook

---

## 🚀 How to Run
1. Click the **Open In Colab** badge above to launch the notebook directly in your browser.
2. Upload the sample interaction dataset (`Twitter Customer Services.xlsx`) to the Colab session storage panel on the left.
3. Run the cells sequentially (`Shift + Enter`) to process the dataset and generate the outputs.
