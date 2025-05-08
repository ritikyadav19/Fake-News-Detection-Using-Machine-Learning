
# 📰 Fake News Detection using Machine Learning

A machine learning project to detect fake news articles using natural language processing (NLP) and classification algorithms.

This project uses the **Fake and Real News Dataset** from Kaggle and applies text preprocessing, TF-IDF vectorization, and supervised learning models such as **Logistic Regression** to classify news articles as real or fake.

---

## 🔍 Features
- Text preprocessing (cleaning, tokenization, stopword removal)
- Feature extraction using **TF-IDF**
- Classification using **Logistic Regression**
- Evaluation with accuracy, precision, recall, F1-score
- Confusion matrix visualization
- Easily extendable to advanced models like **BERT**, **SVM**, or **Random Forest**

---

## 📂 Folder Structure
```
📁 data/            → Dataset files (Fake.csv, True.csv)
📁 src/             → Source code for preprocessing and model
📊 outputs/         → Plots and evaluation results
📄 fake_news_detection.py → Main script for training & testing
```

---

## 📊 Model Performance
- Accuracy: ~95%
- High precision and recall on balanced test set
- Robust against overfitting on cleaned text data

---

## 📁 Dataset
[Kaggle - Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

---

## 🧠 Future Improvements
- Add deep learning models (LSTM, BERT)
- Use explainability tools like **SHAP**
- Deploy model via **Flask** or **Streamlit**

---

## 👨‍💻 Author
**Ritik Yadav** 
