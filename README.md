# Momentum-Trading


## What is Momentum Trading?
Momentum is the speed or velocity of price changes in stock, security, or tradable
instrument. Momentum shows the rate of change in price movement over a period of
time to help investors determine the strength of a trend. Stocks that tend to move with
the strength of momentum are called momentum stocks.

## Dataset
We have Downloaded Data From Yahoo Finance using library **yfinance**.
We just have to Give Start and End period with the Stock Symbol Name.

Here we have Done Two Things:
1. [Predicting Buy and Sell Signal](Momentum_Trading_Predicting_Signals(Buy,Sell).ipynb)
  
    Here we have build a Machine Learning Model Which Predict signals i.e. **Buy** or **sell** of a particular stock.
    RandomForestClassifier outperform other Model like KNeighborsClassifier, DecisionTreeClassifier, SVC, RandomForestClassifier, GaussianNB with 97% Accuracy.
  
![Model_perfomance](download (1).png)
   
2. [Portfolio Managment](Momentum_Trading_Portfolio_Management.ipynb)

    Here we build a Automatic Trading System which Buy the Best Momentum Stock and even Sell when it is not performing well.
    We only have to give the initial amount and the tarding charge.
 
![Model_perfomance](download .png)
