# Kokushibo_Token

# MyToken Solidity Contract
This is a Solidity contract for a simple token called MyToken. The contract allows minting and burning of tokens, as well as keeping track of token balances. It can be deployed and interacted with using the Remix IDE.

Requirements:-
1.The contract has public variables for the token name, abbreviation, and total supply.
2.It uses a mapping to store balances of addresses.
3.The mint function increases the total supply and the balance of the sender's address.
4.The burn function deducts tokens from the total supply and the sender's balance, with a conditional check to ensure sufficient balance.

Usage:-
1.Open the Remix IDE (https://remix.ethereum.org/) in your web browser.
2.Create a new Solidity file and paste the code of the MyToken contract.
3.Compile the contract using Solidity version 0.8.18.
4.Deploy the contract in the Remix IDE's "Deploy & Run Transactions" tab.
5.Interact with the contract by calling its functions in the "Deployed Contracts" section.

Public Variables:-
tokenName: The name of the token (e.g., "Kokushibo").
tokenAbbrv: The token abbreviation (e.g., "KS").
totalSupply: The total supply of tokens.

Minting Tokens:-
Use the mint function to add tokens:
function mint(address _address, uint _value) public
_address: The address to receive the minted tokens.
_value: The number of tokens to mint.

Burning Tokens:-
Use the burn function to remove tokens:
function burn(address _address, uint _value) public
_address: The address from which to deduct tokens.
_value: The number of tokens to burn.

Note: The function checks if the sender's balance is sufficient before burning tokens.
