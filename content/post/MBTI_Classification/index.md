---

title: MBTI Classification
description: Personality Prediction with ML
date: 2025-03-10
image: mbtiprediction.jpg
categories:
    - Project
    - Graduate
tags:
    - machine learning
    - Python

---

# MBTI Personality Prediction Project

This project was developed with the goal of **automating MBTI personality type predictions** using user-generated text.

---

##  Problem Statement

Traditional MBTI personality assessments rely on **self-reports**, which can be subjective and biased.  
**Goal**: Predict personality types based on text data, offering a scalable and objective solution for:

- Recruitment & candidate-job fit
- Personalized recommendations
- Mental health applications
- Ad targeting & behavioral analysis

---

##  Workflow

**1. Data Cleaning**  
- Tokenization  
- Removal of URLs, special characters, stopwords  

**2. Feature Engineering**  
- Traditional: TF-IDF  
- Deep Learning: Token Embeddings  

**3. Model Training**  
- Compared Logistic Regression, Random Forest, and GRU (deep learning)  

**4. Evaluation Metrics**  
- Accuracy, Precision, F1-score  
- Stratified train/test split to reduce class imbalance impact  

**5. Deployment Consideration**  
- API-based prediction system for scalable real-time usage

---

##  Models & Performance

| Model              | Accuracy | Precision | F1-score |
|-------------------|----------|-----------|----------|
| Logistic Regression | 0.6406   | 0.66      | 0.64     |
| Random Forest       | 0.6083   | 0.64      | 0.59     |
| GRU (Deep Learning) | **0.6486**   | **0.7974**   | N/A      |

- **Logistic Regression**: Fast, interpretable, but weak in semantic nuance  
- **Random Forest**: Great for short-texts and robust to overfitting  
- **GRU**: Best for long-form text like Reddit posts and job applications

---

##  Insights

- GRU provided the best accuracy and is suited for real-world, high-stakes predictions  
- Logistic Regression still performs well in constrained environments  
- Wordcloud visualizations helped illustrate key lexical differences between personality types  

---

##  Future Improvements

-  Add more data, especially underrepresented MBTI types (e.g., INFJ)  
-  Try BERT/RoBERTa for better context modeling  
-  Use SMOTE to balance class distribution  
-  Incorporate user metadata (likes, shares, activity patterns)  

---

##  Business Impact

- Scalable pipeline to support AI-driven hiring platforms  
- Enables real-time personalization for apps & services  
- Bridges psychology and machine learning in a production-ready format  

---

📎 **PDF Slide Deck**: [MBTI Classification Report](MBTI_Classification_VickiYE.pdf)  
💻 **Code Repository**: [MBTI Classification Code](VickiYE_mbtiprediction.ipynb)