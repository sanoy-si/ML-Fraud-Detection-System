# ML-Fraud-Detection-System

An end-to-end machine learning system for detecting fraudulent activity across e-commerce and credit card transactions.

---

## 📖 About The Project

This project aims to build accurate and robust fraud detection models by analyzing two distinct datasets: e-commerce purchases and credit card transactions. The core challenge involves handling highly imbalanced data, where fraudulent events are rare.

By leveraging advanced machine learning models, detailed feature engineering, and modern explainability techniques, this system can effectively identify fraudulent patterns, helping to prevent financial losses while building a foundation of trust and security.

###  Features

*   Comprehensive Exploratory Data Analysis (EDA)
*   Feature engineering from temporal and geographical data
*   Implementation of techniques (e.g., SMOTE) to handle class imbalance
*   Training and comparison of multiple models (Logistic Regression, Ensemble Methods)
*   Model evaluation using metrics appropriate for imbalanced data (AUC-PR, F1-Score)
*   Model interpretation using SHAP (SHapley Additive exPlanations)

###  Built With

*   Python 3.9+
*   Pandas & NumPy
*   Scikit-learn, XGBoost
*   Imbalanced-learn
*   Matplotlib & Seaborn
*   SHAP

---

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

###  Prerequisites

You will need the following software installed on your system:
*   [Python (version 3.9 or higher)](https://www.python.org/downloads/)
*   [Git](https://git-scm.com/downloads/)

###  Installation

1.  **Clone the repository**
    ```sh
    git clone https://github.com/your_username/ML-Fraud-Detection-System.git
    cd ML-Fraud-Detection-System
    ```

2.  **Set up the data**
    Place the provided CSV files (`Fraud_Data.csv`, `IpAddress_to_Country.csv`, `creditcard.csv`) into the `data/raw/` directory.

3.  **Create and activate a virtual environment**
    A virtual environment is a self-contained directory that holds a specific Python installation and its packages, isolating your project from others.

    *   For macOS/Linux:
        ```sh
        python3 -m venv venv
        source venv/bin/activate
        ```
    *   For Windows:
        ```sh
        python -m venv venv
        .\venv\Scripts\activate
        ```

4.  **Install project dependencies**
    With your virtual environment activated, install all the required libraries from the `requirements.txt` file.
    ```sh
    pip install -r requirements.txt
    ```

You are now ready to start working on the project!

