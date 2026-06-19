# Titanic Survival Prediction

This project uses the Titanic dataset to predict passenger survival using Logistic Regression.

The dataset was preprocessed by handling missing values, removing unnecessary columns, applying one-hot encoding, and scaling numerical features.

## Data Preprocessing

* Filled missing values in `Age` using the median
* Filled missing values in `Embarked` using the mode
* Removed unnecessary columns:

  * PassengerId
  * Name
  * Ticket
  * Cabin
* Applied One-Hot Encoding to categorical features
* Scaled features using StandardScaler

## Models Used

* Logistic Regression (Baseline)
* L1 Regularization (Lasso)
* L2 Regularization (Ridge)

## Results

| Model    | Accuracy |
| -------- | -------- |
| Baseline | 81.0%    |
| Lasso    | 79.9%    |
| Ridge    | 80.4%    |

The baseline Logistic Regression model achieved the highest accuracy on this dataset.

## Technologies Used

* Python
* Pandas
* Seaborn
* Matplotlib
* Scikit-Learn
* Jupyter Notebook
