# CS175 Project
## Demo Code
To run the demo, first run `pip install -r requirements.txt` in a new environment.  
Then run the cells in order. Be sure to run each cell only **once**!
### src/pretrained_models/
This directory contains the pretrained models for all clusters.
### src/sentiment_stock_data/
This directory contains the preprocessed data of the stocks and their average sentiment.
### src/risk_free_rates.csv
This csv file contains the risk-free rate used in the Sharpe ratio.
### src/stock_clustering.ipynb
This file clusters the stocks based on their price trajectories.
### src/stock_and_tweet_preprocessing.ipynb
This file preprocesses the stock data, sentiment data, and the risk-free rate data.
### src/StockTrader.ipynb
This file contains the custom Gym environment, and also trains and evaluates the models.
