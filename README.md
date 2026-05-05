# 📧 Spam Detection using Logistic Regression

## 📌 Project Overview

This project implements a **Spam Detection System** using **Machine Learning (Logistic Regression)**.
The model classifies SMS messages as:

* ✅ **Ham (Not Spam)**
* 🚫 **Spam**

The system uses **TF-IDF (Term Frequency - Inverse Document Frequency)** to convert text data into numerical features and then trains a classification model.

---

## 🎯 Objectives

* Convert text messages into numerical format
* Train a machine learning model for classification
* Evaluate model performance
* Visualize results using graphs and word clouds

---

## 🗂️ Dataset

* File used: `datasetspam.csv`
* Important columns:

  * `text` → Message content
  * `label_num` → Target label (0 = Ham, 1 = Spam)

---

## ⚙️ Technologies Used

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* WordCloud

---

## 🚀 Workflow

### 1. Data Loading

* Dataset is loaded using Pandas
* Only relevant columns are selected

### 2. Data Preprocessing

* Renaming columns:

  * `text` → `message`
  * `label_num` → `label`

### 3. Feature Extraction

* Used **TF-IDF Vectorizer**
* Converts text into numerical form

### 4. Model Training

* Algorithm: **Logistic Regression**
* Data split into:

  * 80% Training
  * 20% Testing

### 5. Prediction

* Model predicts whether a message is spam or not

### 6. Evaluation

* Accuracy Score
* Confusion Matrix

### 7. Visualization

* Confusion Matrix Plot 📊
* WordCloud for:

  * Spam messages ☁️
  * Ham messages ☁️

---

## 📊 Results

* ✔️ High accuracy (~95%+ depending on dataset)
* ✔️ Effective classification of spam messages
* ✔️ Clear visualization of important words

---

## 🧪 Example Prediction

**Input:**

```
Congratulations! You won a free prize
```

**Output:**

```
Spam
```

---

## 📷 Visualizations Included

* Confusion Matrix
* Spam WordCloud
* Ham WordCloud

---

## 💡 Key Concepts Used

* Logistic Regression
* Text Vectorization (TF-IDF)
* Classification
* Data Visualization

---

## ▶️ How to Run

1. Install dependencies:

```
pip install numpy pandas matplotlib scikit-learn wordcloud
```

2. Run the Python file:

```
python spam_detection.py
```

---

## 📈 Future Improvements

* Use Deep Learning (LSTM, BERT)
* Build Web App (Streamlit)
* Add real-time spam detection
* Improve accuracy with advanced NLP

---

## 👨‍💻 Author
AAYUSHMAN CHOUHAN


---

## ⭐ Conclusion

This project demonstrates how machine learning can be used to solve real-world problems like **spam detection** effectively using simple and efficient algorithms.
