# Hyperparameter Optimization using Optuna

## Overview

This project demonstrates hyperparameter optimization using **Optuna** on the Breast Cancer dataset from Scikit-learn. The objective is to improve model performance by automatically searching for the best combination of hyperparameters.

## Dataset

The project uses the **Breast Cancer Wisconsin Dataset** available in Scikit-learn.

Features:

* 30 numerical features
* Binary classification problem
* Target classes:

  * 0 : Malignant
  * 1 : Benign

## Technologies Used

* Python
* Optuna
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Project Workflow

1. Import required libraries
2. Load the Breast Cancer dataset
3. Perform exploratory data analysis
4. Split data into training and testing sets
5. Define the Optuna objective function
6. Optimize hyperparameters
7. Train the model using the best parameters
8. Evaluate model performance

## Hyperparameter Optimization

Optuna is used to:

* Automatically search the parameter space
* Compare different parameter combinations
* Identify the best-performing configuration

Optimization techniques used:

* TPESampler
* RandomSampler

## Results

The study returns:

* Best trial
* Best score
* Best hyperparameters

Example:

```python
study.best_trial.params
```

## Installation

```bash
pip install optuna
pip install scikit-learn
pip install pandas
pip install numpy
```

## Running the Notebook

Clone the repository:

```bash
[git clone https://github.com/yourusername/Optuna-Hyperparameter-Tuning.git](https://colab.research.google.com/drive/1Re42xRjbD9VgUxBJi5lNpVLW_bm7Ofml?usp=sharing)
```

Move into the project directory:

```bash
cd Optuna-Hyperparameter-Tuning
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
optuna.ipynb
```

## Repository Structure

```text
Optuna-Hyperparameter-Tuning/
│
├── optuna.ipynb
├── README.md
└── requirements.txt
```

## Author

Abhi Alekar

---

⭐ If you found this project useful, consider giving the repository a star.
