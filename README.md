# ELEVATE_LABS_INTERNSHIP
TASK-1
# Titanic Dataset - Data Cleaning & ML 🚢

This project involves cleaning, preprocessing, and applying a basic ML model on the Titanic dataset using Python in Google Colab.

## 📌 Tasks Performed

- Loaded dataset using `kagglehub`
- Handled missing values (Age, Embarked)
- Dropped unused columns (Cabin, Ticket, Name, etc.)
- Encoded categorical variables (`Sex`, `Embarked`)
- Standardized numerical features (`Age`, `Fare`, etc.)
- Visualized and removed outliers
- Split data into train/test sets
- Trained a Logistic Regression model
- Evaluated model using accuracy and classification report


TASK 2
🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs **exploratory data analysis** on the Titanic dataset to uncover patterns and insights related to passenger survival.

## 🔍 Key Tasks

- Generated summary statistics (mean, median, std)
- Created histograms and boxplots for numerical features
- Plotted correlation matrix and pairplot to analyze relationships
- Visualized survival trends by gender, class, and fare
- Highlighted key insights from the data

## 🛠 Tools Used

- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab

## 📁 Dataset

- Source: Kaggle ([yasserh/titanic-dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset))

## ✅ Output

- ~78% accuracy using Logistic Regression

  TASK 3
  🗂️ Key Tasks
Load and preprocess dataset

Split data into train/test sets

Train Linear Regression model

Predict housing prices

Evaluate using MAE, MSE, RMSE, R²

Visualize actual vs predicted results

Interpret model coefficients
Source: Kaggle Dataset - harishkumardatalab/housing-price-prediction


TASK-4

# Breast Cancer Classification with Logistic Regression 🎯

This project implements a binary classification pipeline using **Logistic Regression** on the **Breast Cancer Wisconsin Dataset**.

## 📌 Tasks Performed

- Loaded and cleaned the dataset
- Encoded target labels (Malignant/Benign)
- Standardized features using `StandardScaler`
- Trained a Logistic Regression classifier
- Evaluated using:
  - Accuracy, Precision, Recall
  - Confusion Matrix
  - ROC Curve and AUC Score
- Tuned classification threshold
- Explained the Sigmoid function with a plot

## 🧰 Tools Used

- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab
- `kagglehub` to fetch dataset

## 📁 Dataset

- [Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Downloaded using:
  ```python
  path = kagglehub.dataset_download("uciml/breast-cancer-wisconsin-data")



