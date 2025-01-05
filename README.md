
# Online Shoppers' Intention Prediction Using Machine Learning

This project predicts online shoppers' purchase intentions using machine learning algorithms. The dataset consists of various features related to user sessions, such as page views, durations, bounce rates, and special days, among others. Several classification models are implemented to compare their performance in predicting the likelihood of a purchase.

---

## Table of Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Models Implemented](#models-implemented)
6. [Evaluation Metrics](#evaluation-metrics)
7. [Visualizations](#visualizations)
8. [Results](#results)
9. [License](#license)

---

## Overview

The goal of this project is to predict whether a user will complete a purchase (`Revenue = True`) based on their session data. The models are evaluated on their performance using metrics such as accuracy, confusion matrix, and classification report.

---

## Dataset

The dataset contains the following features:

- **Administrative**: Number of administrative pages visited during the session.
- **Administrative_Duration**: Time spent on administrative pages.
- **Informational**: Number of informational pages visited.
- **Informational_Duration**: Time spent on informational pages.
- **ProductRelated**: Number of product-related pages visited.
- **ProductRelated_Duration**: Time spent on product-related pages.
- **BounceRates**: Percentage of visitors who leave the site without interacting further.
- **ExitRates**: Percentage of pageviews that end at that specific page.
- **PageValues**: Average value of the page concerning purchase transactions.
- **SpecialDay**: Proximity of the browsing date to special days or holidays.
- **Month, Region, OperatingSystems, Browser, VisitorType**: Categorical features describing the session.
- **Weekend**: Boolean indicating if the session occurred on a weekend.
- **Revenue**: Target variable (True if a purchase occurred, False otherwise).

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/shoppers-intention-prediction
   cd shoppers-intention-prediction
   ```

2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Place the dataset (`online_shoppers_intention.csv`) in the project directory.

---

## Usage

Run the script in jupyter notebook to execute the data preprocessing, model training, and evaluation pipeline:
```bash
final_code_V2.ipynb
```

---

## Models Implemented

The following machine learning models are used to predict purchase intention:
1. Random Forest Classifier
2. Logistic Regression
3. Gradient Boosting Classifier
4. Support Vector Machine (SVM)

Each model is trained and evaluated using the processed dataset.

---

## Evaluation Metrics

The performance of the models is assessed using:
- **Accuracy**: Proportion of correct predictions out of total predictions.
- **Confusion Matrix**: A table showing the true vs. predicted labels.
- **Classification Report**: Includes precision, recall, F1-score, and support for each class.

---


