# Fraud Detection Model

This project focuses on building a fraud detection model using machine learning techniques, with an emphasis on preprocessing, feature engineering, and model evaluation. The goal was to develop an effective fraud detection system to identify fraudulent activities in a given dataset.

## About

The project involved an in-depth exploration of the dataset, which included understanding the nature of features, their relationships, and potential irregularities. It delved into preprocessing techniques, including time series encoding, lagging for transaction history, and engineering features to capture anomalies related to browsers and transaction types. Label encoding was employed for categorical values, enhancing the dataset for model training.

## Data Preprocessing

Several preprocessing steps were implemented to prepare the data for model training. Time series encoding, lagging for previous transactions, and engineering new features were undertaken to capture essential information about user behavior. Additionally, label encoding was employed to convert categorical features into numerical representations, facilitating the training of machine learning models.

## Feature Engineering

Feature engineering aimed to extract meaningful information from the dataset. New features such as net spend, average spend, and standard deviation were calculated, providing insights into user transactions. Features were also engineered to capture anomalies in browser types and transaction histories, enriching the dataset for model training.

## Model Training and Evaluation

The CatBoost classifier was chosen as the model for this project due to its effectiveness in handling categorical data. The model was trained using a portion of the dataset and evaluated on a separate test set. The evaluation included generating a classification report to assess the model's precision, recall, and F1-score. Despite the efforts, the model struggled to identify clear patterns and achieved an average performance, hinting at irregularities or randomness in the dataset.

## Outcome

The project outcome suggests that the dataset might lack coherence, potentially being synthetically generated. The model's performance indicates that it was essentially guessing outcomes, underscoring the importance of dataset authenticity and quality in building effective machine learning models, especially for fraud detection.

For more details, refer to the [Modelling and Evaluation Report](./Modelling_Evaluation_Report.md).


