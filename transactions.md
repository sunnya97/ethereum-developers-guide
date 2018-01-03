## Transactions

###### [Introduction to Transactions](http://decypher.tv/series/ethereum-development/video/4) - Decypher \[15 min video\]

In this video by Decypher.tv, Jordan Leigh uses his favorite tools, Web3 and EthereumJS, to show how to construct a raw transaction from the very basics.

###### [Ether Transfer Transaction Example](https://etherscan.io/tx/0x19c52e17a598e39c18101a75d7754a35b1e858179df420ca52e1146b6f283b0b) - Etherscan, 2017 \[Resource\]

This is an example of an Ether transfer function, what happens when you send Ether to another Externally Owned Contract.  Feel free to poke around the Etherscan page of this type of transaction.  Note that the input data of this type of transaction is "0x".

###### [Interacting with Smart Contracts](https://www.youtube.com/embed/uOL26c1Qu5U?start=1024&end=1679&version=3) - Matt Thomas, 2017 \[11 min video\]

While Jordan's video showed us how to send generic raw transactions, we will head back once again to Matt Thomas's video to see how to use transactions to interact with smart contracts.

###### [Smart Contract Transaction Example](https://etherscan.io/tx/0x8534d2e4129baa16965f51420b9fa8f87bbdab90ae767095dc6c6fcfe5ce554a) - Etherscan, 2017 \[Resource\]

This is an example of a transaction being sent to a contract account in order to invoke a function.  In the "Input Data" section, we can see that a "transfer" section is being called with two arguments, an address and a value.  It happens that this is a specific type of smart contract called a Token, which we will cover later in this guide.  Once again, please look around to see what you can learn.

###### [Ethereum Whitepaper: Messages, Transactions, and State Transition Function](https://github.com/ethereum/wiki/wiki/White-Paper#messages-and-transactions) - Ethereum Whitepaper, 2014 \[10 min read\]

We will return to our handy dandy Ethereum whitepaper and read the three sections titled:  "Messages and Transactions", "Messages", and "Ethereum State Transition Function".  In this, we now see how transactions with account states allow Ethereum to now act as a general computation state transition machine.

###### [Smart Contract Internal Calls](https://etherscan.io/txsInternal) \[Resource\]

As we now know, not only can external accounts call smart contracts, but smart contracts can also call other smart contracts.  On this page in Etherscan, we will see a list of all these internal smart contract calls.  Feel free to poke around!

