# Sonar Rock vs Mine Classification

This project uses Logistic Regression to classify sonar signals as either rocks or mines based on sonar frequency data.

## Dataset
The dataset used is `sonar data.csv`, which consists of 60 numerical features representing sonar signal readings, followed by a label (`R` for rock, `M` for mine).

## Installation
To run this project, install the required dependencies:
```bash
pip install numpy pandas scikit-learn matplotlib
```

## Usage
Run the Jupyter Notebook to:
1. Load and preprocess the dataset.
2. Train a Logistic Regression model.
3. Evaluate model accuracy.
4. Make predictions on new sonar data.

### Example Prediction
```python
input_data = (0.0123, 0.0309, 0.0169, ... , 0.0092, 0.0009, 0.0044)
prediction = model.predict([input_data])
if prediction == "R":
    print("it was rock")
else:
    print("it was mine")
```

## Model Performance
The Logistic Regression model achieved an accuracy of **85.7%** on the test set.

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## License
This project is open-source. Feel free to modify and enhance it!

