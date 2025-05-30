# Formula 1 Race Winner Prediction using Artificial Neural Network (ANN)

## Overview
This project builds an **Artificial Neural Network (ANN)** model to predict the **winner of Formula 1 races** using historical data. The goal is to analyze past race statistics and use machine learning to forecast race outcomes based on dynamic factors like driver performance, constructor stats, qualifying data, and track conditions.



## Problem Statement
Formula 1 is a high-stakes sport where predicting race outcomes is challenging due to multiple influencing factors. This project attempts to predict the **race winner** using a supervised machine learning approach with an **ANN** trained on historical F1 data.



## Features
- **Historical Dataset**: Data spanning from 1980 to 2022 seasons.
- **Neural Network Model**: Feedforward ANN built for multi-class classification (predicting race winners).
-  **Feature Engineering**: Incorporating dynamic factors like:
  - Driver and Constructor performance
  - Qualifying position
  - Weather conditions (if available)
  - Track-specific variables
- **Performance Evaluation**: Model trained and tested with evaluation metrics like accuracy and confusion matrix.
-  **Visualization**: Training/validation accuracy curves to monitor model performance.



## Tech Stack
- **Python 3.x**
- **Pandas**, **NumPy** (Data Processing)
- **Scikit-Learn** (Preprocessing, Train-Test Split)
- **TensorFlow** / **Keras** (Building and training ANN)
- **Matplotlib**, **Seaborn** (Visualizations)


## Data Science Workflow
- Load and clean the historical Formula 1 dataset.
- Perform feature engineering and preprocessing.
- Build a Feedforward ANN with:
  - Input Layer: Engineered features
  - Hidden Layers: ReLU activation
  - Output Layer: Softmax activation for multi-class classification
- Train the model and monitor performance.
- Evaluate the model on unseen test data.


## Installation

```bash
# Clone the repository
git clone https://github.com/avic7/-Formula-1-Race-winner-prediction-using-Artificial-Neural-Network-ANN-.git
cd -Formula-1-Race-winner-prediction-using-Artificial-Neural-Network-ANN-

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
