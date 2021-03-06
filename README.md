# A guide to ecofriendly CryptoArt (NFTs)

## Introduction
*This article is not a comprehensive “CryptoArt for beginners”. It’s more of a very brief (as possible) **first step** towards a guide for the adventurous artist who wants to create and sell CryptoArtworks (or NFTs) on the blockchain - **on sustainable platforms**. Since the field is moving so rapidly, the information below is likely to go out of date very quickly. We will try to keep it up to date via [pull-requests](https://github.com/memo/eco-nft/pulls) and [issues](https://github.com/memo/eco-nft/issues). And I **hope the platforms themselves will add relevant information, “Statement of Values”, and roadmaps to their own site**.*

---

The CryptoArt NFT Market (i.e. selling digital art on the blockchain) is worth at least $150M - and this excludes some of the largest marketplaces like [opensea.io](http://opensea.io), (and this figure is quite heavily skewed of course, with the top artists earning the most [[1](https://cryptoart.io/artists)]).

Selling work on a blockchain can be a technically challenging task. For this reason, many platforms and websites have emerged, aiming to make this process as seamless and easy as possible for artists. Unfortunately, currently many of these platforms are based on the Ethereum blockchain, which is very inefficient and ecologically costly by design. E.g. selling just a single-edition artwork on Ethereum has a carbon footprint starting at around 100 KgCO2, which is equivalent to a 1 hour flight (and depending on the platform, can reach a long-haul flight) [[2](https://memoakten.medium.com/the-unreasonable-ecological-cost-of-cryptoart-2221d3eb2053)]. Selling an edition of 100 works has a carbon footprint of over 10 tonnes CO2, which is more than the per capita annual footprint of someone in the EU - including all emissions from industry and trade [[3](https://ourworldindata.org/co2-and-other-greenhouse-gas-emissions#co2-embedded-in-trade)].

But there are more sustainable routes emerging. As the CryptoArt NFT market is exploding in a gold-rush style free-for-all, there is a lack of clear information on the ecological impact of different approaches to NFTs. The purpose of this guide is to help those CryptoArtists who are interested in exploring more sustainable alternatives. Currently, these more sustainable platforms do not have the volume of their unsustainable counterparts (i.e. the Ethereum-based platforms). For this reason, collectors and sales are likely to be significantly lower too on the more sustainable alternatives. However, hopefully as more artists dip their toes in these waters, this can encourage platforms, developers, investors and collectors, to invest in and develop more **ecologically friendly and transparent platforms**. 



**We are also hoping the platforms themselves will be more transparent on the matter, and we can eventually retire this document**. However, at the time of writing, to my knowledge not a single platform has publicly acknowledged the issue on their website. If they do, I will include the relevant links below.


**What would be great to see from CryptoArt / NFT platforms regarding sustainability**:
- A statement of values
- A commitment to transparency, communication and guidance for CryptoArtists
- A roadmap (other than “We hope ETH2 will resolve the issue when it’s released in a year or two - e.g. alternate chains, side chains, lazy minting, layer 2 scaling etc)

---

## Glossary
The purpose of this section is to introduce concepts in an incredibly brief (1-2 sentences each) manner. For more information please follow the links. 
(TODO: more links?)

- **Blockchain**: A decentralized database. The technicalities of this are not relevant for our discussion. What is important to know however, is that there are many different blockchains (e.g. Bitcoin, Ethereum, Cardano etc), and usually, each blockchain has its own (crypto)currency.
- **Cryptocurrency**: Magic internet money. Bitcoin (BTC) is the most well known cryptocurrency. Ethereum (ETH) is another well known cryptocurrency (and the basis for most current CryptoArt platforms). There are thousands of other cryptocurrencies (collectively known as **altcoins**).
- **CryptoArt**: Art registered on the blockchain. I.e. Media is associated with an **NFT**.
https://www.artnome.com/news/2018/1/14/what-is-cryptoart 
- **NFT**: Non-Fungible Token. A unique token (i.e. long number or string) that is associated with some media (e.g. image, video, poem, whatever), and registered on the blockchain. 
Detailed description: https://opensea.io/blog/guides/non-fungible-tokens
- **Smart Contract**: A fancy way of saying “a program that lives and runs on the blockchain”. Smart contracts are what creates and keeps track of NFTs. 
- **Minting an NFT**: The act of ‘creating’ an NFT, i.e. registering the token on the blockchain, and associating it with your media (e.g. file). 
- **NFT Platform / Marketplace**: A website which allows people to buy & sell NFTs. Think ebay or Amazon, except it uses a blockchain in the background. Different platforms can:
    - use different blockchains (though currently nearly all of them use Ethereum)
    - Be open to everybody (e.g. ebay) vs invite only and curated (e.g. galleries)
    - **NFT Minting only** (website uses its own smart-contract) vs **NFT Factory** (allows artist to own smart-contract, this can allow artist more control)
    - Compatible with other platforms (e.g. list the same work on multiple platforms)
- **Gas fee**: A fee one must pay (usually paid by the seller, i.e. artist) to be able to mint (think ebay listing fee). This fee goes not to the platform, but to the blockchain. Currently Ethereum gas fees are very high (e.g. >$100) because the network is very congested. There are some existing and WIP solutions discussed in the next section.
- **Wallet**: A blockchain analog for a bank account on the blockchain, which contains your cryptocurrency. Different cryptocurrencies often require different wallets. Without going into too much detail, usually this is a piece of software (or browser extension) which gives you a **private seed** - which is typically a bunch of random words, like “red fox banana submarine tutu” (this is like your password for the wallet, which you should keep safe and never share with anyone!) and a corresponding ‘hashed’ version (e.g. 17ah2k25djhsa7974) which is your public facing **wallet address** (like an IBAN, so it’s what you share with others to get paid or trade).
- **Consensus Algorithm**: The algorithm that underlies the blockchain. Details of this are irrelevant for this guide, except to say that Proof-of-Work (PoW) is the consensus algorithm that is hundreds of times more inefficient than the other ones (deliberately so), and is also the one which is the most common today unfortunately. For familiarity, here are some other consensus algorithms (how they work is not important for now): Proof-of-Work (PoW), Proof-of-Stake (PoS), Delegated Proof-of-Stake (DPoS), Proof-of-Authority(PoA), Byzantine Fault Tolerance (BFT), Delegated Byzantine Fault Tolerance (dBFT), etc.


---
## Ways to make it better
Here are just some of the ways to improve the carbon footprint of NFTs:
### Still using Ethereum:
- **Lazy minting**: This is not nessecarily dramatically better, around 2x, or maybe 3x less carbon footprint. 
- **Sidechains**: NFTs are minted on non-Ethereum PoS sidechains, but can be moved onto Ethereum later. If they are not moved, can be hundreds times more efficient.
- **Various Layer 2 (L2) scaling optimisations**: Can be upto 100x more efficient.

### Using other blockchains:
- Instead of Ethereum, other blockchains are used. This can be up to hundreds of times better for the environment in terms of carbon footprint.

---

## NFT Platforms & Marketplaces
These are the websites that you would use to upload, ‘mint’ and sell your works. 
For sake of simplicity, we can say that from an ecological perspective, Ethereum (which uses PoW), is the worst (unless sidechains or L2 scaling is implemented).

Platforms using different blockchains (e.g. using PoS, PoA etc) will generally be hundreds times more efficient. For those wishing to not incur the immense footprints of Ethereum, look for - and support - alternatives. However, this is likely to have other issues. Such platforms are likely to not have had the time or investment to be as developed, polished or user friendly as the older, more established Ethereum based platforms. Sales are also likely to be lower for now (see the **Risks** section at the end). This document doesn’t aim to give advice, instead it is a **first step** in collecting this information in one place. 

Hopefully if there is enough demand for **sustainable and transparent platforms**, this can encourage developers, investors and collectors to invest in and develop these more ecologically friendly alternatives and grow the market. (And hopefully the community can provide more feedback - perhaps in the [issues](https://github.com/memo/eco-nft/issues)).

 
### Opensea - open marketplace for all kinds of digital collectibles
- https://opensea.io/ 
- Blockchain: **Ethereum** (ETH), but **Tezos** (XTZ) support coming soon [[link](https://opensea.io/blog/announcements/tezos-nfts-are-coming-to-opensea/)]
- Also uses Matic sidechain for ETH [[link](https://matic.opensea.io/)]
- Open to everybody (not invite only or curated)
- NFT Factory: allows users to create their own contracts 
- No gas fees (lazy minting)
- If minted on ETH, cross-compatible with SuperRare, Makersplace, Rarible

### Mintbase - open marketplace for all kinds of digital collectibles
- https://mintbase.io/ 
- Blockchain: **Ethereum** (ETH), but **NEAR** coming soon [[link](https://near.org/how-mintbase-made-minting-nfts-cheaper-faster-scalable-and-secure-with-near/), [link](https://medium.com/mintbase/scaling-mintbase-with-near-503375d92702)]
- NFT Factory: allows users to create their own contracts 
- Open to everybody (not invite only or curated)

### Rarible - open marketplace for all kinds of digital collectibles
- https://rarible.com/ 
- Blockchain: **Ethereum** (ETH)
- NFT Factory: allows users to create their own contracts 
- Open to everybody (not invite only or curated)

### Viv3 - open marketplace for digital art
- https://viv3.com/ 
- Blockchain: **Flow** (by CryptoKitties folks, used by one of the largest NFT platforms, [NBA topshots](https://www.nbatopshot.com/))
- Open to everybody (not invite only or curated)

### Cargo - open marketplace for all kinds of digital collectibles
- https://cargo.build/
- Blockchain: **Ethereum** (ETH)
- NFT Factory: allows users to create their own contracts 
- Open to everybody (not invite only or curated)

### NFTshowroom - open marketplace for digital art
- https://nftshowroom.com/
- Blockchain: **HIVE**
- Open to everybody (not invite only or curated, but verified)

### Async Art - curated marketplace for programmable art
- https://async.art/ 
- Blockchain: **Ethereum** (ETH)
- Curated

### SuperRare - curated marketplace for digital art
- https://superrare.co/ 
- Blockchain: **Ethereum** (ETH)
- Curated
- Minting Only (i.e. platform owns contract)

### NiftyGateway - curated marketplace for digital art
- https://niftygateway.com/ 
- Blockchain: **Ethereum** (ETH)
- Curated
- Minting Only (i.e. platform owns contract)

### Foundation - curated marketplace for digital art
- https://knownorigin.io/ 
- Blockchain: **Ethereum** (ETH) 
- Curated 

### Makerspace - curated marketplace for digital art
- https://makersplace.com/ 
- Blockchain: **Ethereum** (ETH) 
- Curated 

### Known Origin - curated marketplace for digital art
- https://knownorigin.io/ 
- Blockchain: **Ethereum** (ETH) 
- Curated 

### Atomic - open marketplace for all kinds of digital collectibles
- https://wax.atomichub.io/
- Blockchain: **Wax**
- open to everybody (not invite only or curated)

### Zora
- https://zora.co/ 
- Blockchain: **Ethereum** (ETH)
- open to everybody (not invite only or curated)

### Paras - curated marketplace for digital art cards
- https://paras.id/ 
- Blockchain: **NEAR**
- Open to everybody (not invite only or curated, but verified)

### Lovada - inclusive marketplace for digital art
- https://twitter.com/lovadaart
- Blockchain: **Cardano** (ADA)
- *Under development*

### Kalamint - curated marketplace for digital art
- https://kalamint.io/ 
- Blockchain: **Tezos** (XYT)
- *Under development*

---

## Blockchains
There’s not much an individual CryptoArtist can do with the following information without a platform (i.e. website and marketplace) using these blockchains, or without coding everything themselves. But the list is still included here as a guide, in case you hear these words and wonder what they are:

### Ready for NFTs and public use
- <span style="color:red">Ethereum (ETH) : (PoW)</span>
- NEAR: https://near.org/ (PoS)
- WAX: https://on.wax.io/wax-io/ (PoS)
- Avalanche (AVAX): https://www.avalabs.org/ (PoS)
- Tezos (XTZ): https://tezos.com/ (PoS)
- Flow: https://www.onflow.org/ (PoS) (by CryptoKitties folks, used by one of the largest NFT platforms, NBA topshots)
- EOS: https://eos.io/ (DPoS)
- HIVE: https://hive.io 
- Kira: https://kira.network/ (PoS)
- Harmony: https://www.harmony.one (PoS)
- Binance Smart Chain (BSC): https://www.binance.org/en/smartChain (PoS)
- xDai (DAI): https://www.xdaichain.com/ (Ethereum PoS sidechain)
- Matic, Polygon: https://matic.network/ https://polygon.technology/ (Ethereum PoS sidechain)

### WIP
- Ethereum2: https://ethereum.org/en/eth2/ (PoS)
- Cardano (ADA): https://cardano.org/ (PoS)
- Solana (SOL): https://solana.com/ (PoS)
- Polkadot (DOT): https://polkadot.network/ (PoS)

---

## Risks
There are risks involved with selling on the blockchain in general, but especially on some of these smaller blockchains (i.e. that aren’t Ethereum):
- Cryptocurrencies are notoriously volatile [[4](https://coinmarketcap.com/)], (even the biggest ones, BTC and ETH), and their values can dramatically fall (or rise). E.g. if you sell a NFT for 1 ETH, which is currently worth ~\$1600, the value of ETH could later drop to a few hundred $ in a few months, or even in a few weeks (alternatively, it could rise to two or three thousand $$ too).
- This becomes potentially even more risky (or potentially more rewarding) with cryptocurrencies that have a much smaller market cap (e.g. NEAR, XTZ, AVAX etc), which could die and drop to zero (or go to the moon) in a few weeks. 
- Essentially this is a gamble, so please act responsibly. Seek financial advice if need be (preferably not from YouTube, TikTok, Elon Musk or Chamath Palihapitiya). 
- The smaller blockchains are likely to have fewer collectors - or at least - fewer collectors who are willing to spend large amounts. So expect smaller sales on these platforms. (Though as more people start to use the smaller blockchains, this may or may not change). 

---

## Acknowledgements & Contributions
The information in this document is a collective effort from many people including:

Memo Akten, Primavera De Filippi, Joanie Lemercier, Mat Dryhurst, Sutu_eats_flies, 
(please add names)
and many more.
(Also see https://github.com/memo/eco-nft/graphs/contributors )

Please submit a [pull-request](https://github.com/memo/eco-nft/pulls) or [issue](https://github.com/memo/eco-nft/issues) if you would like to make any changes or have any comments.

Pull requests: 
- Small and atomic (i.e. each pull request should be a change to one location, and in a separate branch if need be)
- Please don’t send pull-requests which change whitespace or line-endings etc


---
## References
1. https://cryptoart.io/artists 
2. https://memoakten.medium.com/the-unreasonable-ecological-cost-of-cryptoart-2221d3eb2053 
3. https://ourworldindata.org/co2-and-other-greenhouse-gas-emissions#co2-embedded-in-trade 
4. https://coinmarketcap.com/ 

