# <span style="color:#7E3517">Machine Learning Models for Fraud Detection</span>

This project is presented thourgh an Ipython notebook where I tune multiple machine learning models for fraud detection. The data used was obtained from Kaggle fraudulent e-commerce [Dataset](https://www.kaggle.com/datasets/shriyashjagtap/fraudulent-e-commerce-transactions).  

>"This synthetic dataset, "Fraudulent E-Commerce Transactions," is designed to simulate transaction data from an e-commerce platform with a focus on fraud detection. It contains a variety of features commonly found in transactional data, with additional attributes specifically engineered to support the development and testing of fraud detection algorithms."

Approaches taken on the [models](https://www.kaggle.com/datasets/shriyashjagtap/fraudulent-e-commerce-transactions/code) tried by other Kaggle engineers aim for a high accuracy. This is not a good approach because Fraud is typically an imbalanced data problem. Most corporations are more concerned about preventing fraud at the expense of a handful of false positives, this means that they are willing to trade precision for recall. To achieve this ML engineer must focus its attention on maximizing recall and specifically on finding multiple levels of potential fraud. 

As I will show on this notebook, The KS statistic helps us determine the decile (or bucket) that is most appropriate to separate fruad vs non-fraud but will also allow us to decide if, as a business, we want to put different lebels on suspicious activity rather than label it all equally. Multiple labels allow workflows to take different actions on transactions depending on the assigned level of fraud suspicion.
