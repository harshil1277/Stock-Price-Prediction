# Stock Price Prediction

## Project Overview
This project implements and compares the performance of N-BEATS, ARIMA and LSTM models to predict stock prices. The dataset used contains historical stock prices, and additional features like moving averages and volatility are introduced to enhance the N-BEATS model.

The project includes:
- **Exploratory Data Analysis (EDA)**: Basic insights and visualization of the dataset.
- **Modeling**: Building and training N-BEATS, ARIMA and LSTM models.
- **Model Comparison**: Evaluation of model performance using metrics such as MAE, MSE and RMSE.

## Prerequisites
Before you start, make sure you have Python 3.x installed.

### Create a Virtual Environment

1. Open your terminal or command prompt.
2. Navigate to the project directory where your `.ipynb` file and dataset are located.
3. Create a virtual environment by running the following command:
    ```bash
    python -m venv venv
    ```
4. Activate the virtual environment:
    - On Windows:
      ```bash
      .\venv\Scripts\activate
      ```
    - On macOS and Linux:
      ```bash
      source venv/bin/activate
      ```
### Install Dependencies

1. Ensure you have `pip` installed to manage Python packages.
2. Use the `requirements.txt` file provided in the repository to install all necessary dependencies.

#### Installation Steps:

1. Open your terminal or command prompt.
2. Navigate to the project directory where your `.ipynb` file and dataset are located.
3. Run the following command to install all dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Dataset

Make sure the dataset (e.g., `stock_price.csv`) is placed in the same directory as your Jupyter notebook. The notebook will automatically load this dataset and use it for training and testing the models.

## Running the Jupyter Notebook

To run the `.ipynb` notebook file, follow these steps:

1. Open your terminal or command prompt.
2. Navigate to the project directory.
3. Start Jupyter Lab or Jupyter Notebook by running the following command
```bash
jupyter lab
```
Or
```bash
jupyter notebook
```
4. Once Jupyter opens in your browser, navigate to the `.ipynb` file and open it.
5. Ensure that the dataset (e.g., `stock_price.csv`) is in the same directory as the `.ipynb` file.
6. Run each cell of the notebook to execute the code, including data preprocessing, model training, and evaluation.

### Output
After running the notebook, you will see the following results:

- Plots: Visualizations of time series data, moving averages, ACF, and PACF plots.
- Model Predictions: Forecast outputs from both N-BEATS and LSTM models.
- Evaluation Metrics: Metrics such as MAE and RMSE for each model.
- Comparison: A summary comparing the performance of N-BEATS and LSTM based on evaluation metrics.

### Key Files
- `stock_price_prediction.ipynb`: The Jupyter notebook containing the code for stock price prediction using N-BEATS and LSTM.
- `stock_price.csv`: The dataset file containing historical stock prices.
- `requirements.txt`: The file containing a list of dependencies to run the project.
