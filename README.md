# Bank_Customer_Churn-ML

This project aims to use machine learning techniques to analyze customer data from a bank and predict the likelihood of customers churning (leaving) the bank or is likely to remain loyal.

# _Table of Contents_
       * Introduction
       * Dataset
       * Objectives
       * Model Building
       * Results

# _Introduction_
  In the ever-evolving landscape of the banking industry, customer churn has emerged as a critical challenge for financial institutions. Customer churn, also known as customer attrition, refers to the phenomenon where clients discontinue their relationship with a bank, seeking services elsewhere. It is a key metric that directly impacts a bank's profitability, market share, and long-term success.

  This project leverages the power of machine learning to analyze historical customer data and predict whether a customer is prone to churn or is likely to remain loyal. The project's primary objective is to develop a robust and accurate churn prediction model that empowers the bank to make data-driven decisions to retain its valuable clientele.

# _Dataset_
  The project utilizes a labeled dataset of bank customers for training and testing the churn prediction model. The dataset consists of 28382 rows and 21 columns. It does not contains null values.

Dataset link: https://drive.google.com/file/d/1l_0nIgrIEYWatlvG5HCBS72TT5yPWoij/view?usp=sharing

# _Objectives_
The main objectives of this project are as follows:

   1. Explore and preprocess dataset.
   2. split the dataset into train and test in data_ingestion
   3. Create a pipeline for data preprocessing technique in data_transformation
   4. Apply machine learning techniques in model_training

# _Model Building_
  The dataset was analyzed using four different machine learning models: 
    SVM, 
    KNN,
    DecisionTree,
    Random Forest.
 
  Among these models, the Random Forest  performed the best in terms of predicting weather the customer churn or not, achieving an accuracy score of 86%.

# Results
  The **Random Forest** demonstrated its effectiveness in predicting the customer churn or not, achieving an accuracy score of **86%**. Random Forest model can serve as a valuable tool for detecting the customer churn.
