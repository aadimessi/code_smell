# Code Smell Detection using Machine Learning

A machine learning based system for detecting code smells in Python source code using TF-IDF feature extraction and XGBoost classification.

## Features

- Detects multiple types of code smells in Python programs
- Uses TF-IDF vectorization for source code analysis
- Trained using XGBoost classifier
- Supports real-time code prediction
- Includes Streamlit-based user interface

## Technologies Used

- Python
- Scikit-learn
- XGBoost
- Pandas
- NumPy
- Streamlit
- Joblib

## Code Smells Detected

- Chain Indexing
- Data Leakage
- Long Method
- Duplicate Code
- In-Place APIs Misused
- Hyperparameter Not Explicitly Set
- Randomness Not Controlled
- Unused Variable
- Gradients Not Cleared

## Project Workflow

1. Dataset preprocessing
2. TF-IDF feature extraction
3. Model training using XGBoost
4. Model evaluation
5. Real-time prediction

## Model Performance

- Accuracy
- Precision
- Recall
- F1-Score

## How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Repository Structure

```text
code-smell-detection/
│
├── app.py
├── train_model.py
├── preprocessing.py
├── predict.py
├── requirements.txt
├── model.pkl
└── README.md
```

## Author

Adithyan Hemakumar
