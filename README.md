# Simplified Token Trade Contract
Extremely simpilified Uniswap-based contract

## Contracts
***Factory***   
The Factory contract to create *SwapPool* contracts. This contract create new pools specific to ERC20 token.

***SwapPool***      
The Pool contract. This contract mints liquidity token *RToken*, also burns and sends tokens.

***RToken***      
The ERC20-compatible liquidity token. RToken shows the right to receive pooled asset.

***Periphery***   
User interacts the *Periphery* contract instead of calling Factory or SwapPool Contract directly. This contract interact with other contracts. 

## Installation
`npm install ` 

## Typechain
If you want to create Typechain artifacts for ethers v5, run:

`npm run typechain`

## Testing
`npm test `