# House Price Prediction

This project predicts house prices using the **California Housing Dataset** with two machine learning models: **Random Forest Regressor** and a **Neural Network** built using TensorFlow/Keras.

## Table of Contents
- [Project Overview](#project-overview)
- [Models Used](#models-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to predict housing prices in California based on features such as:
- Median Income
- House Age
- Average Rooms per Household
- Population, etc.

Two models are implemented:
1. **Random Forest Regressor**: A robust ensemble learning technique.
2. **Neural Network**: A deep learning approach for non-linear relationships.

## Models Used

### Random Forest Regressor
- Trained with 1000 estimators.
- Achieved a Mean Squared Error (MSE) of **0.2514** on the test data.

### Neural Network
- Built with a simple architecture of two hidden layers.
- Achieved a Mean Squared Error (MSE) of **0.2644** on the test data.

## Installation

To run this project locally, clone the repository and install the required dependencies:

```bash
git clone https://github.com/Sudo_User/house-price-prediction.git
cd house-price-prediction
pip install -r requirements.txt
