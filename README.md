# Diabetes Risk Prediction using Machine Learning

## Project Overview

This project focuses on early diabetes detection using supervised machine learning models. The goal is to classify patients into three categories:

* Non-Diabetic
* Pre-Diabetic
* Diabetic

Machine learning models were trained using medical and demographic features to support faster and more efficient screening.

## Dataset Features

The dataset includes:

* Gender
* Age
* BMI
* Urea
* Creatinine
* HbA1c
* Cholesterol
* Triglycerides (TG)
* HDL
* LDL
* VLDL

Target labels:

* N = Non-Diabetic
* P = Pre-Diabetic
* Y = Diabetic

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Machine Learning Models

* Support Vector Machine (SVM)
* Decision Tree
* K-Nearest Neighbors (KNN)

## Model Performance Comparison

| Model         | Accuracy | Notes                            |
| ------------- | -------: | -------------------------------- |
| Decision Tree |    0.965 | Best overall performance         |
| SVM           |     0.95 | Stable and strong classification |
| KNN           |     0.91 | Baseline model                   |

## Best Performing Model

The Decision Tree model achieved the best overall performance with the highest accuracy and balanced classification across all classes. It also showed strong precision, recall, and F1-score, making it the most suitable model for this dataset.

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Classification Report

## Confusion Matrices

### Decision Tree
![Decision Tree](images/decision_tree_cm.png)

### SVM
![SVM](images/svm_cm.png)

### KNN
![KNN](images/knn_cm.png)

## Workflow

1. Data Loading
2. Data Cleaning
3. Feature Encoding
4. Train/Test Split
5. Feature Scaling
6. Model Training
7. Hyperparameter Tuning
8. Model Evaluation
9. Performance Comparison

## Project Structure

```text
ML_Project
├── images
│   ├── decision_tree_cm.png
│   ├── svm_cm.png
│   └── knn_cm.png
├── diabetes_risk_prediction.ipynb
├── Dataset of Diabetes .csv
└── README.md
```

## How to Run

Clone the repository:

```bash
git clone https://github.com/ShahadAlgadah/diabetes-risk-prediction-ml.git
```

Install dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

Run the notebook:

```bash
jupyter notebook diabetes_risk_prediction.ipynb
```

## Results Summary

Decision Tree achieved the highest performance with an accuracy of 0.965 and balanced classification across all diabetes categories.
SVM showed stable performance with an accuracy of 0.95.
KNN achieved an accuracy of 0.91 and served as a baseline model.

## Author

Shahad Algadah

## License

This project is licensed under the MIT License.
