<p align="center">
  <img src="banner.png" alt="Sentiment Analysis Banner">
</p>

# DistilBERT Sentiment Analysis

Fine-tunes **DistilBERT** (`distilbert-base-uncased`) with Hugging Face Transformers to classify movie reviews as **positive** or **negative**. Training uses the Hugging Face `Trainer` with an 80/20 train/test split, and the model is evaluated with accuracy and F1 score.



## 🚀 Getting Started

Follow these steps to set up and run the sentiment analysis project locally:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/seiifff/distilbert-sentiment-analysis.git
cd distilbert-sentiment-analysis
```

### 2️⃣ Install Dependencies

Make sure you have Python 3.8+ and run:

```bash
pip install -r requirements.txt
```

### 3️⃣ Train and evaluate

```bash
python sentiment_analysis.py
```

This fine-tunes DistilBERT on `train.csv` (columns `review`, `sentiment`), evaluates accuracy and F1 on the held-out 20%, saves the model to `sentiment_model/`, and includes a `predict_sentiment(text)` helper. You can also run everything step by step in `DistilBERT_Sentiment_Analysis_FIXED.ipynb`.

---

## 🧪 Example

Try entering:

```
This movie was surprisingly good, with great acting and a powerful script.
```

Expected Output:

```
Positive 😊
```



![Python](https://img.shields.io/badge/Language-Python-blue)
![HuggingFace](https://img.shields.io/badge/Transformers-HuggingFace-yellow)
![NLP](https://img.shields.io/badge/Task-Sentiment_Analysis-red)

---

## 🔗 Connect with Me

- [LinkedIn](https://www.linkedin.com/in/seif-ferooz-/)
- [GitHub Portfolio](https://github.com/seiifff)

