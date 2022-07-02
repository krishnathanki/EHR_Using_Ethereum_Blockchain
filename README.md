# EHR_Using_Ethereum_Blockchain

## To run this project Kindly install following requirements :

* "Truffle" v5.1.20
    * solc: "0.5.16"
    (used for compiling n migrating the smart contracts)
* "Node" v12.16.1 (Install Following with npm)
    * "@emotion/react": "^11.9.0",
    * "@emotion/styled": "^11.8.1",
    * "@mui/icons-material": "^5.6.0",
    * "@mui/material": "^5.6.0",
    * "antd": "^3.9.0",
    * "axios": "^0.19.2",
    * "bootstrap": "^4.4.1",
    * "bs58": "^4.0.1",
    * "ipfs-api": "^26.1.2",
    * "react": "16.11.0",
    * "react-bootstrap": "^1.0.0",
    * "react-dom": "16.11.0",
    * "react-router-dom": "^6.2.2",
    * "react-scripts": "3.2.0",
    * "web3": "^1.7.1"
	(used to help run the server n few react compont)

* Install Metamask as Google Chrome extension.

* Install Ganache for deployement of Contracts.

## Steps to run project : 
0) load ganache with a new workspace, conf it as per the truffle conf file in the root dir.
1) Add ___truffle-config.js___ file in Ganache, after creation edit the first address to the 3rd smart contract aka owner.
2) Create new network in ___metamask___ with port number same as in ___truffle-config.js___
3) Configure Ganache with same port number.
4) Goto Project Directory and run ___"truffle migrate"___ on command prompt, dont skip this, this will convert ur sol contracts into json.
5) Goto Client directory and run ___"npm install --force"___ to install all req and then run ___"npm start"___ to start react server.
6) Project will be open in your browser.
7)making accounts from ganache to meta mask n marking them as per it.
8)if accounts are proper the it will load or else not.

Execution will start from __App.js__ file in client directory.

## sildes chould find

https://docs.google.com/presentation/d/1OizR6slIn5KHgvNGpl9funr0OJHTKV811LbKO4bVFgY/edit?usp=sharing

