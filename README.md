# RalphGamingToken Contract

# Overview
DegenGamingToken is a Solidity smart contract based on the ERC20 standard and utilizes the Ownable contract from OpenZeppelin for access control. It allows users to manage and redeem tokens for games and also includes functionality for minting, transferring, and burning tokens.

# Functions
- totalSupply: Returns the total supply of tokens.
- balanceOf: Returns the balance of tokens for a specific account.
- transfer: Enables users to transfer tokens to other addresses.
- allowance: Returns the amount of tokens that an owner has approved for a spender.
- approve: Allows an account to approve the transfer of tokens from their account to another.
- transferFrom: Allows approved spenders to transfer tokens on behalf of the owner.
- mint: Allows the owner to mint new tokens and distribute them to an account.
- burn: Allows users to burn their own tokens.
- redeemGame: Allows users to redeem tokens for games.
- buyGame: Allows users to buy games using their tokens.
- isGameAvailable: Checks if a specific game is available for redemption or purchase.

# Usage in Remix IDE

- Copy the contract code into the Remix IDE.
- Compile the contract using a Solidity compiler version compatible with ^0.8.0.
- Deploy the contract, specifying the token name, symbol, decimals, initial supply, and initial owner.
- Interact with the deployed contract using the provided functions.
  
# Detailed Function Descriptions

- totalSupply: function totalSupply() public view override returns (uint256);
Returns the total supply of tokens in circulation.

- balanceOf: function balanceOf(address account) public view override returns (uint256);
Returns the number of tokens owned by a specific account.

- transfer: function transfer(address recipient, uint256 amount) public override returns (bool);
Transfers a specified number of tokens to a recipient address.

- allowance: function allowance(address owner, address spender) public view override returns (uint256);
Returns the remaining number of tokens that an owner has allowed a spender to transfer.

- approve: function approve(address spender, uint256 amount) public override returns (bool);
Approves a spender to transfer a specified number of tokens from the caller's account.

- transferFrom: function transferFrom(address sender, address recipient, uint256 amount) public override returns (bool);
Transfers tokens from a sender to a recipient, using the allowance mechanism.

- mint: function mint(address account, uint256 amount) public onlyOwner;
Mints new tokens and assigns them to a specified account. Only the owner can call this function.

- burn: function burn(uint256 amount) public;
Burns a specified number of tokens from the caller's account, reducing the total supply.

- redeemGame: function redeemGame(uint256 gameId) public;
Allows users to redeem a game using their tokens. Mints tokens equivalent to the game's price and marks the game as redeemed.

- buyGame: function buyGame(uint256 gameId) public;
Allows users to buy a game using their tokens. Transfers tokens equivalent to the game's price and marks the game as unavailable.

- isGameAvailable: function isGameAvailable(uint256 gameId) public view returns (bool);
Checks if a specific game is available for redemption or purchase.

# Owner
Ralph Lauren Bensurto

# License
MIT License
