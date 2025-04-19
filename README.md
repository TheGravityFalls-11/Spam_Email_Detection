# 📧 Spam Email Detection using Naive Bayes

This project implements a **Spam Email Classifier** using the **Naive Bayes algorithm** with `scikit-learn`. It uses **text vectorization** (Bag of Words via `CountVectorizer`) and builds a pipeline for efficient prediction.

---

## 🚀 Features

- Preprocessing of text data using `CountVectorizer`
- Classification using `MultinomialNB` (Naive Bayes)
- High accuracy (>98%) on test data
- Uses `Pipeline` for simplified model building and prediction

---

## 🧠 Algorithms Used

- **Text Vectorization:** CountVectorizer (Bag of Words)
- **Classifier:** Multinomial Naive Bayes

---

## 📁 Dataset

The dataset contains two columns:

| Category | Message |
|----------|---------|
| ham      | Normal (non-spam) message |
| spam     | Unwanted promotional or scam message |

---

##📦 Dependencies
pip install pandas scikit-learn

---

##📌 Conclusion
This project demonstrates how to classify emails as spam or ham using a simple and powerful Naive Bayes approach. With a proper dataset and text preprocessing, it achieves high accuracy and can be integrated into real-world applications like spam filters.

---

##📃 License
This project is open-source and free to use under the MIT License.
