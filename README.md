# Introduction to Machine Learning with Python

## Code Reproduction + Theoretical Deep Dive

### Author
**Sulthon Arif Imadudin**  
S1 Teknik Komputer - Telkom University

### Course
Machine Learning & Deep Learning Enrichment Assignment

### Reference Book
**Introduction to Machine Learning with Python: A Guide for Data Scientists**  
Andreas C. Müller & Sarah Guido  
O'Reilly Media

---

# Repository Overview

This repository contains code reproduction, chapter summaries, theoretical explanations, and practical implementations based on the book *Introduction to Machine Learning with Python*.

The objective of this project is to strengthen both theoretical understanding and practical skills in Machine Learning using Python and Scikit-Learn.

All chapters have been reproduced in Google Colab/Jupyter Notebook format and include:

- Chapter Summary
- Theoretical Explanation
- Code Reproduction
- Experiment Results
- Chapter Conclusion

---

# Topics Covered

## Chapter 1 - Introduction

Topics:

- What is Machine Learning
- Supervised Learning
- Unsupervised Learning
- Features and Labels
- Train-Test Split
- K-Nearest Neighbors (KNN)

Implementation:

- NumPy Basics
- Pandas DataFrame
- Iris Dataset
- Train-Test Split
- KNN Classification

---

## Chapter 2 - Supervised Learning

Topics:

- Classification
- Regression
- Generalization
- Overfitting
- Underfitting

Algorithms:

- K-Nearest Neighbors (KNN)
- Linear Regression
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Neural Network (MLP)

Implementation:

- Breast Cancer Dataset
- Diabetes Dataset
- Model Comparison

---

## Chapter 3 - Unsupervised Learning and Preprocessing

Topics:

- Data Preprocessing
- Feature Scaling
- Dimensionality Reduction
- Clustering

Algorithms:

- StandardScaler
- Principal Component Analysis (PCA)
- K-Means
- Agglomerative Clustering
- DBSCAN

Implementation:

- Iris Dataset
- PCA Visualization
- Clustering Analysis

---

## Chapter 4 - Representing Data and Engineering Features

Topics:

- Feature Engineering
- Categorical Variables
- One-Hot Encoding
- Polynomial Features
- Feature Selection

Implementation:

- Pandas get_dummies()
- PolynomialFeatures
- SelectKBest

---

## Chapter 5 - Model Evaluation and Improvement

Topics:

- Cross Validation
- Hyperparameter Tuning
- Grid Search
- Evaluation Metrics

Techniques:

- Cross Validation
- GridSearchCV
- Confusion Matrix
- Classification Report
- Accuracy Evaluation

Implementation:

- KNN Optimization
- Model Evaluation

---

## Chapter 6 - Algorithm Chains and Pipelines

Topics:

- Pipeline
- Data Leakage
- Workflow Automation
- Hyperparameter Optimization

Implementation:

- Pipeline
- make_pipeline
- Pipeline + GridSearchCV
- SVM Classification

---

## Chapter 7 - Working with Text Data

Topics:

- Natural Language Processing (NLP)
- Bag of Words
- TF-IDF
- N-Grams
- Topic Modeling

Algorithms:

- CountVectorizer
- TfidfVectorizer
- Latent Dirichlet Allocation (LDA)

Implementation:

- Text Vectorization
- Topic Discovery
- Word Frequency Analysis

---

## Chapter 8 - Wrapping Up

Topics:

- End-to-End Machine Learning Workflow
- Humans in the Loop
- Production Machine Learning
- Data Drift
- Future Learning Path

Discussion:

- Deployment
- Monitoring
- MLOps
- Advanced Learning Roadmap

---

# Libraries Used

This project utilizes the following Python libraries:

```python
numpy
pandas
matplotlib
scikit-learn
scipy
```

---

# Machine Learning Workflow

```text
Problem Definition
        ↓
Data Collection
        ↓
Data Preprocessing
        ↓
Feature Engineering
        ↓
Model Selection
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Deployment
        ↓
Monitoring
```

---

# Key Learning Outcomes

After completing this project, the following concepts were successfully learned and implemented:

### Machine Learning Fundamentals

- Supervised Learning
- Unsupervised Learning
- Classification
- Regression

### Data Processing

- Data Cleaning
- Feature Engineering
- Data Scaling
- Dimensionality Reduction

### Model Development

- KNN
- Logistic Regression
- Decision Tree
- Random Forest
- SVM
- Neural Networks

### Model Evaluation

- Accuracy
- Precision
- Recall
- F1 Score
- Cross Validation
- Grid Search

### Advanced Topics

- Pipelines
- Text Processing
- Topic Modeling

---

# Repository Structure

```text
Introduction-to-Machine-Learning-with-Python/
│
├── README.md
│
├── Chapter01_Introduction.ipynb
├── Chapter02_Supervised_Learning.ipynb
├── Chapter03_Unsupervised_Learning_and_Preprocessing.ipynb
├── Chapter04_Representing_Data_and_Engineering_Features.ipynb
├── Chapter05_Model_Evaluation_and_Improvement.ipynb
├── Chapter06_Algorithm_Chains_and_Pipelines.ipynb
├── Chapter07_Working_with_Text_Data.ipynb
└── Chapter08_Wrapping_Up.ipynb
```

---

# Conclusion

This repository demonstrates the implementation of fundamental Machine Learning concepts presented in *Introduction to Machine Learning with Python*.

Through theoretical study and practical code reproduction, various Machine Learning techniques were explored, including supervised learning, unsupervised learning, feature engineering, model evaluation, pipelines, and natural language processing.

The project serves as a solid foundation for further study in:

- Deep Learning
- Computer Vision
- Natural Language Processing
- Reinforcement Learning
- MLOps

---

# References

Müller, A. C., & Guido, S. (2017).

*Introduction to Machine Learning with Python: A Guide for Data Scientists.*

O'Reilly Media.
