# Diabetes Prediction ML Project

## Overview
This project predicts whether a person has diabetes using the PIMA Diabetes dataset. It demonstrates data preprocessing, model training, evaluation, and creating a simple predictive system.

## Dataset
- PIMA Diabetes Dataset (publicly available)
- Contains 8 clinical features such as glucose level, BMI, age, etc.
- Outcome: 0 = Non-diabetic, 1 = Diabetic

## Methods
1. **Data Preprocessing**
   - Loaded dataset with Pandas
   - Standardized features using `StandardScaler`
   - Split data into training and test sets

2. **Model Training**
   - Support Vector Machine (linear kernel)
   - Trained on 80% of the data

3. **Evaluation**
   - Accuracy on training data
   - Accuracy on test data
   - Simple predictive system for individual input data

## Results
- Training Accuracy: ~XX%
- Test Accuracy: ~XX%
- The model can predict diabetes status for new input data

## Usage
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
