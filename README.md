# Bank Marketing Campaign Analysis — Mini Project

This project analyzes the UCI Bank Marketing Dataset to identify which customers are most likely to subscribe to a term deposit. 
The work includes exploratory data analysis (EDA), feature preprocessing, logistic regression modeling, clustering using K-Means, t-SNE visualization, and a final narrative report.

The goal is to understand both customer-level behavior and macroeconomic conditions that influence subscription decisions, and to build interpretable models that support targeted marketing strategies.

## 📁 Project Structure
ALEKSIEIEVA_DIANA_MINIPROJECT

requirements.txt #files for installing all required libraries

scratch/  # Drafts 

scratch/data-processing-eda.ipynb    # Notebook for cleaning, preprocessing, and EDA
scratch/modeling.ipynb               # Notebook for logistic regression, K-Means, t-SNE, metrics
        
final-report.ipynb                  # Narrative-style report with plots & conclusions

README.md                           # Project documentation

## 📊 Project Objectives

Identify which customers are most likely to subscribe to a term deposit.

Understand how customer attributes (age, job, marital status, education, contact behavior) influence outcomes.

Explore how macroeconomic factors (interest rates, employment variation, confidence index) shape subscription behavior.

Build and evaluate models using:

Logistic Regression (with recall optimization)

K-Means clustering 

PCA and t-SNE visualization

Create a final, interpretable report summarizing key findings and actionable insights.

## 🧠 Results 

Logistic regression with threshold identifies ~74% of true subscribers.

K-Means clustering captures only ~23% of subscribers.

Subscribers typically fall within the 30–50 age range, respond after 1–2 contacts, and tend to have recent prior interactions.

Subscription likelihood increases during:

Lower employment levels

Lower interest rates

Moderately low consumer confidence

## 📘 Dataset Justification

UCI Machine Learning Repository:
Bank Marketing Dataset (Portuguese Bank, 2008–2010)
https://archive.ics.uci.edu/dataset/222/bank+marketing

The Bank Marketing Dataset is well-suited for this analysis because it integrates customer demographic information with campaign characteristics and macroeconomic indicators over the 2008–2010 period. This structure allows for examination of how individual client attributes and broader economic conditions influence subscription decisions. The dataset contains 4,119 observations and 20 input features, providing sufficient variability for exploratory analysis and predictive modeling. The binary outcome variable enables modeling the probability of a customer subscribing to a term deposit (“yes” or “no”), making the dataset appropriate for classification-based analysis.

A key limitation is that the data covers only the recession period, which strongly affects customer decisions and may not generalize to stable or high-growth periods. 

## Run Instructions

1. Clone the repository

git clone ....
cd ALEKSIEIEVA_DIANA_MINIPROJECT

2. Install dependencies

pip install -r requirements.txt

3. Open Jupyter Notebook

final-report.ipynb
