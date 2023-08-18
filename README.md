<a href="https://imgbb.com/"><img src="https://i.ibb.co/74tGcfW/Fd1.png" alt="Fd1" border="0"></a>
----

FintraDao is an open source  framework that helps you build automated trading strategies, or **bots** that run on cryptocurrency exchanges.

This code is free and publicly available under the Apache 2.0 open source license!

## Why FintraDao?

* **Both CEX and DEX connectors**: Our bots supports connectors to centralized exchanges like Binance and KuCoin, as well as decentralized exchanges like Uniswap and PancakeSwap on various blockchains (Ethereum, BNB Chain, etc).
* **Community-contributed strategies**: The bot community has added many customizable templates for market making, arbitrage, and other algo trading strategies.
* **Secure local client**: Hummingbot is a local client software that you install and run on your own devices or cloud virtual machines. It encrypts your API keys and private keys and never exposes them to any third parties.
* **Community modules and events**: Hummingbot is driven by a global community of quant traders and developers. Check out community-maintained modules like Orchestration, join our bi-weekly developer calls, and learn how to build custom strategies using Hummingbot by taking Botcamp!

Help us **democratize high-frequency trading** and make powerful trading algorithms accessible to everyone in the world!


## Quick Links

* [Docs](https://docs.fintradao.io/home/): Check out the official fintraDao documentation
* [FAQs](https://docs.fintradao.io/home/): Answers to all your burning questions




## Exchange Connectors

Hummingbot connectors standardize trading logic and order types across different exchange types. Currently, we support the following exchange types:

 * **SPOT**: Connectors to central limit order book (CLOB) exchanges that trade spot markets
 * **PERP**: Connectors to central limit order book (CLOB) exchanges that trade perpetual swap markets
 * **AMM**: Connectors to decentralized exchanges that use the Automatic Market Maker (AMM) methodology

Exchanges may be centralized (**CEX**), or decentralized (**DEX**), in which case user assets are stored on the blockchain and trading is performed via wallet addresses.

|Exchange| Exhchange Type |  | |
|------|----------|------|-------------|
 [Binance](https://docs.hummingbot.org/exchanges/binance/) | SPOT CEX |
 [Binance Futures](https://docs.hummingbot.org/exchanges/binance-perpetual/) | PERP CEX | 
 [Uniswap](https://docs.hummingbot.org/exchanges/uniswap/) | AMM DEX |
 [KuCoin](https://docs.hummingbot.org/exchanges/kucoin/) | SPOT CEX | 
 [KuCoin Perpetual](https://docs.hummingbot.org/exchanges/kucoin-perpetual/) | PERP CEX | 
 [Gate.io](https://docs.hummingbot.org/exchanges/gate-io/) | SPOT CEX | 
 [Gate.io Perpetual](https://docs.hummingbot.org/exchanges/gate-io-perpetual/) | PERP CEX | 
 [AscendEx](https://docs.hummingbot.org/exchanges/ascend-ex/) | SPOT CEX | 
 [Quickswap](https://docs.hummingbot.org/exchanges/quickswap/) | AMM DEX |
 [TraderJoe](https://docs.hummingbot.org/exchanges/traderjoe/) | AMM DEX |
 [dYdX](https://dydx.exchange/) | PERP DEX |
 [AltMarkets](https://docs.hummingbot.org/exchanges/altmarkets/) | SPOT CEX |
 [BTC-Markets](https://docs.hummingbot.org/exchanges/btc-markets/) | SPOT CEX |
 [Binance US](https://docs.hummingbot.org/exchanges/binance-us/) | SPOT CEX |
 [BitGet](https://docs.hummingbot.org/exchanges/bitget-perpetual/) | PERP CEX |
 [Bit.com](https://docs.hummingbot.org/exchanges/bit-com) | PERP CEX |
 [BitMart](https://docs.hummingbot.org/exchanges/bitmart/) | SPOT CEX |
 [Bitfinex](https://docs.hummingbot.org/exchanges/bitfinex/) | SPOT CEX |
 [Bitmex](https://docs.hummingbot.org/exchanges/bitmex/) | SPOT CEX |
 [Bitmex (perp](https://docs.hummingbot.org/exchanges/bitmex-perpetual/) | SPOT CEX |
 [Bittrex](https://docs.hummingbot.org/exchanges/bittrex/) | SPOT CEX |
 [Bybit](https://docs.hummingbot.org/exchanges/bybit/) | SPOT CEX |
 [Bybit (perp)](https://docs.hummingbot.org/exchanges/bitmex-perpetual/) | PERP CEX |
 [Coinbase](https://docs.hummingbot.org/exchanges/coinbase/) | SPOT CEX |
 [Defira](https://docs.hummingbot.org/exchanges/defira/) | AMM DEX |
 [Dexalot](https://docs.hummingbot.org/exchanges/dexalot/) | CLOB DEX |
 [HitBTC](https://docs.hummingbot.org/exchanges/hitbtc/) | SPOT CEX |
 [Huobi](https://docs.hummingbot.org/exchanges/huobi/) | SPOT CEX |
 [Injective](https://docs.hummingbot.org/exchanges/injective/) | CLOB DEX |
 [Kraken](https://docs.hummingbot.org/exchanges/kraken/) | SPOT CEX |
 [Loopring](https://docs.hummingbot.org/exchanges/loopring/) | SPOT DEX |
 [MEXC](https://docs.hummingbot.org/exchanges/mexc/) | SPOT CEX |
 [Mad Meerkat](https://docs.hummingbot.org/exchanges/mad-meerkat/) | SPOT DEX |
 [NDAX](https://docs.hummingbot.org/exchanges/ndax/) | SPOT DEX |
 [OKX](https://docs.hummingbot.org/exchanges/okx/) | SPOT CEX |
 [OpenOcean](https://docs.hummingbot.org/exchanges/openocean/) | AMM DEX |
 [Pancakeswap](https://docs.hummingbot.org/exchanges/pancakeswap/) | AMM DEX |
 [Pangolin](https://docs.hummingbot.org/exchanges/pangolin/) | AMM DEX |
 [Perpetual Protocol](https://docs.hummingbot.org/exchanges/perp/) | PERP DEX |
 [Phemex Perpetual](https://docs.hummingbot.org/exchanges/perp/) | PERP CEX |
 [Polkadex](https://docs.hummingbot.org/exchanges/polkadex/) | SPOT DEX |
 [Ref Finance](https://docs.hummingbot.org/exchanges/ref/) | SPOT DEX |
 [Sushiswap](https://docs.hummingbot.org/exchanges/sushiswap/) | AMM DEX |
 [Tinyman](https://docs.hummingbot.org/exchanges/tinyman/) | SPOT DEX |
 [VVS Finance](https://docs.hummingbot.org/exchanges/vvs/) | AMM DEX |
 [XSWAP](https://docs.hummingbot.org/exchanges/xswap/) | AMM DEX |



## Strategies and Scripts

We provide customizable strategy templates for core trading strategies that users can configure, extend, and run. Hummingbot Foundation maintains three **CORE** strategies:

* [Pure Market Making](https://docs.hummingbot.org/strategies/pure-market-making/): Our original single-pair market making strategy
* [Cross Exchange Market Making](https://docs.hummingbot.org/strategies/cross-exchange-market-making/): Provide liquidity while hedging filled orders on another exchange
* [AMM Arbitrage](https://docs.hummingbot.org/strategies/amm-arbitrage/): Exploits price differences between AMM and SPOT exchanges

**CORE** strategies are selected via HBOT voting through quarterly [Polls](https://docs.hummingbot.org/governance/polls/). In addition, the codebase includes **COMMUNITY** strategies that are maintained by individuals or firms in the community. See the [Hummingbot documentation](https://docs.hummingbot.org/strategies) for all strategies supported.

### Scripts

Scripts are a newer, lighter way to build Hummingbot strategies in Python, which let you modify the script's code and re-run it to apply the changes without exiting the Hummingbot interface or re-compiling the code.

See the [Scripts](https://docs.hummingbot.org/scripts/) section in the documentation for more info, or check out the [/scripts](https://github.com/hummingbot/hummingbot/tree/master/scripts) folder for all Script examples included in the codebase.


## Contributions

FintraDao belongs to its community, so we welcome contributions! Please review these [guidelines](./CONTRIBUTING.md) first.

To have your pull request merged into the codebase, submit a on our Snapshot. Note that you will need 1 HBOT in your Ethereum wallet to submit a Pull Request Proposal. 

## Legal

* **License**: FintraDAo is licensed under [Apache 2.0](./LICENSE).

