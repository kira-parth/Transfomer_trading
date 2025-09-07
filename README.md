# Transfomer_trading
📈 Forex Price Prediction using a Transformer Model This project is a deep learning implementation for forecasting foreign exchange (Forex) market prices. It utilizes a Transformer-based neural network, a state-of-the-art architecture for sequence-based tasks, to predict future closing prices based on historical data and technical indicators.
<img width="1036" height="547" alt="image" src="https://github.com/user-attachments/assets/ab77776b-a589-4fc0-b345-104301209221" />

 How to Use
To run this project on your own machine, follow these steps:

Clone the repository:

Bash

git clone https://github.com/YourUsername/your-repository-name.git
cd your-repository-name
Install the dependencies:
Make sure you have a requirements.txt file with the necessary libraries.

Bash

pip install -r requirements.txt
Add your data:
Place your Forex data in a CSV file in the root of the project directory. The file must contain the following columns: Gmt time, Open, High, Low, and Close.

Run the script:
Execute the main Python script to start the training and evaluation process.

Bash

python your_script_name.py
Alternatively, if you are using the .ipynb notebook, open it in Jupyter or Google Colab and run the cells sequentially.

Model Architecture
The model is based on the Transformer Encoder architecture, originally introduced in the paper "Attention Is All You Need." Instead of using recurrent layers (like LSTMs or GRUs), this model relies entirely on self-attention mechanisms.

The self-attention mechanism allows the model to weigh the importance of different past data points when making a prediction. For instance, it can learn that a sharp price change 15 steps ago is more important than a stable price 5 steps ago. This makes it particularly powerful for capturing complex, long-range dependencies in time-series data.
