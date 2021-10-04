# CryptocurrencyCluster
The task of the project is to find cryptocurrencies, the pattern / price of which does not depend on the pattern / price of bitcoin
- I took information on cryptocurrency from cryptocompare
- Transposed data and translated into time series

Selected 100 cryptocurrencies

```
CryptoDict = ['BTC', 'ETH', 'ATOM', 'AVAX', 'XRP','ADA', 'SOL', 'DOT', 'FIL', 'LUNA', 
              'LINK', 'BNB', 'XTZ','LTC','FTT', 'TRX', 'DOGE', 'CELR', 'BCH', 'EOS',
              'FTM', 'OMG', 'ALGO', 'COTI', 'ETC', 'DYDX', 'OKB', 'CELO', 'MATIC',
             'SAND', '1INCH', 'ZIL', 'REP', 'ELF', 'MTL', 'LSK', 'DENT','CVC','AR',
             'ACH', 'XEM', 'WBTC', 'ICX', 'BAT', 'ZEN', 'ZRX', 'RSR', 'LTO', 'UTK',
             'XMR', 'IOST', 'MLN', 'VET', 'SRM', 'JST', 'HBAR', 'NEAR', 'AXS', 'SUSHI',
             'MKR', 'QTUM', 'EGLD', 'ZEC', 'DASH', 'REN', 'NEO', 'KAVA', 'FET', 'CHZ',
             'CRV', 'RVN', 'GRT', 'NULS', 'SHIB', 'MANA', 'AAVE', 'KSM', 'CAKE', 'MIOTA',
             'FLOW', 'ONT', 'RUNE', 'ENJ', 'WAVES', 'ROSE', 'SXP', 'SNX', 'COMP', 'YFI',
             'ONE', 'IOTX', 'UNI', 'HT', 'BTT', 'XLM', 'BSV', 'THETA', 'ICP', 'PUNDIX']
USD = 'USD'
```

DataFrame

<img width="836" alt="Снимок экрана 2021-10-04 в 23 22 12" src="https://user-images.githubusercontent.com/43303016/135919350-0c651c99-4f74-4f68-b5ff-f170834670bc.png">

Preprocess the data and add the date, see what happened

![1](https://user-images.githubusercontent.com/43303016/135918654-eb905539-7c87-43eb-8bc5-6bf0f1c06102.png)

There are about five clusters

![2](https://user-images.githubusercontent.com/43303016/135919653-6300e9ac-77f7-4e65-ad81-47e6a8e10dd8.png)
![Unknown](https://user-images.githubusercontent.com/43303016/135919659-bb875a89-cbc2-4aba-86fb-8ccbf490babe.png)

1 Cluster 

![11](https://user-images.githubusercontent.com/43303016/135921146-d0e36f43-9cfb-40b1-97a0-062372edbe46.png)

2 Cluster

![22](https://user-images.githubusercontent.com/43303016/135921348-2a71cdf3-7403-44de-91dc-a2616c50c1e2.png)

3 Cluster

![33](https://user-images.githubusercontent.com/43303016/135921334-c0a5f2f3-805a-4a0c-9d9c-8577a97b8fbc.png)

4 Cluster

![44](https://user-images.githubusercontent.com/43303016/135921304-2d575f51-f516-4d3e-a36a-99d3b795f4ff.png)

5 Cluster

![55](https://user-images.githubusercontent.com/43303016/135921290-2cdddbd0-cfbf-4fac-88d6-2eb46dd1b99c.png)
