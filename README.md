# Sentiment-Analysis-on-Nepali-text

# Nepali Text Sentiment Analysis using SVM

This project implements a **Sentiment Analysis system for Nepali text** using the **Support Vector Machine (SVM)** algorithm.  
It classifies any Nepali sentence into **Positive**, **Negative**, or **Neutral** sentiment categories.

---

##  Features

-  Preprocessing of Nepali text (cleaning, tokenization, stopword removal)  
-  TF-IDF vectorization for text representation  
-  SVM classifier for high-accuracy sentiment prediction  
-  Handles Unicode Nepali text effectively  
-  Predicts sentiment of custom user input  

---

##  Project Architecture

1. **Data Collection**  
   Nepali text sentences with labeled sentiments (positive/negative/neutral).

2. **Data Preprocessing**  
   - Lowercasing  
   - Removal of punctuation, numbers, and special symbols  
   - Tokenization  
   - Stopword removal  

3. **Feature Extraction**  
   - TF-IDF (Term Frequency–Inverse Document Frequency)  
   - Produces a sparse numeric representation of Nepali sentences  

4. **Model Training**  
   - Support Vector Machine (SVM) with linear or RBF kernel  
   - Hyperparameter tuning using GridSearchCV (optional)

5. **Model Evaluation**  
   - Accuracy  
   - Precision, Recall, F1-score  
   - Confusion Matrix  

6. **Prediction**  
   - Input any Nepali text  
   - Model outputs: **Positive / Negative / Neutral**

---

