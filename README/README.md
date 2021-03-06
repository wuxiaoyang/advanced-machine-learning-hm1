# Advanced-Machine-Learning Homework 1
## Logistic Regression Implementation

**Introduction**

This repository contains homework No.1 during course "Advanced Machine Learning".

Goal of Homework 1 is to implement logistic regression to classify the given set of documents as one of two classes "+1 or -1".

+ Documents are from two news groups:
	- Hockey
	- Baseball

+ Document Structure
	- From (email address)
	- Subject
	- Body

+ Partitioned into 5 subsets (s1-s5) for cross validation

We can extract features from raw texts using many methods, like:

- Bag of words
- Tf-idf weighting

In fact, I use TF-IDF method to get features.

**Execution**

python extract_feature.py
python logistic.py

**Modules**

+ logistic.py ------ Logistic Regression Module
+ extract_feature.py ------ TF-IDF feature-extraction Module

**Performance**

+ Average Precision : about 0.97
+ Average Recall : about 0.985
+ F1 Score : about 0.98

**GitHub links**

https://github.com/wuxiaoyang/advanced-machine-learning-hm1
