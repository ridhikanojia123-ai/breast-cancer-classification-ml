# breast-cancer-classification-ml
Machine learning project to classify breast cancer using Logistic Regression, Decision Tree, Random Forest and SVM.
# Breast Cancer Classification Using Machine Learning

## Project Overview
This project uses machine learning classification algorithms to classify breast cancer cases based on diagnostic features. The objective is to compare different classification models and evaluate their performance.

## Dataset
- 569 records
- 33 original columns
- Target variable: `diagnosis`
- Classes: Benign (B) and Malignant (M)

## Tools & Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Data loading and inspection
2. Exploratory Data Analysis (EDA)
3. Data cleaning and preprocessing
4. Handling missing values
5. Encoding the target variable
6. Feature scaling
7. Train-test splitting
8. Model training and evaluation

## Machine Learning Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

## Model Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 96.49% |
| Decision Tree | 92.98% |
| Random Forest | 97.37% |
| Support Vector Machine | 97.37% |

**Best reported F1 Score:** Random Forest — 96.30%

## Key Learning Outcomes
- Practiced data preprocessing and exploratory analysis.
- Compared multiple machine learning classification algorithms.
- Evaluated models using accuracy, precision, recall and F1 score.
- Used a confusion matrix to understand classification performance.

## Project Files
- `breast_cancer_data.ipynb` — Jupyter Notebook containing the analysis and model implementation.
- `breast_cancer_data.pdf` — Project report.

## How to Run
1. Clone this repository.
2. Install the required Python libraries.
3. Make sure the dataset file `breast_cancer_data.csv` is available in the working directory.
4. Open the notebook in Jupyter Notebook or Google Colab.
5. Run the notebook cells.

## Disclaimer
This project is for educational and learning purposes only. It is not intended for medical diagnosis or clinical decision-making.
