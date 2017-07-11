## Hashing and Merkle Trees

All blockchain technologies are based upon two fundamental cryptographic primitives: hashes and public-key cryptography.  In this section, we will explore the first of these two, hashing along with one of its most important uses within Blockchains, the Merkle Tree.

#### Understanding Hash Functions

###### [**If you understand Hash Functions, you’ll understand Blockchains**](https://decentralize.today/if-you-understand-hash-functions-youll-understand-blockchains-9088307b745d)** \[3 min read\]**

###### Begin by reading this short introduction to hash functions written by Decentralized Today.  This article will provide a basic model by which to think about hashes, which will be expanded upon by further articles.

###### [**Blockchain Underpinnings: Hashing**](/h ttps://medium.com/@ConsenSys/blockchain-underpinnings-hashing-7f4746cbd66b)** \[8 min read\]**

This article by ConsenSys delves further into the ideas behind hashing, providing an interesting analogy comparing bits to an array of light bulbs.  It goes on to explore how hash functions relate to blockchains and why they are important.

###### [**Formal Properties of Hash Functions**](https://www.youtube.com/embed/pCgD3RgXHEE?start=2433&end=3156&version=3)** \[12 min video\]**

Up until now, we've been discussing hash functions in only semi-formal terms.  This video by Blockchain at Berkeley explores the formal properties of hashes in terms of _preimage resistance_.  Furthermore, it shows these properties in an interesting use case of a commitment scheme, in using hash functions to fairly play a guessing game over the internet.

###### [Hashing Inforgraphic](https://media.consensys.net/guide-hashing-33dc0467c126) \[Diagram\]

This inforgraphic by Yunyun Chen of ConsenSys is a nice easy way to remember the two main properties of a hash function.  Just take a quick glance at it.  If you're really loving hash functions so far, maybe print it out and hang it up on your wall :\)

#### Merkle Trees

###### [Video Introduction to Binary Merkle Trees](https://www.youtube.com/watch?v=MkaiDK_Eido) \[4 min video\]

This introductory video by AltcoinXP introduces the idea of using a binary merkle tree to map a large amount of data to a single value and identify when changes occur.  In this video, he demonstrates a merkle tree using an addition function, rather than the normal hash function, to make it easier to follow.

###### [Merkle Trees Infographic](https://media.consensys.net/ever-wonder-how-merkle-trees-work-c2f8b7100ed3) \[Diagram\]

In this infographic also by Yunyun Chen of ConsenSys, we replace the addition function from the previous video with the hash function normally used.  We also compare the purpose of using a binary tree rather than just hashing all values together at the same time.  Once again, feel free to hang up the beautiful graphic on your wall!

###### [Merkling in Ethereum](https://blog.ethereum.org/2015/11/15/merkling-in-ethereum/) \[9 min read\]

This article by Vitalik Buterin, co-founder of Ethereum, shows how the blockchains incorporate Merkle trees into their structure.  He then also shows the differences in the models that the Ethereum blockchain uses as compared to the Bitcoin blockchain, especially as it relates to Ethereum's state concept.

###### [\(Optional\) Patricia Trees](https://github.com/ethereum/wiki/wiki/Patricia-Tree) \[8 min read\]

Near the end of the previous article, Vitalik mentions that Ethereum actually uses a little bit more complicated of a data structure than the binary tree used in normal Merkle trees.  For a deeper explanation of Ethereum's specific merkle tree structure, read this section of the Ethereum wiki.

###### [\(Optional\) Patricia Trees Breakdown](https://easythereentropy.wordpress.com/2014/06/04/understanding-the-ethereum-trie/) \[30 min tutorial\]

In this walkthrough by Ethan Buchman, we walk through a deep dive of exploring Ethereum Patricia tries through code.  Note: this walkthrough assumes familiarity with Python programming.

