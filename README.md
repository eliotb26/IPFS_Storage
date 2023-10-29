# Moralis IPFS Tutorial - How to use IPFS with Ethereum

## Resourse 
- https://moralis.io/ipfs-ethereum-tutorial-how-to-use-ipfs-with-ethereum/

## Installation 
` npm i moralis fs dotenv `

add `MORALIS_KEY= {moralis API key}` to .env file 


## Steps 

` node index.js `


## Confirming 

## Running Smart Contract & Deploying 
- remix.io 
- Compile and Deploy using Goerli testnet 
- once deployed, view on etherscan, view the contract created under the "TO" address 
- On the contract address, select contract tab, and "Verify and Publish"
- Complete the compiler information and MIT Open source License Type
- Past in the entire smart contract code in the following designated field 
- Verify and Publish, now there is a deployed smart contract onchain that can be executed directly on Etherscan - Write Contract, Read Contract, etc. 
    - Ex. Read Contract - fetchHash - to return the IPFS address is actually stored in your smart contract 
    - Test that if any other user besides the owner tries to execute "changeHash" then they will be blocked




Write Contract 
- https://goerli.etherscan.io/address/0xdbeb19db593decbde2e12b5b826a58d4fddb8209#writeContract

