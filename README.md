# Amazon E-commerce Data Mining Project

This repository contains my implementation of the **Data Mining Techniques (2024–2025)** course project at the National and Kapodistrian University of Athens (NKUA).  
The project applies **data mining and machine learning methods** to the **Amazon Product Reviews dataset**, showcasing skills in preprocessing, feature engineering, clustering, recommendation systems, and sentiment analysis.

---

## Project Overview

The objective of this project was to extract insights from Amazon reviews and design intelligent systems that improve product understanding, customer experience, and personalized recommendations.

The project was divided into two main phases:

### Part A — Data Preprocessing & Feature Engineering
- **Data Extraction**: Selected product categories from the [Amazon Reviews 2023 dataset](https://huggingface.co/datasets/McAuley-Lab/Amazon-Reviews-2023).  
- **Data Cleaning**: Removed missing values, normalized price information, and preprocessed review text.  
- **Exploratory Data Analysis (EDA)**: Visualized rating distributions, review volumes, and sentiment patterns.  
- **Feature Engineering**:  
  - Created **sentiment scores** using VADER.  
  - Generated word clouds and text-based features.  
  - Constructed price-related and normalized rating metrics.  

### Part B — Machine Learning Applications
1. **Clustering for Product Grouping**  
   - Applied **K-Means** clustering on product features.  
   - Reduced dimensionality using **PCA** for visualization.  
   - Evaluated clusters with the **Silhouette Score**.  

2. **Recommendation Systems**  
   - Implemented a **Content-Based Filtering** approach using TF-IDF and cosine similarity.  
   - Generated personalized recommendations based on review content and product similarity.  

3. **Sentiment Analysis (Classification Task)**  
   - Preprocessed review texts with **NLTK** (tokenization, lemmatization, stopword removal).  
   - Converted text into vectors using **TF-IDF** and **Word2Vec** embeddings.  
   - Trained and evaluated multiple classifiers: **Naive Bayes, KNN, SVM, Random Forests**.  
   - Used **cross-validation** and metrics (Accuracy, Precision, Recall, F1-score) to assess performance.  

---
