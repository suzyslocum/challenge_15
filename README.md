# Module 15 Challenge Assignment 
---

## Create a Robo Advisor That Gives Retirement Portfolio Recommendations
---

## Overview 
---
  In order to improve customer experience, we created a robo advisor that can give retirement portfolio recommendations. This will appeal to both new and existing customers. This is accomplished using Amazon Lex and Amazon Lambda. The Lambda function validates the user's input and returns an investment portfolio recommendation.

## Results
---

![Demo](https://user-images.githubusercontent.com/75707305/116795792-4eda3a00-aa8c-11eb-847c-ea205d16d7e0.mov)

---

## Technologies

The application was created using Amazon Lex and Lambda
The following packages are used:

Amazon Lex - to create the chatbot [Amazon Lex documentation](https://docs.aws.amazon.com/lex/)

Amazon Lambda - to validate user input and return recommendations [Amazon Lambda documentation](https://docs.aws.amazon.com/lambda/index.html)

datetime - to standardize the format of dates - [datetime documentation](https://docs.python.org/3/library/datetime.html)

dateutil - to compute relative deltas - [dateutil documentation](https://dateutil.readthedocs.io/en/stable/)


---

## Installation Guide

In the Amazon Lambda code area, the code begins with the following imports:

Install the datetime library using the following command: 'from datetime import datetime'

Install the dateutil package using the following command: 'from dateutil.relativedelta import relativedelta'

---

## Contributors
Susannah Slocum 
suzyslocum@gmail.com

---

## License

None
