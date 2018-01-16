# crypto_portfolio_analysis
A Jupyter notebook that helps me get a better viewpoint into my crypto portfolio.

## Requirements
To be able to run the notebook, you'll need to first install the python packages listed in requirements.txt. I suggest doing so in a virtual environment.

```
virtualenv -p python3 env
source env/bin/activate
pip install -r requirements.txt
```

## Data
You need to create a tradesheet which includes your FIAT deposits, FIAT withdrawals, and crypto trades as they occurred in your portfolio. An example is included called tradesheet.csv.

You should also download data in CSV format from https://www.coingecko.com and place it in the data directory. Make sure you keep BTC in the data directory as it's used as the benchmark in the notebook.

## Run
```
jupyter notebook
```
