## Common Bugs/Attacks and Best Practices

###### [Ethereum Subtleties](https://github.com/ethereum/wiki/wiki/subtleties) \[4 min read\]

An explanation of the subtleties of Ethereum. Black hats don't often lurk in the daylight of the obvious, but in the darkness of subtleties where much fewer white hats roam. For example, one of the DoS attacks used “note: there is a difference between zero-balance and nonexistent!”

###### [Smart Contract Best Practices](https://consensys.github.io/smart-contract-best-practices/) \[20 minute read\]

Smart Contract Best Practices guide compiled by [ConsenSys Diligence](https://media.consensys.net/introducing-consensys-diligence-cf38f83948c). This guide provides numerous security tips, overviews of known attacks, and general engineering techniques.

###### [Smart Contract Security Tips](https://www.youtube.com/watch?v=_pqDAMRwkzY) \[16 min video\]

In this talk from dev con 2, Joseph Chow of ConsenSys walks us through some common things to avoid when developing and deploying smart contracts, using illustrative examples.

###### [Compiler Bugs](http://solidity.readthedocs.io/en/develop/bugs.html) \[3 min read\]

Occasionally, a nightly version of the Solidity compiler itself may contain bugs. It is suggested to avoid using any compiler version that is known to be faulty in some way.  This page from the [Solidity docs](http://solidity.readthedocs.io/en/develop/index.html) has a list of some of the known compiler bugs.

###### [Contract Safety Checklist](https://www.kingoftheether.com/contract-safety-checklist.html) \[8 min read\]

This list compiled by [King of the Ether](https://www.kingoftheether.com/thrones/kingoftheether/index.html) records some of the most common known bugs and attack vectors found in Ethereum smart contracts.  Read through this list and then in the following resources, as the following articles will explore some of these in greater depth.

###### [Analysis of TheDAO Exploit](http://hackingdistributed.com/2016/06/18/analysis-of-the-dao-exploit/) \[4 min read\]

This article by Phil Daian explains the reentrancy attack that affected TheDAO and cost over $150 million USD.

###### [Tx.origin](http://vessenes.com/tx-origin-and-ethereum-oh-my/) \[5 min read\]

Often times, contracts mistakingly use the tx.origin to test for who is calling a function, when they mean to use msg.sender.  This article by Peter Vessenes explains why this is dangerous and can, and has, lead to malicious behavior.

###### [Parity MultiSig Bug](http://hackingdistributed.com/2017/07/22/deep-dive-parity-bug/) \[7 min read\]

This article by Lorenz Breidenbach, Phil Daian, Ari Juels, and Emin Gün Sirer explains the exploit that affected allowed hackers \(combination of blackhat and whitehat\) to drain over $200 million USD from Parity Multisignature Wallets v1.5 and above.

###### [Underhanded Naming](https://www.reddit.com/r/ethereum/comments/4e5y30/live_example_of_underhanded_solidity_coding_on/) \[2 min read\]

In this reddit post, Vitalik Buterin exposes underhanded code \(code that is written to appear simple, but contains a hidden bug or exploit\) that tried to steal money by naming variables slightly different things so as to be missed by a quick reader.

###### [Breaking RNG](http://martin.swende.se/blog/Breaking_the_house.html) \[10 min read\]

This article by Martin Swende gives an account of his attempt to crack the pseudo-random generation of a roulette smart contract, and eventually being beaten to it.

