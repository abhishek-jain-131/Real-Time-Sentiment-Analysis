# 🧠 Real-Time Sentiment Analysis on Social Media

A Flask-based web application that fetches live tweets using the Twitter API and performs sentiment analysis (Positive, Negative, Neutral) using NLTK's VADER model. Results are visualized for users with easy-to-understand charts and data.

---

## 🚀 Features

- 🔍 Search tweets by keyword or hashtag
- 📊 Real-time sentiment breakdown (positive, neutral, negative)
- 📈 Visual sentiment analysis
- 🧠 Sentiment classification using NLTK VADER
- 💾 MongoDB integration for storing fetched tweets

---

## 🧰 Tech Stack

### 💻 Frontend
- HTML5, CSS3, Bootstrap
- Chart.js for visualizations
- JavaScript

### 🖥️ Backend
- Python (Flask)
- Twitter API v2 (Recent Search)
- NLTK (VADER Sentiment Analyzer)
- MongoDB (via Flask-PyMongo)

---

## 🧠 Machine Learning Integration

- Uses **NLTK’s VADER** (Valence Aware Dictionary for Sentiment Reasoning) for sentiment scoring.
- Each tweet is classified into:
  - **Positive** (compound ≥ 0.05)
  - **Negative** (compound ≤ -0.05)
  - **Neutral** (between -0.05 and 0.05)
