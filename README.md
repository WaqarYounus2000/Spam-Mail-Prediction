# Spam-Mail-Prediction
spam-mail-detection-tfidf-logistic-regression


# Spam Mail Detection System (TF-IDF + Logistic Regression)

This project is a **Machine Learning based Spam Email Detection System** that classifies emails as **Spam or Ham (Not Spam)**.

The model uses **Natural Language Processing (NLP)** techniques to convert email messages into numerical features using **TF-IDF Vectorization**, and then applies **Logistic Regression** to classify the messages.

---

## Project Goal

The goal of this project is to demonstrate how **Machine Learning and NLP** can automatically detect spam emails by learning patterns from message text.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Jupyter Notebook

---

## Dataset

The dataset contains email messages with two columns:

| Column | Description |
|------|------|
| Category | Spam or Ham |
| Message | Email text content |

Example:

| Category | Message |
|------|------|
| ham | I'm going to the meeting tomorrow |
| spam | Congratulations! You won a free prize |

---

## Project Workflow

### 1️⃣ Data Loading

The dataset is loaded using Pandas.

```python
pd.read_csv("mail_data.csv")
