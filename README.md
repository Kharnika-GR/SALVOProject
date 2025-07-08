# 🧠 Automated Short Answer Grading System

This is the final draft notebook for an **Automated Short Answer Grading (ASAG)** project developed during my internship at **SALVO – the AI Club of SASTRA University**. The system aims to evaluate students' descriptive answers automatically by comparing them with model (ideal) answers using NLP techniques.

## 📌 Project Overview

The goal of this project is to reduce the manual effort required in grading short answers, ensuring faster and consistent evaluation. The system compares a student's answer with a reference answer and generates a similarity-based score.

### ✨ Key Features:
- Input: A question, a model answer, and one or more student answers.
- Output: A similarity score (normalized between 0 and 1 or converted to marks).
- Evaluation: Cosine similarity, TF-IDF, and semantic matching using NLP models.

## 🛠️ Tools & Libraries Used

- Python (Jupyter Notebook)
- **NLTK** – Natural Language Toolkit
- **Scikit-learn** – for TF-IDF vectorization and cosine similarity
- **Pandas** – for data handling
- **NumPy** – for numerical computations
- Optional: **spaCy**, **BERT embeddings** (for future improvements)

## 🔍 How It Works

1. **Preprocessing**  
   - Tokenization, lowercasing, stopword removal, stemming/lemmatization.
2. **Vectorization**  
   - Transform model and student answers using **TF-IDF**.
3. **Similarity Calculation**  
   - Use **cosine similarity** to compare the vectors.
4. **Scoring**  
   - Convert similarity score to a mark (e.g., 0–5 scale).

## 📈 Sample Output

| Question ID | Model Answer | Student Answer | Score |
|-------------|--------------|----------------|-------|
| Q1          | Gravity pulls objects... | Gravity is the force... | 4.5/5 |

## 🚀 Future Scope

- Integrating **semantic similarity models** like BERT, RoBERTa.
- Building a web-based grading UI with Flask/Streamlit.
- Support for multiple model answers or rubrics.
- Multi-lingual short answer grading.

## 🧑‍💻 Author

**Kharnika G R**  
SASTRA University  
[GitHub Profile](https://github.com/Kharnika-GR)


