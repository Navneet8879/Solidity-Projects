Public Variables:
1. name: A string to store the name of the token.
2. symbol: A string to store the abbreviation (symbol) of the token.
3. totalSupply: An unsigned integer to store the total supply of tokens.
   
Mapping:
1. balances: A mapping from addresses to their respective balances.
   
Mint Function:
mint(address to, uint amount): This function takes an address and an amount as parameters.
1. Increases the totalSupply by the specified amount.
2. Increases the balance of the specified address (to) by the specified amount.
   
Burn Function:
burn(address from, uint amount): This function takes an address and an amount as parameters.
1. Includes a require statement to ensure that the balance of the specified address (from) is sufficient to burn the specified amount.
2. Decreases the totalSupply by the specified amount.
3. Decreases the balance of the specified address (from) by the specified amount.
