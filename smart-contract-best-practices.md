## Common Bugs/Attacks and Best Practices

###### [Ethereum Subtleties](https://github.com/ethereum/wiki/wiki/subtleties) \[4 min read\]

A lot of the subtleties of Ethereum. Black hats don't often lurk in the daylight of the obvious, but in the darkness of subtleties where much fewer white hats roam. For example, one of the DoS attacks used “note: there is a difference between zero-balance and nonexistent!”

###### [Smart Contract Best Practices](https://github.com/ConsenSys/smart-contract-best-practices) \[20 minute read\]

Amazing Best Practices guide compiled by ConsenSys that provide numerous security tips, overviews of known attacks, and general engineering techniques.

###### [Smart Contract Security Tips](https://www.youtube.com/watch?v=_pqDAMRwkzY) \[16 min video\]

Through the use of examples, Joseph Chow of ConsenSyswalks us through some common things to avoid when developing and deploying smart contracts.

###### [Analysis of the DAO Exploit](http://hackingdistributed.com/2016/06/18/analysis-of-the-dao-exploit/) \[4 min read\]

This article by Phil Daian explains the reentrancy attack that affected TheDAO and cost over $150 million USD in great detail.

###### [Compiler Bugs](https://solidity.readthedocs.io/en/develop/bugs.html) \[3 min read\]

Occasionally, a nightly version of the Solidity compiler itself may contain bugs. It is suggested to avoid using any compiler version that is known to be faulty in some way.  This page from the Solidity docs has a list of some of the known compiler bugs.

###### [Tx.origin](http://vessenes.com/tx-origin-and-ethereum-oh-my/) \[5 min read\]

Often times, contracts mistakingly use tx.origin when they mean to use msg.sender.  This article by Peter Vessenes explains why this is dangerous and can lead to malicious behavior.

###### [Parity MultiSig Bug](http://hackingdistributed.com/2017/07/22/deep-dive-parity-bug/) \[7 min read\]

This article by Lorenz Breidenbach, Phil Daian, Ari Juels, and Emin Gün Sirer explains the exploit that affected allowed hackers \(combination of blackhat and whitehat\) to drain over $200 million USD from Parity Multisignature Wallets v1.5 and above.

###### [Underhanded Naming](https://www.reddit.com/r/ethereum/comments/4e5y30/live_example_of_underhanded_solidity_coding_on/) \[2 min read\]

In this reddit post, Vitalik Buterin exposes an underhanded malicious code that tried to steal money by naming variables slightly different things that might be missed by a quick reader.

[http://www.kingoftheether.com/postmortem.html](http://www.kingoftheether.com/postmortem.html)

