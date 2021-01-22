## Solidity

# Intro to Solidity

For the purposes of learning, we will start with the coding game Crypto Zombies created by the Loom Network.


Chapter 1:
All solidity source code starts with a "version pragma". This tells a compiler which Solidity version it should use.
A "contract" creates a shell in which you can begin to write your smart contract.

"For the scope of this tutorial, we'll want to be able to compile our smart contracts with any compiler version in the range of 0.5.0 (inclusive) to 0.6.0 (exclusive). It looks like this: **pragma solidity >=0.5.0 <0.6.0;.**"

Chapter 2:
Solidity's code is encapsulated in contracts. A contract is the fundamental building block of Ethereum applications — all variables and functions belong to a contract, and this will be the starting point of all your projects.

An empty contract named HelloWorld would look like this:

**contract HelloWorld {

}**


# State Variables & Integers
