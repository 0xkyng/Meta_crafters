# Project Overview

## Project Name: MyToken

Purpose: This Solidity smart contract, `MyToken`, aims to create a basic token on the Ethereum blockchain. It provides functionalities for minting and burning tokens, as well as tracking token balances for Ethereum addresses.

## Contract Functionality
Token Details

    `tokenName`: A public variable storing the token's name, set to `0xkyng`.
    `tokenAbr`: A public variable storing the token's abbreviation, set to `0xk`.
    `totalSupply`: A public variable representing the total supply of tokens, initially set to `0`.

## Minting

    `mint(address _address, uint256 _value):` A public function allowing the creation of new tokens and assigning them to a specific Ethereum address. It increases the total supply by the specified value and adds the same value to the balance of the provided address.

## Burning

   ` burn(address _address, uint256 _value)`: A public function for destroying tokens held by a specific address. It checks if the address has a sufficient balance, and if so, decreases the total supply and the address's balance by the specified value.

This contract provides a foundation for creating a simple ERC20-like token, although it lacks some critical features and security measures typically found in production-level tokens. This code is suitable for educational purposes or as a starting point for more complex token contracts.
