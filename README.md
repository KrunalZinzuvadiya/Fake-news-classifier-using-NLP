# Fake News Detection using Machine Learning

## Overview
This project applies Natural Language Processing (NLP) and Machine Learning techniques to detect fake news articles. The model is trained on a dataset of real and fake news articles and classifies news as **fake** or **real** based on textual content.

## Features
- **Data Preprocessing:**  
  - Cleaning and tokenizing text data.  
  - Removing stop words and punctuation.  
  - Converting text into numerical representations using TF-IDF.  

- **Machine Learning Models Used:**  
  - Logistic Regression  
  - Naïve Bayes  
  - Support Vector Machine (SVM)  
  - Random Forest Classifier  

- **Performance Evaluation:**  
  - Accuracy, Precision, Recall, and F1-score metrics used to assess model performance.  
  - Comparison of different ML models to determine the best-performing classifier.  

## Dataset
The dataset consists of labeled news articles categorized as:
- **Fake News (1)** – Misleading or fabricated information.  
- **Real News (0)** – Authentic and factual articles.  

## Dependencies
Install the required Python libraries using:

```bash
pip install numpy pandas matplotlib seaborn nltk scikit-learn
