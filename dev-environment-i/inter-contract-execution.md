## Inter-Contract Execution

One of the most valuable properties of Ethereum is the ability for different contracts to interact with each other, allowing for the ability to build applications in a modular way with multiple smart contracts, as well as allowing for interoperability between different applications.

###### [Basic example of interaction between 2 contracts?](https://ethereum.stackexchange.com/questions/1599/basic-example-of-interaction-between-2-contracts)  - Ethereum StackExchange, 2016 \[Exercise\]

Read this StackOverflow thread to see how to pass in the address of a smart contract into a second smart contract in order to call its functions.  It is suggested you test this out on [Remix](https://remix.ethereum.org/).

###### [Interactions Between Contacts](https://dappsforbeginners.wordpress.com/tutorials/interactions-between-contracts/) - Dapps for Beginners \[10 min read\]

In this tutorial from the Dapps for Beginners series, you will practice interacting with a smart contract called MetaCoin through another smart contract.  First, we will make a smart contract that acts as a proxy for calling functions in a Metacoin Contract as in the previous exercise. Then we will make a "Factory contract" that creates new Metacoin smart contracts.  It is suggested you follow along with the tutorial using [Remix](https://remix.ethereum.org/).

###### [Difference Between CALL, CALLCODE, and DELEGATECALL](https://ethereum.stackexchange.com/questions/3667/difference-between-call-callcode-and-delegatecall) - Ethereum StackExchange, 2016 \[4 min read\]

Within Solidity, there are different ways for a smart contract to call another smart contract.  In the EVM, there are three opcodes for calling other contracts, CALL, CALLCODE, and DELEGATECALL.  Read this StackOverflow thread to learn about the differences between these three opcodes.

