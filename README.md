# Bangla YouTube Clickbait Detection

This project presents a multimodal Bangla YouTube clickbait detection framework using Machine Learning and Transformer-based approaches. The study combines TF-IDF text features with YouTube engagement metadata to identify clickbait content in Bangla video titles.

## Features

* Bangla text preprocessing
* TF-IDF feature extraction
* Metadata feature engineering
* Machine Learning models:

  * Logistic Regression
  * Random Forest
  * SVM
* Transformer model:

  * BanglaBERT
* Performance evaluation using Accuracy, Precision, Recall, and F1-score

## Dataset

The experiments were conducted using the human-labeled subset of the BaitBuster-Bangla dataset collected from Kaggle.

## Best Result

BanglaBERT achieved the highest performance with:

* Accuracy: 98.70%
* F1-Score: 98.70%

## Technologies Used

* Python
* Scikit-learn
* PyTorch
* Transformers
* Pandas
* Matplotlib
