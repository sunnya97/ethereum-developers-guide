# Storage vs. Memory

By now, you understand that smart contracts are interacted with by using transactions on the Ethereum blockchain. As a result, there is a distinction between storage and memory in Ethereum. Storage is what persists in-between Ethereum transactions, while memory is transaction specific. This can be thought of similarly to global variables.

###### [Difference Between Memory and Storage?](https://ethereum.stackexchange.com/questions/1232/difference-between-memory-and-storage) - Ethereum StackExchange, 2016 \[2 min read\]

This short StackExchange post explains the difference between the two by comparing them to the memory and hard disk of a computer, as well as explaining a bit about how the EVM deals with both of them.

###### [Data Location](http://solidity.readthedocs.io/en/develop/types.html#data-location) - Solidity Documentation \[3 min read\]

Read the Data Location subsection from the Types section of the Solidity docs once again, and see if you can understand it better now that you know the difference between storage and memory.

###### [What is the memory keyword? What does it do?](https://solidity.readthedocs.io/en/latest/frequently-asked-questions.html#what-is-the-memory-keyword-what-does-it-do) - Solidity Documentation \[1 min read\]

This answer from the FAQ section of the Solidity docs provides an explanation of how to use the memory and storage keywords and the default location of variables when not specified.

