# Cross-Blockchain Token-Swap with Ethereum
This is a comprehensible swap protocol that enables exchanging assets on and between different blockchains on the Ethereum network with the help of Hashed Timelock Contracts (HTLC).

This project was conducted during the course of our bachelor studies at the University of Regensburg, Germany.

## Table of contents
* [Technologies](#technologies)
* [Setup](#setup)
* [Installing](#installing)
* [Running the tests](#running-the-tests)
* [Usage](#usage)
* [Sources](#sources)

## Technologies 
-	Solidity v0.6.0
-	Bootstrap v3.3.7
-	jQuery v1.12.4
-	HTML 5
-	CSS
-	JavaScript

## Setup
Fork this repository and cd into it:
```
git clone https://github.com/TuanUR/Projektseminar

cd Projektseminar
```
To run this project, install the following dependencies locally:
1.	npm (v6.14.8 or above)
2.	hd-wallet-provider
3.	openzeppelin contracts

## Installing
1.	npm 
```
npm install
```
2.  @openzeppelin/contracts, containing the necessary token standards for the usage of ERC-20 tokens
```
npm install @openzeppelin/contracts
```
3.
truffle-hdwallet-provider
```
npm install truffle-hdwallet-provider
```

## Running the tests
To run the Truffle tests, simply run the command
```
truffle test
```

## Usage 
TODO

## Sources 
The code of the HTLC contract was inspired by hashed-timelock-contract-ethereum project on GitHub:
https://github.com/chatch/hashed-timelock-contract-ethereum
