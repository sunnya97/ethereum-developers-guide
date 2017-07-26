## Basic Practice Reading Contracts

In this section, we will link to a couple of real, albeit simple smart contracts.  See what you can understand from analyzing these contract using the knowledge you have now and try to understand what each function does.

###### [SimpleStorage](https://gist.github.com/naterush/79b585a5cdd9537fc0af95b75458b87d) \[exercise\]

This simple contract stores a single integer in storage and then allows anyone to update the value of this integer.

###### [Incrementor](https://github.com/fivedogit/solidity-baby-steps/blob/master/contracts/20_value_incrementer.sol) \[exercise\]

This example is similar to SimpleStorage, however instead of being able to pass in any new value to update the stored integer to, we can now only use the increment function \(which takes no arguments\) to increment the counter by 1 every time it is called.

###### [Greeter](https://github.com/fivedogit/solidity-baby-steps/blob/master/contracts/05_greeter.sol) \[exercise\]

This contract is also similar to SimpleStorage, however, this time instead of integer being stored, we store and get a String.

###### [Basic Iterator](https://github.com/fivedogit/solidity-baby-steps/blob/master/contracts/08_basiciterator.sol) \[exercise\]

This contract simply instantiates an array upon construction and then calculates the sum every time the getSum function is called.

###### [Creator Balance](https://github.com/fivedogit/solidity-baby-steps/blob/master/contracts/10_creator_balance_checker.sol) \[exercise\]

This contract begins to use some of the global variables we've learned about in order to retrieve and store the ether balance of the contract creator.

###### [Global Variables Kitchen Sink](https://github.com/fivedogit/solidity-baby-steps/blob/master/contracts/15_basic_info_getter.sol) \[exercise\]

This contract doesn't serve much real purpose, but rather shows many of the other global variables available and provides some details in the contract comments.

