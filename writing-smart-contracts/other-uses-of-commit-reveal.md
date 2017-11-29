## Other Uses of Commit-Reveal

The commit-reveal commitment scheme is a very valuable construct that appears in many types of smart contracts beyond just voting.  In this section we will show a few more examples of commit-reveal being used in smart contracts.

###### [RanDAO](https://github.com/randao/randao) \[4 min read\]

One of the biggest open problems in distributed systems is how to create deterministic ungameable random numbers.  This random number generation \(RNG\) is incredibly useful for a multitude of on-chain applications ranging from gambling to .  Although, not perfect due to a process called griefing, a commit-reveal scheme for RNG is often sufficient for most use cases.  RanDAO is an on-chain system that outputs fair random numbers and uses incentivize schemes to minimize griefing.  Read through the ReadMe on it's Github page as well as randao.sol in the contracts folder to see if you can work out how the contract works.

###### [Blind Auction](http://solidity.readthedocs.io/en/develop/solidity-by-example.html#blind-auction) \[10 min read\]

Another common usage of blockchain is to hold auctions for ownership of items.  However, for many use cases, it is beneficial for the auction to be blind so there won't be a time pressure towards the end of the bidding period.  To allow for these blind auctions, we can use a commit-reveal scheme.  The ENS Domain Auctions use a similar scheme.  In this snippet from the Solidity docs, you will first read the smart contract for a normal auction and then see how to modify it for a blind auction.

###### [Rock Paper Scissors](https://github.com/SCBuergel/ethereum-rps) \[10 min read\]

In many games, there is often a need for both players to make a move at the same time without knowing what the other player did.  To achieve this effect on a blockchain, we can use a commit-reveal scheme as well.  To see how this works, read through the rps-advanced.sol file in this github repository.

