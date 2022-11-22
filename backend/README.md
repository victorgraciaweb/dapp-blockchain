# dapp-blockchain
Dapp developed with Solidity, Angular, Ganache and Truffle in Ethereum blockchain

How to run?
--

1. Install dependencies

   `npm i package.json`

2. Compile and migrate Smart Contract

   `truffle migrate --reset --compile-all`

Deploy contracts in Binance Smart Chain Testnet (BSC)
--
1. Create file ".secret" with secret key wallet in Root folder

2. Compile and migrate Smart Contract

   `truffle migrate --reset --network bsc`

Deploy contracts in Polygon Testnet (MATIC)
--
1. Create file ".secret" with secret key wallet in Root folder

2. Compile and migrate Smart Contract

   `truffle migrate --reset --network polygon`

Testing
--
1. Testing Smart Contracts

   `truffle test`