# IBM Coursera Capstone: Seattle Car Collision Severity factors

![Python 3.6](https://img.shields.io/badge/python-3.5%20%7C%203.6%20%7C%203.7-blue.svg)

## Describe project

It is always rainy and windy in Seattle, and on the way, you always come across a terrible traffic jam on the other side of the highway, with long lines of cars barely moving. It would be great if there is something in place that could warn you, given the weather and the road conditions about the possibility of you getting into a car accident and how severe it would be, so that you would drive more carefully or even change your travel if you are able to.

## Objective

Luckily enough, The Seattle Police Department (SPD) has recorded all car collision accident from 2004 to present. Basing on those historical data (194,673 records), we can create a map and information chart to help us understand the high-risk areas, understand car injury factors to avoid accident, and plan our next trip to Seattle better.

## Documentation
- ipynb code file (reports/)
- [Report this project](reports/)

## Datasource
The datasource is: http://data-seattlecitygis.opendata.arcgis.com/datasets/5b5c745e0f1f48e7a53acec63a0022ab_0.csv

## Algoritms
- K nearest neighbors
- The Decision Tree Analysis
- Logistic regression
- Support Vector Machine (SVM) 

## Quickstart
1. [Data Exploration and Data Cleaning](notebooks/)
2. [Modeling and Evaluation](notebooks/)


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
clone eliuqiong/IBM_Coursera_Capstone
cd challenge-keyrus
```

2. Choose which environment to running
 - [local](src/environment/README.md)
 - [virtual environment](src/environment/README.md)
 - [container](src/environment/README.md)

3. In terminal running command `jupyter-notebook` and navigate in this repository: `notebooks`
