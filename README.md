# MessageIntelligenceSystem
Spam Message Classification using K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Gaussian Naive Bayes, Probability Analysis, ROC-AUC, and Machine Learning with Python and Scikit-learn.
# Spam Message Classification using Machine Learning

## Project Overview

This project focuses on building an intelligent spam message classification system using supervised machine learning algorithms. The objective is to classify messages as **Spam** or **Legitimate** based on message content and extracted numerical features.

The project demonstrates the implementation and comparison of K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Gaussian Naive Bayes classifiers using Python and Scikit-learn.

---

## Problem Statement

Spam messages are one of the major challenges in modern communication systems. This project aims to develop a machine learning model capable of automatically classifying incoming messages as spam or legitimate.

---

## Dataset Information

The dataset contains approximately **5200 messages** with features including:

- message_id
- message_text
- message_length
- word_count
- num_urls
- num_digits
- num_special_chars
- spam_keyword_score
- legit_keyword_score
- sender_activity_score
- sender_account_age_days
- messages_sent_last_24h
- timestamp
- hour_of_day
- day_of_week
- spam_label (Target Variable)

Target Variable:

- 0 → Legitimate Message
- 1 → Spam Message

---

## Project Workflow

### Part A – Theory

- Conditional Probability
- Bayes' Theorem
- Naive Bayes Classifier
- K-Nearest Neighbors
- Support Vector Machine

---

### Part B – Data Preparation

- Dataset Loading
- Data Exploration
- Missing Value Analysis
- Train-Test Split
- Feature Scaling

---

### Part C – K-Nearest Neighbors (KNN)

- Baseline KNN Model
- Multiple K Value Comparison
- Distance Metric Analysis
- Misclassified Message Analysis

---

### Part D – Support Vector Machine (SVM)

- Linear Kernel
- RBF Kernel
- Support Vector Analysis
- Comparison with KNN

---

### Part E – Naive Bayes

- Gaussian Naive Bayes
- Conditional Probability
- Bayes' Theorem Demonstration
- Probability-Based Classification

---

### Part F – Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score

---

### Part G – Final Analysis

- Model Comparison
- Strengths and Weaknesses
- Business Recommendation
- Final Model Selection

---

## Machine Learning Algorithms

- K-Nearest Neighbors (KNN)
- Support Vector Machine (Linear)
- Support Vector Machine (RBF)
- Gaussian Naive Bayes

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

---

## Visualizations

The project includes:

- Spam Message Distribution
- Correlation Heatmap
- Confusion Matrix
- ROC Curve
- Accuracy Comparison
- Precision Comparison
- Recall Comparison
- F1 Score Comparison
- ROC-AUC Comparison
- Distance Metric Comparison

---

## Python Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Learning Outcomes

After completing this project, the following concepts were understood:

- Binary Classification
- K-Nearest Neighbors
- Support Vector Machine
- Gaussian Naive Bayes
- Bayes' Theorem
- Conditional Probability
- Feature Scaling
- Model Evaluation
- ROC-AUC Analysis
- Distance Metrics

---

## Conclusion

This project successfully developed a spam message classification system using K-Nearest Neighbors, Support Vector Machine, and Gaussian Naive Bayes classifiers. Each model was evaluated using Accuracy, Precision, Recall, F1 Score, Confusion Matrix, and ROC-AUC. The Support Vector Machine with the RBF kernel achieved the best overall performance due to its ability to classify complex patterns effectively. Gaussian Naive Bayes provided fast and efficient predictions for text classification, while KNN demonstrated reliable performance for smaller datasets. The project highlights the importance of selecting an appropriate classification algorithm based on both predictive performance and computational efficiency.

---

## Repository Structure

```
Spam-Message-Classification/
│
├── Spam_Message_Classification.ipynb
├── Message_Intelligence_Dataset_5200.xlsx
├── README.md
├── images/
└── requirements.txt
```

---

## Author

**Nandani Rajput**

B.Tech Computer Science Engineering

GLS University
