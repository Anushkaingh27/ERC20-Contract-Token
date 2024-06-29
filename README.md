# ERC20-Contract-Token
This is a smart contract written in Solidity that enables you to create your own token on a local HardHat network. The contract inherits from the ERC20 standard token contract, providing all 
the necessary functionalities for managing and transferring tokens.
## Description

The smart contract is implemented in Solidity and contains the following features:

- *Token Creation:* The contract allows you to create your own token with a custom name and symbol when deploying the contract.

- *Minting:* Any user can mint new tokens to a specified address. Minting increases the total supply of the token.

- *Burning:* Any user can burn their own tokens, reducing the total supply of the token.

- *Transfers:* Users can transfer tokens to other addresses, given they have a sufficient balance.

## Getting Started

#### Prerequisites
- A development environment with Solidity compiler (version 0.8.13 or compatible) and HardHat installed.
- Access to a local HardHat network or testnet with an active provider.

Follow the steps listed below to interact with the smart contract.

##### **Remix IDE**
   - Open the Remix IDE (https://remix.ethereum.org/) in your web browser.
   - Copy and paste the smart contract `(contract.sol)` code into the Remix editor.
   - Select the appropriate compiler version for the smart contract.
   - Compile the contract by clicking the "Compile" button.
   - Ensure that the contract is successfully compiled without any errors.

##### **Deployment**
   - Switch to the "Deploy & Run Transactions" tab in Remix.
   - Set up a local network or testnet to deploy the contract.
   - From the "Environment" dropdown, select the HardHat development environment.
   - Click the "Deploy" button to deploy the contract using the HardHat deployment scripts, providing the desired name and symbol for your token.
## Authors
  Name: Anushka Singh email id-anushkasingh272005@gmail.com
