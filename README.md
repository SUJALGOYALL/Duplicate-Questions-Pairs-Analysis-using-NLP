# 🤖 Duplicate Question Detection using Quora Dataset - NLP application

This project focuses on building a machine learning model to identify **duplicate questions** on Quora — questions that are phrased differently but mean the same thing. It uses Quora’s publicly released dataset containing over 400,000 question pairs.

---

## 📌 Problem Statement

Given two questions, determine whether they are semantically equivalent (i.e., duplicates). This task is critical for platforms like Quora to reduce redundancy and ensure that users access consistent, high-quality answers.

Example:
- “What is the most populous state in the USA?”
- “Which state in the United States has the most people?”

These questions are different in structure but share the same intent.

---

## 📁 Dataset Overview

- **Source**: [Quora First Dataset Release](https://data.quora.com/First-Quora-Dataset-Release-Question-Pairs)
- **Columns**:
  - `id`: Unique ID for the question pair
  - `qid1`, `qid2`: Unique IDs for each question
  - `question1`, `question2`: Text of each question
  - `is_duplicate`: Target variable (1 if duplicate, else 0)

---

## 🛠️ Project Workflow

1. **Data Cleaning**
   - Null value handling
   - Text preprocessing (lowercasing, punctuation removal, stopword removal)

2. **Exploratory Data Analysis (EDA)**
   - Distribution of duplicates vs. non-duplicates
   - Question frequency and length analysis

3. **Feature Engineering**
   - Text-based similarity features (TF-IDF, word overlap, fuzzy matching)
   - Embedding-based features (e.g., Word2Vec, GloVe)

4. **Modeling**
   - Machine learning models: Logistic Regression, Random Forest, XGBoost

5. **Evaluation**
   - Metrics: Accuracy, F1 Score, Precision, Recall
   - Confusion matrix and ROC curve

---

## 🧠 Technologies Used

- Python
- Pandas, NumPy
- NLTK / SpaCy
- Scikit-learn
- XGBoost

---

## 📊 Results

- Achieved accuracy of **79.2%** (among the top accuracies on this dataset)

---


## 🙏 Acknowledgements

- [Quora’s Dataset Announcement](https://data.quora.com/First-Quora-Dataset-Release-Question-Pairs)
- Thanks to Quora for enabling open research in semantic similarity tasks.

---

## 📬 Contact

For queries or collaboration:
**Sujal Goyal**  
IIIT Bhagalpur 
Email: sujalgoyal70@gmail.com  

