Detecting Cyberbullying Against Bangladeshi Sportsmen
A Machine Learning–Based Analysis Across Social Media Platforms
📌 Overview

This repository contains the implementation of a machine learning–based system for detecting cyberbullying in Bangla social media comments targeting Bangladeshi sportsmen. The study focuses on supervised learning techniques applied to real-world data collected from social media platforms related to cricket and football.

The project is conducted as part of an MSc thesis in Computer Science and Engineering (Data Science).

🎯 Objectives

Detect and classify cyberbullying content written in Bangla.

Analyze linguistic patterns used in abusive and toxic comments.

Compare the performance of multiple supervised machine learning models.

Support automated moderation and safer online environments.

🗂 Dataset

Source: Social media comments (Facebook)

Domain: Cricket and football–related posts

Language: Bangla

Classes:

Normal

Toxic

Note: Duplicate entries were removed, and extensive text preprocessing was applied.

⚙️ Methodology
1. Data Preprocessing

Removal of URLs, emojis, mentions, hashtags, digits, and English words

Retention of Bangla Unicode characters only

Tokenization using Bangla-aware regex

Stopword removal

2. Feature Extraction

TF-IDF Vectorization

Unigram and bigram features

3. Machine Learning Models

The following supervised models were implemented and evaluated:

Logistic Regression

Linear Support Vector Classifier (LinearSVC)

Random Forest

XGBoost

K-Nearest Neighbors (KNN)

4. Evaluation Metrics

Accuracy

Precision

Recall

F1-score

Confusion Matrix

🧪 Experiments

Train–test split with stratified sampling

Class imbalance handled using class weighting

Best-performing model saved using joblib

🏆 Results

The models were compared based on Accuracy and Weighted F1-score, and the best-performing pipeline was selected and saved for deployment or future use.

🧑‍💻 My Role

I developed the complete project, including data preprocessing, feature extraction, model implementation, and evaluation. I also conducted all experiments and authored the full thesis report and documentation.
