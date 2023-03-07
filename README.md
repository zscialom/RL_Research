# RL_Research
Reinforcement Learning approach for optimal execution

This repository contains the data and the code related to the paper. Results and figures are also available. Helpful codes are also provided to get some insight on the data and the key processes studied.

The main code (with the RL set-up) specifically focuses on the data from Microsoft on the 3rd of November 2014. It has been extracted from a set of files (provided by the University of Toronto) containing other data about other tickers during the whole month of November 2014.

For primary data, please use the following link: 
http://utstat.utoronto.ca/sjaimung/data/Nov-2014.zip

There are totally 180 files including the entire November 2014 data for the following tickers: AMZN, EBAY, FB, GOOG, INTC, MSFT, MU, PCAR, SMH, VOD for every second of the trading day.

Each file contains a structure called LOB where each field has entries corresponding to one
second of the trading day. The following table describes the structure of each data file:

| Field | Description |
| ------------- | ------------- |
| NumberMO | The total count of Buy and Sell market orders during that second of the trading day |
| VolumeMO | The total volume of Buy and Sell market orders during that second of the trading day |
| EventTime | Time stamp milliseconds from midnight at the start of the second (value = 0 at 12:00:00 am) |
| BuyPrice | The list of limit order buy prices at the start of the second |
| SellPrice | The list of limit order sell prices at the start of the second |
| BuyVolume | The list of limit order buy volumes at the start of the second at the corresponding buy prices in the BuyPrice field |
| SellVolume | The list of limit order sell volumes at the start of the second at the corresponding buy prices in the SellPrice field |


