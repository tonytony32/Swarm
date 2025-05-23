# Swarm 101
# Intro

### Name

Swarm

### Project Logo

[Swarm Logo (.ai)](https://github.com/tonytony32/swarm/blob/1f17ec882ca53dda68daceca0c3a861651cfe6bb/Swarm_ALL.ai)

[Logo PNG](https://user-images.githubusercontent.com/46597871/223733983-57114c40-433a-49d1-a2de-594f92c2decb.png)

[Logo Circled MAX](https://raw.githubusercontent.com/tonytony32/swarm/6b9a3d5a5dc7cb749b5a7131f0d00c98ee11c6e7/Circle_Orange_onWhite.png)

### Project description

Incepted at Ethereum Foundation, Swarm is a peer-to-peer network of nodes that collectively provide a decentralised storage and communication service. Swarm’s vision is to extend the blockchain with peer-to-peer storage and communication to realise the world computer that can serve as an operating system and deployment environment for decentralised applications.

Economically self-sustaining due to a built-in incentive system, enforced through smart contracts on the Ethereum blockchain and powered by the BZZ token, Swarm provides exceptional privacy features like anonymous browsing, deniable storage, untraceable messaging and file representation formats that leak no metadata.

### Founders

- Viktor Tron - President ([Github](https://github.com/zelig), [Forbes Council](https://councils.forbes.com/profile/Viktor-Tr%C3%B3n-Founder-President-Swarm/42d8ba43-4fda-493e-9cde-7a707f317ed9), [LinkedIn](https://www.linkedin.com/in/viktortron), [Twitter](https://twitter.com/zeligf))
- Daniel Nagy - Vice President

### Website

[https://www.ethswarm.org](https://www.ethswarm.org/)

### Twitter

[https://twitter.com/ethswarm](https://twitter.com/ethswarm)

### GitHub/GitLab

[https://github.com/ethersphere](https://github.com/ethersphere)

### Blog

[https://blog.ethswarm.org/](https://blog.ethswarm.org/)

### Discord

[https://discord.ethswarm.org/](https://discord.ethswarm.org/)

### Youtube

[https://www.youtube.com/channel/UCu6ywn9MTqdREuE6xuRkskA/videos](https://www.youtube.com/channel/UCu6ywn9MTqdREuE6xuRkskA/videos)


-------

# Launch details

### Launch style
- Initial Exchange Offering (IEO): [Swarm Token sale drives over 20,000 new token holders](https://blog.coinlist.co/swarm-token-sale-drives-over-20-000-new-token-holders/)
- Private Sale: [Bitcoin Suisse Facilitates Private Fundraising Round of Swarm](https://www.bitcoinsuisse.com/news/bitcoin-suisse-facilitates-private-fundraising-round-of-swarm) and [Swarm secures funds for mainnet release](https://medium.com/ethereum-swarm/swarm-secures-funds-for-mainnet-release-2992d453fa09)
- Airdrop: [Swarm is airdropping 1,000,000 BZZ](https://medium.com/ethereum-swarm/swarm-is-airdropping-1-000-000-bzz-bd3b706918d3)

### Token Emission, Vesting, and Distribution Details

- Token sale (50%)
- Ecosystem (24%)
- Team rewards (19%)
- Swarm Foundation (7%)

All tokens are fully transferable since August 2nd 2021.

Tokenomics: 
[BZZ Tokenomics](https://medium.com/ethereum-swarm/swarm-tokenomics-91254cd5adf) 

### Exchanges list

Coinmarketcap: https://coinmarketcap.com/currencies/ethereum-swarm/markets/
Coingecko:https://www.coingecko.com/en/coins/swarm#markets

### DEX Markets

- Uniswap (BZZ/ETH): https://app.uniswap.org/#/swap?chain=ethereum&inputCurrency=ETH&outputCurrency=0x19062190B1925b5b6689D7073fDfC8c2976EF8Cb
- Balancer (xBZZ/xDAI): https://balancer.fi/swap/gnosis/xDAI/0xdbf3ea6f5bee45c02255b2c26a16f300502f68da

-------
# Onchain information

### Main chain

Ethereum

### Token name and symbol

BZZ (ERC-20)

### Secondary chains

Gnosis chain

### Token Contract Addresses

| Blockchain | Ticker | Address |
| --- | --- | --- |
| Ethereum | BZZ | 0x19062190B1925b5b6689D7073fDfC8c2976EF8Cb |
| Gnosis chain | xBZZ | 0xdBF3Ea6F5beE45c02255B2c26a16F300502F68da |
| Goerli testnet | gBZZ | 0x2ac3c1d3e24b45c6c310534bc2dd84b5ed576335 |
| Sepolia testnet | sBZZ | 0x543dDb01Ba47acB11de34891cD86B675F04840db |

### Token Services

https://tokenservice.ethswarm.org/circulating_supply

https://tokenservice.ethswarm.org/token_price (Deprecated)

### Block Explorer

[https://etherscan.io/token/0x19062190b1925b5b6689d7073fdfc8c2976ef8cb](https://etherscan.io/token/0x19062190b1925b5b6689d7073fdfc8c2976ef8cb)

### Token usage

BZZ usage is two-fold:

- Write and persist data: Publishers in Swarm use BZZ to write data on Swarm and have it stored over time.
- Participate as a storage provider: Receive BZZ through Swarm’s redistribution mechanism for providing storage services.

### Token supply

Fixed at 63149437.8365502211917282 tokens.

### Storage Incentives Contracts
| Contract | Blockchain | Address |
| --- | --- | --- |
| Postage Stamp	| Gnosis Chain	| 0x30d155478eF27Ab32A1D578BE7b84BC5988aF381
| Staking	| Gnosis Chain	| 0x781c6D1f0eaE6F1Da1F604c6cDCcdB8B76428ba7
| Redistribution	| Gnosis Chain |	0x1F9a1FDe5c6350E949C5E4aa163B4c97011199B4
| Price Oracle |	Gnosis Chain |	0x344A2CC7304B32A87EfDC5407cD4bEC7cf98F035

-----
# Technology highlighs
Swarm nodes form a network with quasi-permanent peer connections. The overlay topology chosen is Kademlia, involving message relay. 

The underlying storage model of Swarm is called DISC: Distributed Immutable Store of Chunks. A chunk is the canonical unit of storage, consisting of at most 4 kbytes of data.

This model produces a network behaviour that has the following properties:

- Privacy-preserving and permissionless upload and download
- Robust defences against blocking or changing access to content once published
- Auto-scaling with increased demand
- Integrity protected content
- Eventually forgetting content that is no longer relevant to preserve

The Swarm Accounting Protocol (SWAP) ensures that node operators collaborate in routing messages, while protecting the network against frivolous use of bandwidth.

Postage Stamps is a verifiable proof of payment associated with a chunk, signaling its relative importance and preventing frivolous uploads.

The uploaders pay a rent in BZZ to storers in proportion to the amount of storage space required and the duration of using it. This rent is redistributed to storers at regular intervals in a probabilistic fashion, similarly to how validation rewards and transaction fees are paid in proof-of-stake consensus mechanisms.

[Network SLAs](https://network.ethswarm.org/)

[Whitepaper](https://www.ethswarm.org/swarm-whitepaper.pdf) (document, 13 pages)

[Book of Swarm](https://www.ethswarm.org/The-Book-of-Swarm.pdf) (document, 271 pages)

[The Mechanics of Swarm network's Storage Incentives](https://medium.com/ethereum-swarm/the-mechanics-of-swarm-networks-storage-incentives-3bf68bf64ceb) (Medium article, paper to be released)

[All published papers](https://papers.ethswarm.org/)

### Code Audits

Include links to any security audits that have been completed

[Swarm Token - Quantstamp](https://github.com/tonytony32/Swarm/blob/ceb8bd6776f49a4241da4f90976d7d0846b0b372/Audits/Swarm%20Token%20-%20Quantstamp.pdf)

[Bee + Bee Clef - Least Authority](https://github.com/tonytony32/Swarm/blob/ceb8bd6776f49a4241da4f90976d7d0846b0b372/Audits/Least%20Authority%20-%20Swarm%20Association%20Bee%20%2B%20Bee%20Clef%20Initial%20Audit%20Report.pdf)

[Penetration test - Cure53](https://github.com/tonytony32/Swarm/blob/ceb8bd6776f49a4241da4f90976d7d0846b0b372/Audits/cure53-SWA-01-report.pdf)
