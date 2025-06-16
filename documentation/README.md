
---

## ✅ `documentation/README.md`

```markdown
# 📘 Token Documentation - Byte42 (BYT)

This folder contains the functional and technical documentation for the **Byte42** ERC20 token.

---

## 🔹 Token Overview

| Property       | Value          |
|----------------|----------------|
| Name           | Byte42         |
| Symbol         | BYT            |
| Standard       | ERC20          |
| Decimals       | 18             |
| Initial Supply | 1,000 BYT      |

---

## 🔹 Contract Details

- The token is based on OpenZeppelin's audited ERC20 implementation.
- A fixed supply of **1,000 BYT** is minted once at deployment.
- Tokens are sent to the **`recipient` address** provided as a constructor parameter.

---

## 🔹 Contract Functions

| Function             | Description                                       |
|----------------------|---------------------------------------------------|
| `totalSupply()`      | Returns the total supply of BYT                  |
| `balanceOf(address)` | Returns balance of given address                 |
| `transfer(to, amount)` | Transfers tokens to a recipient               |
| `approve(spender, amount)` | Approves a spender                     |
| `transferFrom(from, to, amount)` | Transfers from one address to another using allowance |
| `allowance(owner, spender)` | Returns approved spending amount       |

---

## 🔐 Security Considerations

- Relies entirely on OpenZeppelin’s secure ERC20 logic.
- No custom functions or privileges.
- No further minting after deployment — supply is fixed.
- The deployer address has no special admin rights.

---

## 🌍 Deployment Summary

- **Network**: Ethereum Sepolia Testnet
- **Contract Address**: `0xYourContractAddressHere`
- **Etherscan Link**: https://sepolia.etherscan.io/address/0xYourContractAddressHere
