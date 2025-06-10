# Blockchain Platform Comparison

## Problem Statement

**Create a comparison table or markdown sheet** with the following columns for each platform:

- **Blockchain Name**
- **Type (Public/Private/Consortium)**
- **Consensus Mechanism Used**
- **Permission Model (Open/Permissioned)**
- **Speed / Throughput (TPS if available)**
- **Smart Contract Support (Y/N + Language)**
- **Token Support (Native or not)**
- **Typical Use Case**
- **Notable Technical Feature (e.g., privacy, pluggable consensus)**

## Overview

This comparison analyzes three distinct blockchain platforms representing different deployment models: public, private, and consortium blockchains.

## Comparison Table

| **Blockchain Name**    | **Type**   | **Consensus Mechanism Used** | **Permission Model** | **Speed/Throughput (TPS)** | **Smart Contract Support** | **Token Support**                              | **Typical Use Case**                                                | **Notable Technical Feature**                                           |
| ---------------------- | ---------- | ---------------------------- | -------------------- | -------------------------- | -------------------------- | ---------------------------------------------- | ------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| **Ethereum**           | Public     | Proof of Stake (PoS)         | Open                 | 15-20 TPS (Layer 1)        | Yes - Solidity, Vyper      | Native (ETH) + ERC tokens                      | DeFi, NFTs, dApps, Web3 applications                                | EVM (Ethereum Virtual Machine) enables diverse smart contract ecosystem |
| **Hyperledger Fabric** | Private    | Pluggable (PBFT, Raft, Solo) | Permissioned         | 3,000-20,000 TPS           | Yes - Go, JavaScript, Java | No native token (can create custom assets)     | Enterprise supply chain, healthcare records, identity management    | Modular architecture with pluggable consensus and privacy channels      |
| **R3 Corda**           | Consortium | Notary-based consensus       | Permissioned         | 170-1,700 TPS              | Yes - Kotlin, Java         | No native token (represents real-world assets) | Financial services, trade finance, insurance, regulatory compliance | Point-to-point transactions with legal identity integration             |
