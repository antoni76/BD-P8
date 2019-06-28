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
   > Deploying 'RealEstateERC721Token'
   ---------------------------------
   > block number:        4641125
   > block timestamp:     1561746652
   > account:             0x51c31EFf1759634431f634C0fB61d0BF7f51144B
   > balance:             13.62723141
   > gas used:            3315733
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.06631466 ETH

   Deploying 'SquareVerifier'
   ---------------------------------
   > block number:        4641126
   > block timestamp:     1561746743
   > account:             0x51c31EFf1759634431f634C0fB61d0BF7f51144B
   > balance:             13.59173657
   > gas used:            1774742
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.03549484 ETH

   Deploying 'SolnSquareVerifier'
   ---------------------------------
   > block number:        4641127
   > block timestamp:     1561746758
   > account:             0x51c31EFf1759634431f634C0fB61d0BF7f51144B
   > balance:             13.49740951
   > gas used:            4716353
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.09432706 ETH

Contract ABI (xxxxx.json) located in build/contracts

# Mint token

Go to Remix - Solidity IDE

Choose injected web3 and copy contract address to "At address"

Mint 10 token according to proof.json and tokenid is from 1 to 10

Result: Total Supply: 10 RE XXXXh

# Opensea storefront

 My storefront is on XXXXX
 
 tokenid from 1001 to 1005 is brought by XXXXXX htXXXXX


# Project Resources

* [Remix - Solidity IDE](https://remix.ethereum.org/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Truffle Framework](https://truffleframework.com/)
* [Ganache - One Click Blockchain](https://truffleframework.com/ganache)
* [Open Zeppelin ](https://openzeppelin.org/)
* [Interactive zero knowledge 3-colorability demonstration](http://web.mit.edu/~ezyang/Public/graph/svg.html)
* [Docker](https://docs.docker.com/install/)
* [ZoKrates](https://github.com/Zokrates/ZoKrates)
