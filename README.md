#MyToken Smart Contract
This repository contains a simple Solidity smart contract called MyToken. The contract is designed to create and manage a custom ERC20-like token with minting and burning capabilities.

Table of Contents
1.Introduction
2.Contract Details
3.Getting Started
      I. Prerequisites
      II. Installation
      III. Deployment
4.Usage
      I. Minting Tokens
      II. Burning Tokens
5.Interacting with the Contract
      I. Using Remix IDE
6.License


**Introduction**
The MyToken contract allows the creation and management of a custom cryptocurrency. It includes functions to mint new tokens and burn existing ones, while keeping track of token balances and total supply.

**Contract Details**
Token Name: DogeshCulture
Token Abbreviation: DC
Total Supply: Initially set to 0

**Getting Started**
I. Prerequisites
A computer with internet access
A web browser
Basic understanding of Solidity and smart contracts
II. Installation
To work with this contract, you will need to use Remix IDE, an online Solidity compiler and IDE.

III. Deployment
I. Open Remix IDE: Go to Remix IDE.

II. Create a New File:
- Click on the "File Explorers" icon on the left panel
- Click on the "New File" button
- Name your file with a .sol extension, e.g., MyToken.sol

III. Paste the Code:
- Copy the Solidity code from this repository and paste it into the newly created file

IV. Compile the Code:
- Click on the "Solidity Compiler" icon on the left panel
- Select the appropriate compiler version (e.g., 0.8.18)
- Click on the "Compile MyToken.sol" button

V. Deploy the Contract:
- Click on the "Deploy & Run Transactions" icon on the left panel
- Select "JavaScript VM" in the Environment dropdown for a local blockchain environment
- Click on the "Deploy" button

**Usage**
I. Minting Tokens
To mint new tokens, call the mint function with the recipient's address and the amount of tokens to mint. This increases the total supply and updates the recipient's balance.
#Solidity
function mint(address recipient, uint amount) public

II. Burning Tokens
To burn tokens, call the burn function with the account's address and the amount of tokens to burn. This decreases the total supply and updates the account's balance, provided the account has enough tokens.
#Solidity
function burn(address account, uint amount) public

**Interacting with the Contract**
I. Using Remix IDE
Open Remix and create a new file (e.g., MyToken.sol).
Copy and paste the contract code into the new file.
Compile the contract using the Solidity compiler.
Deploy the contract using the "Deploy & Run Transactions" panel.
Use the provided UI to call the mint and burn functions and observe the changes in coinTotalSupply and balances.


**License**
This project is licensed under the MIT License - see the LICENSE file for details.


Author
Awanish Singh
