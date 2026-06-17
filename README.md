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
1. Data Cleaning
Removed missing values
Converted data types
Cleaned review text
Removed punctuation and stopwords
Applied lemmatization
2. Exploratory Data Analysis
Product review analysis
Category-level analysis
Customer engagement trends
Sentiment distribution analysis
3. Feature Engineering

Created custom features including:

Review Length
Sentiment Polarity
Price Drop Percentage
Product Categories
4. NLP Processing

Implemented:

Text Cleaning
Tokenization
Lemmatization
TF-IDF Vectorization
5. Sentiment Classification

Built and evaluated:

Logistic Regression
Decision Tree
Random Forest

Metrics:

Accuracy
Precision
Recall
F1 Score
Confusion Matrix
6. Rating Prediction

Built regression models to predict product ratings:

Linear Regression
Ridge Regression
Lasso Regression

Metrics:

MAE
MSE
RMSE
R²
7. Deep Learning Models

Implemented:

LSTM Network
GRU Network

Used for sentiment prediction and comparison with traditional machine learning approaches.

8. Text Summarization

Implemented a TextRank-inspired extractive summarization technique to generate concise summaries from customer reviews.

9. Interactive Application

Developed a Gradio-based interface that accepts multiple customer reviews and automatically generates a summarized output.
