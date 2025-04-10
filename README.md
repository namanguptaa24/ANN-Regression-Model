ANN Regression Model for Used Bikes Price Prediction

📌 Project Overview

This project uses an Artificial Neural Network (ANN) for predicting the price of used bikes based on various features like kilometers driven, bike age, power, and categorical attributes like brand, city, and ownership type. The dataset is preprocessed and fed into a deep learning model built using TensorFlow and Keras.

📂 Dataset

The dataset contains the following key columns:

bike_name: Name of the bike

city: Location where the bike is sold

owner: Ownership type (First Owner, Second Owner, etc.)

brand: Brand of the bike

kms_driven: Total kilometers driven

age: Age of the bike in years

power: Engine power

price: (Target Variable) Selling price of the bike

🔧 Preprocessing Steps

Identify Feature Types:

Categorical: bike_name, city, owner, brand

Numerical: kms_driven, age, power

Preprocessing Techniques:

One-Hot Encoding for categorical features

Standardization for numerical features

Train-Test split (80-20 ratio)

🏗 Model Architecture

Input Layer: Matches preprocessed feature size

Hidden Layers:

64 neurons (ReLU activation)

32 neurons (ReLU activation)

Output Layer:

1 neuron (linear activation for regression)

⚙️ Training Details

Loss Function: Mean Squared Error (MSE)

Optimizer: Adam

Batch Size: 32

Epochs: 50

Evaluation Metric: Mean Absolute Error (MAE)

📊 Results

The model is evaluated using MSE and MAE.

Performance metrics indicate how well the model predicts used bike prices.

🚀 How to Run

Install dependencies:pip install pandas scikit-learn tensorflow

pip install pandas scikit-learn tensorflow

Run the script:python ann_regression.py
