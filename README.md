# MyToken Contract

# Overview
MyToken is a Solidity smart contract based on the ERC20 standard and utilizes the Ownable contract from OpenZeppelin for access control. It allows users to manage and redeem tokens for daily allowance and also includes functionality for minting, transferring, burning tokens, and managing redeemable items.

# Functions

- **mint**: Allows the owner to mint new tokens and distribute them.
- **transfer**: Enables users to transfer tokens to other addresses.
- **redeemItem**: Allows users to redeem tokens for items.
- **burn**: Allows users to burn their own tokens.
- **totalSupply**: Returns the total supply of tokens.
- **balanceOf**: Returns the balance of tokens for a specific account.
- **allowance**: Returns the amount of tokens that an owner has approved for a spender.
- **approve**: Allows the owner to approve the transfer of tokens from their account to another.
- **transferFrom**: Allows approved spenders to transfer tokens on behalf of the owner.
- **isItemAvailable**: Checks if a specific item is available for redemption or purchase.

# Usage in Remix IDE
1. Copy the contract code into the Remix IDE.
2. Compile the contract using a Solidity compiler version compatible with ^0.8.20.
3. Deploy the contract, specifying the token name, symbol, decimals, initial supply, and initial owner.
4. Interact with the deployed contract using the provided functions.

# Owner
Ralph Lauren Bensurto

# License
MIT License

## SPDX-License-Identifier
MIT
