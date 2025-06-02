# Fake_news_detection

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
🧹 Data Preprocessing
Missing values are filled with empty strings.

A new content column is created by merging the author and title.

Stemming is applied to reduce words to their root form.

Text data is converted to numerical features using TfidfVectorizer.

🧪 Model Training
The dataset is split into training and testing sets (80/20 split), and the model is trained using Logistic Regression.

⚙️ Model Evaluation
Accuracy on training data and test data is printed using accuracy_score.

🔮 Prediction Example
A sample news item from the test set is used for prediction, and the model outputs whether it's Real or Fake.

📊 Results
The model typically achieves:

Training Accuracy: ~98%

Test Accuracy: ~94%
