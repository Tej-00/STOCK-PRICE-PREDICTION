# Stock Price Prediction

## Project Description
This project is a **Stock Price Prediction Web App** that predicts future stock prices using machine learning techniques.

### Key Features:
- Utilizes a **stacked Long Short-Term Memory (LSTM)** model to capture the sequential nature of stock prices.
- Data is normalized using **Min-Max scaling** to enhance model performance.
- Includes **Moving Average** and **Rolling Mean** for trend detection and noise reduction in stock prices.
- The application's performance is measured by **Mean Square Error (MSE)** and **Mean Absolute Error (MAE)**, ensuring precise prediction evaluations.
- The final project is displayed using **Streamlit**, providing an interactive and easy-to-use interface for users.

### Technology Justification:
The choice of a stacked LSTM model allows for effective learning from past price sequences, crucial for time-series data like stock prices. Streamlit enables a smooth and interactive user experience, ideal for quick data analysis and visualization in a browser interface.

### Challenges Faced:
- Fine-tuning the LSTM layers and sequence length to balance between accuracy and overfitting.
- Implementing moving averages and rolling means without affecting data integrity.
- Managing and visualizing real-time data updates in Streamlit efficiently.

### Future Improvements:
- Implement additional prediction algorithms (e.g., Support Vector Machine) for ensemble learning to increase accuracy.
- Introduce features to compare multiple stocks at once.
- Enhance the user interface with additional data visualization options in Streamlit.

## How to Install and Run the Project

### Prerequisites
- Python 3.x
- Libraries: `TensorFlow`, `Pandas`, `NumPy`, `Streamlit`, and `yfinance`

### Installation
1. Clone the repository:
   ```terminal
   git clone https://github.com/Tej-00/stock-price-prediction.git
   ```
2. Navigate into the project directory:
   ```terminal
   cd stock-price-prediction
   ```
3. Install the required packages:
   ```terminal
   pip install -r requirements.txt
   ```

### Running the Project
1. Fetch data from Yahoo Finance, and process it using the code provided in the repository.
2. Run the Streamlit app:
   ```terminal
   streamlit run app.py
   ```

## How to Use the Project
- On launching, select a stock ticker and date range for predictions.
- View the processed stock price data, moving averages, and predictions.
- Use the interactive Streamlit features to select other stocks and observe prediction changes.

## Contributors

We'd like to thank the following people who have contributed to this project:

- [@Tej-00](https://github.com/Tej-00) - Project Lead, Model Development, Data Preprocessing
- [@vidhiya](https://github.com/vee) - Data Collection, Documentation and Testing
