# Udacity Blockchain Capstone

The capstone will build upon the knowledge you have gained in the course in order to build a decentralized housing product. 

# Install

npm install -g ganache-cli

npm install 

# Testing

ganache-cli -m "muffin fix icon pelican finish alcohol puzzle farm scheme topple wish jewel"

npm run compile

npm run test-erc721

npm run test-square-verifier

npm run test-soln-square-verifier

# ZoKrates

docker run -v ~/github/Blockchain-Capstone/zokrates/code:/home/zokrates/code -ti zokrates/zokrates /bin/bash

cd code/square

~/zokrates compile -i square.code

~/zokrates setup

~/zokrates compute-witness -a 3 9

~/zokrates generate-proof

~/zokrates export-verifier

# Deployment

Go to Infura to create an account for creating a project.

Get the ENDPOINT url for Rinkeby test network.

Get the test ETH from faucet.rinkeby.io

Config truffle-config.js with Infura ENDPOINT

Run: npm run deploy

Deploy result

   Deploying 'RealEstateERC721Token'
   ---------------------------------
   > contract address:    0x1a6D7e089b17fBE7D8e6E08a36A4231DeE5F769d

   Deploying 'SquareVerifier'
   ---------------------------------

   > contract address:    0x4E0FFBe6F26A30D187dC35F72382d65f12C05210

   Deploying 'SolnSquareVerifier'
   ---------------------------------
   > contract address:    0xa989462334c95F9fA4E253a1b031833fF2423367
   

# Opensea storefront

 My storefront is on https://rinkeby.opensea.io/assets/real-estate-v62


# Project Resources

* [Remix - Solidity IDE](https://remix.ethereum.org/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Truffle Framework](https://truffleframework.com/)
* [Ganache - One Click Blockchain](https://truffleframework.com/ganache)
* [Open Zeppelin ](https://openzeppelin.org/)
* [Interactive zero knowledge 3-colorability demonstration](http://web.mit.edu/~ezyang/Public/graph/svg.html)
* [Docker](https://docs.docker.com/install/)
* [ZoKrates](https://github.com/Zokrates/ZoKrates)
