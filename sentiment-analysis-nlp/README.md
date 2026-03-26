# 🎬 Sentiment Analysis using NLP Pipeline

This project implements a **Natural Language Processing (NLP) pipeline** to classify movie reviews as **positive or negative**.

It demonstrates a complete workflow including **text preprocessing, TF-IDF vectorization, model training, and evaluation**.

---

## 🚀 Kaggle Notebook

👉 **View Full Notebook:**
https://www.kaggle.com/code/tushardobal/sentiment-analysis-using-nlp-pipeline ([Kaggle][1])

---

## 📊 Dataset

* IMDB Movie Reviews Dataset (50,000 reviews)
* Balanced dataset with equal positive and negative samples

---

## 🚀 Project Workflow

1. Data Loading
2. Text Preprocessing
3. TF-IDF Vectorization
4. Model Training
5. Model Evaluation
6. Model Comparison

---

## 🧠 Models Used

* Logistic Regression ✅ (Best Performing)
* Naive Bayes
* Random Forest

---

## 📈 Model Performance

| Model               | Accuracy   |
| ------------------- | ---------- |
| Logistic Regression | **88.36%** |
| Naive Bayes         | 84.78%     |
| Random Forest       | 84.73%     |

---

## 🔍 Key Insights

* Logistic Regression performs best on high-dimensional text data
* TF-IDF effectively converts text into numerical features
* Simpler models often outperform complex ones in NLP tasks

---

## ⚠️ Limitations

The model may misclassify neutral or mildly positive reviews (e.g., "interesting") due to weak sentiment signals.

---

## 🛠️ Tech Stack

* Python
* Scikit-learn
* Pandas
* NumPy
* NLP (TF-IDF)

---

## 👨‍💻 Author

**Tushar Dobal**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!

[1]: https://www.kaggle.com/code/tushardobal/sentiment-analysis-using-nlp-pipeline?utm_source=chatgpt.com "Sentiment Analysis using NLP Pipeline"
