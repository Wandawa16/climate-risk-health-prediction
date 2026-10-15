# Climate Risk and Health Prediction

## Project Overview

This project focuses on predicting whether a recorded death is climate-sensitive using demographic, geographic, health-related, and climate data. It is based on the **Climate Risk and Health Prediction Challenge** hosted on [Zindi](https://zindi.africa/).

The goal is to apply machine learning classification techniques to identify patterns associated with climate-sensitive mortality and explore how environmental conditions may relate to health outcomes.

## Problem Statement

Climate conditions such as temperature and precipitation can influence health risks, particularly among vulnerable populations. Understanding patterns in mortality data can support research into the relationship between environmental conditions and public health.

This project aims to develop a supervised machine learning model that predicts whether a recorded death belongs to a climate-sensitive category.

## Objectives

* Explore and understand the provided datasets.
* Perform data cleaning and exploratory data analysis (EDA).
* Investigate demographic, geographic, and climate-related features.
* Engineer relevant features to improve model performance.
* Train and evaluate classification models.
* Generate predictions and probabilities in the required Zindi submission format.
* Document the workflow and findings.

## Dataset

The competition data includes demographic, geographic, and climate-related information.

Expected features include:

* **Demographic:** Age and gender.
* **Geographic:** Zone, location, latitude, and longitude.
* **Climate:** Average, maximum, and minimum temperature, and precipitation.
* **Temporal:** Date of death.

The target variable is `is_climate_sensitive`, which indicates whether a recorded death is labelled climate-sensitive.

*Note: Competition datasets are not included in this repository. Refer to the official Zindi competition page for access and applicable data-use conditions.*

## Methodology

The project will follow these stages:

1. Data loading and inspection.
2. Data cleaning and preprocessing.
3. Exploratory data analysis.
4. Feature engineering.
5. Model training and validation.
6. Model evaluation using F1-score and ROC-AUC.
7. Prediction generation and submission preparation.

## Evaluation Metrics

The competition uses a weighted combination of two metrics:

* **F1-score (60%):** Evaluates the balance between precision and recall.
* **ROC-AUC (40%):** Evaluates how effectively the model ranks positive cases above negative cases.

Binary predictions will use the required default probability threshold of 0.5.

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab
* Git and GitHub

Additional libraries may be introduced as the project develops.

## Repository Structure

```text
climate-risk-health-prediction/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   └── climate_risk_analysis.ipynb
├── src/
│   └── train.py
└── submissions/
    └── .gitkeep
```

The repository structure will be updated as the project progresses.

## Current Status

**In progress**

* [x] Initial dataset inspection
* [x] Identification of the target variable
* [ ] Data quality assessment
* [ ] Exploratory data analysis
* [ ] Feature engineering
* [ ] Baseline model development
* [ ] Model evaluation and improvement
* [ ] Submission generation

## Expected Outcome

The intended outcome is a reproducible machine learning workflow that predicts climate-sensitive mortality labels, evaluates model performance, and produces a valid submission file for the Zindi competition.

## Disclaimer

This is a machine learning project for research and educational purposes. Model predictions indicate patterns in the supplied data and should not be interpreted as proof that climate conditions caused an individual death.

## Author

**Gerald Wanjala**

* GitHub: [Wandawa16](https://github.com/Wandawa16)
* Portfolio: [gerald_portfolio](https://wandawa16.github.io/gerald_portfolio)
*
