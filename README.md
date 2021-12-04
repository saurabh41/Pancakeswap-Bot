# Frontrunning Pancakeswap Sniper Bot For Mempool Snipping. New and Improved
The PancakeSwap Bot Front-runs (specific trade volumes, slippage and gas price) transactions by placing a buy order on the same block and at the same time by setting a higher gas price.

The bot scans the mempool for pending transactions several times every second. Whenever the bot sees the AddLiqudity event of your token, it will front-run the token, so you will be the first one who is able to get the token.

The bot will come with an 30-page instruction guide and an instruction video for easy use.
## Buying Information
If you want to purchase the bot contact me on discord **saurbh#4266** OR **Telegram: <a href="https://t.me/saurbh99">@saurbh99</a>** . You can directly purchase the bot by sending  **0.4 BNB** to this address **0x2ffdee5ad28735839ead1e4848cfcae7e64ea839**  USE **BEP20** Network Only 

## Key Features 
1)Snipes in mempool.
2)Buy, approve, sell in the same block as liquidity.
3)DxSale sniper.
4)Pinksale sniper.
5Autodetect whenever trading is enabled
6)Save mode ( honeypot check before buy)
7)Great error handling
8)Automatic gas settings.
9)Snipes antibot tokens.
10)Timer before buying.
11)Honeypot / Ruggpull checker.
## Bot Settings
![config](https://user-images.githubusercontent.com/92146797/144708875-824a790b-dab2-4aa3-aa81-32a195fbb04a.PNG)

- **PurchaseToken** : Put the contract address of the token you would like to snipe
- **purchaseAmount**: How much would you like to buy of this token in wbnb (The bot is using
wbnb because the event to trade with is faster than paying with bnb. so make sure you have
enough wbnb)
- **websocket**: Fill in your websocket url.
- **websocket**: Fill in your websocket url, more about this on page 14.
- **buys**: fill in how many buy orders you would like to perform, by default this is 1. For example
if you filling in 5, the bot will do 5 buy orders
- **recipient**: Fill in your wallet hash, I have explained how to get this on page 8.
- **Mnemonic (now privatekey)**: Fill in your wallet privatekey

## Other bot setup and settings are explained in PDF guide

## Troubleshot
there are some reason if your tx failed :

- your gas price are to small
- your GWEI are to small
- your slippage are to small

Among the most common ones: web3.exceptions.ContractLogicError: execution reverted. The token contract is wrong or the pair contract may have not been created yet.
