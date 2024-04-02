# Earning-money-using-LSTM!

## Stock Market Prediction and Trading Bot Evaluation

Let's create a trading bot using LSTM that gives positive returns! This repository represents an attempt to assess the effectiveness of LSTM neural networks in predicting stock market trends and developing a trading bot strategy. Please note that this project is primarily an exploration and evaluation exercise and does not claim originality in model architecture or trading strategy.

### About the Project

The project originated from a Kaggle Jupyter notebook and utilized the Nifty-50 dataset for training and testing purposes. The dataset spans from 2000 to 2021 and provides comprehensive stock market data for analysis and modeling. 

For the LSTM model, a train-test split strategy was implemented to assess its predictive performance. Following model training, the LSTM predictions were utilized within a greedy trading strategy to evaluate potential profit-generation opportunities in the stock market.

### Kaggle Notebook and Dataset

The project is based on a Kaggle notebook, which can be accessed via this [Kaggle Notebook Link](https://www.kaggle.com/code/dobariyanaitik/predicting-stocks-and-earning-using-lstm-rnn/notebook). The dataset used in the project, the Nifty-50 dataset, is freely available on Kaggle. 

### Pseudocode for Trading Bot Strategy

The trading bot strategy employed in this project can be summarized as follows:

Loop through each day's predicted and actual prices:
    If the predicted price is higher than the actual price:
        buy shares using available money.
    If the predicted price is lower than the actual price:
        sell shares to convert them into money.
Calculate the final amount based on the remaining shares and available money

### Libraries Used

The project relies on various libraries for implementation, including:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- DateTime
- Scikit-learn
- TensorFlow
- Keras

### Results

The LSTM model demonstrated promising performance, achieving an MSE loss of 0.0978 and a mean absolute percent error of 5.6%. 

![__results___25_0](https://github.com/NaitikDobariya/Earning-money-using-LSTM-/assets/113834773/42ff6699-2e36-4c76-ad66-2eb91c3106b2)

Additionally, the trading bot, initialized with an initial amount of 50,000 units of money, was able to generate a profit of 69,751 units.

![image](https://github.com/NaitikDobariya/Earning-money-using-LSTM-/assets/113834773/1494f62f-6a40-4b1f-ab52-da1780f3f52f)

While the model and trading bot show promise, further refinement and validation are necessary before considering deployment in real-world trading scenarios.

Thank you for your interest.
