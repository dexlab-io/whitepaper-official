# Dexwallet
![](https://i.imgur.com/KDXmYHG.png)



## Abstract
The mobile wallet for decentralized finance. Borrowing, lending, exchange and staking in one place. Start building your passive income strategy now.

## Introduction
### What is Decentralized Finance?
Decentralized Finance *(aka DeFi)*, otherwise better referred to as **open finance** is a new set of financial primitives that use smart contracts to recreate traditional financial products and services in an environment where incentives, fault tolerance, and data availability are guaranteed by open source software verifiable by anyone.

Open finance enables permissionless, trust-minimized financial infrastructure being built on top of the Ethereum blockchain.

### Core principles of DeFi

**Interoperability and Open Source**: DeFi protocols are built with interoperability into account. This helps strengthen the compounding effects of all the projects as a whole. Open sourcing helps us reach this goal by allowing us to collectively understand how all of our products can be woven together on a technical level.

**Accessibility and Financial Inclusion :**  The open financial system is accessible to anyone with an internet connection.

**Financial Transparency :** Decentralized financial services are not be built in opaque silos. Informations are transparent and auditable to all participants, users don't have to trust a central party to ensure that transactions are valid.

**Censorship Resistance:** No central party is able to reverse the order of transactions and turn off the service.


### The open finance landscape

The rise of blockchains has enabled anyone to own and transfer assets across an open network without needing to trust any external parties. Unlike existing financial architecture, blockchains are freely and equally available worldwide. 

This has led to a large and rapidly increasing number of financials primitives being built on top of the Ethereum blockchain.

Such financial instruments are generally broken up into the following categories:

* Asset Exchange
* Insurance
* Indexing/Baskets
* Lending
* Derivatives
* Stablecoins
* Smart Securities
* Prediction Markets
* Open Source Banking Applications

![](https://i.imgur.com/ZjgUQRl.jpg)


#### Examples:

[MakerDAO](https://makerdao.com/)  —  a decentralized system that allows users to collateralize crypto-assets to create the DAI stablecoin.

[Compound](https://compound.finance/)  —  a decentralized protocol for money markets on the Ethereum blockchain. Users can lend their crypto assets for algorithmically set interest rates.

[Kyber Network](https://kyber.network/)  —  an on-chain liquidity protocol that allows any application to access decentralized token swaps.

[dy/dx](https://dydx.exchange/)  —  a decentralized protocol for derivatives and margin trading on the Ethereum blockchain.


### Why do we need DeFi over traditional finance?

Tradition finance is built on the premise that ordinary people pass control over their assets to banks and other financial intermediaries so professional managers can work wisely with the money in the markets.

The result is a strongly centralized landscape that keeps control and risk at the center of the system.

**We know for a fact that bankers are fallible**, as experienced as they may be, they can still fail to see risks in the markets, as in the 2008 housing bubble.

A single point of failure also means a single place where risk accumulates and endangers the entire system.

**Open finance is about disintermediation**, compared to traditional finance where financial services are invetibly operated through an intermediary who charges rent for mediating financial transactions, Ethereum-based financial services connect individuals peer-to-peer and allow them to access basic financial instruments easily and affordably without the need of intermediaries.

DeFi achieves that by coordinating economic behavior via many smart contracts that perform functions that might otherwise be performed by financial institutions.

A growing number of experts envision DeFi impacting the financial world the same way that open source software has changed software products.

## Product Vision
The goal of DexWallet is to empower millions to have financial freedom via DeFi. We do that by providing cutting-edge technology to make DeFi opportunities accessibles to anyone.

The number one problem with decentralized applications is UX. Dexwallet streamlined user experience is designed for both power and novice users. We build interfaces that provide clarity, reduce complexity and provide users with tools to make sophisticated operations seamless.

What makes Dexwallet unique is the understanding that interoperability between DeFi protocols generates a compounding effect to maximize the financial value that wouldn't be otherwise accessible by a single protocol.

> **Dexwallet is more than the sum of his parts.** 
> *Alessio Delmonti, Founder of Dexwallet.* 

### Native integrations and recipies

Dexwallet does not provide a dapp browser, instead it provides a native user interface for smartcontracts.

#### Why native integrations?

1. Using a dapp within a web3-enabled browser dapp is clunky and unacceptable UX. Any legitimate experiences on mobile today happen in native apps.

2. As someone who already has ETH and tokens, needing to transfer some of these funds permanently from my preferred mobile wallet to another account in order to use a dapp is an awkward experience.

3. Web dApp are insecure, suffering from phishing and dns attacks. ([Source](https://news.bitcoin.com/myetherwallet-servers-are-hijacked-in-dns-attack/)) ![](https://i.imgur.com/iloo6XA.png)
4. Single web-based dApps limit the potential of combining protocols together via batched transactions.
5. Native integrations are resiliant, since they are connected directly to the blockchain. ![](https://i.imgur.com/tUhYsxe.png)

Furthermore, any native integration in Dexwallet acts like a building block to seemless execute financial strategies, we call them *recipies*.


#### What are recipies?
> **Recipes are a way to extract the maximum financial value by a batch of signed Ethereum transactions.**
> *Alessio Delmonti, Founder of Dexwallet.* 

Recipes can be extended to any number of txs to take advantage of complex opportunities involving arbitrage or stacking, furthermore by using recipes you could easily switch from one strategy to another in one-click.

**A simple example:**

Alice has 1 ETH, she wants to open a CDP to draw some DAI that she can then lend to Compound finance for a yield of 10%.

Using Metamask or Trust wallet this is the process:
1. Alice visits https://cdp.makerdao.com/
2. Connects her wallet
3. Compile the CDP
4. Finalize and conferm in the website
5. Confirm in Metamask/Trustwallet
6. Adjust gas if needed
7. Wait for a block to mine
8. Visit https://compound.finance/
9. Enable DAI allowance
10. Confirm in Metamask/Trustwallet
11. Adjust gas if needed
12. Wait for a block to mine
13. Click supply
14. Finalize and conferm in the website
15. Confirm in Metamask/Trustwallet
16. Adjust gas if needed
17. Wait for a block to mine
18. Done

Using Dexwallet this is the process:
1. Alice opens Dexwallet
2. Selects ETH to Lended DAI Recipe
3. Compile amount
4. Approves transaction in the Dexwallet
5. Done

Example of other one-click possible recipies:

- Leveraging ETH with Liquidity pool
- Leveraging ETH with MakerDAO
- Carry trade with leveraged stablecoin
- Arbitrage between Decentralized exchange
- Move assets from mainchain to a sidechain

Many more recipies are possible, at Dexwallet we focus on delivering DeFi One-click strategies that make people money.

### How is Dexwallet different from Trust or imToken?

Trust and imToken are focusing on supporting multiple chains neglecting the value of DeFi in their product.

Access to dapp is provided only by a web3 webview, vulnerable to DNS, phishing attacks and downtime.

Dexwallet makes DeFi protocols first-class citizens in the wallet experience, providing resilian and secure interfaces.

**A simple example:**

Bob's DAI portfolio looks like this:
* 100 DAI in his hot wallet 
* 20DAI in Uniswap liquidity pool
* 100DAI supplied in Compound Finance
* 30DAI in Fulcrum iToken
* 2000DAI in Idex exchange smart contract
* 1000DAI in Dharma Lever
* 100DAI in dy/dx
* 2000DAI in a Kyber Network reserve.

When Bob opens Trust Wallet or imToken **he only sees 100DAI**, he has no understanding of how his wealth is deployed and how his investment is performing.

When Bob opens Dexwallet, **he sees a total of 5350DAI**, where his capital is deployed, and how much interest is gaining. In one click, he can interact with all this protocol to rebalance his portfolio.

Bob, using Dexwallet, can manage his assets across a unified customer experience. Desktop and mobile both.

![](https://i.imgur.com/XmWUI3Z.png)


### How is Dexwallet different from Argent Wallet?

The main goal of Argent Wallet is to replace seed phrases, by using smart contract wallets and Guardians.

Guardians are not a new concept in the smart contract industry, Argent has mutuated it to a smart contract wallet.

Smart contract wallets are an interesting evolution that we are observing and researching closely.

Marketing claims aside, the reality is that each smart contract adds a non-zero chance of taking your position to -100% via bugs. 

This has happened many times by some of the best known players in the space like Parity.

A vulnerability was found on the Parity Multisig Wallet version 1.5+, which allowed an attacker to steal over 150,000 ETH (~30M USD). *([Source](https://blog.zeppelin.solutions/on-the-parity-wallet-multisig-hack-405a8c12e8f7))*

A user has accidentally evaporated $300 million from a Polkadot project smart contracts. *([Source](https://medium.com/cybermiles/i-accidentally-killed-it-and-evaporated-300-million-6b975dc1f76b))*

Dexwallet has a different mission from Argent, we focus on what our user wants most. An easy way to generate passive income using DeFi and cryptocurrencies.

If and when smart contract wallet will prove themselves to be secure, Dexwallet will just fork Argent smartcontracts being open source software.

### Why users choose Dexwallet?

There are many reasons why users trust and use Dexwallet.

**Some of them love the smooth user experience.**

![](https://i.imgur.com/yFZHSwa.png)
![](https://i.imgur.com/exX2bIq.png)

**Some other like how easy is to use DeFi products.**
![](https://i.imgur.com/4exBOHG.png)
![](https://i.imgur.com/n3L0aD1.png)
*(˄About Uniswap Liquidity Pool management tools)*

**Some care about being ahead of the curve with new features.**

![](https://i.imgur.com/IDARiwY.png)
![](https://i.imgur.com/R0ZTTp2.png)

**Many use it to generate passive income easily**

![](https://i.imgur.com/joqlReo.png)
![](https://i.imgur.com/WR2YqhL.png)


**Others love the community we are building**
![](https://i.imgur.com/4YhECmj.png)


Whatever the reason is we work hard to deliver the best possible value for our users. 

We see early adopters as an extended family which is supporting us along the way, we are bootstrapping this project since day one, trying to give the best we can every day.

## The Master Plan

> Build a usable entry point for DeFi
Build pro tools for financial DeFi strategies
Use that money to build an even more simplified DeFi strategies
While doing above, also give financial indipendece to your users.
Tell eveyone.
*Alessio Delmonti, Founder of Dexwallet.* 

## Our journey

We believe in an agile way and user centric approach to develop products, our roadmap is often re-organized based on the continuos feedback loop with our users.

### So far...
DexWallet Progress in the last months.

- Oct 10, 2018 | DexWallet first Announcement | https://medium.com/dexlab-io/introducing-dexwallet-39afa2311300
- Oct 26, 2018 | DexWallet is the Fist Wallet Supporting xDAI Network Ever | https://medium.com/dexlab-io/dexwallet-welcomes-poas-xdai-chain-17d4a45a3453
- Oct 27, 2018 | DexWallet is giving away Free ENS Names | https://medium.com/dexlab-io/dexwallet-is-giving-away-ens-names-for-a-limited-time-only-3a985bfe4ef7
- Oct 28, 2018 | DexWallet New UI + Several Cool Features | https://medium.com/dexlab-io/dexwallet-new-ui-several-cool-features-ab09bc0a98a3
- Nov 14, 2018 | DexWallet Team won the POA 1st Prize at the #cryptolife Status Hackathon 
- Feb 6, 2019 | DexWallet Compound Integration | https://twitter.com/Alexintosh/status/1093229910175481861
- Feb 17, 2019 | DexWallet Collectibles Support and Native dApp store | https://twitter.com/Alexintosh/status/1096928006772346880 
- Feb 18, 2019 |  256% increase in downloads for DexWallet
- Feb 22, 2019 | DexWallet featured in StateOfTheDapps | https://twitter.com/Alexintosh/status/1098931174234341376
- Feb 27, 2019 | DexWallet Introduce Native Bridge DAI ⇢ xDAI and xDAI ⇢ DAI | https://twitter.com/Alexintosh/status/1100688159581573122
- Mar 8, 2019 | Design exploration on saving accounts! | https://twitter.com/dimarconicola/status/1104039048367226880
- Mar 17, 2019 | KyberNetwork native DApp inside DexWallet | https://twitter.com/Alexintosh/status/1107405829936959489
- Mar 23, 2019 | Introducing DeFi Tab in DexWallet | https://twitter.com/Alexintosh/status/1109476140727631872
- Mar 25, 2019 | DexWallet is featured on etherscan ! https://twitter.com/Alexintosh/status/1110111883879727106
- Mar 28, 2019 | @UniswapExchange integration in @DexWallet 🦄 | https://twitter.com/Alexintosh/status/1111281627873902593
- Mar 29, 2019 | Official Announcement Stake Capital & DexWallet @DexWallet partner together for Staking 🚀 |  https://twitter.com/crypto__mak/status/1111760200506077185
- Mar 31, 2019 | Community members start earning passive income | https://twitter.com/JordiMorris1/status/1112447435215904775
- Apr 9, 2019 | TheBlock Researcher says: DexWallet is probably best mobile wallet i’ve used to date. | https://twitter.com/teo_leibowitz/status/1115638567701585920
- Apr 23, 2019 | UniswapExchange Liquidity Management App | https://twitter.com/Alexintosh/status/1120742355861213184
- Apr 24, 2019 | Over $1.8M managed by single DexWallet | https://twitter.com/Alexintosh/status/1120975274038976513
- Apr 25, 2019 | Dydx integration in @DexWallet | https://twitter.com/Alexintosh/status/1121406122110455809
- Apr 25, 2019 | Tour Mode | https://twitter.com/dimarconicola/status/1121702820598689792
**[Add new stuff here]**

### And beyond

- [ ] Staking tools Livepeer
- [ ] PRO Version
- [ ] BZX iFulcrum integration
- [ ] Staking tools Loom 
- [ ] Automated lending Recipe
- [ ] Leverage ETH registry
- [ ] Automated arbitrage Recipe
- [ ] Automated Market Making Recipe
- [ ] Android Version
- [ ] Desktop Version