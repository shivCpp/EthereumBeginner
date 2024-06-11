# Introduction:

It is simple smart contract ( MY TOKEN ) for minting and burning tokens on the Ethereum blockchain.

# Description:

MyToken is a simple ERC20-like token contract implemented by Solidity. It allows tracking the total supply and balances of individual addresses, as well as minting new tokens and burning old ones. This contract is intended to be a learning tool for basic token management and smart contract creation..

# Characteristics:

- Accessible variables to store information about tokens, such as name, symbol, and Total supply.

- Mapping for tracking the balance of each address available.

- A function that contains the necessary controls to create new IDs and delete existing records.


# Contract Details:


## - Variables Used

tokenName(string): Data type used string for given a name to the token.(Token Name: META)

tokenSymbol(string): This  gives a shortform for the token.(Token Symbol: MTA)

totalSupply(uint): Data type used uint i.e only positive number, this gives the amount of token .(Initial balance :0)

## - Mapping

balances: An association between addresses and token balances.


## - Functions
  
mint(address account, uint amount): This function adds the designated amount to the address's balance and increases the total token supply.

burn(address account, uint amount): This function subtracts the specified amount from the address's balance and reduces the total token supply. Before continuing, it makes sure that the address's balance is more than or equal to the burnt.

# Usage


- Deployment: Open the left pan and then select Deploy Option.  
- Minting Token: Use the mint function and enter the address and desired number of minted tokens to create new tokens. For example, you can add mint(0xAbc123..., 100) 100 characters 0xAbc123....
- Burning token: Use the burn feature and enter the address and number of characters to burn to remove them. For example, you can use burn(0xAbc123....., 50) to extract 50 characters from 0xAbc123....., but only if the balance is sufficient. of.
