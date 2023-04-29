
# MyToken Contract
MyToken is a Solidity smart contract that allows for the creation and management of a custom ERC-20 token.

# Functionality
This contract has the following functionality:

## Token Details:
Public variables store the details about the token, including its name, abbreviation, and total supply.

## Balance Mapping: 
A mapping of addresses to balances is included to keep track of how many tokens each address holds.

## Mint Function: 
A mint function increases the total supply by a specified amount and increases the balance of the specified address by the same amount.

## Burn Function: 
A burn function decreases the total supply by a specified amount and decreases the balance of the specified address by the same amount.

## Validation: 
The burn function includes conditionals to ensure that the balance of the specified address is greater than or equal to the amount being burned.

# Usage
To use this contract, you can deploy it to a blockchain network that supports Solidity smart contracts. Once deployed, you can interact with the contract using a blockchain explorer or by using a web3-enabled wallet, such as MetaMask.

To mint new tokens, you can call the mint function and specify the address and the number of tokens to be minted. To burn tokens, you can call the burn function and specify the address and the number of tokens to be burned.

# License
This contract is licensed under the MIT License.
