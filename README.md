# listing sniper bot

The Telegram Listing Sniper Bot is designed to automatically buy newly listed tokens from the "Coinmarketcap Fastest Alerts" and/or "CoinGecko Fastest Alerts" telegram channels. Before using the bot, ensure you have a Telegram account. Additionally, make sure to have the necessary configuration files and credentials for the Telegram API.

### Requirements
- Telegram Account

#### Telegram Requirements
1. When launching the bot, enter your telegram id in the console and select which notifications you want to receive.
   - Coinmarketcap Fastest 
   - CoinGecko Fastest Alerts
![](https://github.com/deadspyexx/listing-sniper-bot/assets/140325300/3681d9c5-e3db-4dbe-b73b-b9582ae99e9c)

#### Configure the Sniper Bot
1. Obtain the pre-compiled binaries from the "dist" folder. These binaries should work on any platform, including mobile devices.
2. Ensure you have all accompanying files required for the Telegram API.
3. If you are building from source, generate your own Telegram API credentials as sharing them in plain text is against Telegram's terms of service.
4. Rename :

```
# Your wallet address
RECIPIENT=

# Your wallet's private key
PRIVATE_KEY=

# BSC node web socket address
BSC_NODE_WSS=wss://bsc-ws-node.nariox.org:443

# Gas limit for transaction
GASLIMIT="1000000"

# Gas price for transaction
GASPRICE="5"

# CoinGecko settings
COINGECKO=true
COINGECKO_PURCHASEAMOUNT="0.005"

# CoinMarketCap settings
COINMARKETCAP=true
COINMARKETCAP_PURCHASEAMOUNT="0.01"

# Run bot in whitelist only mode?
WHITELIST_ONLY=false

# Always buy whitelisted tokens?
WHITELIST_ALWAYS=true
WHITELIST_PURCHASEAMOUNT="0.05"

# Comma separated list of tokens to whitelist
WHITELIST=
```

Please note that the bot will buy each token only once to avoid duplicate purchases.
