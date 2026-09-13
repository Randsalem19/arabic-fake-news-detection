# 📰 Arabic Fake News Detection

An end-to-end Natural Language Processing (NLP) and Machine Learning system for detecting fake news in Arabic text, built with a full text classification pipeline — from Arabic-specific preprocessing to model evaluation and comparison.

---

## 📖 Overview

This project tackles the problem of misinformation in Arabic media by classifying news articles as **real** or **fake**. It combines Arabic-specific text normalization techniques with classical machine learning models to build an accurate and interpretable classification pipeline.

The project demonstrates practical experience in:
- Arabic Natural Language Processing (NLP)
- Text classification and feature engineering
- Machine learning model evaluation and comparison

---

## 📊 Dataset

| Category | Count | Percentage |
|----------|-------|------------|
| Real News | 3,913 | 73.11% |
| Fake News | 1,439 | 26.89% |
| **Total** | **5,352** | **100%** |

---

## 🔧 Data Preprocessing

The following preprocessing steps were applied to prepare the Arabic text for modeling:

- Arabic text normalization
- Removal of diacritics (Tashkeel)
- Removal of punctuation and numbers
- Arabic stopword removal
- Arabic stemming using `ISRIStemmer`
- TF-IDF feature extraction

---

## 🤖 Machine Learning Models

Three classical machine learning models were trained and evaluated on the processed dataset:

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 88.98% |
| Random Forest | 88.80% |
| **Support Vector Machine (SVM)** | **90.29%** |

### 🏆 Best Model
The **SVM classifier** achieved the best overall performance, with an accuracy of approximately **90.3%**, outperforming both Logistic Regression and Random Forest.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** / **NumPy**
- **Scikit-learn**
- **NLTK**
- **TensorFlow / Keras**
- **Matplotlib** / **Seaborn**

---

## 📌 Project Type

Academic NLP project developed as part of **Data Science and Artificial Intelligence** studies.

---

## ▶️ Open in Google Colab

🔗 **[Open the Notebook in Google Colab](https://colab.research.google.com/drive/13OHyLZ8UpvJchyWs6Okjwl4LCsdlarM0)**

---

## 👩‍💻 Author

**Rand Salem**
- GitHub: [Randsalem19](https://github.com/Randsalem19)
- LinkedIn: [rand-majed-salem](https://linkedin.com/in/rand-majed-salem)
- Kaggle: [randsalem](https://kaggle.com/randsalem)
