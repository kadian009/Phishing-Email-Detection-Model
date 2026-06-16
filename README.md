# Phishing-Email-Detection-Model

A machine learning-based security tool that detects and classifies emails into **Phishing** or **Safe** categories using Natural Language Processing (NLP) techniques. 

This project utilizes a TF-IDF (Term Frequency-Inverse Document Frequency) pipeline alongside a Logistic Regression classifier to analyze textual content and structural patterns (like suspicious URLs and urgent keywords).

## 🚀 Key Features

 **Text & URL Analysis:** Tokenizes text and parses keyword highlights (e.g., "URGENT", "verify", "compromised").

 **Machine Learning Pipeline:** Implements Scikit-Learn's `TfidfVectorizer` and `LogisticRegression` for optimized, lightweight classification.
  **Evaluation Metrics:** Outputs model accuracy scores, full classification reports, and a visual confusion matrix.
  **Interactive Predictions:** Includes an inference function to test custom, unseen email strings instantly.

## 🛠️ Tech Stack & Dependencies
  **Language:** Python 3.8+
  **Libraries:**
  * `pandas` (Data manipulation)
  * `scikit-learn` (Machine learning & text vectorization)
  * `matplotlib` & `seaborn` (Data visualization)

Output :
<img width="505" height="393" alt="17815984634965123642541091290849" src="https://github.com/user-attachments/assets/3abfaafe-5b9f-4cda-95b0-1fdf7521219c" />

Mase by Yuvraj 
