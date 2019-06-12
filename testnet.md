
```
$ truffle migrate --network testnet

Compiling your contracts...
===========================
> Compiling ./contracts/Migrations.sol
> Compiling ./contracts/MyERC721.sol
> Compiling ./node_modules/zeppelin-solidity/contracts/AddressUtils.sol
> Compiling ./node_modules/zeppelin-solidity/contracts/introspection/ERC165.sol
> Compiling ./node_modules/zeppelin-solidity/contracts/introspection/SupportsInterfaceWithLookup.sol
> Compiling ./node_modules/zeppelin-solidity/contracts/math/SafeMath.sol
> Compiling ./node_modules/zeppelin-solidity/contracts/token/ERC721/ERC721.sol
> Compiling ./node_modules/zeppelin-solidity/contracts/token/ERC721/ERC721Basic.sol
> Compiling ./node_modules/zeppelin-solidity/contracts/token/ERC721/ERC721BasicToken.sol
> Compiling ./node_modules/zeppelin-solidity/contracts/token/ERC721/ERC721Receiver.sol
> Compiling ./node_modules/zeppelin-solidity/contracts/token/ERC721/ERC721Token.sol
Unable to find image 'ethereum/solc:0.4.25' locally
0.4.25: Pulling from ethereum/solc
ff3a5c916c92: Already exists
1be672671677: Already exists
9ba3fef0961a: Pulling fs layer
99bbca9791cf: Pulling fs layer
134fea4d2f66: Pulling fs layer
134fea4d2f66: Verifying Checksum
134fea4d2f66: Download complete
99bbca9791cf: Verifying Checksum
99bbca9791cf: Download complete
9ba3fef0961a: Download complete
9ba3fef0961a: Pull complete
99bbca9791cf: Pull complete
134fea4d2f66: Pull complete
Digest: sha256:6758ae249443854fa794c5ab402af821072eba67cc219edd44d214191985cfbb
Status: Downloaded newer image for ethereum/solc:0.4.25
> Artifacts written to /opt/smilo/erc721/build/contracts
> Compiled successfully using:
   - solc: 0.4.25+commit.59dbf8f1.Linux.g++


Starting migrations...
======================
> Network name:    'testnet'
> Network id:      10
> Block gas limit: 210000000


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x1203269f4014f3c7f328e40801bdaf74420f4f7c627e452668d15eadeb9e0832
   > Blocks: 0            Seconds: 0
   > contract address:    0x88682647109F3571910CCA7E026B5b6474f463c2
   > account:             0x8D6a2ea777580253c90aF3d562b6090fad91c068
   > balance:             0.99933326943
   > gas used:            161323
   > gas price:           0.01 gwei
   > value sent:          0 ETH
   > total cost:          0.00000161323 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:       0.00000161323 ETH


2_erc721_migration.js
=====================

   Deploying 'MyERC721'
   --------------------
   > transaction hash:    0xc0e30c27f73431083c3309cfbfc22d625646492cb896d96c7ba650bbeb9b922f
   > Blocks: 0            Seconds: 0
   > contract address:    0xE4c1A5C3CF5bAB951DED3aaebF79241D67d6e91A
   > account:             0x8D6a2ea777580253c90aF3d562b6090fad91c068
   > balance:             0.99925242338
   > gas used:            1298131
   > gas price:           0.01 gwei
   > value sent:          0 ETH
   > total cost:          0.00001298131 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:       0.00001298131 ETH


Summary
=======
> Total deployments:   2
> Final cost:          0.00001459454 ETH
```
