
# 🎬 NLP Text Classification Project

Harness the power of Natural Language Processing and Machine Learning to classify text data using traditional ML algorithms. This project walks through everything from cleaning raw HTML-laden text to building performant models and visualizing word patterns.

---

## 📌 Overview

This notebook-based project focuses on **text classification** using popular machine learning models. It covers the complete NLP workflow:

* 🧹 Cleaning & preprocessing
* 🧠 Feature engineering with Bag of Words & TF-IDF
* 🤖 Training ML models (Naive Bayes, Random Forest, Logistic Regression, XGBoost)
* 📈 Evaluating and comparing model performance

---

## 🗂️ Project Flow

### 🔹 1. Data Preprocessing

* Remove HTML tags
* Strip punctuation
* Generate word clouds for visualization

### 🔹 2. Feature Engineering

* Train-Test split
* Bag of Words vectorization
* TF-IDF transformation

### 🔹 3. Model Building

* 🧪 **Naive Bayes**
* 🌲 **Random Forest**
* 📊 **Logistic Regression**
* ⚡ **XGBoost**

### 🔹 4. Evaluation

Compare training and testing accuracy, and detect underfitting or overfitting.

---

## 🧪 Model Comparison

| 🔍 Model                | ✅ Test Accuracy | 🏋️‍♂️ Train Accuracy | 📌 Notes                |
| ----------------------- | --------------- | --------------------- | ----------------------- |
| **Naive Bayes**         | 86%             | 86%                   | ✔️ Balanced performance |
| **Random Forest**       | 82%             | 83%                   | ⚠️ Slight underfitting  |
| **Logistic Regression** | 82%             | 91%                   | ⚠️ Overfitting detected |
| **XGBoost**             | 86%             | 91%                   | ⚠️ Slight overfitting   |

---

## 🛠️ Installation

Make sure you have Python 3.x installed. Then install the dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Running the Project

### ▶️ Option 1: Run in Jupyter Notebook

```bash
jupyter notebook "nlp.ipynb"
```

### ▶️ Option 2: Convert and run as script

```bash
jupyter nbconvert --to script "nlp.ipynb"
python nlp.py
```

---

## 📌 Conclusion

✨ **Key Takeaway**:
Naive Bayes and XGBoost achieved the highest test accuracy of **86%**.
Random Forest slightly underfit, while Logistic Regression overfit the training data.
