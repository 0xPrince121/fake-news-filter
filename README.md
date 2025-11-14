<div align="center">

# 🚀 Fake News’ Filter | AI-Driven News Verification & Truth Detection

  <img src="https://img.shields.io/badge/Status-Completed-gree?style=flat&logo=github" alt="Status"> 
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=flat&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat" alt="License">

</div>

---

## 🌟 Overview

Fake News' Filter is an AI/ML-powered news verification system that predicts whether a given news article is Real or Fake.
It uses NLP (Natural Language Processing), ML classification, and probability scoring to ensure credible results.

Key highlights:  
- AI-powered real/fake news detection.  
- Fast predictions with machine-learning model.  
- Clear output: Real News ✅ / Fake News ❌.  
- Easy API + frontend integration.  
- Trainable with your own dataset.

---

## 🛠️ Tech Stack

| Component        | Technology Used                         |
|------------------|------------------------------------------|
| Core Language     | Python 3.x                               |
| Data Processing   | pandas, numpy                            |
| NLP Pipeline      | NLTK / scikit-learn                      |
| Text Vectorizer   | TF-IDF Vectorizer                        |
| ML Model          | Logistic Regression / Naive Bayes        |
| Dataset Storage   | CSV (Balanced Fake + Real News)          |
| API Framework     | FastAPI                                  |
| Frontend          | HTML / CSS                               |
| Model Export      | joblib                                   |
 

---
## 📂 Project Structure

```
Fake New’s Filter/
├── api/
│   ├── main.py
│   └── requirements.txt
│
├── Frontend/
│   ├── index.html
│   ├── script.js
│   └── style.css
│
├── model/
│   ├── fake_news.csv
│   ├── train.py
│   ├── model.pkl
│   └── vectorizer.pkl
│
└── README.md

```
---

## ✨ Features

- Detects whether news is fake or real using AI.  
- Shows a confidence score for each news item.  
- Works with text or news links.  
- Fast and easy to use.  
- Explains why a news item is fake or real.

---

## 📁 Project Layout

- `ml/` — folder handles all data and model-related files.  
- `api/` — folder is where you serve predictions via endpoints..  
- `static/` + `templates//` structure handles frontend assets.
- `project_settings/settings.py` — makes it environment-friendly,


---

## ⚡ Quick Start (Local)

1. Clone :
   ```bash
   git clone https://github.com/0xPrince121/fake-news-filter.git
   ```

3. Install Python dependencies :  
    ```bash
    pip install -r requirements.txt
    ```
4. Train Model :  
    ```bash
   cd /Users/youePath/Desktop/Fake\ New\'s\ Filter/model && python3 train.py

    ```
5.  Start Backend API :  
    ```bash
    cd ~/Desktop/"Fake New's Filter"/api && uvicorn main:app --reload
    ```

6. Open Frontend :
   ```bash
   Frontend/index.html
   ```


---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🙏 Acknowledgements
- Developed as part of my learning and practice in AI & Machine Learning.
- Inspired by real-world fact-checking and news verification best practices.

<br>
<br>
<div align="center"> Made with 💌  by Prince | © 2025 Cybersecurity.
  </div>
