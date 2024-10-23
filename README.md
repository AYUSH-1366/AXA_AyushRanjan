```python
# Mental Illness Prediction

## Overview
This project uses a stacking classifier with Random Forest, XGBoost, and LightGBM to predict whether an individual will suffer from mental illness based on their lifestyle and demographic features.

## Structure
- src/: Contains the Python scripts used for training and evaluating the model.
- test/: Contains unit tests to validate the model functionality.
- requirements.txt: Lists the dependencies required to run this project.

## How to Run
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the `model_training.py` file in the `src/` folder to train the model.
4. Use the `test/test_model.py` to validate the model.

## Results
The model achieved an accuracy of 63% with a ROC-AUC score of 0.523. Class 0 (No History of Mental Illness) predictions were more accurate compared to class 1.

## Dataset
The dataset used for this project is a mental health dataset, which includes demographic and lifestyle variables.

## Improvements
Future work includes additional feature engineering, cost-sensitive learning, and advanced ensemble methods.

```
