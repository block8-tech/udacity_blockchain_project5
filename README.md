# Udacity Blockchain Developer Nanodegree - Project 5 - Build CryptoStar Dapp on Ethereum

## How to use this API:

#### Install the code
1. Download OR clone this GitHub repository
2. Open a terminal or command-prompt and navigate to the directory where this repository was saved and type: `npm install`
3. Navigate into the `app` directory
4. From terminal or command-prompt (remaining in the same directory as above) type: `npm run dev`.
5. Open your internet browser and goto: [http://localhost:8080](http://localhost:8080)


## Dapp Details
* Type of Ethereum Token: `ERC-721`
* ERC-721 Token Name: `Block Star`
* ERC-721 Token Symbol: `BST`
* Token Contract Address: [`0x43bE1c6b05322eaB944355fF32a3d9eC7ec04E71`](https://rinkeby.etherscan.io/address/0x43be1c6b05322eab944355ff32a3d9ec7ec04e71)
* Example of transaction hash: [`0xdd8603be87e5511f5389f530692e36a23f12f2bcb3b481137bb23fa8e480e11f`](https://rinkeby.etherscan.io/tx/0xdd8603be87e5511f5389f530692e36a23f12f2bcb3b481137bb23fa8e480e11f)

## Result of deploying Dapp to rinkeby
#####console output
```$xslt
1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   ⠼ Saving migration to chain.   > transaction hash:    0xc6948fca889d0f1ca6751cc6186e054ce8cbaea1536b57fa8b584369cfdcbbb9


   > Blocks: 0            Seconds: 12
   > contract address:    0x9aFcf5C76D5720DfBfb438F7F0E61a7C242321Ae
   > block number:        4466914
   > block timestamp:     1559133352
   > account:             0x3D38C8894a7213A0dF4142958dC0f0DE94147D25
   > balance:             18.71636432
   > gas used:            284908
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00284908 ETH

   Pausing for 2 confirmations...
   ------------------------------
   ....
   ...
   ..
   .
   ------------------------------
   
   2_deploy_contracts.js
   =====================
   
      Deploying 'StarNotary'
      ----------------------
      > transaction hash:    0x24aa87b4ae4c55629985913a879c0e6114d1acaa7ea86710136e7874a8947ef0
      > Blocks: 0            Seconds: 12
      > contract address:    0x43bE1c6b05322eaB944355fF32a3d9eC7ec04E71
      > block number:        4466918
      > block timestamp:     1559133412
      > account:             0x3D38C8894a7213A0dF4142958dC0f0DE94147D25
      > balance:             18.68492587
      > gas used:            2724684
      > gas price:           10 gwei
      > value sent:          0 ETH
      > total cost:          0.02724684 ETH
   
      Pausing for 2 confirmations...
      ------------------------------
      > confirmation number: 1 (block: 4466919)
      > confirmation number: 2 (block: 4466920)
   
      > Saving migration to chain.
      > Saving artifacts
      -------------------------------------
      > Total cost:          0.02724684 ETH
   
   
   Summary
   =======
   > Total deployments:   2
   > Final cost:          0.03009592 ETH
```

Enjoy!