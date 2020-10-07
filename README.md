# IBM Coursera Capstone: Seattle Car Collision Severity factors

## 1. Introduction

It is always rainy and windy in Seattle, and on the way, you always come across a terrible traffic jam on the other side of the highway, with long lines of cars barely moving. It would be great if there is something in place that could warn you, given the weather and the road conditions about the possibility of you getting into a car accident and how severe it would be, so that you would drive more carefully or even change your travel if you are able to. 

Luckily enough, The Seattle Police Department (SPD) has recorded all car collision accident from 2004 to present. Basing on those historical data (194,673 records), we can create a map and information chart to help us understand the high-risk areas, understand car injury factors to avoid accident, and plan our next trip to Seattle better.


# Capstone Proposal - Allstate Claims Severity
![Python 3.6](https://img.shields.io/badge/python-3.5%20%7C%203.6%20%7C%203.7-blue.svg)
![License](https://img.shields.io/badge/Code%20License-MIT-blue.svg)

## Describe project
 This project is my Capstone in course Udacity Machine Learning Engineer Nanodegree.

## Objective
The objective is use supervised learning technical for understend how severe is an insurance claim.

## Documentation
- [Capstone proposal](reports/)
- [Report this project](reports/)

## Datasource
The datasource is: https://www.kaggle.com/c/allstate-claims-severity/data

## Algoritms
- Linear Regression
- Random Forest Regressor
- XGBoost

## Quickstart
1. [Data Exploration and Data Cleaning](notebooks/)
2. [Modeling and Evaluation](notebooks/)

## Struture this Project
```
.
├── data
│   ├── cleansing
│   │   ├── test.csv
│   │   └── train.csv
│   ├── raw
│   │   ├── sample_submission.csv
│   │   ├── test.csv
│   │   └── train.csv
│   └── submissions-kaggle
│       ├── lin_regression_submission.csv
│       ├── random_forest_submission.csv
│       └── xgb_submission.csv
├── LICENSE
├── notebooks
│   ├── 1-data-exploration-and-data-cleaning.ipynb
│   └── 2-algoritm-selection-and-tranning-model.ipynb
├── README.md
├── references
│   └── images
│       └── allstate.jpg
├── reports
│   ├── capstone-proposal.md
│   ├── images
│   │   ├── corr_cont_types_13_ate_14.png
│   │   ├── corr_cont_types_1_ate_4.png
│   │   ├── corr_cont_types_5_ate_8.png
│   │   ├── corr_cont_types_all.png
│   │   ├── corr_matrix_cont.png
│   │   ├── default_loss.png
│   │   ├── describe-cat.png
│   │   ├── describe-continuos2.png
│   │   ├── describe-continuos.png
│   │   ├── distribuicao.png
│   │   ├── linear_regression-1.png
│   │   ├── linear_regression-2.png
│   │   ├── log_loss.png
│   │   ├── mae.png
│   │   ├── PCA.png
│   │   ├── random_forest-1.png
│   │   ├── random_forest-2.png
│   │   ├── random_forest-3.png
│   │   ├── test_data.png
│   │   ├── train_data.png
│   │   ├── xgboost-1.png
│   │   ├── xgboost-2.png
│   │   └── xgboost-3.png
│   ├── machine-learning-capstone.md.ipynb
│   ├── proposta.pdf
│   └── relatorio_machine-learning-capstone.pdf
└── src
    ├── environment
    │   ├── config_environment.txt
    │   ├── container
    │   │   └── Dockerfile
    │   ├── create_requirements.sh
    │   ├── create_virtual_env.sh
    │   ├── __init__.py
    │   ├── jupyter_notebook_config.py
    │   ├── makefile
    │   ├── prepare_env.py
    │   ├── README.md
    │   ├── requirements.txt
    │   ├── show_config_environment.sh
    │   ├── show_struture_project.sh
    │   ├── struture_project.txt
    │   ├── test_environment.py
    │   ├── venv
    │   └── virtualenv_requirements.txt
    ├── __init__.py
    └── visualization
        ├── hidden_code.js
        └── visuals.py

14 directories, 58 files
```

## Requirements
- Python 3.7.3 or more
```sh
sudo apt-get install Python3.7.3
```

- pip
```
sudo apt-get install python3-pip
```

- Python Virtual Environment
```sh
pip3 install --user virtualenv==16.6.0
```

- Git
```sh
sudo apt-get install git
```

## Running
1. Clone this repository
```sh
git clone https://github.com/brunocampos01/challenge-keyrus
cd challenge-keyrus
```

2. Choose which environment to running
 - [local](src/environment/README.md)
 - [virtual environment](src/environment/README.md)
 - [container](src/environment/README.md)

3. In terminal running command `jupyter-notebook` and navigate in this repository: `notebooks`
