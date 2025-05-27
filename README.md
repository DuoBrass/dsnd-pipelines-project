# Clothing Review Recommendation Classifier

This project builds a machine learning pipeline to predict whether a customer recommends a clothing product based on review text and metadata features. It includes data preprocessing, feature engineering, and hyperparameter tuning of a Logistic Regression classifier.

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.

### Dependencies

```
pandas
scikit-learn
numpy
```

### Installation

Step by step explanation of how to get a dev environment running (for anaconda prompt)

1.Clone the repository:

```
git clone https://github.com/yourusername/clothing-review-classifier.git

```
2.Change directory into the project folder:

```
cd clothing-review-classifier

```
3.Create a virtual environment
```
python -m venv venv
source venv/bin/activate

```
4.Install required packages:
```
pip install -r requirements.txt

```
## Testing

To run automated tests, run:
```
pytest tests/

```
### Break Down Tests

- test_data_loading.py — verifies dataset loads without errors.
- test_preprocessing.py — tests correct handling of missing values and encoding.
- test_model_training.py — ensures model pipeline trains and predicts as expected.

## Project Instructions

- Load and explore the dataset.

- Preprocess numeric, categorical, and text data appropriately.

- Build a pipeline combining preprocessing with Logistic Regression.

- Fine-tune model hyperparameters

- Evaluate on test set for accuracy/precision

## Built With

- Python - Programming language

- pandas - Data manipulation

- scikit-learn - Machine learning pipeline and models

## License

MIT License


