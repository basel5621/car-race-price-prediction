# Car Race Price Prediction Project

This project develops predictive models to estimate car prices based on detailed features such as engine horsepower, cylinders, MPG ratings, and more. We explore several statistical models ranging from simple linear regressions to more complex regularized linear models.

## Overview

### Dataset
- **Source**: Locally hosted file `car_race.csv`
- **Features**: Engine HP, Engine Cylinders, Highway MPG, City MPG, Popularity, etc.
- **Label**: Price (transformed to Log Price for modeling)

### Models Implemented using Noraml equation once and once with sklearn library
1. **Base Linear Regression Model**:
   - Features: Engine HP, Engine Cylinders, Highway MPG, City MPG, Popularity

2. **Extended Model with Age Feature**:
   - Additional Feature: Age 

3. **All Features Model Including Categorical Variables**:
   - Categorical Handling: One-hot encoding and Target Encoding for specific features

4. **Regularized Linear Model**:
   - Regularization: Ridge regression to address potential overfitting

## Installation and Usage

### Requirements
- Python 3.x
- Required packages: `numpy`, `pandas`, `seaborn`, `matplotlib`, `scikit-learn`

### Installation

1. Ensure Python 3.x is installed on your machine.
2. Install necessary Python packages:
   ```bash
   pip install numpy pandas seaborn matplotlib scikit-learn
