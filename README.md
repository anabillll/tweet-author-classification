# Tweet Author Classification

This project uses machine learning to classify tweets by their author. The dataset consists of tweets from different authors, and the goal is to build a model that can predict the author of a tweet based on its content.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)

## Introduction

This project demonstrates how to use machine learning techniques to classify tweets by their author. The project includes data preprocessing, feature extraction using TF-IDF, and classification using a Linear Support Vector Classifier (LinearSVC).

## Dataset

The dataset used in this project is a collection of tweets from various authors. Each tweet is labeled with its author.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/tweet-author-classification.git
    cd tweet-author-classification
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Prepare the dataset:
   - Ensure the `datasets/tweets.csv` file is in the correct location.

2. Run the script to train and test the model:
    ```bash
    python main.py
    ```

## Models

The project uses the following machine learning models:
- TF-IDF Vectorizer for feature extraction.
- Linear Support Vector Classifier (LinearSVC) for classification.



