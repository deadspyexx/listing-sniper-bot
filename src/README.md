
<p align="center"><a href="https://github.com/Scott-778/coinmarketcap-sniperbot"><img src="https://user-images.githubusercontent.com/91510798/154884209-769e345f-7e1a-46b5-ae64-1dff8752b564.PNG" alt="Logo" height="100"/></a></p>
<h1 align="center">CoinMarketCap Sniper Bot</h1>
<p align="center">Sniper bot to buy new tokens listed on CoinMarketCap.</p>



## Getting Started
CoinMarketCap sniper bot that buys BSC tokens when you recieve Telegram notification from this channel https://t.me/CMC_CG_listing_alerts or this channel https://t.me/CMC_fastest_alerts use links and join channels. 
This bot uses Smart Chain BNB to buy tokens not WBNB.

#### First, if you don't have node.js installed go to https://nodejs.org and install the lastest LTS version.
#### Then install git https://git-scm.com/downloads, or you can just download zip file if you don't want to clone repository.
#### Then go to https://my.telegram.org sign in, click Api developement tools and create an app to get app apiID and app apiHash.

Then Use the following commands either in VScode terminal or command prompt 
```
git clone https://github.com/Scott-778/coinmarketcap-sniper-bot.git
```
```
cd coinmarketcap-sniper-bot
```
```
npm install
```
#### Then edit .env file with your bsc wallet address, mnemonic seed phrase, telegram apiId and apiHash in your code editor and save file.

To start bot run this command
```
node cmcBot.js
```

When bot is running it it will ask for your telephone number to log in to Telegram enter your telephone number with country code ex 15555555555 then press enter. Then telegram will send you a code to log in enter that number and press enter. If you have two step verification on the bot will ask for your two step password. Then pick your buying strategy default, low liquidity, medium liquidity, high liquidity or create a custom strategy. Then leave the bot running and when you recieve a notification from the channel you select it will buy that token.

## Channels

#### CoinGecko & CoinmarketCap Listing Alerts Premium https://t.me/CMC_CG_listing_alerts
#### Coinmarketcap Fastest Alerts https://t.me/CMC_fastest_alerts

## Strategies
#### Default: 
This option is if you don't want to enter all your settings everytime you run the bot. Enter your settings in the config.js file and bot will use those settings.
#### Low liquidity strategy: 
This strategy buys all low liquid tokens 1-150 BNB. You can choose your buy and sell tax limits. Choose either CoinMarketCap or CoinGecko. High risk. You don't need to change the config.js file for this option.
#### Medium liquidity strategy:
This strategy buys all medium liquid tokens 150-300 BNB. You can choose your buy and sell tax limits. Choose either CoinMarketCap or CoinGecko. Medium risk. You don't need to change the config.js file for this option.
#### High liquidity strategy:
This strategy buys all high liquid tokens 300-700 BNB. You can choose your buy and sell tax limits. Choose either CoinMarketCap or CoinGecko. You don't need to change the config.js file for this option.
#### Custom strategy:
This strategy buys any token within your own custom settings. You can set you own liquidity and tax limits.Choose either CoinMarketCap or CoinGecko. Low risk. You don't need to change the config.js file for this option.

## Screenshots

![ghss2](https://user-images.githubusercontent.com/91510798/154159575-bdebb6cb-b81d-4567-8733-3dca4ae743d6.png)
## Features coming soon
Soon I will add support for different Telegram channels.

## Social
Join my telegram group where we can talk about this project, tokens and the best strategies. https://t.me/CoinMarketCapSniperBot



## Disclaimer
Use at your own risk. Investing in cryptocurrency is risky. This is not financial advice.
There is a small 0.7% buying fee per buy. This is to help me buy a cup of coffee and support for this project. 
If you have an issue please don't post screenshots with personal information like seed phrase, telephone number, Telegram code, Telegram two factor password, or Telegram string session. Please keep that information private!
## Supporters
[![Stargazers repo roster for @Scott-778/coinmarketcap-sniper-bot](https://reporoster.com/stars/Scott-778/coinmarketcap-sniper-bot)](https://github.com/Scott-778/coinmarketcap-sniper-bot/stargazers)

