# Data Preprocessing and Regression Model Training for Backpack Price.

This proyect consists of data preprocessing and training of a regression model for Kaggle's Restaurant Revenue Predicition competition. You can download the data from the competition's [page](https://www.kaggle.com/c/restaurant-revenue-prediction/data)

## Included Files

- 'rest_rev_pred.ipynb': notebook containing the preprocessing and model.

## Requirements

To run the project, Python 3.9 and the following libraries are required:  
- pandas  
- numpy  
- scikit-learn 
- jupyter  
- lightgbm  
- optuna
- matplotlib
- seaborn

To install the dependencies, you can use the following command:

```bash
pip install numpy pandas scikit-learn lightgbm optuna matplotlib seaborn jupyter
```

## Download the Dataset
Before running the project, download the dataset from Kaggle, using the link provided above and place it in the same directory as the Jupyter notebook ('rest_rev_pred.ipynb').

## How to run

1. Clone the repository
If you don't have Git installed, first [install](https://git-scm.com/) it, then run this command in your terminal to clone the repository:

```bash
git clone https://github.com/FernanZL/rest_rev_pred.git
```

2. Install the dependencies
Once you have cloned the repository, install the necessary libraries using the following command:
```bash
pip install numpy pandas matplotlib scikit-learn seaborn lightgbm optuna jupyter
```

3. Open the notebook
To open the notebook in Jupyter, run the following command in the terminal:

```bash
jupyter notebook rest_rev_pred.ipynb
```

Within the Jupyter notebook, you can run the code cells one by one by pressing Shift + Enter to perform the analysis and get the results.
