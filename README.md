# Chainlink-functions-examples
Using chainlink functions to make API request off chain and save it on chain. 

In order to used it it's necessary to download chainlink functions hardhat started kit:
https://github.com/smartcontractkit/functions-hardhat-starter-kit/tree/main/scripts

Then create a functions contract address and a subscription id in order to found it with link token

## Code

**To simulate** http request using chainlink functions:
  node weather_api.js

**To execute** in to the blockchain:
npx hardhat functions-request --network ethereumSepolia --contract $CONTRACT_ADDR --subid &SUB_ID --simulate true
