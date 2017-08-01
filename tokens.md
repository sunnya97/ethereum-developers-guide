## Tokens

Tokens have often been called Ethereum's "killer app".  In this section, we learn about what the ERC20 token protocol is and how we can make and exchange our own tokens.

###### [What are Tokens?](https://medium.com/@ConsenSys/tokens-on-ethereum-e9e61dac9b4e) \[7 min read\]

This blog post from ConsenSys gives a great overview as to what tokens are, what they can represent, and why they are useful.

###### [ERC 20 Tokens](http://decypher.tv/series/ethereum-development/video/20) \[18 min video\]

Now that we understand what tokens are good for, let's learn how to build one.  This video from Decypher.tv walks through making a brand new token from scratch conforming to the ERC20 standard.

###### [ERC 223](https://www.youtube.com/watch?v=GS62VNyPVHs) \[16 min video\]

While the ERC 20 Token standard took off quickly within the Ethereum ecosystem, it was not without flaws.  One of the issues is that when tokens are sent to contract accounts that are not designed to handle them, these tokens are often lost forever.  A developer, Dexaran, created an improvement to the Token standard to try to solve this problem.  This video from Decypher TV explains this new token standard, how it works, and how it differs from the ERC 20 standard.

###### [Make your own token](https://docs.google.com/document/d/13ch2E-yQvs0MnxXcFHe3K5zTRSNZjqjln38DqHL--to/edit?usp=sharing) \[Exercise\]

Now let us try to build our own Token.  This project from the UPenn Blockchain Club will serve as the spec to follow in creating your own token.  Try to make it conform to the ERC 223 standard while keeping compatability with the ERC standard as well.  Please feel free to use external resources to help along the way.

###### [Swap Protocol](https://www.youtube.com/watch?v=lVmqHNtYdCE&feature=youtu.be) \[30 min video\]

One of the most valuable things about ERC 20 token standard is the ability to design contracts that can interoperate with any token.  One interesting use case for this interoperability is an on-chain exchange.  In this video from Consensys Media, Deepa Sathaye explains the Swap Protocol, which allows two users to trade or "swap" different tokens.

###### [Token Exchange](https://docs.google.com/document/d/1kKKFvQQExN045pX2cFA_fJFY6ZsGhrtPWG73klNsVDg/edit) \[Exercise\]

Now that you've learned about the structure of the Swap protocol, let's try to build our own simple on chain token trading smart contract.  In this exercise, designed by the UPenn Blockchain Club, you will use your knowledge of ERC20 and [Inter-Contract Execution](/dev-environment-i/inter-contract-execution.md) to create this very simplistic on-chain exchange.

