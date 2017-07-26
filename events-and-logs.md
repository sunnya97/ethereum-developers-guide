## Events

Events are signals dispatched by smart contracts so that DApps, or anything connected to Ethereum JSON-RPC API, can listen for to know something has happened on the blockchain and then act accordingly.  These events are then recorded in Logs.

###### [Technical Introduction to Events and Logs](https://media.consensys.net/technical-introduction-to-events-and-logs-in-ethereum-a074d65dd61e) \[5 min read\]

This post from ConsenSys Media gives a great introduction to Events and Logs, and explore three different use cases: return values for the front-end, asynchronous triggers, and cheap storage.

###### [Solidity Docs Events](http://solidity.readthedocs.io/en/develop/contracts.html#events) \[2 min read\]

This section of the Solidity docs shows some examples of using logs from both the Solidity side and Javascript side.

###### [Events Example Contract](https://github.com/ethchange/smart-exchange/blob/master/lib/contracts/SmartExchange.sol) \[Exercise\]

This basic contract uses fires event based on which of its functions are called.  Make sure you understand what is going on.  Bonus, try to see if you can figure out what the contract does!

