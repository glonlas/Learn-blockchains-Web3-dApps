# Web 3.0 learning content
**Welcome to the Crypto/DeFi/Web3.0 ramp-up page**  
This page is indeded to provide information on Crypto / DeFi / Web3.0 / and Tokenomics. It is a list of short articles and videos you can follow at your own pace.

## Want to contribute? 
Feel free to send your pull-request to add new content you feel relevant to this knowledge sharing page.


## 1. Understand what is blockchain

1. What is a blockchain
    1. [Technical explanation of a blockchain](https://www.youtube.com/watch?v=Jp7T9qtuRIE&ab_channel=DistributedSystemsCourse) (3 min video)
    2. [Why is there so many blockchains](https://podcasts.apple.com/us/podcast/blockchains-explained-with-dragonfly-capitals-haseeb/id1593332793?i=1000554933893) (38 min podcast)
2. Cryptocurrency wallets
    1. [What is Crypto wallet](https://www.youtube.com/watch?v=SQyg9pyJ1Ac&ab_channel=WhiteboardCrypto) (5 min video)
    2. [The Present & Future of Self-Custody with Coinbase Wallet Director of Engineering](https://podcasts.apple.com/us/podcast/the-present-future-of-self-custody-with/id1593332793?i=1000556375654) (33 min podcast)
3. Layer 0 Blockchain (Cross chain interoperability):
    1. [What is Polkadot blockchain](https://www.youtube.com/watch?v=YlAdEQp6ekM&ab_channel=WhiteboardCrypto) (8 min video)
    2. [What is Polkadot blockchain](https://polkadotters.medium.com/what-is-polkadot-85d4af1b2fe7) (article)
    3. [What is Cosmos](https://www.youtube.com/watch?v=y4d8XMBVF1A) (21 min video)
        1. [Cosmos Complete Begineer's guide](https://www.youtube.com/watch?v=sgIGVsg51W8&ab_channel=CoinBureau) (21 min video)
4. Layer 1 Blockchain: 
    1. [Ethereum Explained](https://www.youtube.com/watch?v=BR8jgh6-6gs) (explain blockchain, contract, wallet, ...) (16 min video)
        1. [What is Ethereum v2.0?](https://www.youtube.com/watch?v=pycVClxWUN8) (9 min video)
    2. [What is Cardano blockchain](https://www.youtube.com/watch?v=UMUztLQNqSI&t=439s) (10 min video)
    3. [What is Solana blockchain](https://www.youtube.com/watch?v=1jzROE6EhxM)(10 min video)
        1. [Solana components detailed](https://www.analyticssteps.com/blogs/what-solana-features-and-working-system) (article) 
    4. [What is Avalanche blockchain](https://www.youtube.com/watch?v=CbM2jidEn0s) (10 min video)
        1. [Advantage of Avalanche - a high TPS EMV blockchain](https://cryptobriefing.com/what-is-avalanche-the-layer-1-blockchains-ecosystem-unpacked/) (article)
    5. [What is Fantom blockchain](https://www.youtube.com/watch?v=wPFjbhyLpCY&ab_channel=CoinBureau) (24 min video)
5. Layer 2 Blockchain (Parachain):
    1. [What is a Layer-2 blockchain](https://www.youtube.com/watch?v=9pJjtEeq-N4) (8 min video)
    2. [What is a Layer 2](https://www.youtube.com/watch?v=BgCgauWVTs0) (10 min video)
    3. [Understand Layer 2 with Polygon: What is Polygon](https://www.youtube.com/watch?v=f7F67ZP9fsE) (10 min video)
    4. [What is Polygon](https://www.youtube.com/watch?v=IijtdpAtOt0) (14 min video)
    5. [Blockchain bridges explained](https://www.youtube.com/watch?v=OPfjEtACFMs) (6 min video)
    6. How to [Bridge to Layer 2](https://www.youtube.com/watch?v=z09LyktKau4) (34 min video)
    7. [Layer-2 will not save Ethereum](https://medium.com/coinmonks/layer-2-wont-save-ethereum-a52aa2bd719b) (article)
    8. Binance Smart Chain (BSC)
        1. [BSC is a lost cause](https://github.com/binance-chain/bsc/issues/553) (post)
6. [Detail overview of blockchains](https://medium.com/coinmonks/unhyped-comparison-of-blockchain-platforms-679e122947c1) (article)

**Deep dive:**

* [What is a Merkle Tree](https://www.youtube.com/watch?v=fB41w3JcR7U&ab_channel=Telusko) (3 min video)
* [Anatomy of a blockchain block](https://medium.com/@eiki1212/ethereum-block-structure-explained-1893bb226bd6) (article)
* [How Ethereum nodes communicate together](https://medium.com/orbs-network/the-actual-networking-behind-the-ethereum-network-how-it-works-6e147ca36b45) (article)

**Official Development documentation**

* [Ethereum Development doc](https://ethereum.org/en/developers/docs/) (official doc)
    * [Deep dive into Ethereum P2P network](https://github.com/ethereum/wiki/wiki/%C3%90%CE%9EVp2p-Wire-Protocol) (Ethereum doc)
    * [Deep dive on how Ethereum works](https://github.com/ethereum/wiki/wiki) (Ethereum doc)
* [Solana Development doc](https://docs.solana.com/developing/programming-model/overview)
* [Cardano Development doc](https://docs.cardano.org/)
* [Bitcoin Development doc](https://developer.bitcoin.org/reference/)
* [Polkadot Development doc](https://wiki.polkadot.network/docs/build-build-with-polkadot)
* [Polygon Development doc](https://docs.polygon.technology/)

**To the question:** “How a new node to the network with no past experience can find other nodes?” The answer is there is a list of boot nodes hardcoded in the code. A new nose without any cache will hit these Nodes as entry point, they will share other available nodes addresses. The discovery peer advertisement uses the [Kademelia DHT protocol](https://en.m.wikipedia.org/wiki/Kademlia).
In 2015 when Ethereum started it had only 3 boot nodes (seems to be still the case, this is the only centralize point is the blockchain).

## 2. What is a consensus? What type of consensus exists?

1. [What is a proof of work?](https://www.youtube.com/watch?v=XLcWy1uV8YM) (10 min video)
2. [What is a Proof of stake? How it works](https://www.youtube.com/watch?v=x83EVUZ_EWo) (10 min video)
3. [What is a Proof of stake?](https://www.youtube.com/watch?v=sRgrn9HDYpM&ab_channel=DappUniversity) (5 min video)
4. What is proof of Authority? (Used by smaller blockchain)
5. [What is proof of History?](https://medium.com/solana-labs/how-solanas-proof-of-history-is-a-huge-advancement-for-block-time-178899c89723) (Used by Solana)
6. [13 Proof of (Consensus algorithm) explained](https://www.youtube.com/watch?v=ah94PuwR1DI&t=444s)(12 min)

**Deep dive**

1. [What is a consensus](https://www.youtube.com/watch?v=LFZDpF_A-BE&t=34s&ab_channel=DistributedSystemsCourse) (1 min video)
2. [Paxos Consensus](https://www.youtube.com/watch?v=SRsK-ZXTeZ0&t=809s&ab_channel=DistributedSystemsCourse) (35 min video)
3. [Bysantin Consensus](https://www.youtube.com/watch?v=_e4wNoTV3Gw&ab_channel=DistributedSystemsCourse) (27 min video)
4. [Bitcoin Blockchain consensus](https://www.youtube.com/watch?v=f1ZJPEKeTEY&ab_channel=DistributedSystemsCourse) (20 min video)
5. [Should you use Bitcoin Consensus](https://www.youtube.com/watch?v=MVPkHPEsC4Y&t=2s&ab_channel=DistributedSystemsCourse) (12 min video)

## 3. Blockchain Wallets

1. Must watch: [Explanation of BIP-39: Wallet Mnemonic words derivation](https://youtu.be/hRXcY_tIlrw) (18 min video) 
2. Must watch: [Explanation of BIP-32: Hierarchical Deterministic Wallet](https://youtu.be/2HrMlVr1QX8) (26 minvideo) 
3. [BIP-39: Mnemonic word list](https://github.com/bitcoin/bips/blob/master/bip-0039/bip-0039-wordlists.md) (github)
4. BIP-44: [Hierarchical Deterministic Wallet](https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki) (github) 
    1. [Keys, Addresses, Wallets explained](https://www.oreilly.com/library/view/mastering-bitcoin/9781491902639/ch04.html) (article)
5. BIP-48: [Multi-sig Wallet](https://github.com/bitcoin/bips/blob/master/bip-0048.mediawiki) (github)
    1. [Multi-signature Wallet, how does it work?](https://https://www.makeuseof.com/what-are-multi-signature-wallets/) (article)
6. [Ethereum HD Wallet (BIP-32) spec](https://www.alibabacloud.com/blog/how-ethereum-bip-32-hardware-digital-wallet-works_597788) (article)
    1. [Ethereum HD wallet BIP-32/BIP-44 spec and implementation](https://wolovim.medium.com/ethereum-201-hd-wallets-11d0c93c87f7) (article)
    2. [Ethereum Mnemonic BIP-39 specs and implementation](https://wolovim.medium.com/ethereum-201-mnemonics-bb01a9108c38) (article)
7. [Solana Wallet specs](https://docs.solana.com/wallet-guide/paper-wallet) (official docs)
8. [Cardano Wallet specs](https://input-output-hk.github.io/cardano-wallet/) (official doc)

### 3.1 Wallet Connect

[What is Wallet connect?](https://www.youtube.com/watch?v=PHRPoSRXPI0) (13 min video) 

## 4. What is the notion of Web3.0. Example of products using it

* [What is Web3.0](https://www.youtube.com/watch?v=TV7SHUGTxNU&ab_channel=DappUniversity) (14 min video)
* [Web 3.0 in a nutshell](https://eshita.mirror.xyz/H5bNIXATsWUv_QbbEz6lckYcgAa2rhXEPDRkecOlCOI) (article)

**Denomination**

* Fungible token: ERC-20
    * Official bank token: CBDC (Central Bank Digital Currencies)
* Non Fungible Token: ERC-721

### 4.1 Smart contracts

* [Smart Contract explained](https://www.youtube.com/watch?v=pWGLtjG-F5c) (15 min video)
* [Create your first ETH Smart Contract](https://www.youtube.com/watch?v=ooN6kZ9vqNQ) (20 min video) 
* [Create a Token (ERC-20)](https://www.youtube.com/watch?v=ZLFiGHIxS1c&t=204s) (22 min video)
* [Make a Payment Subscription with Smart contract](https://www.youtube.com/watch?v=yMwdovqrbM4) (15 min video)
* [How to upgrade an immutable Smart Contract?](https://www.youtube.com/watch?v=bdXJmWajZRY) (30 min video) 
* [How to upgrade a smart contract?](https://www.youtube.com/watch?v=RoXgaAvoIjg) (22 min video)
* [How much data can be saved in a smart contract](https://ethereum.stackexchange.com/questions/68712/how-much-data-can-i-store-in-a-smart-contract-what-is-the-cost-and-how-it-is-im#:~:text=The%20contract%20size%20must%20be,really%20use%20all%20this%20memory%3F) (article)
    * *As for the maximum amount of data a contract can store you can check Is there a (theoretical) limit for amount of data that a contract can store? . So **in theory you can store 2^261 bytes** but in practice you can never get anywhere near that limit. As Vitalik points on in his post in that link **the blockchain will cease to function before you reach that hard limit***
* [How gas is calculated?](https://hackernoon.com/ether-purchase-power-df40a38c5a2f) (article)

### 4.2 Tokenomic
1. [Deep dive into Web 3.0 and Tokenomy](https://github.com/sherminvo/TokenEconomyBook) (book)

### 4.3 dApps

* [Swap token explained](https://www.youtube.com/watch?v=LpjMgS4OVzs) (12 min video)
* [Bitcoin on Etherum blockchain? how is it possible?](https://www.youtube.com/watch?v=iExly7FGKAQ) (14 min video)

### 4.4 DeFI: Decentralized Finance vs Centralized Finance

* [History of DeFi](https://www.youtube.com/watch?v=qFBYB4W2tqU) (18 min video)
* [What is DeFi?](https://www.youtube.com/watch?v=k9HYC0EJU6E) (12 min video)
* [What is a DEX (Decentralized Exchange)](https://www.youtube.com/watch?v=2tTVJL4bpTU) (7 min video)
* [What is a Liquidity pool](https://www.youtube.com/watch?v=cizLhxSKrAc) (10 min video)
* [What are Flash loan](https://www.youtube.com/watch?v=Aw7yvGFtOvI) (18 min video)
* [What is a Yearn finance](https://www.youtube.com/watch?v=qG1goOptZ5w) (10 min video)
* [Lending Borrowing finance explained](https://www.youtube.com/watch?v=WwE3lUq51gQ) (14 min video)
* [Impermanent loss explained](https://www.youtube.com/watch?v=8XJ1MSTEuU0) (10 min video)
* [How hacker steal tokens with DeFi?](https://rekt.news/) (list of articles) 

#### 4.5 DAO (Decentralized Autonomous Organization)

1. [What is a DOA](https://www.youtube.com/watch?v=ubZKD_BAvpo) (2 min video)
2. [Dive deep is all type of a DAO](https://www.youtube.com/watch?v=MFEXFvCFywc) (22 min video)

### 4.6 Rebase DAO

1. [What is OlympusDOA](https://docs.olympusdao.finance/main/) (the project that created this trend)
2. [Dive deep into Rebase DAO Tokenomics](https://www.youtube.com/watch?v=-ZodrK_V8Fw&t=1s&ab_channel=SiamKidd)

### 4.7 Oracles

1. [What is an oracle?](https://www.youtube.com/watch?v=ZJfkNzyO7-U&ab_channel=Chainlink) (6 min video)

### 4.8 NFT: Collectibles

1. [NFTs explained](https://www.youtube.com/watch?v=Xdkkux6OxfM) (10 min video)
2. [Example of NFT platform](https://www.youtube.com/watch?v=z8MCevWETm4) (30 min video)
3. [How to create a collectible](https://www.youtube.com/watch?v=YPbgjPPC1d0) (NFT ERC-721) (2 hours video)

Deep dive:

* [CryptoKitties](https://www.cryptokitties.co/) (website)
* [CryptoPunk](https://www.larvalabs.com/cryptopunks) (website)
* [Opensea](https://opensea.io/) (website)

### 4.9 Other type of NFT

1. [Arianee protocol](https://www.youtube.com/watch?v=Z7v41l4I-Gc&ab_channel=Arianee)(2 min video) (prevent product counterfeit)
2. [ENS (decentralized domain name)](https://www.youtube.com/watch?v=P8RlPsjGaR8) (7 min video)
3. [Build a transparent Supply chain with blockchain](https://hbr.org/2020/05/building-a-transparent-supply-chain) (article)

### 4.10 Play to earn

* [Top 10 Crypto games](https://medium.com/general_knowledge/top-10-crypto-gaming-projects-bonus-612249019a5e) (Article)
* [What is Play to Earn](https://www.youtube.com/watch?v=zchIkjXtOtk) (20 min video)
* [Play to earn game: Axie Infinity](https://www.youtube.com/watch?v=mXEYCXCPI5c) (6 min video)

Deep dive:

* [Axies infinity](https://axieinfinity.com/) (website)
* [Skyweaver Trading card game](https://www.skyweaver.net/) (website)

## 5. Hand-on code: Building products on top of Blockchain

### 5.1 Building on Ethereum network

* [Beginner: Step by step creating a dApps](https://www.youtube.com/watch?v=nvw27RCTaEw) (1.5 hour video)
* [Master Solidity development](https://www.youtube.com/watch?v=YJ-D1RMI0T0) (2 hours video)
* [Build a token swap dApps](https://www.youtube.com/watch?v=99pYGpTWcXM) (3 hours video)
* [Create an Instagram clone with Blockchain](https://www.youtube.com/watch?v=8rhueOcTu8k) (2 hours video)
* [Full course](https://www.youtube.com/watch?v=M576WGiDBdQ&list=WL&index=39) (16 hours video)
* [Create a token Airdrop](https://www.youtube.com/watch?v=YXsMgSgE_Pw) (34 min video)
* https://buildspace.so/

**5.2 Blockchain (Smart Contract) Dev env:**

* [https://remix.ethereum.org](https://remix.ethereum.org/) (Web IDE)
* https://www.trufflesuite.com/ganache (Development Blockchain)
* https://www.trufflesuite.com/ (Truffle, Smart contract testing framework)

**5.3 Frontend Dev env:**
JS frameworks: 

* [Web3.js](https://web3js.readthedocs.io/en/v1.3.4/): JS Connector to the blockchain (ideally to connect the website to the blockchain)
* [Ether.js](https://docs.ethers.io/v5/)
* React.js
* [Express.js](https://expressjs.com/)
* [Expo](https://expo.dev/)

### 5.4 Building on Solana network

* [Create Solana Token and NFT](https://www.youtube.com/watch?v=L4WWQzOBNIg) (41 min video) 
* [Solana dev doc](https://docs.solana.com/)
* [Solang a Solidity compiler for Solana](https://solang.readthedocs.io/en/latest/)

### 5.5 How to connect a Wallet with Wallet connect

[What is Wallet connect?](https://www.youtube.com/watch?v=PHRPoSRXPI0) (13 min video) 

# Appendix

## 1. Energy consumption and environmental footprint

**Open discussion:** with blockchain layer 1 and layer 2 multiplying, company who want to onboard to blockchain/web3.0 will also have to consider their environmental footprint. For instance, I foresee companies moving a blockchain because the cost in energy will be lesser than another blockchain.
On this topic I found the following articles, but please free to add your in comment of this thread.

1. [Ethereum average energy consumption per transaction compared to that of VISA as of October 21, 2021](https://www.statista.com/statistics/1265891/ethereum-energy-consumption-transaction-comparison-visa/)
2. [Bitcoin average energy consumption per transaction compared to that of VISA as of October 21, 2021](https://www.statista.com/statistics/881541/bitcoin-energy-consumption-transaction-comparison-visa/) (even if Bitcoin does not present any interest on Web3 for now)
3. [Solana’s Energy Use Report: November 2021](https://solana.com/news/solana-energy-usage-report-november-2021)
4. [Tezos Excels As An Energy-Efficient Blockchain According To New PWC Report](https://xtz.news/latest-tezos-news/tezos-excels-as-energy-efficient-blockchain-according-to-new-pwc-report/)

## 2. Security exploit and past errors to be aware of

1. [Kucoin hack, $45M stolen](https://rekt.news/epic-hack-homie/) (article)
1. [Poly Network hack, $611M stolen](https://rekt.news/polynetwork-rekt/) (article)
1. [Ethereum Uniswap V3 LP lower performance than V2 LP](https://rekt.news/uniswap-v3-lp-rekt/) (article)
1. [Solana BadgerDAO, $120M Stolen ](https://www.theblockcrypto.com/post/126072/defi-protocol-badgerdao-exploited-for-120-million-in-front-end-attack) (article)
1. [Bitmart hack, $196M stolen](https://rekt.news/bitmart-rekt/) (article)
1. [Compound hack, $147M stolen](https://rekt.news/compound-rekt/) (article)
1. [Avalanche Snowdog DAO Rekt](https://rekt.news/snowdog-rekt/) (article)
1. [Crypto.COM $33.7M stolen](https://rekt.news/cryptocom-rekt/) (article)
1. [Solana Wormhole $326 stolen](https://rekt.news/wormhole-rekt/) (article)
1. [Solana Cashio infinite minting](https://rekt.news/cashio-rekt/) (article)
1. [Ronin network $624M stolen](https://rekt.news/ronin-rekt/) (article)

## 3. Various articles on the Blockchain/Web3.0 economy

1. [Tokens are a new digital primitive, analogous to the website](https://cdixon.mirror.xyz/0veLm9KKWae4T6_H3siLpKF933NSdC3F75jhPQw_qWE) (article)
2. [What is Olympus Pro (Bond as a service, Liquidity provide)](https://olympusdao.medium.com/introducing-olympus-pro-d8db3052fca5) (article)
