# Customer_Behavior_Prediction
# Customer Behavior Classification with Random Forest

This project utilizes a **Random Forest Classifier** to predict customer behavior based on various purchase-related features. By classifying customers into two categories—**Bargain Hunters** and **Premium Buyers**—the model aims to help businesses tailor their marketing strategies for different customer segments.

### **Table of Contents**
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Model Evaluation Metrics](#model-evaluation-metrics)
- [Confusion Matrix Visualization](#confusion-matrix-visualization)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## **Project Overview**
In this project, we aim to build a machine learning model that classifies customer behavior based on their **spending habits**, **purchase value**, and **visit frequency**. The customers are classified into two categories:
- **Bargain Hunters**: Customers who tend to look for discounts and buy less expensive items.
- **Premium Buyers**: Customers who prefer to make larger and more expensive purchases.

The model is built using a **Random Forest Classifier**, an ensemble learning method that aggregates multiple decision trees to make more accurate predictions.

---

## **Dataset Description**
The dataset (`customer_behavior.csv`) contains customer purchase data, and the features are as follows:

- **`total_spent`**: The total amount a customer has spent.
- **`avg_purchase_value`**: The average value of the customer's purchases.
- **`visits_per_month`**: The average number of visits the customer makes to the store per month.
- **`buyer_type`**: The target variable, which indicates whether the customer is a "Bargain Hunter" or a "Premium Buyer."

The goal of the project is to predict the `buyer_type` based on the other features.

---

## **Installation**

### **Prerequisites**
Before running the project, make sure you have the following libraries installed:

- `pandas`: Data manipulation and analysis.
- `matplotlib`: Plotting and visualization.
- `seaborn`: Statistical data visualization.
- `scikit-learn`: Machine learning library for model building and evaluation.

You can install the required dependencies using `pip`:

```bash
pip install pandas matplotlib seaborn scikit-learn
