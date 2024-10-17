# Phishing URL Detection using Machine Learning

This project focuses on detecting phishing URLs using various machine learning models. Phishing is a form of cyber attack where malicious websites masquerade as legitimate ones to steal sensitive information such as usernames, passwords, and credit card numbers. By leveraging machine learning algorithms, we can automatically classify URLs as either legitimate or phishing.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Models Used](#models-used)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Future Work](#future-work)
- [Contributing Team](#contributing)

## Overview
This project builds a phishing URL detection system using a variety of machine learning models such as Logistic Regression, Decision Tree, Random Forest, and others. The system can take a URL as input and classify it as either "phishing" or "legitimate" based on several features extracted from the URL.

## Dataset
The dataset consists of two columns:

1. **Total Entries**: 549,346
2. **Columns**: 2 (URL, Label)
3. **URL**: The web address of the site to be analyzed.
4. **Label**: The prediction label that categorizes each URL into two categories:
   - **Good**: Indicates that the URL is safe and does not contain any malicious content. The site is not a phishing site.
   - **Bad**: Indicates that the URL contains malicious content, and the site is classified as a phishing site.
5. **Missing Values**: None

You can download the dataset from public sources like [Kaggle]([https://www.kaggle.com](https://www.kaggle.com/datasets/taruntiwarihp/phishing-site-urls) or other dataset [Mendeley Data](https://data.mendeley.com/datasets/vfszbj9b36/1).

## Models Used
Several machine learning models are used and compared for phishing detection:

- Logistic Regression

## Evaluation Metrics
The models are evaluated using several performance metrics including:

- Accuracy
- Precision
- Recall
- F1-Score

## Results
The Logistic Regression model showed the highest accuracy of 97% on the testing data.

| Model               | Accuracy | Precision | Recall | F1-Score 
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 97%      | 0.97      | 0.97   | 0.97     


## Future Work
- Explore deep learning techniques such as RNNs or CNNs for URL detection.
- Classification methods can be developed by comparing other classification methods such as Random Forest, SVM, and Ensemble Method.
- Add more features to improve accuracy, such as content analysis and IP address checks.

## Contributing Team
### @afif  Aafif Amirullah:
1. Importing Libraries, Load Dataset.
2. Data analysis and preprocessing.

### @wawanwfs WAHYU FAJAR SETIAWAN:
1. Visualize some important keys using word cloud.
2. Visualize internal links, it will shows all redirect links.
 
### @ARTPHD Ilham Ariatama
1. CountVectorizer,  Spliting Data, & Creating Model
2. Save Model & Deployment Model


## Presentation and explanation of the project can be watched on this YouTube
[![Watch the video](https://img.youtube.com/vi/uczK73i_sCM/0.jpg)](https://www.youtube.com/watch?v=uczK73i_sCM)
