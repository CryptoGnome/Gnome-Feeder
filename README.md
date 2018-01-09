# Detailed Profit Trailer Setup Guide

## 1. Create Some Accounts!
Create an account at [CoinBase](https://www.coinbase.com/join/596e0bae9fb680020742d903) (NOW WITH $10 FREE!)
Create an account at one or more of the following 3 supported exchanges: 

[BITTREX](https://bittrex.com/) – 0.25% Fees

[POLONIEX](https://poloniex.com/) – 0.25% Fees

[BINANCE](https://www.binance.com/?ref=11615560) – 0.05% Fees MUCH LOWER & No Dust (If you buy some BNB to pay fees)

Create and verify your accounts and set up 2FA protection.

Go to settings / API keys.

Create TWO API keys with all options enabled, except “withdraw”. Each one will also have a SECRET key with them. IMPORTANT: On Bittrex, make a copy of your secret keys as these will be hidden permanently.

## 2. Buy Your ProfitTrailer License!
Go here: [BUY  LICENSE ](https://profittrailer.com/pt/CryptoGnome/ )

Purchase your ProfitTrailer license.
 
At check out you will be asked to enter your API key. Enter the first API key you created at Bittrex/Poloniex/Binance. (Not your secret key – never give these away).

Send BTC from your wallet to the given wallet address. 

If you bought BTC on Coinbase, log into GDAX and deposit your BTC from Coinbase Wallet to GDAX wallet then withdraw from GDAX wallet to the given ProfitTrailer Checkout wallet. This will avoid the high BTC transaction fees!

Wait for the PT email with your license.

## 3. Buy A Windows VPS!
You NEED a Windows VPS so that the bot runs 24/7 reliably and has a super-fast internet and super-low latency (ping) to snipe those trades!

Go here: [BUY VPS](https://billing.virmach.com/aff.php?aff=3389)

Purchase the correct VPS

1 PT = SSD2G

1 PT + 1 PTF = SSD4G

2 PT = SSD4G

2 PT + 1 PTF = SSD8G

2 PT + 2 PTF = SSD8G

Any location will work

Pay and wait for email with log in details

## 4. Setup the VPS!

Log into the VPS

Open Google Chrome

Install Java 8 JRE

Install Nodepad++

## 5. Setup ProfitTrailer!
Download Latest Profit Trailer Release Here: https://github.com/taniman/profit-trailer/releases and [CryptoGnome's Settings](https://github.com/CryptoGnome/Profit-Trailer-Settings/releases) for PT to your desktop

Unzip the files

Navigate to the CryptoGnome’s settings folder for your exchange and decide on conservative (1-2% Daily Gainz) or moderate (3-7% Daily Gainz) settings and drag them into the proper location in the ProfitTrailer folder.

Open up the application.properties file in Notepad++. 

Update these settings:

trading.exchange = THE EXHANGE YOU ARE USING e.g. BITTREX 

default_apiKey = THE FIRST API KEY YOU CREATED

default_apiSecret = THE FIRST SECRET KEY YOU CREATED

trading_apiKey = THE SECOND API KEY YOU CREATED

trading_apiSecret = THE SECOND SECRET KEY YOU CREATED

server.password = PASSWORD HERE

Click save

Now open your pairs.properties file in your text editor

Update this setting:

WARNING THE BOT WILL START TRADING AND SELL ANYTHING THAT CAN BE SOLD

ALL_trading_enabled = true

Click save

Please read through the ProfitTrailer Wiki to see what you think you should change to get started as we do not like it if you use these settings without changing anything! Now you are ready to go!

## 6. Getting ProfitTrailer Running!
Double click the ProfitTrailer.cmd file that you will find in your ProfitTrailer files. Then go to [http://localhost:8081/monitoring](http://localhost:8081/monitoring)
This is where you will find your dashboard, and where you can monitor your bot.

## 7. Maximize Returns.

- The Bot is ready out of the box however we suggest to tweak the settings a bit because the default settings are just like they sound.. default!

- Visit our current strategies below and feel free to read more about them on the Wiki and change to your liking
https://github.com/CryptoGnome/Bot-Settings/releases







# Helpful Videos
https://www.youtube.com/watch?v=L643dYJs948&list=PLSXs1QhY3SalNEO3ZApUdtRPDuYFr75kz
