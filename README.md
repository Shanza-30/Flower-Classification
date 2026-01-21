# Iris Flower Classification 🌸

This project demonstrates a complete **Machine Learning workflow** for classifying Iris flowers into three species: **Setosa**, **Versicolor**, and **Virginica**.

## 📁 Dataset

The dataset used is the classic Iris dataset from Kaggle:

[Download Iris Dataset](https://www.kaggle.com/datasets/uciml/iris)

It contains 150 samples with 4 features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species (Target)

---

## 🧪 Features

- **Exploratory Data Analysis (EDA):** Summary statistics, null value check, and pairplot visualization.
- **Data Preparation:** Train-test split, optional standardization.
- **Models Used:**
  - Logistic Regression
  - Decision Tree Classifier
- **Model Evaluation:** Accuracy comparison, confusion matrix plotting, and classification report (precision, recall, F1-score).

---

## 🔧 Step-by-Step Usage

1. **Clone the Repository**

```bash
git clone <your-repo-link>
cd <repo-folder>

Install Dependencies

pip install pandas numpy matplotlib seaborn scikit-learn


Prepare Dataset

Download Iris.csv from Kaggle and place it in the project folder.

Run EDA and Model Training

Open train_models.py (or Jupyter Notebook) and execute:

# Load data
import pandas as pd
df = pd.read_csv("Iris.csv")

# Perform EDA
# Train models
# Compare accuracy
# Plot confusion matrix
# Save trained model and scaler


Save Models

import pickle
pickle.dump(log_reg, open("model.pkl", "wb"))
pickle.dump(scaler, open("scaler.pkl", "wb"))


Run CLI Prediction Script

python predict_iris.py 5.1 3.5 1.4 0.2


Output will show the predicted species.

📊 Evaluation

Compare Logistic Regression and Decision Tree accuracies.

Confusion matrix shows correct and misclassified samples.

Classification report provides precision, recall, and F1-score for each class.

🛠 Technologies Used

Python 3.x

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn
