## Credit Card Fraud Detection
This is a personal project with the aim of learning how to build a machine learning model that accurately predicts and detects credit card fraud so that customers of the credit card company are not charged for items they did not purchase.

### Dataset
The dataset is found [here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
The dataset contains transactions made by credit cards in September 2013 by European cardholders.This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

### Issues
The main challenges involved in credit card fraud prediction are:

1. Enormous Data is processed every day and the model build must be fast enough to respond to the scam in time.
2. Imbalanced Data i.e most of the transactions (99.8%) are not fraudulent which makes it really hard for detecting the fraudulent ones
3. Data availability as the data is mostly private.
4. Misclassified Data can be another major issue, as not every fraudulent transaction is caught and reported.
5. Adaptive techniques used against the model by the scammers.

### Handling Issues
1. For the imbalanced data, we can use oversampling or undersampling technique to balance the fraudulent vs valid datasets

### Project
This personal project follows a tutorial from various sources online. This is for learning purposes only. Some of the blogs and resources are referenced in the Reference section below.

### Reference(s)
1. [Geekforgeeks](https://www.geeksforgeeks.org/ml-credit-card-fraud-detection/)
2. [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## License

This project is released under the MIT License 

Copyright (c) 2022 Opetunde Adepoju

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
