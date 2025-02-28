# BASIC-SMART-CONTRACT-DEVELOPMENT

"COMPANY": COTECH IT SOLUTIONS

"NAME": AKSHITHA S

"INTERN ID": CT08IYL

"DOMAIN": BLOCK CHAIN TECHNOLOGY

"DURATION": 4 WEEKS

"MENTOR": NEELA SANTHOSH KUMAR

"DESCRIPTION":

Task 1:
Token Transfer Smart Contract
Overview
This project implements a simple smart contract in Solidity for a token transfer system. The contract allows users to transfer tokens, approve spending limits, and handle delegated transfers.

Features
Token transfer functionality
Approval and allowance system
Secure and efficient Solidity implementation
Deployment on Ethereum testnets
Smart Contract: TokenTransfer.sol
Functions
transfer(address _to, uint256 _value): Transfers tokens from the sender to another address.
approve(address _spender, uint256 _value): Allows a spender to transfer tokens on behalf of the sender.
transferFrom(address _from, address _to, uint256 _value): Allows an approved spender to transfer tokens.
Deployment Steps
Open Remix IDE.
Create a new file and paste the TokenTransfer.sol code.
Compile the contract using Solidity 0.8.x compiler.
Deploy the contract using MetaMask on a test Ethereum network (Goerli, Sepolia, etc.).
Use Remix UI or Web3.js to interact with the contract.
Example Transactions
Deploy with an initial supply of 1000 tokens.
Transfer 50 tokens from the deployer to another account.
Approve an account to spend 30 tokens.
Use transferFrom to move 30 tokens on behalf of the owner.
Dependencies
Solidity ^0.8.0

MetaMask for Ethereum transactions

Remix IDE or Hardhat for development

"OUTPUT":

Task1:
![image](https://github.com/user-attachments/assets/022bd9cb-083e-4260-8095-fd094c3ec5b7)




