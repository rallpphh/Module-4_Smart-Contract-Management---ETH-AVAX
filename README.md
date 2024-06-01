# MyAllowance Contract

# Overview
MyAllowance is a Solidity smart contract that allows users to manage and redeem their daily allowance tokens. It is built on top of the ERC20 standard and utilizes the Ownable contract from OpenZeppelin for access control.

# Functions
### mintAllowance:### Allows the owner to mint new tokens and distribute them to players as rewards.
### transferAllowance:### Enables players to transfer their tokens to other addresses.
### redeemAllowance:### Allows players to redeem their tokens for daily allowance.
### burnAllowance:### Allows anyone to burn their own tokens.
### getBalance:### Allows players to check their token balance, including redeemed allowance.
### AllowancePerDay:### Returns the allowance options per day.

## Usage in Remix IDE
1. Copy the contract code into the Remix IDE.
2. Compile the contract using a Solidity compiler version compatible with ^0.8.20.
3. Deploy the contract, specifying the token name and symbol.
4. Interact with the deployed contract using the provided functions.

## Owner
Ralph Lauren Bensurto

## License
MIT License

## SPDX-License-Identifier
MIT

