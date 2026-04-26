# AgroPharm Shield - Blockchain Service

## Overview
Blockchain layer for **AgroPharm Shield** — secure traceability of medicinal plants (Agriculture domain).

It records farming data + AI quality assessment on an immutable ledger, ensuring raw materials are safe for pharmaceutical use.

## Core Contract: PlantBatch.sol
- Registers medicinal plants (Rosemary, Artemisia, etc.)
- Stores: soil quality, pesticide levels, environmental data, **AI Quality Score**
- Automatic approval based on AI score (≥ 70 = approved for pharma)

## How to Run (Demo for Jury)

1. Start local blockchain:
   ```bash
   npx hardhat node