# avaloncoin

[![Build Status](https://travis-ci.org/avaloncoin/avaloncoin.svg?branch=master)](https://travis-ci.org/avaloncoin/avaloncoin)

avaloncoin (codename avaloncoin) began as a fork of Bitcoin after block height 491406 on Tue, 24 Oct 2017 01:17:35 GMT and began being mined as a separate chain at block height 491407 on Sun, 12 Nov 2017 13:34:01 GMT.

The primary goal is to maintain a variant of Bitcoin that is more decentralized by using an ASIC-resistant Proof of Work algorithm, removing barriers to entry for new miners around the world and reducing the concentration of power in the hands of massive-scale mining operations.

avaloncoin preserves and implements Bitcoin features such as SegWit. Significant differences at launch time included:

- ASIC-resistant GPU-minable PoW algorithm (Equihash)
- Per-block difficulty adjustment algorithm
- Replay protection (SIGHASH_FORK_ID)
- Unique wallet addresses (prefixes of G and A)

Although BTG was bootstrapped on 12 Nov to create an entirely new network, it contains the entire Bitcoin blockchain until block 491406. As a result, avaloncoin became a full fork with all Bitcoin transaction history since 2009. Any Bitcoin wallet address which held Bitcoin in BTC block 491406 before the fork held an equal number of avaloncoin in BTG block 491407 after the fork.

## WARNING

This is the staging tree of avaloncoin. If you don’t understand what you are doing, please don’t compile and run your own client from the staging tree. For release version, please switch to [0.15 branch](https://github.com/avaloncoin/avaloncoin/tree/0.15) or [release page](https://github.com/avaloncoin/avaloncoin/releases).

## Links

* Website: https://avaloncoin.org
* Tech Spec: https://github.com/avaloncoin/avaloncoin/wiki/Technical-Spec
* Forum: https://forum.avaloncoin.org
* Discord: [invitation](https://discord.gg/HmVUU6S)
