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
- Private Sale: [Bitcoin Suisse Facilitates Private Fundraising Round of Swarm](https://www.bitcoinsuisse.com/news/bitcoin-suisse-facilitates-private-fundraising-round-of-swarm)
- Airdrop: [Swarm is airdropping 1,000,000 BZZ](https://medium.com/ethereum-swarm/swarm-is-airdropping-1-000-000-bzz-bd3b706918d3)

### Token Emission, Vesting, and Distribution Details

- Token sale (50%)
- Ecosystem (24%)
- Team rewards (19%)
- Swarm Foundation (7%)

All tokens are fully transferable since August 2nd 2021.

More information: 
[BZZ Tokenomics](https://medium.com/ethereum-swarm/swarm-tokenomics-91254cd5adf) 
[Whitepaper](https://www.ethswarm.org/swarm-whitepaper.pdf)

### Exchanges list

Coinmarketcap: https://coinmarketcap.com/currencies/ethereum-swarm/markets/
Coingecko:https://www.coingecko.com/en/coins/swarm#markets

### Markets

Uniswap: https://app.uniswap.org/#/swap?chain=ethereum&inputCurrency=ETH&outputCurrency=0x19062190B1925b5b6689D7073fDfC8c2976EF8Cb

-------
# Onchain information

### Main chain

Ethereum

### Token name and symbol

BZZ (ERC-20)

### Block Explorer

[https://etherscan.io/token/0x19062190b1925b5b6689d7073fdfc8c2976ef8cb](https://etherscan.io/token/0x19062190b1925b5b6689d7073fdfc8c2976ef8cb)

### Token usage

BZZ usage is two-fold:

- Write and persist data: Publishers in Swarm use BZZ to write data on Swarm and have it stored over time.
- Participate as a storage provider: Receive BZZ through Swarm’s redistribution mechanism for providing storage services.

### Token Contract Address

eth:0x19062190B1925b5b6689D7073fDfC8c2976EF8Cb

### Token Services

https://tokenservice.ethswarm.org/circulating_supply

https://tokenservice.ethswarm.org/token_price

### Maximum supply

The token supply is not fixed and can increase or decrease via the bonding curve. Put simply, if the supply goes up by one token, so does its price in the bonding curve contract, and vice versa. This makes BZZ neither inflationary nor deflationary. You can read about Swarm’s supply and bonding curve in detail [here](https://medium.com/ethereum-swarm/swarm-and-its-bzzaar-bonding-curve-ac2fa9889914).

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



[Whitepaper](https://www.ethswarm.org/swarm-whitepaper.pdf) (document, 13 pages)

[Book of Swarm](https://www.ethswarm.org/The-Book-of-Swarm.pdf) (document, 271 pages)

[The Mechanics of Swarm network's Storage Incentives](https://medium.com/ethereum-swarm/the-mechanics-of-swarm-networks-storage-incentives-3bf68bf64ceb) (Medium article, paper to be released)

### Audits

Include links to any security audits that have been completed

[Cure53](https://crypt.swarm.foundation/s/kJCA4wXGCTs6yed)

[Least Authority](https://crypt.swarm.foundation/s/mR7TKQBp24cjLco)

