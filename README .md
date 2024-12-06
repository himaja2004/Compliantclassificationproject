
# Compliant Classification – Marriott Hotels

## Project Overview

This project implements a machine learning-based classification system to analyze customer reviews and categorize complaints for Marriott Hotels. The goal is to identify key areas of improvement in service quality and customer satisfaction using automated feedback analysis.

---

## Features

1. **Data Collection**: 
   - Customer reviews were collected using web scraping with Selenium.
   - The dataset includes reviews, ratings, customer details, and other metadata.

2. **Data Preprocessing**:
   - Text cleaning, stop word removal, and lemmatization were applied.
   - Reviews were tokenized and converted into structured formats for analysis.

3. **Topic Modeling**:
   - Latent Dirichlet Allocation (LDA) and Non-Negative Matrix Factorization (NMF) were used for extracting topics from reviews.

4. **Multi-label Classification**:
   - Reviews were categorized into multiple complaint types: 
     - Product-related
     - Service-related
     - Payment-related
     - Technical issues
   - TF-IDF features were used for feature extraction.
   - Models implemented: Logistic Regression, Random Forest, Support Vector Classifier, and Multinomial Naive Bayes.

5. **Evaluation**:
   - Metrics like precision, recall, and F1-score were evaluated for each classifier.
   - Hyperparameter tuning was performed using GridSearchCV.

---

## Dataset

- Dataset source: Scraped from [Consumer Affairs](https://www.consumeraffairs.com/travel/marriott.html) and TripAdvisor reviews.
- Format: CSV file containing customer reviews, star ratings, and complaint categories.

---

## Usage

### Prerequisites
- Python 3.7+
- Required Libraries: Install dependencies using `pip install -r requirements.txt`.

### Steps to Run
1. Clone the repository.
2. Extract the dataset (`Dataset.zip`) into the working directory.
3. Open and execute the Jupyter notebook `Compliant_classification_project.ipynb` for training and evaluation.
4. Review the output classification and topic modeling results in the provided `Project_outputs.pdf`.

---

## Outputs

- Classified complaints for different categories.
- Visualizations for topic distributions and model performance.

