# 🎬 IMDB Sentiment Analysis: From Bag-of-Words to Neural Networks
<img width="567" height="379" alt="image" src="https://github.com/user-attachments/assets/924c227f-8ed6-4fce-9de9-12deb29e6d34" />

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![PyTorch](https://img.shields.io/badge/PyTorch-DL-red?logo=pytorch)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

</p>

> A comparative Natural Language Processing (NLP) project that evaluates **Classical Machine Learning** and **Deep Learning** models for binary sentiment classification using the **IMDB Movie Review Dataset**.

---

## 📌 Project Overview

This project explores how different Machine Learning and Deep Learning algorithms perform on the same sentiment analysis task.

The objective is to classify movie reviews as **Positive** or **Negative** while comparing traditional NLP techniques with modern neural network architectures.

The project includes:

- Text preprocessing
- Feature engineering
- Classical Machine Learning
- Deep Learning
- Performance evaluation
- Comparative analysis

---

## 🚀 Models Implemented

### Classical Machine Learning

- Logistic Regression
- Bernoulli Naive Bayes
- Linear Support Vector Classifier (LinearSVC)
- Random Forest

### Deep Learning

- Vanilla RNN
- LSTM
- BiLSTM + FastText
- Cross-Attention Classifier

---

## 🛠 Tech Stack

- Python
- Scikit-learn
- PyTorch
- Pandas
- NumPy
- NLTK
- Matplotlib
- Google Colab

---

## 🧹 NLP Pipeline

```
Raw Reviews
      │
      ▼
Text Cleaning
      │
      ▼
Tokenization
      │
      ▼
Lemmatization
      │
      ▼
Feature Extraction
      │
      ├──────────────┐
      ▼              ▼
 Bag-of-Words   Word Embeddings
      │              │
      ▼              ▼
 Classical ML   Deep Learning
      │              │
      └──────┬───────┘
             ▼
      Performance Evaluation
```

---

## 📂 Dataset

**Dataset:** IMDB Movie Review Dataset

- 50,000 Movie Reviews
- Binary Classification
- Balanced Dataset
- 25,000 Positive Reviews
- 25,000 Negative Reviews

The dataset is downloaded automatically inside the **Google Colab notebook**, so it is **not included** in this repository.

Dataset Link:

https://ai.stanford.edu/~amaas/data/sentiment/

---

## 📊 Experimental Results

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|---------:|----------:|-------:|---------:|
| 🥇 LinearSVC | **87.41%** | 87.14% | 87.77% | **87.45%** |
| 🥈 Logistic Regression | **87.34%** | 86.59% | **88.38%** | 87.47% |
| 🥉 Random Forest | 85.49% | 85.41% | 85.60% | 85.50% |
| Cross Attention | 82.76% | 83.86% | 81.13% | 82.47% |
| Bernoulli Naive Bayes | 82.32% | 86.81% | 76.22% | 81.17% |
| BiLSTM + FastText | 81.86% | **88.00%** | 73.79% | 80.27% |
| LSTM | 80.16% | 79.35% | 81.54% | 80.43% |
| Vanilla RNN | 49.78% | 49.79% | 52.61% | 51.16% |

---

## 📈 Key Findings

- **LinearSVC** achieved the highest overall accuracy (**87.41%**).
- **Logistic Regression** performed almost identically while maintaining the highest recall.
- **Cross-Attention** was the best-performing deep learning model.
- **Vanilla RNN** struggled due to the vanishing gradient problem.
- **BiLSTM + FastText** produced the highest precision among neural models.
- Classical linear models outperformed deep learning models for this experimental setup.

---

## 💡 Skills Demonstrated

- Natural Language Processing (NLP)
- Text Preprocessing
- Feature Engineering
- Bag-of-Words
- Word Embeddings
- Machine Learning
- Deep Learning
- Model Evaluation
- PyTorch
- Scikit-learn
- Google Colab

---

## 📁 Repository Structure

```
IMDB-Sentiment-Analysis/
│
├── IMDB_Sentiment_Analysis.ipynb
├── README.md
└── Documentation
```

---

## ▶️ Running the Project

### Option 1: Google Colab (Recommended)

1. Open `IMDB_Sentiment_Analysis.ipynb` in Google Colab.
2. Run all cells sequentially.
3. The notebook automatically downloads the IMDB dataset.
4. Training and evaluation results will be generated automatically.

---

## 📚 Future Improvements

- TF-IDF Vectorization
- Word2Vec Embeddings
- GloVe Embeddings
- BERT
- RoBERTa
- DistilBERT
- Hyperparameter Optimization
- Explainable AI (SHAP/LIME)
- Streamlit Deployment

---

## 📖 References

- IMDB Movie Review Dataset
- Scikit-learn Documentation
- PyTorch Documentation
- FastText Documentation
- Jurafsky & Martin – Speech and Language Processing

---

## 👨‍💻 Author

**Suman Khamaru**

Software Engineer • Frontend Developer • AI & Machine Learning Enthusiast

If you found this project useful, consider giving it a ⭐ on GitHub.

