# 📊 RedditInsightEngine

A robust Python-based sentiment analysis tool designed to extract, process, and visualize public discourse from Reddit. By leveraging the **Reddit API (PRAW)** and Natural Language Processing (NLP), this engine provides real-time insights into community sentiment on any given topic.

---

## 🚀 Project Overview
**RedditInsightEngine** automates the collection of subreddit data to determine the emotional "pulse" of a community. Whether tracking brand reputation, market trends, or social discourse, this tool transforms raw text into actionable sentiment scores.

* **Data Source:** Reddit API via PRAW (Python Reddit API Wrapper)
* **Core Logic:** Sentiment scoring using NLTK/TextBlob
* **Architecture:** Modular Python scripts for data ingestion and analysis

---

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** PRAW, TextBlob/NLTK, Pandas
* **Environment:** Dotenv (for secure API credential management)
* **Configuration:** `requirements.txt` for easy environment setup

---

## ⚙️ Features
* **Real-time Extraction:** Fetch latest posts and comments from any subreddit.
* **Sentiment Scoring:** Categorizes text into Positive, Neutral, or Negative polarities.
* **Secure Config:** Uses `.env` files to protect sensitive API client IDs and secrets.
* **Scalable Structure:** Organized for easy integration with web frameworks like Flask or FastAPI.

---

## 📋 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/harshit11purohit/RedditInsightEngine.git](https://github.com/harshit11purohit/RedditInsightEngine.git)
   cd RedditInsightEngine
