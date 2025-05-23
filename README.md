# Heart Attack Prediction Using Gaussian Naive Bayes

This repository contains the implementation of a heart attack prediction model using the Gaussian Naive Bayes algorithm. The dataset used in this project is `heart.csv`, which contains various medical attributes to predict the likelihood of a heart attack. The project demonstrates the entire workflow, including data preprocessing, model training, evaluation, and visualization of results.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Heart disease is one of the leading causes of death worldwide. Early prediction of heart attacks can significantly improve the chances of successful treatment and survival. This project uses the Gaussian Naive Bayes algorithm to predict the likelihood of a heart attack based on various medical attributes such as age, sex, cholesterol levels, and more.

## Dataset

The dataset used in this project is `heart.csv`, which contains the following attributes:

- Age
- Sex
- Chest Pain Type (4 values)
- Resting Blood Pressure
- Serum Cholesterol in mg/dl
- Fasting Blood Sugar > 120 mg/dl
- Resting Electrocardiographic Results
- Oldpeak = ST depression induced by exercise relative to rest
- and more

## Installation

To get started, clone this repository and install the required dependencies.

```bash
git clone https://github.com/Ich-Asadullah/4-Heart-Attack_prediction_using_guassian-native-bayes.git
cd heart-attack-prediction-using-gaussian-naive-bayes
pip install -r requirements.txt
```

## Usage

- Place the heart.csv file in the project directory.
- Run the Jupyter Notebook to see the entire workflow, including data preprocessing, model training, and evaluation.
```bash
jupyter notebook Heart_Attack_Prediction.ipynb
```

## Results
The project includes detailed evaluation metrics and visualizations to understand the performance of the Gaussian Naive Bayes model. You can find `accuracy scores`, `confusion matrices`, and more in the Jupyter Notebook.

## Contributing
Contributions are welcome! If you have any improvements or new ideas, feel free to open an issue or submit a pull request.

## License
This project is licensed under the `MIT License`.

