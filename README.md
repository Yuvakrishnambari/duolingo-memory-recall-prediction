**Duolingo Memory Recall Prediction**

A machine learning project to predict user recall probability on the Duolingo learning platform using Apache Spark, SparkML, and Python.
This project processes a large-scale dataset (~13M+ rows) and builds a scalable ML pipeline for spaced-repetition learning analysis.

**Project Overview**

The goal of this project is to estimate how likely a user is to remember a vocabulary item after a certain period of time, based on factors like:

*Time since last practice*

*Language metadata*

*User behavior*

*Lexeme difficulty*

*Learning session patterns*

This enables Duolingo-like systems to optimize personalized learning schedules using spaced repetition.

**Key Features**

Big-data processing using Apache Spark (Spark DataFrames)

Machine Learning pipeline using SparkML

Feature engineering for timestamp-based recall modeling

Model training & evaluation (Random Forest, Linear Regression, etc.)

Recall prediction (continuous value between 0–1)

Exploratory data analysis and schema inspection

**Repository Structure**
Duolingo Final Code File.ipynb     # Complete end-to-end ML pipeline & analysis
Duolingo Report.pdf                # Detailed project report & interpretation
README.md                          # Project documentation

**Technologies Used**

Python

Apache Spark (PySpark)

SparkML

Pandas, NumPy

Databricks environment

Modeling Summary

Preprocessing & feature engineering

Train-test split using Spark

**ML models:**

Linear Regression

Random Forest Regressor

Gradient-Boosted Trees

Evaluated using:

RMSE

MAE

R² Score

**Project Report**

A detailed explanation of methodology, results, and findings is provided in:

📎 [Duolingo Report.pdf](Duolingo%20Report.pdf)


**Author**

Yuva Narasimha Rao Nambari
Msc Data Science & Statistical Learning
yuvanarasimharao@gmail.com

LinkedIn: https://linkedin.com/in/yuva-narasimha-rao-nambari
This project was completed as part of a group academic assignment with contributions from team members.
