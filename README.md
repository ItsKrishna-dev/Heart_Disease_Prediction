# Heart Disease Prediction

A machine learning project that predicts the likelihood of heart disease using logistic regression based on various health indicators and patient characteristics.

## Overview

This project analyzes heart disease data to build a predictive model that can help identify patients at risk of heart disease. The model uses 13 different health features to make binary predictions (heart disease present or absent).

## Dataset

The project uses a heart disease dataset (`heart_disease_data.csv`) containing 303 patient records with the following features:

### Input Features:

- **age**: Patient's age (29-77 years)
- **sex**: Gender (0 = female, 1 = male)
- **cp**: Chest pain type (0-3)
- **trestbps**: Resting blood pressure (94-200 mm Hg)
- **chol**: Serum cholesterol level (126-564 mg/dl)
- **fbs**: Fasting blood sugar > 120 mg/dl (0 = false, 1 = true)
- **restecg**: Resting electrocardiographic results (0-2)
- **thalach**: Maximum heart rate achieved (71-202)
- **exang**: Exercise induced angina (0 = no, 1 = yes)
- **oldpeak**: ST depression induced by exercise (0-6.2)
- **slope**: Slope of peak exercise ST segment (0-2)
- **ca**: Number of major vessels colored by fluoroscopy (0-4)
- **thal**: Thalassemia type (0-3)


### Target Variable:

- **target**: Heart disease presence (0 = no disease, 1 = disease present)


## Technology Stack

- **Python 3.x**
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computing
- **scikit-learn**: Machine learning library
    - `LogisticRegression`: Classification algorithm
    - `train_test_split`: Data splitting
    - `accuracy_score`: Model evaluation


## Model Performance

The logistic regression model achieves:

- **Training Accuracy**: 85.1%
- **Test Accuracy**: 81.97%


## Project Structure

```
heart-disease-prediction/
├── HeartDiseasePrediction.ipynb    # Main Jupyter notebook
├── heart_disease_data.csv          # Dataset (not included)
└── README.md                       # Project documentation
```


## Getting Started

### Prerequisites

```bash
pip install pandas numpy scikit-learn jupyter
```


### Running the Project

1. Clone this repository
2. Ensure `heart_disease_data.csv` is in the project directory
3. Open and run `HeartDiseasePrediction.ipynb` in Jupyter Notebook

## Key Insights

- The dataset shows a balanced distribution with 54.5% positive cases
- Most patients are male (68.3%)
- Average age is 54.4 years
- The model demonstrates good generalization with minimal overfitting (3% difference between training and test accuracy)


## Future Improvements

- Feature engineering and selection
- Hyperparameter tuning
- Cross-validation for robust evaluation
- Comparison with other algorithms (Random Forest, SVM, etc.)
- Feature importance analysis
- Model interpretability enhancements


## Usage

The trained model can be used to predict heart disease risk for new patients by providing their health metrics. This tool could assist healthcare professionals in early screening and risk assessment.

## License

This project is for educational and research purposes.

*Note: This model is for educational purposes only and should not be used as a substitute for professional medical advice.*

<div style="text-align: center">⁂</div>

[^1]: HeartDiseasePrediction.ipynb

