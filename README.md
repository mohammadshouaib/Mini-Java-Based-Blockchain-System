# Mini-Java-Based-Blockchain-System
Java Blockchain with transaction fees, coinbase rewards, and dynamic difficulty. Implements UTXO-based transactions, wallet signing, block mining with Merkle roots, and automatic difficulty adjustment, providing a practical simulation of a functional cryptocurrency system.


# Java Blockchain System

This project implements a basic blockchain system in Java, extended to support **transaction fees**, **coinbase transactions**, and **dynamic difficulty adjustment**. It is based on a university course project for CSC438 Blockchain Systems.

## Features

- **Transaction System**
  - Users can create cryptocurrency transactions using UTXOs.
  - Transaction fees are supported, allowing miners to collect fees.

- **Mining**
  - Blocks contain multiple transactions.
  - Coinbase transactions reward miners for successfully mining a block.
  - Difficulty adjusts automatically based on the average time to mine the last `n` blocks.

- **Wallet**
  - Generates public/private key pairs.
  - Signs transactions for secure transfers.

- **Blockchain Integrity**
  - Validates transactions and blocks before addition.
  - Computes Merkle root for transactions within a block.

## Implementation Details

- Java classes: `Transaction`, `Block`, `Wallet`, `TransactionInput`, `TransactionOutput`.
- Mining includes proof-of-work and difficulty adjustment.
- Transactions consume previous UTXOs and generate new ones.
- Sample wallets demonstrate the creation and transfer of cryptocurrency.

## TO DO LIST
-Have to work on UI
-Documentation

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd blockchain-java
