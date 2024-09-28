# Bayesian Networks Projects Repository

This repository contains two projects that implement Bayesian Networks for two different scenarios:

1. **Credit Worthiness Prediction**: A Bayesian Network is used to predict a client's credit worthiness based on various factors such as income, assets, debt ratios, and payment history.
   
2. **Obesity Prediction**: A Bayesian Network is used to predict the likelihood of obesity based on factors like eating habits, physical activity, and family history of obesity.

## Project 1: Credit Worthiness Prediction

This project models the relationships between financial factors and the likelihood of a client having a high credit score. It uses Bayesian Networks to structure and evaluate dependencies between parameters such as:
- Income
- Assets
- Ratio of debts to income
- Payment history
- Age
- Client reliability
- Future income

### Files:
- **BayesCreditScore.ipynb**: Contains the Bayesian Network implementation for predicting credit worthiness.
- **BayesCreditScore.pdf**: Contains notebook's preview in a pdf format

## Project 2: Obesity Prediction

This project models the likelihood of a person becoming obese based on lifestyle factors such as diet and exercise, and uses Bayesian Networks to predict outcomes based on different scenarios. Key factors include:
- Family history of obesity
- Frequency of high-calorie food consumption
- Vegetable consumption
- Number of meals per day
- Water intake

### Files:
- **BayesObesity.ipynb**: Contains the Bayesian Network implementation for predicting obesity.
- **BayesObesity.pdf**: Contains notebook's preview in a pdf format
- **OB.csv**: Dataset used to train the model.

## Usage

To run either of the models, simply execute the respective Python scripts. Both models are implemented using the `bnlearn` library for Bayesian Networks.

### Requirements:
- Python 3.x
- bnlearn
- pandas

### Install the dependencies:
```bash
pip install -r requirements.txt
