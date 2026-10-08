# Titanic Survival Prediction: ML Classification

## Project Overview
This project uses machine learning classification algorithms to predict whether a passenger survived the Titanic disaster. It uses the Titanic dataset available through Seaborn.

The goal is to practice data preprocessing, model training, and performance evaluation using Python.

## Dataset
- Source: Seaborn Titanic dataset
- Original records: 891 passengers
- Records after preprocessing: 889 passengers
- Target variable: `survived`
  - 0 = Did not survive
  - 1 = Survived

## Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Data Preprocessing
- Removed selected redundant columns
- Handled missing age values using the mean
- Removed rows with missing embarkation values
- Encoded categorical variables using LabelEncoder
- Converted the dataset to integer data types
- Split the data into training and testing sets (80:20)
- Applied StandardScaler for selected models

## Machine Learning Algorithms
The notebook implements and evaluates the following classification algorithms:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Gaussian Naive Bayes
4. Decision Tree Classifier
5. Support Vector Machine (SVM)

## Model Performance

| Algorithm | Test Accuracy |
|---|---:|
| Logistic Regression | 80.34% |
| K-Nearest Neighbors (KNN) | 79.21% |
| Gaussian Naive Bayes | 77.53% |
| Decision Tree | 80.34% |
| Support Vector Machine (SVM) | 81.46% |

The SVM model achieved the highest test accuracy among these models.

The notebook also evaluates the SVM model using 5-fold cross-validation, with a reported mean accuracy of approximately 82.79%.

## Evaluation Metrics
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score
- Cross-validation

## How to Run
1. Clone this repository:
   `git clone https://github.com/YOUR-USERNAME/titanic-survival-prediction-ml.git`
2. Open the project folder.
3. Install the required libraries:
   `pip install numpy pandas seaborn matplotlib scikit-learn jupyter`
4. Launch Jupyter Notebook:
   `jupyter notebook`
5. Open `logistic_regression.ipynb` and run the cells.

## Key Learnings
- Data cleaning and preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Training classification models
- Comparing model performance
- Evaluating models using classification metrics

## Future Improvements
- Improve preprocessing and feature engineering
- Tune model hyperparameters
- Use pipelines to prevent data leakage
- Compare models using more robust validation

## Author
Abhishek Singh Rawat

GitHub: https://github.com/Abhishekuk04
LinkedIn: Add your LinkedIn profile URL here
