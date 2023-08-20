# Linear Regression for Tip Prediction

This repository contains code that demonstrates the process of data preprocessing and training a Linear Regression model to predict tips based on various restaurant features. The project showcases the steps involved in mapping categorical variables, splitting data, and training a regression model.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to predict tips based on restaurant-related features such as total bill amount, customer gender, smoking status, day of the week, time of the meal, and party size.

## Prerequisites

#### Clone the repository : 

```bash
git clone https://github.com/Mohshaikh23/Waiter-Tips-Prediction.git
```

Before running the code, ensure you have the required libraries installed:

- numpy
- pandas
- scikit-learn

You can install them using the following command:

```bash
pip install numpy pandas scikit-learn
```

## Usage

1. Load your dataset into the 'data' DataFrame in the code.
2. Run the code in a Python environment.

## Data Preprocessing

Categorical variables like 'sex', 'smoker', 'day', and 'time' are mapped to numerical values for compatibility with the model. This process is known as label encoding. The data is then split into training and testing sets using `train_test_split()`.

## Model Training

A Linear Regression model is trained using the training data to predict tips based on the provided features. The model uses the total bill amount, customer gender, smoking status, day of the week, time of the meal, and party size as input features to predict tips.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.