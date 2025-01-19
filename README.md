# Friend Recommendation System on Social Networks using Link Prediction

This repository contains the code for a Friend Recommendation System that leverages link prediction techniques to recommend potential friends on social networks. The system achieves a best accuracy of 92.8%.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Models](#models)
- [Results](#results)

## Overview
This project aims to enhance the friend recommendation process on social networks by employing link prediction techniques. It uses a variety of tree-based algorithms to predict the likelihood of a connection between users, based on engineered features from the dataset.

## Features
- Exploratory Data Analysis
- Link prediction on social networks
- Feature engineering to improve predictive capability
- High accuracy with a success rate of 92.8%

## Technologies
The project utilizes the following technologies and algorithms:
- Random Forest
- XGBoost
- LightGBM
- Ensemble Learning (Combination of the above 3 models)

## Installation
To get a local copy up and running, follow these simple steps:

1. Clone the repo
    ```sh
    git clone [https://github.com/idkupickaname/Friend-Recommendation-System-Using-Link-Analysis.git]
    ```

## Usage
Instructions on how to use the project:

1. Download the dataset from the link provided in the Dataset section and place it in the default directory.
2. A Notebook is provided which has all the implemented functionalities starting from explaoratory dataset, feature engineering, training, testing and finally the results obtained in a tabular format. 

## Dataset
The project uses the Facebook dataset from a hiring contest, which contains 1,862,220 nodes (users) and 9,437,519 edges (connections). Please download the dataset from [https://www.kaggle.com/code/genialgokul1099/social-network-graph-link-prediction] and place it in the default directory.

## Models
The project employs tree-based algorithms including Random Forest, XGBoost, and LightGBM, as well as an ensemble of these models. Feature engineering techniques such as Jaccard distance, HITS score, PageRank, and SVD are used to enhance the predictive capability of the models.

## Results
The system achieves a best accuracy of 92.8% in predicting potential friend connections on social networks.

