# STEG-Fraud-Detection-Challenge
---

## Customer Fraud Prediction in Electricity and Gas Consumption for STEG company


This project focuses on predicting customer Fraud in the STEG company for the Electricity and Gas Consumption using machine learning techniques. The objective is to develop a model that can effectively identify customers who are at risk of Frauding, enabling STEG company to take proactive measures to retain them.

### Overview

Customer Fraud, or the loss of customers, can significantly impact the revenue and growth of STEG company. Identifying and understanding the factors that contribute to fraud is crucial for implementing targeted strategies to retain valuable customers. This project utilizes a dataset provided by a STEG company, which contains information about their clients, electricity, and gas consumption levels.

### Key Features

- Data preprocessing: The provided dataset is loaded and preprocessed to handle missing values and perform necessary feature engineering.

- Feature engineering: The invoice data is aggregated at the client level, calculating the mean consumption levels for different categories. Additional features such as the number of transactions are derived.

- Model development: A LightGBM classifier is trained using the training data to predict customer churn. The model is evaluated using the validation set, and the trained model is saved for future use.

- Prediction and submission: The trained model is used to make predictions on the test data, and the results are formatted according to the submission template. The final submission file is generated.

### Dependencies

To run this project, you will need the following dependencies:

- Python (version 3.0 or higher)
- NumPy
- Pandas
- Matplotlib
- Seaborn
- LightGBM
- scikit-learn

### Usage

1. Clone the repository:

```
git clone https://github.com/Abdalkader-Kouhda/STEG-Fraud-Detection-Challenge/
```

2. Install the dependencies:

```
pip install numpy pandas matplotlib seaborn lightgbm scikit-learn
```

3. Download the required dataset files and place them in the project directory.

4. Run the main script:

```
python Fraud_detection.ipynb
```

### Results and Discussion

The project aims to provide valuable insights into customer fraud prediction for STEG company. By accurately identifying customers who are likely to fraud, STEG company can devise targeted retention strategies to mitigate churn and enhance customer satisfaction. The model's accuracy is evaluated using the provided training data, and the final predictions are submitted for evaluation.

This project can be expanded by exploring additional features, incorporating advanced machine learning algorithms, or applying different data preprocessing techniques. The insights gained from this project can assist utility companies in optimizing customer retention efforts and improving overall business performance.

---
