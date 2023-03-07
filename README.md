# RL_Research
Reinforcement Learning approach for optimal execution

For primary data, please use the following link: 
http://utstat.utoronto.ca/sjaimung/data/Nov-2014.zip

There are totally 180 samples, with the entire November (18 trading days from Nov 3 to Nov 26) trading data for 10 stocks. There is no trading data on Nov 27 due to holiday reason, and the exchange closed early at 1pm est on Black Friday Nov 28.

The following table describe the structure of each data file:

| Field | Description |
| ------------- | ------------- |
| NumberMO | The total count of Buy and Sell market orders during that second of the trading day |
| VolumeMO | The total volume of Buy and Sell market orders during that second of the trading day |
| EventTime | Time stamp milliseconds from midnight at the start of the second (value = 0 at 12:00:00 am) |
| BuyPrice | The list of limit order buy prices at the start of the second |
| SellPrice | The list of limit order sell prices at the start of the second |
| BuyVolume | The list of limit order buy volumes at the start of the second at the corresponding buy prices in the BuyPrice field |
| SellVolume | The list of limit order sell volumes at the start of the second at the corresponding buy prices in the SellPrice field |


