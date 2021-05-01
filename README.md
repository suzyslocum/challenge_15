# Module 15 Challenge Assignment 
---

## Create a Robo Advisor That Gives Retirement Portfolio Recommendations
---

## Overview 
---
  In order to improve customer experience, we created a robo advisor that can give retirement portfolio recommendations. This will appeal to both new and existing customers. This is accomplished using Amazon Lex and Amazon Lambda. The Lambda function validates the user's input and returns an investment portfolio recommendation.

## Results
---



## Summary
---
Given the lack of improvement in accuracy precision, and recall, I would not recommend that any of the alternative models be used. The original model itself is also not very accurate. I would reccommend that more alterations be made until improvement is found, or that an entirely different type of model be used for these predictions given the potential loss of capital were these models to be used in practice. 

---

## Technologies

The application is written in Python using Pandas
The following packages are used:

Pandas - to write and run the program [Pandas documentation](https://pandas.pydata.org/docs/)

Pathlib - to create file paths [Pathlib documentation](https://docs.python.org/3/library/pathlib.html)

NumPy - for mathematical functions [NumPy documentation](https://numpy.org/doc/)

hvPlot - to create graphs [hvPlot documentation](https://hvplot.holoviz.org/)

matplotlib - to create graphs [matplotlib documentation](https://matplotlib.org/stable/contents.html)

DateOffset - to create a date range [DateOffset documentation](https://pandas.pydata.org/docs/reference/api/pandas.tseries.offsets.DateOffset.html)

SciKit-Learn - to train models, encode data, and scale data [SciKit Learn documentation](https://scikit-learn.org/0.21/documentation.html)


---

## Installation Guide

Install the Pandas package using the following command: 'import pandas as pd'

Install the Pathlib module using the following command: 'from pathlib import Path'

Install the numpy library using the following command: 'import numpy as np'

Install the hvPlot library using the following command: 'import hvplot.pandas'

Install the matplotlib library using the following command: 'import matplotlib.pyplot as plt'

Install the DateOffset package usi8ng the following command: 'from pandas.tseries.offsets import DateOffset'

Install the SciKit-Learn metrics libraries using the following commands: 'from sklearn import svm', 'from sklearn.preprocessing import StandardScaler', 'from sklearn.metrics import classification_report', 'from sklearn.linear_model import LogisticRegression'


--- 

## Usage

To run this program, clone the repository onto your computer, navigate to its source folder in your terminal and launch it using the command 'jupyter lab' then either run the entire program at once, or run the cells individually (in order) as you move through the file.

---

## Contributors
Susannah Slocum 
suzyslocum@gmail.com

---

## License

None
