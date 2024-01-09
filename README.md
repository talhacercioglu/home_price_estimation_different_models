# Real Estate Price Prediction

## Introduction
This project involves predicting real estate prices based on various features such as square meter area, number of rooms, number of bathrooms, and the year of construction. Different machine learning models are employed to understand and predict the prices accurately.

## Dataset
The dataset used in this project is stored in the `home_prices.csv` file. It includes the following columns:
- `Square Meter`: Area of the property in square meters.
- `Number of Rooms`: Number of rooms in the property.
- `Number of Bathrooms`: Number of bathrooms in the property.
- `Year`: Year of construction.
- `Price`: Price of the property.

## Code Structure
- `data_generation.ipynb`: Python notebook containing code to generate and save the dataset.
- `exploratory_analysis.ipynb`: Python notebook for exploring and visualizing the dataset.
- `linear_regression.ipynb`: Linear regression model for predicting prices.
- `polynomial_regression.ipynb`: Polynomial regression models with different degrees.
- `knn_regression.ipynb`: K-Nearest Neighbors regression model.
- `svr_regression.ipynb`: Support Vector Regression model.

## Instructions
1. Clone the repository: `git clone https://github.com/your-username/real-estate-prediction.git`
2. Navigate to the project directory: `cd real-estate-prediction`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the Jupyter notebooks to explore the data and models.

## Results
- Linear Regression:
  - Mean Square Error (MSE): 1549375256.54
  - R-squared value: 0.706
  - Mean Absolute Error (MAE): 31039.35
  - RMSLE: 0.143

- Polynomial Regression (Degree 2):
  - MSE: 797085828.07
  - R^2: 0.849
  - MAE: 23166.21
  - RMSLE: 0.112

- K-Nearest Neighbors Regression:
  - MSE: 1458322580.65
  - R^2: 0.724
  - MAE: 30064.52

- Support Vector Regression (Linear Kernel):
  - MSE: 1458322580.65
  - R^2: 0.724
  - MAE: 30064.52

## Conclusion
The polynomial regression model with a degree of 2 seems to provide a good balance between accuracy and model complexity. Consider further tuning or using additional features to enhance model performance.

Feel free to explore different models and contribute to the project by experimenting with new features or improving existing models.
