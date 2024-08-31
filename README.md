# IT1244 Project Disaster Dataset

## Overview

This project aims to predict the survivability of passengers on a ship that met with disaster using various machine learning models. 

We employed Python to compare the performance of different models in terms of their accuracy in predicting whether a passenger would survive.

## Features

- Utilized multiple machine learning models to predict passenger survivability.
- Assessed the accuracy of k-Nearest Neighbors (kNN), neural networks, logistic regression, and decision tree models.
- Employed Python and relevant libraries to build, train, and evaluate the models.

## Dataset

The dataset used for this project was obtained from Kaggle.

The dataset contains the ship’s passenger details. The dataset is multivariate with a total of 866 instances and 12 attributes, containing missing values. 

## Setup Instructions

#### Install Dependencies:

```bash
pip install -r requirements.txt
```

#### Run the Google Colab Notebook

1. Open disaster.ipynb in Colab
2. Upload data.csv into /contect directory
3. Run disaster.ipynb as normal

## Results

After repeating the process 30 times, the models had the following accuracies:

1. kNN, 83.58%
2. LR, 81.30%
3. NN, 81.38%
4. DT, 77.27%

## Additional Notes

This project was a part of IT1244.
Project group members were as follows: Ang Lin Xuan, Chew Yu Cai, Yune Thiri Khin.


