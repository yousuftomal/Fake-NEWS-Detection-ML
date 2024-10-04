# Fake News Detection

This project implements a machine learning model for detecting fake news articles using a Naive Bayes classifier. It utilizes a labeled dataset containing both true and fake news articles, enabling the model to classify new articles accurately.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

The goal of this project is to build a reliable model to identify fake news articles, which is crucial in today's digital landscape where misinformation can spread rapidly. The model processes text data through tokenization and removal of stop words before applying the Naive Bayes classification algorithm.

## Dataset

The dataset used in this project consists of two CSV files:
- `True.csv`: Contains true news articles.
- `Fake.csv`: Contains fake news articles.

Each article is labeled as either true (1) or fake (0) to facilitate supervised learning.

## Installation

To set up the project environment, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/fake-news-detection.git
   cd fake-news-detection
2. **Install the required libraries: Ensure you have Python installed, then install the dependencies using pip:**
   ```bash
   pip install pandas nltk scikit-learn joblib
3. **Download the dataset: Ensure you have the `True.csv` and `Fake.csv` files in the project directory.**

## Usage

1. **Run the script: To train the model and evaluate its performance, execute the following command:**

   ```bash
      python fakenews_detector.py

 **Output: The script will output the accuracy and classification report, along with the confusion matrix, in the console.**

## Evaluation

The model is evaluated using metrics such as accuracy, precision, recall, and F1-score. It achieved an overall accuracy of 93% on the test dataset.

## Results

The key metrics from the evaluation are as follows:

Accuracy: 93%
Precision:
   Fake News (0): 0.93
   True News (1): 0.93
Recall:
   Fake News (0): 0.94
   True News (1): 0.92
F1-Score:
   Fake News (0): 0.93
   True News (1): 0.92

## Confusion Matrix

[[4396  300]
 [ 347 3937]]


## Contributing

Contributions are welcome! If you would like to improve the project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.