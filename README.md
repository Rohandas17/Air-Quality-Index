# Air Quality Index (AQI) Prediction Model 🌬️

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation & Usage](#installation--usage)
- [Contributing](#contributing)
- [Author](#author)
- [Contact](#contact)

## Introduction
This project presents a regression model designed to predict the Air Quality Index (AQI) value. Using a dataset containing daily AQI readings from various countries, the model leverages a Linear Regression algorithm to forecast AQI based on temporal and categorical features. The workflow includes essential preprocessing steps like date decomposition and one-hot encoding to prepare the data for effective model training.
## Features  
- **Linear Regression Model:** Implements a straightforward and interpretable linear model to predict AQI values.
- **Date-based Feature Engineering:** Decomposes the Date column into Year, Month, and Day to capture temporal patterns in the data.
- **Categorical Data Handling:** Uses one-hot encoding to convert categorical features like Country and Status into a numerical format that the model can process.

## Installation & Usage
**1. Clone the repository:**
```bash
git clone https://github.com/Rohandas17/Air-Quality-Index
cd Air-Quality-Index
```
**2. Installation:**
```bash
python -m venv venv
.\venv\Scripts\activate
pip install pandas scikit-learn
```

**3. Usage:**
```bash
python app.py
```

## Contributing
This project is open source so others can easily get involved. If you'd like to contribute, please fork the repository, create a feature branch, and open a pull request. All kinds of contributions bug fixes, features, or suggestions — are welcome!
