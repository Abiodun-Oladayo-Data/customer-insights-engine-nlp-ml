# Customer Insights Engine Using NLP & Machine Learning

## Project Overview

The Customer Insights Engine is an end-to-end customer analytics solution designed to extract actionable insights from customer reviews.

Using Natural Language Processing (NLP), Machine Learning, Deep Learning, and Text Summarization techniques, this project transforms unstructured customer feedback into meaningful business intelligence.

The solution analyzes Amazon customer reviews to:

- Classify customer sentiment
- Predict product ratings
- Generate concise review summaries
- Identify customer engagement patterns
- Support business decision-making through data-driven insights

## Business Problem

Organizations receive large volumes of customer feedback every day. Manually analyzing thousands of reviews is time-consuming and often impractical.

This project demonstrates how AI and machine learning can automate customer review analysis and help businesses:

- Understand customer sentiment
- Identify product strengths and weaknesses
- Predict customer satisfaction
- Summarize large amounts of feedback
- Improve product and marketing strategies

## Dataset

Amazon Product Reviews Dataset

The dataset includes:

- Product information
- Customer ratings
- Customer review text
- Pricing information
- Discount information
- Product categories

## Technologies Used
## Programming
- Python

## Data Analysis
- Pandas
- NumPy

## Visualization
- Matplotlib
- Seaborn

## NLP
- NLTK
- TextBlob
- TF-IDF Vectorization

## Machine Learning
- Logistic Regression
- Decision Tree
- Random Forest
- Linear Regression
- Ridge Regression
- Lasso Regression

## Deep Learning
- TensorFlow / Keras
- LSTM
- GRU

## Application Layer
Gradio


## Project Workflow
### 1. Data Preparation

- Loaded and inspected the Amazon reviews dataset
- Handled missing values
- Removed duplicates
- Converted data types where necessary
- Applied lemmatization

### 2. Exploratory Data Analysis (EDA)

- Analyzed rating distributions
- Examined sentiment trends
- Identified product category performance
- Visualized customer engagement patterns
  
### 3. Feature Engineering

Created additional features including:

- Review length
- Sentiment polarity
- Price discount percentage
- Encoded product categories

### 4. NLP Processing

- Text cleaning
- Tokenization
- Stopword removal
- Lemmatization
- TF-IDF vectorization

### 5. Sentiment Classification

Built and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

Evaluation metrics included:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 6. Rating Prediction

Developed regression models to predict customer ratings:

- Linear Regression
- Ridge Regression
- Lasso Regression

Evaluation metrics included:

- MAE
- MSE
- RMSE
- R² Score

### 7. Deep Learning Models

Implemented:

- LSTM Network
- GRU Network

to compare performance against traditional machine learning approaches.

### 8. Review Summarization

Implemented an extractive text summarization solution to automatically generate concise summaries of lengthy customer reviews.

### 9. Interactive Application

Developed a Gradio-based user interface that allows users to submit reviews and receive automatically generated summaries.

## Business Impact

This solution enables organizations to:

- Monitor customer sentiment at scale
- Identify recurring customer complaints
- Predict customer satisfaction levels
- Summarize large volumes of feedback
- Support product improvement and marketing decisions

## Future Improvements

- Incorporate transformer-based models such as BERT
- Address class imbalance using SMOTE
- Deploy the solution to a cloud environment
- Build a real-time analytics dashboard
- Integrate external review sources for broader analysis

## Author

Abiodun Oladayo

Data Analytics | Machine Learning | Artificial Intelligence
