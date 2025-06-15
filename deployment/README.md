# 📦 Deployment Instructions - Byte42 (BYT)

This folder contains instructions on how to deploy the **Byte42 (BYT)** token on the Ethereum testnet using **Remix IDE** and **OpenZeppelin Contracts**.

---

## 🔧 Requirements

- Metamask installed and connected to a testnet (e.g., Sepolia)
- Some testnet ETH (via [Sepolia Faucet](https://sepoliafaucet.com/))
- Remix IDE: https://remix.ethereum.org
- Solidity version: ^0.8.22
- OpenZeppelin Contracts (via GitHub import)

---

## 📝 Deployment Steps

1. Go to [Remix IDE](https://remix.ethereum.org).
2. Create a new file named `Byte42.sol` inside the `contracts/` folder.
3. Paste the following contract code:

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.22;

import {ERC20} from "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract Byte42 is ERC20 {
    constructor(address recipient) ERC20("byte42", "BYT") {
        _mint(recipient, 1000 * 10 ** decimals());
    }
}
