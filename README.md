# Byte42 Token (BYT) — ERC20 on Ethereum Testnet

## 🧩 Project Overview

This is a simple ERC20 token called **Byte42 (BYT)** created as part of the 42 Web3 curriculum project. It demonstrates how to create, deploy, and interact with an Ethereum-based token using **Remix IDE** and **OpenZeppelin** libraries.


** Web3

Web3 is a decentralized version of the internet where users own their data and interact with apps (dApps) through wallets, without relying on central servers. Unlike Web2, where companies like Google control user data for profit (mainly through ads), Web3 uses blockchains (for logic), decentralized storage systems (like IPFS), and cryptographic tools to keep personal data secure and user-controlled. While blockchain data is public, sensitive information is encrypted and stored off-chain. dApps run on decentralized networks of nodes operated by individuals and communities rather than centralized servers, making the system more open, resilient, and governed by its users.

** What is smart contract
* A smart contract is just the name for the code (like your token code) that runs on a blockchain.
* It's called a “contract” because it defines rules, and “smart” because it runs automatically.
* When you used Remix to deploy your token, you created and launched a smart contract.


## 📜 Token Information

- **Name**: Byte42
- **Symbol**: BYT
- **Standard**: ERC20
- **Decimals**: 18
- **Initial Supply**: 1,000 BYT (sent to deployer-provided address)

## 🔨 Stack Used

- **Solidity**: ^0.8.22
- **Remix IDE**
- **OpenZeppelin Contracts v5**
- **Ethereum Testnet (e.g., Sepolia or Goerli)**
- **Metamask + Faucet ETH**

## 🛰 Deployment Summary

- **Network**: Ethereum Testnet (e.g., Sepolia)
- **Contract Address**: `0xYourContractAddressHere`
- **Block Explorer**: [Etherscan Testnet Link](https://sepolia.etherscan.io)

## 🧪 Quick Deployment via Remix

1. Open [Remix IDE](https://remix.ethereum.org)
2. Paste the `Byte42.sol` file inside the `contracts/` folder
3. Compile using Solidity ^0.8.22
4. Select "Injected Provider - Metamask"
5. Deploy by passing your wallet address to the constructor
6. Confirm transaction in Metamask

## 📝 Notes

- This contract uses OpenZeppelin's secure ERC20 base.
- You do **not** need real ETH — use Sepolia faucet to get testnet ETH.

