# NFT Staking App

## Introduction

This example demonstrates a use of several thirdweb tools to create an NFT Staking application. In this example, users can stake their ERC721 NFTs and earn ERC20 tokens as a reward. It combines:

- [NFT Drop contract](https://thirdweb.com/thirdweb.eth/DropERC721): To create a collection of NFTs that users can stake -> 0x8F618c9Eb7805FcC81D734934abD529dd464955C
- [Token contract](https://thirdweb.com/thirdweb.eth/TokenERC20): To create a token that users can earn as a reward for staking -> 0xbd31bd1D2c25BAb5ad9134C6E3840DF9cE9DbE23
- [NFT Staking contract](https://thirdweb.com/thirdweb.eth/NFTStake): To create a contract that users can stake their NFTs in, and earn tokens as a reward -> 0xbA2A2c2EF9a797fD618F0BE9bD7ba6882F727C93

## Using This Template

Create a project using this example:

```bash
npx thirdweb create --template nft-staking-app
```

- Create an [NFT Drop](https://thirdweb.com/thirdweb.eth/DropERC721) contract using the dashboard.
- Create a [Token](https://thirdweb.com/thirdweb.eth/TokenERC20) contract using the dashboard.
- Create an [NFT Staking](https://thirdweb.com/thirdweb.eth/NFTStake) contract using the dashboard.
- Approve the NFT Staking contract to transfer your tokens.
- Deposit the tokens into the NFT Staking contract.
- Update the information in the [contractAddresses.ts](./consts/contractAddresses.ts) file to

## Join our Discord!

For any questions, suggestions, join our discord at [https://discord.gg/thirdweb](https://discord.gg/thirdweb).
