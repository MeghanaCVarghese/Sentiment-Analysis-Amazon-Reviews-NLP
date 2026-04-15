# 🛍️ Sentiment Analysis on Amazon Reviews (NLP)

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-green)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-orange)
![Model](https://img.shields.io/badge/Model-Logistic%20Regression-yellow)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Dataset](https://img.shields.io/badge/Dataset-Amazon%20Reviews-blueviolet)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![NLTK](https://img.shields.io/badge/NLTK-NLP-lightgrey)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-teal)

---

## 📌 About the Project

This project focuses on **Sentiment Analysis using Natural Language Processing (NLP)** to classify Amazon product reviews as **Positive or Negative**.

In real-world e-commerce platforms, customer reviews play a crucial role in:
- 📊 Monitoring product performance  
- ⚠️ Detecting negative feedback early  
- 😊 Improving customer satisfaction  

This system automates sentiment detection using **TF-IDF vectorization** and **Logistic Regression**, making it scalable for large volumes of reviews.

---

## 🎯 Business Problem

Ratings alone may not reflect true sentiment. For example:
- ⭐⭐⭐⭐⭐ with negative text  
- ⭐⭐ with positive wording  

👉 This project solves that by analyzing **actual review text**.

---

## 📂 Dataset Information

- 📊 **10,000 Amazon reviews**
- 🏷️ Labels:
  - `pos` → Positive
  - `neg` → Negative

### Columns:
- `label` → Sentiment category  
- `review` → Raw customer review text  

---

## ⚙️ Project Workflow

### 1️⃣ Data Cleaning
- Removed missing values and duplicates  
- Converted text to lowercase  
- Removed punctuation and stopwords  

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Sentiment distribution visualization  
- WordClouds for:
  - Positive reviews  
  - Negative reviews  

---

### 3️⃣ Text Vectorization
- Applied **TF-IDF Vectorization**
- Converted text into numerical features  

---

### 4️⃣ Model Building
- Algorithm: **Logistic Regression**
- Train-test split: 80-20  

---

### 5️⃣ Model Evaluation
- Accuracy Score  
- Classification Report  
- Confusion Matrix  

---

## 📈 Results

- ✅ Model achieved strong accuracy on test data  
- ✅ Balanced performance for both classes  
- ✅ Successfully predicts sentiment of unseen reviews  

---

## 🔍 Example Predictions

"The product quality is amazing!" → Positive  
"Worst purchase ever" → Negative

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* NLTK (Text Processing)
* Scikit-learn (ML Model)
* Matplotlib & Seaborn (Visualization)
* WordCloud

---

## ▶️ How to Run

### Clone the repository
git clone https://github.com/MeghanaCVarghese/Sentiment-Analysis-Amazon-Reviews.git

### Navigate to folder
cd Sentiment-Analysis-Amazon-Reviews

### Install dependencies
pip install -r requirements.txt

### Run Jupyter Notebook
jupyter notebook

---

## 👩‍💻 Author

Meghana C Varghese
