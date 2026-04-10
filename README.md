# 🤖 AI-Based Peer-to-Peer Knowledge Matching System

## 📌 Overview
This project is an AI-powered system that connects learners with suitable peers based on their skills, interests, and experience levels. It uses Natural Language Processing (NLP) and Machine Learning techniques to recommend the most compatible peers for collaborative learning.

---

## 🎯 Objectives
- Develop an intelligent peer matching system  
- Apply NLP techniques for analyzing user profiles  
- Use Machine Learning (KNN) for similarity-based recommendations  
- Rank users based on compatibility scores  
- Support recommendations for new users  

---

## 🧠 Methodology

### 🔹 Data Collection
- Synthetic dataset of user profiles  
- Includes: Name, Skills, Interests, Experience Level  

### 🔹 Data Preprocessing
- Text cleaning (lowercase, tokenization)  
- Stopword removal  
- Feature preparation  

### 🔹 Feature Extraction
- TF-IDF Vectorization  
- Converts text into numerical feature vectors  

### 🔹 Model Implementation
- K-Nearest Neighbors (KNN)  
- Cosine Similarity (primary metric)  
- Euclidean Distance (comparison metric)  

### 🔹 Recommendation System
- Finds top-K similar users  
- Displays similarity scores  
- Provides explainable results using common skills  

### 🔹 New User Recommendation
- Accepts dynamic input  
- Generates recommendations without retraining  

---

## ⚙️ Technology Stack
- **Programming Language:** Python  
- **Libraries:** pandas, NumPy, scikit-learn  
- **Tools:** Google Colab / VS Code  
- **Dataset:** Synthetic CSV dataset  

---

## 📊 Features
- AI-based peer matching  
- Explainable recommendations  
- Multiple similarity metrics  
- Clean tabular output  
- Supports new users  

