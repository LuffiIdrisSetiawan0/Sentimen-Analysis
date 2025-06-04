# Google Playstore Indodax Sentiment Analysis

This project performs **sentiment classification** on user reviews of the Indodax mobile app, scraped from the Google Play Store using Python. The model uses classic NLP techniques such as text cleaning, TF-IDF vectorization, and Logistic Regression to classify reviews into `positive`, `neutral`, or `negative`.

---

## 🧠 Objective

- Scrape user reviews from Google Play Store
- Preprocess and clean raw text
- Label sentiment based on user ratings
- Train a sentiment classification model using NLP and machine learning
- Achieve minimum 85% accuracy on the test set ✅ *(This project achieved >90% accuracy)*

---
## Setup Environment - Anaconda
```
conda create --name indodax_sentiment python=3.10
conda activate indodax_sentiment
pip install -r requirements.txt
```

## Setup Environment - Shell/Terminal
```
mkdir indodax_sentiment
cd indodax_sentiment
python -m venv env
source env/bin/activate  # Gunakan `env\Scripts\activate` di Windows
pip install -r requirements.txt
```
