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







## Exchange Connectors

Hummingbot connectors standardize trading logic and order types across different exchange types. Currently, we support the following exchange types:

 * **SPOT**: Connectors to central limit order book (CLOB) exchanges that trade spot markets
 * **PERP**: Connectors to central limit order book (CLOB) exchanges that trade perpetual swap markets
 * **AMM**: Connectors to decentralized exchanges that use the Automatic Market Maker (AMM) methodology

Exchanges may be centralized (**CEX**), or decentralized (**DEX**), in which case user assets are stored on the blockchain and trading is performed via wallet addresses.

|Exchange| Exhchange Type |  | |
|------|----------|------|-------------|
 [Binance](https://docs.fintradao.io/home/) | SPOT CEX |
 [Binance Futures](https://docs.fintradao.io/home/) | PERP CEX | 
 [Uniswap](https://docs.fintradao.io/home/) | AMM DEX |
 [KuCoin](https://docs.fintradao.io/home/) | SPOT CEX | 
 [KuCoin Perpetual](https://docs.fintradao.io/home/) | PERP CEX | 
 [Gate.io](https://docs.fintradao.io/home/) | SPOT CEX | 
 [Gate.io Perpetual](https://docs.fintradao.io/home/) | PERP CEX | 
 [AscendEx](https://docs.fintradao.io/home/) | SPOT CEX | 
 [Quickswap](https://docs.fintradao.io/home/) | AMM DEX |
 [TraderJoe](https://docs.fintradao.io/home/) | AMM DEX |
 [dYdX](https://docs.fintradao.io/home/) | PERP DEX |
 [AltMarkets](https://docs.fintradao.io/home/) | SPOT CEX |
 [BTC-Markets](https://docs.fintradao.io/home/) | SPOT CEX |
 [Binance US](https://docs.fintradao.io/home/) | SPOT CEX |
 [BitGet](https://docs.fintradao.io/home/) | PERP CEX |
 [Bit.com](https://docs.fintradao.io/home/) | PERP CEX |
 [BitMart](https://docs.fintradao.io/home/) | SPOT CEX |
 [Bitfinex](https://docs.fintradao.io/home/) | SPOT CEX |
 [Bitmex](https://docs.fintradao.io/home/) | SPOT CEX |
 [Bitmex (perp](https://docs.fintradao.io/home/) | SPOT CEX |
 [Bittrex](https://docs.fintradao.io/home/) | SPOT CEX |
 [Bybit](https://docs.fintradao.io/home/) | SPOT CEX |
 [Bybit (perp)](https://docs.fintradao.io/home/) | PERP CEX |
 [Coinbase](https://docs.fintradao.io/home/) | SPOT CEX |
 [Defira](https://docs.fintradao.io/home/) | AMM DEX |
 [Dexalot](https://docs.fintradao.io/home/) | CLOB DEX |
 [HitBTC](https://docs.fintradao.io/home/) | SPOT CEX |
 [Huobi](https://docs.fintradao.io/home/) | SPOT CEX |
 [Injective](https://docs.fintradao.io/home/) | CLOB DEX |
 [Kraken](https://docs.fintradao.io/home/) | SPOT CEX |
 [Loopring](https://docs.fintradao.io/home/) | SPOT DEX |
 [MEXC](https://docs.fintradao.io/home/) | SPOT CEX |
 [Mad Meerkat](https://docs.fintradao.io/home/) | SPOT DEX |
 [NDAX](https://docs.fintradao.io/home/) | SPOT DEX |
 [OKX](https://docs.fintradao.io/home/) | SPOT CEX |
 [OpenOcean](https://docs.fintradao.io/home/) | AMM DEX |
 [Pancakeswap](https://docs.fintradao.io/home/) | AMM DEX |
 [Pangolin](https://docs.fintradao.io/home/) | AMM DEX |
 [Perpetual Protocol](https://docs.fintradao.io/home/) | PERP DEX |
 [Phemex Perpetual](https://docs.fintradao.io/home/) | PERP CEX |
 [Polkadex](https://docs.fintradao.io/home/) | SPOT DEX |
 [Ref Finance](https://docs.fintradao.io/home/) | SPOT DEX |
 [Sushiswap](https://docs.fintradao.io/home/) | AMM DEX |
 [Tinyman](https://docs.fintradao.io/home/) | SPOT DEX |
 [VVS Finance](https://docs.fintradao.io/home/) | AMM DEX |
 [XSWAP](https://docs.fintradao.io/home/) | AMM DEX |



## Strategies and Scripts

We provide customizable strategy templates for core trading strategies that users can configure, extend, and run. Hummingbot Foundation maintains three **CORE** strategies:

* [Pure Market Making]: Our original single-pair market making strategy
* [Cross Exchange Market Making]: Provide liquidity while hedging filled orders on another exchange
* [AMM Arbitrage]: Exploits price differences between AMM and SPOT exchanges

**CORE** strategies are selected via  voting through quarterly. In addition, the codebase includes **COMMUNITY** strategies that are maintained by individuals or firms in the community.
### Scripts

Scripts are a newer, lighter way to build Hummingbot strategies in Python, which let you modify the script's code and re-run it to apply the changes without exiting the Hummingbot interface or re-compiling the code.



## Contributions
1
FintraDao belongs to its community, so we welcome contributions! 

To have your pull request merged into the codebase, submit a on our Snapshot. Note that you will need 1 FGT in your BSC wallet to submit a Pull Request Proposal. 

## Legal

* **License**: FintraDAo is licensed under [Apache 2.0](./LICENSE).

