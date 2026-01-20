# Fake News Detection using Deep Learning (NLP)

## 📌 Project Overview
This project focuses on detecting **fake vs real news articles** using **Natural Language Processing (NLP)** and **Deep Learning** techniques.  
The goal is to build a text classification system that can automatically identify whether a given news article is fake or real based on its content.

---

## 🧠 Problem Statement
With the rapid spread of misinformation on digital platforms, identifying fake news has become a critical challenge.  
This project aims to address this problem by training a deep learning model on labeled news data.

---

## 📊 Dataset
- **Source:** Kaggle – Fake and Real News Dataset  
- **Files Used:**
  - `Fake.csv` – Fake news articles  
  - `True.csv` – Real news articles  
- **Features:** News title, text, subject, date  
- **Target:** Fake / Real label  

---

## ⚙️ Approach
1. **Data Cleaning & Preprocessing**
   - Text normalization
   - Tokenization
   - Stopword removal
2. **Exploratory Data Analysis (EDA)**
   - Distribution of fake vs real news
   - Text length analysis
3. **Model Building**
   - Deep Learning model using LSTM
   - Word embeddings for text representation
4. **Model Evaluation**
   - Accuracy and loss monitoring
5. **Deployment**
   - Flask-based web application for prediction

---

## 🛠️ Technologies Used
- **Programming:** Python  
- **Libraries:** NumPy, Pandas, NLTK  
- **Deep Learning:** TensorFlow / Keras (LSTM)  
- **Visualization:** Matplotlib, Seaborn  
- **Web App:** Flask  
- **Tools:** Jupyter Notebook, Git, GitHub  

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Gakshat12/fake-news-detection.git
