# Web3 and Blockchain Basics

**Name:** CH D S S S BABA 

**Roll Number:** 23A91A05E9

**Submission Date:** December 17, 2025 

## Project Overview

This project documents a hands-on exploration of Web3 fundamentals, including cryptocurrency wallet setup, testnet interaction, and decentralized application (DApp) usage. The primary goal was to gain practical understanding of blockchain concepts such as Distributed Ledger Technology (DLT), consensus mechanisms, and smart contracts.

## Technical Stack & Configuration

* **Wallet Provider:** MetaMask.

* **Network:** Sepolia Testnet.

* **Block Explorer:** Etherscan (Sepolia).

* **Testnet Faucet:** Sepolia PoW Faucet.

## Activities & Workflow

### 1. Wallet Setup & Network Configuration

* Configured MetaMask for the Sepolia test network.

* Documented the initial interface and wallet status.

### 2. Testnet Faucet Interaction

* Attempted to use standard faucets (Alchemy, Chainlink) but faced restrictions requiring mainnet balances.

* Successfully utilized the **Sepolia PoW Faucet**, performing browser-based mining to acquire SepoliaETH.

* **Mining Reward:** 0.051 SepETH.

### 3. Transaction Execution

Due to connectivity issues with external DApps, a self-transfer was performed to verify blockchain interaction.

* **Transaction Type:** Self-Transfer (0.001 ETH).

* **Status:** Success (Confirmed in 2 minutes).

* **Gas Fee:** 0.0000315 ETH.

### 4. Transaction Details

* **Wallet Address:** `0x3Dd27789ca4897a4A29C5447b2e3fb2140a3eD14`.

* **Transaction Hash:** `0xf577314aecffc29ed4b068f9ae256f28ef019473681dbd29d8a7c3a60f804c9e`.

* **Etherscan Link:** [View Transaction](https://www.google.com/search?q=https://sepolia.etherscan.io/tx/0xf577314aecffc29ed4b068f9ae256f28ef019473681dbd29d8a7c3a60f804c9e).

## Challenges & Troubleshooting

### Faucet Restrictions

* **Issue:** Initial faucets required existing mainnet holdings.

* **Solution:** Used a Proof-of-Work (PoW) faucet to mine the necessary testnet funds.

### DApp Connectivity Issues

* **Issue:** Uniswap and SushiSwap failed to recognize the wallet's SepoliaETH balance, consistently showing "Not enough ETH" despite the wallet holding 0.120 SepoliaETH.

* **Troubleshooting Attempts:**
* Refreshed DApp pages and cleared site data/cache.

* Disconnected and reconnected the MetaMask wallet.

* Attempted to manually select "Sepolia" within the DApp interfaces.

* **Resolution:** Performed a direct self-transfer via MetaMask to fulfill the on-chain interaction requirement.

## Key Learnings & Reflections

### Core Concepts

* **DLT & Immutability:** Experienced how transactions are immutably recorded across a decentralized network, contrasting with centralized databases.

* **Consensus Mechanisms:** Observed how Proof-of-Stake (PoS) validates transactions without intermediaries.

* **Smart Contracts:** Understood that even basic "send" functions leverage underlying smart contract logic to execute trustless transfers.

### Security

* **Self-Custody:** Recognized the responsibility of managing assets and data without a central authority.

* **Seed Phrase Safety:** Highlighted the critical importance of protecting the seed phrase to prevent total fund loss.

* **Transaction Signing:** Learned the importance of verifying DApp URLs and transaction details before cryptographically signing actions.
