# Fake_news_detection
readme_text = """# 📰 Fake News Detection using Logistic Regression

This project aims to detect fake news using Natural Language Processing (NLP) and machine learning. The model uses logistic regression to classify news articles as either **real (0)** or **fake (1)** based on their content.

## 📁 Dataset

The dataset contains metadata of news articles with the following columns:

- `id`: Unique ID for a news article
- `title`: The title of the news article
- `author`: Author of the news article
- `text`: Full or partial text of the article
- `label`: Target label where
  - `1` indicates **Fake News**
  - `0` indicates **Real News**

> The dataset file should be named `News_dataset.csv` and placed in the `/content/` directory.

---

## 🧰 Dependencies

Make sure you have the following Python libraries installed:

```bash
pip install numpy pandas scikit-learn nltk
