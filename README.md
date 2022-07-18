## Projects

### 1.stocknote api scanner

Get Stock data , quotes , trade data , automate trading with stock note api 

Stocknote api provides historical data api and also real time data using websockets
streaming

link : https://github.com/mijos52/stocknote_api_scanner

### 2.Search Engine 

Simple search crawler that would index all the links in a given list of urls or
user input url. Searches for links inside a site and assocaites it with a metadata
and keywords are taken form the site metadata

Uses requests library for http requests and beautifulSoup for indexing pagees

link : https://github.com/mijos52/search_engine

![projectimage](https://raw.githubusercontent.com/mijos52/Portfolio/main/Screenshot%20(8).png)

### 3.Tradingview Selinium

Get 500 candlestick bars from tradingview for any Indian or Global listed tickers
Tradingview uses websockets for data. Data are requested using websocket messages
Main limitation is that only 500 bars can be requested and historic candle data is 
limited 

Selinium broswer automation is used for login and websocket library is used to 
get data.

link : https://github.com/mijos52/selinum-tradingview

### 4 Google sheets stock scanner (Nse_scraper name is not accurate)

### Usage
- Spot opportunities in the indian stock market 
- Momentum based scanner to find in play stocks
- Color coded google sheets 


### Features
- Index based filtering (Nifty 50 , Nifty 500) etc
- Live Scanner (Realtime updates)
- Completely free forever
- Uses economictimes API for data

### Screenshots
### Google Sheets
![first_image](https://github.com/mijos52/nse_scraper/blob/19bd86f277091d24a06f2746fab19f2aa2515889/Images/sheets%20scanner.PNG?raw=true)

### Console output
![second_image](https://github.com/mijos52/nse_scraper/blob/master/Images/sheets_scanner_terminal.PNG?raw=true)


Gets stock data from econimictimes website. Data is sorted using python . Econmictimes
api is used to send and receive requests . Query parameters can be customized 
by user for various indices like Nifty 50 ,Nifty 500 etc. The retreived and sorted 
data is then uploaded to google sheets using google sheets API .

link : https://github.com/mijos52/nse_scraper

### 5.Kite Historical Data , Stock Screener and Stock Backtester

Full historical data for all symbols in all segments Futures , Options , Currency , Indices , ETF , Commodity . Uses Kite Zerodha API for data request
Large data can be requested . Data is requested in steps and processed using pandas and numpy.

link : https://github.com/mijos52/kite-historical-data
