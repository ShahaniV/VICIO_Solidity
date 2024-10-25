# MyToken Smart Contract

A simple smart contract built using Solidity to create and manage a custom token with mint and burn functionalities.

## Description

This project implements a token contract where users can mint and burn tokens. It stores token balances for different addresses, allows minting new tokens to increase the total supply, and burning tokens to reduce the total supply. The contract is designed with basic checks to ensure that tokens cannot be burned unless the balance is sufficient.

## Getting Started

### Installing

To get started with this project, you need to install and set up [Remix IDE](https://remix.ethereum.org/) where the smart contract will be compiled and run.

1. Open [Remix IDE](https://remix.ethereum.org/).
2. Copy and paste the code from the `myToken.sol` file into a new Solidity file in Remix.
3. Compile the contract using Solidity version 0.8.x or higher.

### Executing Program

To execute the program, follow these steps in Remix:

1. **Compile the contract:**
   - In the Remix IDE, select the `Solidity Compiler` tab.
   - Compile the contract `myToken.sol` using the appropriate Solidity version.
   
2. **Deploy the contract:**
   - Go to the `Deploy & Run Transactions` tab.
   - Ensure that the environment is set to `JavaScript VM (London)`.
   - Deploy the contract by clicking `Deploy`.

3. **Mint Tokens:**
   - After deployment, you will see the contract functions.
   - Call the `mint` function, passing an address and a value to mint tokens.
   - Example: Mint 100 tokens to an address.

   ```solidity
   mint("0xAbc...123", 100)
   
4. **Burn Tokens:**
   - Call the burn function, passing an address and a value to burn tokens.
   - Example: Burn 50 tokens from an address.
     
   ```solidity
   burn("0xAbc...123", 50)
5. **Check Balances and Total Supply:**
   - View the total supply of tokens and the balance of any address using the public variables.

   ```solidity
   totalSupply()
   balances("0xAbc...123")
   
### Authors

Metacrafter Shahani Vicio
