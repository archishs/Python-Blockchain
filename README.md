# Basic Python Blockchain

This is a simple blockchain system built in python. It includes essential features for a blockchain system such as hashing, data verification and forking. Read further below to get a sense of some of the crucial elements of a blockchain.

## Hashing

Hashing in blockchain is nothing but taking an input file, and outputting a hash or code of a standard size. If we were using cryptocurrencies as an example, a hashing algorithm would take in transactions of varying lengths and provide an output of one fixed length. The output of the hashing algorithm is called a hash. There are many types of hashing algorithms including bitcoin's SHA-256, SHA-2 and the one we are using called UTF-8. The number following the string of letters indicates how many bits the outputted hash will be.

## Data verification

Whenever a block is created or "mined", it is added to the chain. But wait, there is a step in between mining and adding to the chain, which is validating the block and making sure the block can be used and is not created by someone else.

## Forking

In its most basic form, forking is how the blockchain system deals with the situation of when one block splits into two or more paths. This could happen when two miners attempt to mine the same block and the system has to log both of their interactions with the block. There are many types of forking and it is explained very well in this article: https://lightrains.com/blogs/what-is-meant-by-forking-blockchain.

## Summary and usage guide

Blockchain is a vast and ever-growing field. This system that I have coded is a very rudimentary example of a blockchain. To use it, you can instantiate blocks using the functions for any purpose including data storage, creating your own mini crypto currency, and much more.
