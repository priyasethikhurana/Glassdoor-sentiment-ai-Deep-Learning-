# Glassdoor Sentiment AI 

This project evaluates **employee job satisfaction** using **deep learning models** on textual reviews from Glassdoor.  
The study compares **Bi-LSTM** and **DistilBERT**, integrating **SHAP (Shapley Additive Explanations)** to provide interpretability of model predictions.  

---

##  Project Overview
- **Objective**: Predict employee satisfaction (1–5 scale) using textual reviews, ratings, pros, and cons.  
- **Dataset**: Glassdoor employee reviews (pros, cons, ratings, job role, outlook, etc.).  
- **Models Used**:  
  - Bi-LSTM (baseline deep learning model)  
  - DistilBERT (lightweight transformer model)  
  - DistilBERT + SHAP (for explainable AI)  

---

##  Tech Stack
- **Language**: Python 3.10  
- **Frameworks**: TensorFlow 2.11, Keras, NumPy (<2.0), Pandas  
- **NLP**: HuggingFace Transformers (DistilBERT)  
- **Explainability**: SHAP  
- **Visualization**: Matplotlib, Seaborn, WordCloud  

---

## ⚙️ Methodology
1. **Data Preprocessing** – Cleaning, tokenization, encoding categorical features, handling missing values.  
2. **Modeling** – Multi-input Bi-LSTM and DistilBERT fusion models.  
3. **Evaluation** – Accuracy, F1-scores, Confusion Matrix, Class-level analysis.  
4. **Explainability** – SHAP values to identify key words influencing satisfaction predictions.  

---

## 📊 Key Results
- **Bi-LSTM**: Accuracy ~64%, strong at extremes, weaker on mid-satisfaction levels.  
- **DistilBERT**: Accuracy ~61%, better balance across classes, stronger in capturing subtle sentiments.  
- **DistilBERT + SHAP**: Adds transparency, highlighting words influencing predictions (e.g., *flexibility*, *workload*).  

---

##  Why This Matters
- Helps **job seekers** get unbiased insights about companies.  
- Assists **HR teams** in identifying satisfaction/dissatisfaction drivers.  
- Demonstrates **explainable AI** in real-world HR analytics applications.  

---

## 📈 Visual Insights
- Word clouds of pros/cons  
- Heatmaps of feature correlations  
- SHAP plots showing influential words  
- Trend analysis of satisfaction across roles & years  

---

## 📂 Project Structure
# Glassdoor-sentiment-ai-Deep-Learning-
An explainable deep learning framework for predicting employee job satisfaction from Glassdoor reviews. Compares Bi-LSTM and DistilBERT with SHAP for transparency in HR analytics.
