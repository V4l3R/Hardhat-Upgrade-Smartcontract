# Hardhat Upgrade Smartcontract Project

This is a project based on the FreeCodeCamp tutorial

This project demonstrates an implementation of proxy smart contract which allow to upgrade smart contract logic after his deployment.
It comes with contracts and scripts to deploy them.


To run it:

1. Rename .env.example file to .env
2. Fill the .env file with the private key of a metamask's wallet (with no real fund on it!! https://goerlifaucet.com/)
3. Fill the .env file with an etherscan api key : https://etherscan.io/myapikey
4. Fill the .env file with a coinmarketcap api key : https://pro.coinmarketcap.com/account
5. Run "yarn hardhat deploy --network hardhat" command in the command prompt for a local deployment
6. Run "yarn hardhat deploy --network goerli" command in the command prompt for a testnet deployment

To upgrade the smart contract on testnet : 
1. Run "yarn hardhat run scripts/upgrade-box.js --network goerli" command in the command prompt
