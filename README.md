# Mint-Token-Hardhat
- MyToken Contract
- This contract implements a basic ERC-20 token called "Naruto" (NRT). It allows users to mint new tokens, burn existing tokens, and transfer tokens to other addresses.

## Contract Details
# Variables
- name: A string variable representing the name of the token.
- symbol: A string variable representing the symbol of the token.
- totalSupply: An unsigned integer variable representing the total supply of tokens in circulation.
- balances: A mapping that associates addresses with their token balances.
# Modifiers
- onlyOwner: A modifier that restricts the execution of a function to the contract owner.
# Functions
- constructor(): The constructor function that initializes the token's name, symbol, and sets the contract owner to the deployer's address.
- mint(address to, uint256 amount): A function used to mint new tokens and assign them to the specified address. Only the contract owner can call this function.
- burn(uint256 amount): A function used to burn a specified amount of tokens from the caller's address.
- transfer(address to, uint256 amount): A function used to transfer tokens from the caller's address to the specified address.
# License
- This contract is released under the MIT License. Please see the SPDX-License-Identifier comment at the top of the contract for more details.

