# SMS Spam Detection: Statistical vs. Deep Learning

This project compares traditional statistical machine learning models with a Deep Learning approach to classify SMS messages as 'Ham' or 'Spam'.

## Project Overview
* **Baseline:** Naive Bayes using Count Vectorization.
* **Statistical:** Logistic Regression using TF-IDF.
* **Deep Learning:** A Sequential Neural Network (Keras/TensorFlow) using Word2Vec embeddings.

## Performance Comparison
The project includes a final analysis comparing Accuracy, Precision, Recall, and F1-Scores across all three models.


## Installation & Usage
1. Clone the repo: `git clone https://github.com/yourusername/SMS-Spam-Detection.git`
2. Install dependencies: `pip install pandas numpy scikit-learn tensorflow gensim matplotlib`
3. Run the script: `python src/nlp_mid.py`

## Dataset
Uses the [UCI SMS Spam Collection](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection) dataset.
