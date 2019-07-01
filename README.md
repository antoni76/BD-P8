# Udacity Blockchain Capstone

The capstone will build upon the knowledge you have gained in the course in order to build a decentralized housing product. 

# Install

npm install -g ganache-cli

npm install 

# ZoKrates

docker run -v $PWD/zokrates/code:/home/zokrates/code -ti zokrates/zokrates /bin/bash

cd code/square

~/zokrates compile -i square.code

~/zokrates setup

~/zokrates compute-witness -a 3 9

~/zokrates generate-proof

~/zokrates export-verifier

# Testing

ganache-cli -m "muffin fix icon pelican finish alcohol puzzle farm scheme topple wish jewel"

npm run compile

npm run test-erc721

npm run test-square-verifier

npm run test-soln-square-verifier


# Deployment

Go to Infura to create an account for creating a project.

Get the ENDPOINT url for Rinkeby test network.

Get the test ETH from faucet.rinkeby.io

Config truffle-config.js with Infura ENDPOINT

Run: npm run deploy

## Deploy result

   Deploying 'SolnSquareVerifier'
   ---------------------------------
   > contract address:    0x0790f76a1A4a679D3A1884f4537A327C4a853815
   
## Mint token
Go to Myetherwallet
Go to Menu- Interact with contract adding contract address and ABI from build/contracts/SolnSquareVerifier.json (lines 3 to 705)
Mint 10 token https://rinkeby.etherscan.io/tx/0xed645c38e050ada4d9c7adf44af293e7ee36d4075285ff6d926580f04fe27d3c

## Opensea storefront
My storefront is on https://rinkeby.opensea.io/assets/realestatev69
Tokens have been sold https://rinkeby.etherscan.io/tx/0x8b28da02e96046bf5064da69ad4f54fb22d83aecad6447fa3af041fb34c7f6b4


# Project Resources

* [Remix - Solidity IDE](https://remix.ethereum.org/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Truffle Framework](https://truffleframework.com/)
* [Ganache - One Click Blockchain](https://truffleframework.com/ganache)
* [Open Zeppelin ](https://openzeppelin.org/)
* [Interactive zero knowledge 3-colorability demonstration](http://web.mit.edu/~ezyang/Public/graph/svg.html)
* [Docker](https://docs.docker.com/install/)
* [ZoKrates](https://github.com/Zokrates/ZoKrates)
