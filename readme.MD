# Decentralized Application
nvm alias default 12
truffle compile // Compile to make sure everything is correct
npm install chai
npm install truffle-assertions

truffle test

truffle migrate
truffle console
devToken = await DevToken.deployed(); // await contract to be deployed
let accounts = await web3.eth.getAccounts() // Grab all accounts
await devToken.stake(100, {from: accounts[0]}) // Stake 100 from owner

const helper = require("./helpers/truffleTestHelpers");

truffle test

from: https://itnext.io/creating-a-inheritable-staking-contract-in-solidity-7804ae2d7a32