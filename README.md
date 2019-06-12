
# A Simple ERC-721 on Smilo network Example

What is it?

![](https://cdn-images-1.medium.com/max/2000/0*jr7S0JF8XiousKKz.png)

ERC-721 tokens are a hot topic today with the advent of [crypto kitties](https://www.cryptokitties.co/) and a host of other digital collectibles spawned by its success. The [ERC-721 standard](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md) has gone through a couple iterations and is more or less in place now, so expect more and more players to enter this space. The basic premise of these [non-fungible tokens](https://en.wikipedia.org/wiki/Non-Fungible_Tokens) is that each token is unique and therefore cannot be exchanged on a 1:1 basis like an ERC20 token may be. There are many use cases where a unique tangible or digital asset may represented by these ERC-721 tokens, such as real estate, art, precious stones, etc. Actually, the digital collectible use case is probably the lowest market value use case of them all.

### **Purpose of this article**

This article will attempt to create an ERC-721 in its simplest useful form using the [OpenZeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity/tree/master/contracts/token/ERC721) implementation of the [ERC-21 standard](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md). I would recommend looking at the standard linked above in order to familiarize yourself with the requirements as they can be sometimes be hidden in the excellent OpenZeppelin implementations. There is also a fantastic article written [here](https://medium.com/blockchannel/walking-through-the-erc721-full-implementation-72ad72735f3c) that describes in-depth the ERC-721 spec.

### Setup the project

1. `yarn`

### The Token

Deploy yourself: `truffle migrate --network testnet`

Testnet: `0xE4c1A5C3CF5bAB951DED3aaebF79241D67d6e91A`

Mainnet:


### Test it out

Run the test from the project root

    truffle test

![](https://cdn-images-1.medium.com/max/3236/1*tZ9h1i5oaWrD8ISiGH5L8w.png)

### Addendum

Pretty much all of the regular ERC20 functions are available in the ERC721 contracts. You can approve a third party to spend your token, burn tokens, etc. The functionality is the same, but the inputs and what happens under the covers is a bit more complex. There are a couple ERC721 methods that are not discussed in this article that are worth independent study as well

* safeTransferFrom

* isApprovedForAll

* setApprovedForAll

### Summary

Let’s recap what we learned in this article. 
First, we setup the project with truffle and imported our dependencies including the world class smart contract library, **OpenZeppelin. 
**Next, we coded our ERC721 token using the OpenZeppelin — *ERC721Token *template. 
We ran through a few checks to make sure our contract was valid and then we setup a mocha test to test our assertions. 
Our solidity code is deceptively simple and I would recommend a deeper dive into the ERC721 standard and the OpenZeppelin implementation.
We accomplished our purpose in this article by creating a simple ERC721 token and you should be in a good place to continue your journey in learning this new token type. 
Even though this token was not ‘fungeable’ — I hope you still had ‘fun’ :)

