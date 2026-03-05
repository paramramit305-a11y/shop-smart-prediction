# Shop Smart – Online Shopping Purchase Prediction

## Overview

Machine Learning project that predicts whether a website visitor will complete a purchase during an online shopping session using behavioral data.

## Dataset

The dataset contains **12,330 user sessions** from an e-commerce website.

**Target variable**

* `Revenue` → Indicates whether the visitor completed a purchase.

**Key features**

* Administrative
* Administrative_Duration
* Informational
* Informational_Duration
* ProductRelated
* ProductRelated_Duration
* BounceRates
* ExitRates
* PageValues
* SpecialDay
* Month
* OperatingSystems
* Browser
* Region
* TrafficType
* VisitorType
* Weekend

## Workflow

1. Data loading using **Pandas**
2. Exploratory Data Analysis (EDA)
3. Encoding categorical variables

   * `Month`
   * `VisitorType`
   * `Weekend`
4. Feature and target separation
5. Train-test split
6. Model training using **Decision Tree Classifier**
7. Tree pruning for performance improvement
8. Model evaluation using **F1 Score**

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Repository Structure

```
shop-smart-prediction
│
├── shop_smart.ipynb
├── shop_smart_ecommerce.csv
├── README.md
├── LICENSE
└── .gitignore
```
