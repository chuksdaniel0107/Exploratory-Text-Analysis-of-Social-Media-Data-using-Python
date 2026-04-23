# Exploratory Text Analysis of Social Media Data using Python

## 📌 Overview

This project performs exploratory text analysis on a dataset of social media posts. The objective is to clean and process unstructured text data, extract meaningful insights, and visualise key patterns using Natural Language Processing (NLP) techniques.

The analysis includes text preprocessing, word frequency analysis, and visualisation using word clouds and statistical plots.

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* NLTK
* WordCloud

---

## 📂 Dataset

The dataset is provided in JSON format and contains:

* Text content of posts
* Category labels
* Timestamps

---

## ⚙️ Project Workflow

### 1. Data Loading

* Loaded JSON dataset using Python
* Converted data into a Pandas DataFrame
* Parsed date column into datetime format

### 2. Data Exploration

* Analysed distribution of categories using count plots
* Identified dominant classes in the dataset

### 3. Text Preprocessing

* Removed:

  * Mentions (@user)
  * Hashtags (#topic)
  * URLs
  * Special characters
* Converted text to lowercase
* Removed stopwords using NLTK

### 4. Text Analysis

* Combined cleaned text into a single corpus
* Calculated word frequencies using Python collections

### 5. Data Visualisation

* Category distribution using Seaborn
* Word Cloud to highlight common terms
* Bar chart showing top 10 most frequent words

---

## 📊 Key Insights

* Identified the most frequent words used across posts
* Visualised dominant topics through word cloud representation
* Observed distribution imbalance across categories

---

## 🚀 How to Run the Project

1. Install required libraries:
   pip install pandas matplotlib seaborn nltk wordcloud

2. Download NLTK stopwords:
   import nltk
   nltk.download('stopwords')

3. Run the notebook or Python script

---

## 📈 Future Improvements

* Add sentiment analysis
* Implement topic modelling (e.g., LDA)
* Build a machine learning model for text classification
* Deploy as an interactive dashboard
