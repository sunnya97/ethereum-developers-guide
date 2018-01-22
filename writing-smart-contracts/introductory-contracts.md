## Introductory Contracts

Now we will begin our first foray into writing larger and more useful smart contracts projects using Truffle.

###### [The Hitchhiker’s Guide to Smart Contracts in Ethereum](https://blog.zeppelin.solutions/the-hitchhikers-guide-to-smart-contracts-in-ethereum-848f08001f05) - Manuel Araoz, Zepplin Solutions Medium, 2016 \[Exercise\]

One of the blockchain's most interesting use cases is using it for proof of existence.  Essentially, you can put the hash of some document or data on the blockchain so that at a future date, you can prove that you owned a piece of data at the time it was uploaded to the blockchain.  In this tutorial by Zeppelin Solutions, you will learn how to create a proof of existence contract on Ethereum, build and deploy it using Truffle, and iterate on new versions.

###### [Ethereum Pet Shop ](http://truffleframework.com/tutorials/pet-shop)- Truffle Tutorial \[Exercise\]

Next, we will follow this tutorial by Truffle to create a smart contract to handle ownership of something, in this case pets!  Do only up until _Creating a UI to Interact with our Smart Contract_.  We will come back to the UI section later.

###### [Create a MultiSig Wallet](https://docs.google.com/document/d/1AWLSGX44h5UdtlPHNY3goIe9YqPgJjaXzbEw5Y390Jw/edit) - Nate Rush \[Exercise\]

A multisignature wallet is an account that requires some m-of-n quorum of approved private keys to approve a transaction before it is executed.  Ethereum implements multisignature wallets slightly differently than Bitcoin does.  In Ethereum, multisignature wallets are implemented as a smart contract, that each of the approved external accounts sends a transaction to in order to "sign" a group transaction.  Following this project spec designed by the UPenn Blockchain Club, you will now create your own multisignature wallet contract.  **Note: It is not suggested that you use this multisignature wallet with any real funds, but rather use a far more deeply audited one such as the **[**Gnosis multisignature wallet**](https://wallet.gnosis.pm)**.**

