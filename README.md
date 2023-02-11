# algo-trading
create an algorithmic trading bot that learns and adapts
---

Using models, identify the best algo for trading. Using historcial data and analyzing different methods, we're able to select the best peforming algo to use. 

---

## Overview of the Analysis

The AdaBoost model outperformed the baseline SVC model, returning 1.57 versus 1.52.

The AdaBoost model is better at predicting signals than was the SVC model.

If I were to select a model to use for the Algo-trading, it would be the AdaBoost Classifier. 

---
## Winning performance

![image](https://user-images.githubusercontent.com/23126459/218241726-4921624a-abdc-4b2e-b5a1-2ff8eca163dd.png)

---

## Tools 

import pandas as pd

import numpy as np

from pathlib import Path

import hvplot.pandas

import matplotlib.pyplot as plt

from sklearn import svm

from sklearn.preprocessing import StandardScaler

from pandas.tseries.offsets import DateOffset

from sklearn.metrics import classification_report

---
## Please find the code [algo_trading](https://github.com/Brock-Denton/algo-trading/blob/main/machine_learning_trading_bot.ipynb)
---
## Contributor
### Brock Denton, Brockchecksmail@gmail.com 
---
### License 
MIT 
