# Lottery

### Overview

Decentralised Lottery picking project. This solidity project uses Keccak256 algorithm to randomly pick the winner of the lottery (Caution: The Keccak256 algorithm is used only for the sake of demonstration, not to use this algorithm to deploy a real lottery smart-contract on the Mainnet as this is not the correct algorithm to choose a random participant and hence, can be easily attacked by an attacker). The participants can enter the lottery by simply paying the entry fee at the address of smart contract.

### Implementation

- Create an account in Metamask (Make sure to add some test ETH in your testnet account) - This account will be the manager account for the lottery
- Compile and Deploy this smart contract on Injected Web3 Environment in Remix online IDE
- Create atleast 3 more accounts on the same testnet in Metamask and add some test ETH (> 1 ETH) from any faucet
- Transfer 1 ETH from each of the three accounts made in the previous step to the smart contract
- Cross-check if the contract has received 3 ETH in total from the getBalance function in the deployed contract within Remix IDE
- Last, call the getWinner function in the deployed smart contract within Remix IDE to choose the lottery winner

***

## Pre-Requisites

- Metamask
- Remix IDE



***

<p align='center'>Created with :heart: by <a href="https://github.com/mumukshtayal">Mumuksh Tayal</a>, <a href="https://github.com/tayalmanan28">Manan Tayal</a></p>
