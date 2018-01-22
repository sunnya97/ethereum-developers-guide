## Libraries and EthPM

When developing decentralized applications, it often doesn't make sense for every developer to reinvent the wheel when it comes to basic functions.  For this reason, in order to act more like programming languages you may be more familiar with, Solidity supports libraries - pre-written, reusable pieces of code.

###### [Library Driven Development in Solidity](https://blog.aragon.one/library-driven-development-in-solidity-2bebcaf88736) - Jorge Izquierdo, Aragon Medium, 2017 \[8 min read\]

This article from Jorge Izquierdo of Aragon provides a comprehensive review on how to develop more modular, reusable and elegant smart contract systems on top of the Ethereum Virtual Machine by using libraries.

###### [Gas Savings with Libraries](http://blog.ethereum-alarm-clock.com/blog/2015/10/25/one-reason-to-start-using-libraries) \[3 min read\]

In this short article, Piper Merriam demonstrates another potential benefit of using libraries, that for contracts that are not called often, they can potentially be more gas efficient due to need to deploy less code on the chain.

###### [Importing other Solidity Files](http://solidity.readthedocs.io/en/develop/layout-of-source-files.html#importing-other-source-files) \[3 min read\]

Jumping back to the [Layout of a Solidity Source File](http://solidity.readthedocs.io/en/develop/layout-of-source-files.html#) section of the [Solidity Docs](http://solidity.readthedocs.io/en/develop/index.html) we saw earlier in this tutorial, we will read about how to import Solidity source files into each other so we don't have a messy single file with all of our contracts in it.

###### [ERC190](https://github.com/ethereum/EIPs/issues/190) \[5 min read\]

A common standard called ERC190 was created to allow to make it as easy possible to use and develop common shared libraries.  Learn about its basics by reading its specification.

###### [EthPM](https://medium.com/@timothyjcoulter/why-ethereum-needs-package-management-b9e6e457329f) \[4 min read\]

This article, by Tim Coulter of Truffle, explains the concept behind EthPM, a dedicated package manager for Ethereum libraries that conforms to ERC190 standards.

###### [Using EthPM Packages](https://github.com/ethpm/ethpm-spec) \[10 min read\]

Next, read through the specification of EthPM to learn how to use these packages in your own projects.

###### [EthPM with Truffle](http://truffleframework.com/docs/getting_started/packages-ethpm) \[5 min read\]

In this section from the [Truffle Docs](http://truffleframework.com/docs/), read how to use EthPM within the Truffle Framework to install and use packages.

###### [Dappsys](https://dappsys.readthedocs.io/en/latest/) \[resource\]

Dappsys is a repository of very useful and heavily-audited Solidity Libraries that are exposed as EthPM packages.  In this documentation, you can see what each library is used for and how to interact with it.  When building larger contracts, consider using these as contract building blocks.

