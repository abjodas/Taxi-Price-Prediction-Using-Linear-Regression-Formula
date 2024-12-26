
# Taxi Price Prediction using Linear Regression

This repository contains a Jupyter Notebook that demonstrates a linear regression model for predicting taxi prices based on features such as trip distance, duration, and fare structure.

## Features

- Data preprocessing and exploratory data analysis
- Implementation of linear regression using the normal equation
- Calculation of optimal weight parameters for prediction
- Evaluation of model performance using error metrics
- Analysis of Gaussian noise variance

## Dataset

The dataset includes the following features:
- `Trip_Distance_km`: Distance of the trip in kilometers
- `Base_Fare`: Fixed starting fare
- `Per_Km_Rate`: Rate charged per kilometer
- `Trip_Duration_Minutes`: Duration of the trip in minutes
- `Trip_Price`: Total trip fare (target variable)

*(Dataset source: Kaggle)*

## Prerequisites

To run the notebook, ensure you have the following installed:
- Python 3.x
- Jupyter Notebook or JupyterLab
- NumPy
- Pandas
- Matplotlib
- Other optional dependencies listed in the notebook

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/taxi-price-prediction.git
   ```

2. Navigate to the directory:

   ```bash
   cd taxi-price-prediction
   ```

3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

   *(You can create a `requirements.txt` file with the dependencies if needed.)*

4. Launch the Jupyter Notebook:

   ```bash
   jupyter notebook Taxi_Price_Linear_Regression_Formula.ipynb
   ```

## Usage

Open the notebook and execute the cells step by step to:
- Load and preprocess the dataset
- Train a linear regression model
- Analyze the model's performance and predictions
- Understand the impact of Gaussian noise on predictions

## Examples

### Optimal Parameters
Learn how the normal equation is used to derive the weights for linear regression.

### Error Analysis
Evaluate model performance using metrics such as Mean Squared Error (MSE).

### Noise Variance
Understand how Gaussian noise impacts prediction accuracy.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests with improvements or additional features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy Coding!
