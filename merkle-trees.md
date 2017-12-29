# Merkle \(and other\) Trees

Assumes: [Hashing](/hashing-and-merkle-trees.md)

As a programmer, you have likely heard of trees. Using hashing, we can create trees called Merkle trees, that allow for efficient data verification, proofs, and other useful things.

#### Merkle Trees

###### [Random Crypto-Currency Concept \#1 - Merkle Trees](https://www.youtube.com/watch?v=MkaiDK_Eido) - AltCoinXP, 2017 \[4 min video\]

This introductory video by AltcoinXP introduces the idea of using a binary Merkle tree to map a large amount of data to a single value and identify when changes occur.  In this video, he demonstrates a Merkle tree using an addition function, rather than the normal hash function, to make it easier to follow.

###### [Merkle Trees Infographic](https://media.consensys.net/ever-wonder-how-merkle-trees-work-c2f8b7100ed3) \[Resource\]

In this infographic also by Yunyun Chen of ConsenSys, we replace the addition function from the previous video with the hash function normally used.  We also compare the purpose of using a binary tree rather than just hashing all values together at the same time.  Once again, feel free to hang up the beautiful graphic on your wall!

###### [Merkling in Ethereum](https://blog.ethereum.org/2015/11/15/merkling-in-ethereum/) \[9 min read\]

This article by Vitalik Buterin, co-founder of Ethereum, shows how the blockchains incorporate Merkle trees into their structure.  He then also shows the differences in the models that the Ethereum blockchain uses as compared to the Bitcoin blockchain, especially as it relates to Ethereum's state concept.

#### \(Optional\) Patricia Trees

###### [Patricia Trees](https://github.com/ethereum/wiki/wiki/Patricia-Tree) \[8 min read\]

Near the end of the previous article, Vitalik mentions that Ethereum actually uses a little bit more complicated of a data structure than the binary tree used in normal Merkle trees.  For a deeper explanation of Ethereum's specific Merkle tree structure, read this section of the Ethereum wiki.

###### [Patricia Trees Breakdown](https://easythereentropy.wordpress.com/2014/06/04/understanding-the-ethereum-trie/) \[30 min tutorial\]

In this walkthrough by Ethan Buchman, we walk through a deep dive of exploring Ethereum Patricia trees through code.  Note: this walkthrough assumes familiarity with Python programming.

