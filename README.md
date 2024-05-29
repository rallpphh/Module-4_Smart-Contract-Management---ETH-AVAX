# MyAllowance Smart Contract

# Overview

The `MyAllowance` smart contract is a custom ERC20 token designed for a gamified platform where tokens can be minted, transferred, redeemed, and burned. The owner has exclusive rights to mint new tokens, while players can manage their tokens in various ways.

#cFunctions

Minting New Tokens (`mintAllowance`)
 Description: The owner can mint new tokens and distribute them to players.
 Usage: `mintAllowance(address _to, uint256 _amount)`

Transferring Tokens (`transferAllowance`)
 Description: Players can transfer their tokens to others.
 Usage: `transferAllowance(address _to, uint256 _amount)`

Redeeming Tokens (`redeemAllowance`)
 Description: Players can redeem their tokens for items in the in-game store.
 Usage: `redeemAllowance(uint256 _amount)`

Checking Token Balance (`getBalance`)
 Description: Players can check their token balance at any time.
 Usage: `getBalance()`

Burning Tokens (`burnAllowance`)
 Description: Players can burn tokens they own that are no longer needed.
 Usage: `burnAllowance(uint256 _amount)`

Allowance Per Day (`AllowancePerDay`)
 Description: View the allowance distribution per day.
 Usage: `AllowancePerDay()`

# Usage in Remix IDE

To deploy and interact with the `MyAllowance` contract in Remix IDE:

Open Remix IDE
 Navigate to [Remix IDE](https://remix.ethereum.org/).

Create a New File
 Create a new Solidity file (e.g., `MyAllowance.sol`) and paste the contract code into this file.

Compile the Contract
 Select the appropriate compiler version (e.g., `0.8.20`).
 Click on the "Compile" button to compile the contract.

Deploy the Contract
 Go to the "Deploy & Run Transactions" tab.
 Select the `MyAllowance` contract from the dropdown menu.
 Click on the "Deploy" button.
 Ensure you have selected an appropriate environment (e.g., JavaScript VM, Injected Web3) and have sufficient funds in the selected account.

Interact with the Contract
 Once deployed, you can interact with the contract's functions through the Remix interface.
 Use the input fields and buttons corresponding to each function to mint, transfer, redeem, check balance, and burn tokens.

# Owner

Ralph Lauren Bensurto

# License

This project is licensed under the MIT License. See the SPDX-License-Identifier in the contract code for more details.
