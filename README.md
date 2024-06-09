# Project 2

## Overview

The `Project` implements a basic functions like minting and burning token on the Ethereum blockchain, named "Shiba INU" (SHIB). It includes functionalities to mint and burn tokens, modifying the total supply and individual balances accordingly. To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

## Contract Details

- **Token Name:** Shiba INU
- **Token Abbreviation:** SHIB
- **Total Supply:** This is initially set to 0 but can be increased by the mint function.

## Address Mapping
The contract includes a mapping to track the balance of tokens for each address.

### Available
This is a mapping of addresses to their respective token balances. The balance of any address can be checked using this mapping.

## Functions

### mint_token

This function is used to create new tokens and add them to the total supply and to the balance of a specified address.

**Parameters:**
- `address addres`: The address to which the tokens will be minted.
- `uint supply_Value`: The amount of tokens to be minted.
  
**Usage:**
```solidity
function mint_token(address addres, uint supply_Value) public
```
### burn_token

This function is used to destroy tokens from a specified address, reducing the total supply and the balance of that address.

**Parameters:**
- `address addres`: The address from which the tokens will be burned.
- `uint supply_Value`: The amount of tokens to be burned.

**Usage:**
function burn_token(address addres, uint supply_Value) public

```solidity
function burn_token(address addres, uint supply_Value) public
```
## Authors

Contributors names and contact info

Aakash Sharma  
(aakasharma5504@gmail.com)

