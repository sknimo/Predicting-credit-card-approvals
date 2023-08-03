# Prediction credit card approval

![Image](https://content.jdmagicbox.com/comp/def_content/credit_card_agents/singh-financial-service-hazratganj-lucknow-personal-loans-7.jpg)

<sub><sup>https://content.jdmagicbox.com/comp/def_content/credit_card_agents/singh-financial-service-hazratganj-lucknow-personal-loans-7.jpg</sup></sub>

## Introduction

>Several factors comes into play before a credit application is approved or rejected. That notwithstanding we all need credit at one point or another, especially when it comes to financing  capital intensive projects. This project analyzes the factors that could affect your credit card application.


This project analysis a dataset with information about credit card applications. For identity protection purposes, the dataset came with the name of the features removed. That is to say we have  no idea what those columns represents, where the data was collected or who are the participants.

The nature of the dataset makes it very suitable for investigative analytics and predictive modeling. So we will be training a machine learning model with it.

## Dataset
The dataset was obtained from [kaggle](https://www.kaggle.com/datasets/devzohaib/predicting-credit-card-approvals/download?datasetVersionNumber=1)

## Outline
The following steps would be taken:
1. Load the data
2. clean the data
3. Exploratory analysis
    1. for numerical features
    2. for categorical features
4. Fit a model
    1. preprocessing steps
    2. prediction

### Analysis
#### Loading the data

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

df_cc = pd.read_csv('../input/predicting-credit-card-approvals/cc_approvals.data',header = None)
df_cc.head()
```