# SMS Fraud Detection using Machine Learning

## Overview
This project focuses on detecting and classifying fraudulent SMS messages into ham, spam, and smishing categories using machine learning and natural language processing techniques in R.

The project combines TF-IDF text vectorization with metadata features such as EMAIL, PHONE, and URL presence to improve fraud detection performance.

---

## Dataset
Dataset: SMS Fraud Detection Dataset  
Messages are labeled as:
- Ham
- Spam
- Smishing

Place `Dataset_5971.csv` in the project directory before running the script.

---

## Tools & Libraries
- R
- tidyverse
- tidytext
- tm
- caret
- e1071
- nnet
- ggplot2

---

## Project Features
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- TF-IDF text analysis
- Pie charts and stacked bar visualizations
- Metadata feature engineering
- SMS text classification

---

## Machine Learning Models
- Support Vector Machine (SVM)
- Neural Network

---

## Results
- Neural Network Accuracy: 92.03%
- SVM Accuracy: 90.6%
- Neural Network achieved better smishing detection performance.

---

## How to Run
1. Place `Dataset_5971.csv` in the project folder.
2. Open the R script in RStudio.
3. Set the working directory to the project folder.
4. Run the script.
