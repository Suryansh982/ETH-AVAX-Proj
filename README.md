# ETH-AVAX-Project
# Curse Token (CRSPV) Solidity Contract

This Solidity smart contract implements a basic ERC20-like token called Curse Token (`CRSPV`). It includes functionalities to mint new tokens and burn existing tokens.

## Contract Details

- **Token Name:** curseToken
- **Token Symbol:** CRSPV
- **Total Supply:** 0 (initially)

## Functions

### `mint`

```solidity
function mint(address to, uint256 amount) public
function burn(address from, uint256 amount) public

