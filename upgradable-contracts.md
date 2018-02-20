## Upgradable Contracts

Once a contract is deployed to the chain, the code of the contract cannot be changed.  This is plays into the immutability aspect of blockchains.  However, sometimes you need to be able to update contract code because perhaps a bug has been found or the project is in development with staged rollouts.  In this section, we will learn how to do this.

###### [Writing Upgradeable Contracts in Solidity](https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88) - Elena Dimitrova, Colony Medium, 2016 \[4 min read\]

This article from Colony.io will cover some of the different ways to make the process of deploying a new version of a smart contract more efficient and/or easy.

###### [Using Interfaces to make Contract Upgradeable](https://medium.com/@nrchandan/interfaces-make-your-solidity-contracts-upgradeable-74cd1646a717) - Chandan Gupta, Imaginea, 2017 \[3 min read\]

An extention to the previous article talking about changes that need to be made to the parent contract of an upgradeable contract scheme.

###### [Proxy Libraries in Solidity](https://blog.zeppelin.solutions/proxy-libraries-in-solidity-79fbe4b970fd) - Manuel Araoz, Zepplin Solutions, 2017 \[3 min read\]

Next, this article from  Zeppelin Solutions discusses how to use a dispatcher contract to serve as a holder of of storage values and ether while using libraries to delegate functionality and handle code execution.

###### [Ether Router](https://github.com/ownage-ltd/ether-router) - Ownage Ltd, 2017 \[Resource\]

Some sample code on how to store and load other contracts and delegate calls to them.

