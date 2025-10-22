# LibreFi Smart Contracts - Built on Base

> **Part of the LibreFi ecosystem** - [← Back to Main README](../README.MD)

This repository contains the smart contracts for LibreFi, a permissionless margin trading platform deployed on **Base**. The contracts are built using Foundry for optimal development experience and gas efficiency.

## 🚀 Quick Links
- **Live Contracts**: [Base Sepolia Deployment](../README.MD#-base-sepolia-deployment)
- **Main Documentation**: [LibreFi README](../README.MD)
- **How It Works**: [Protocol Overview](./HowItWorks.md)

## What is Foundry?
**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## 🛠️ Development Setup

### Prerequisites
- [Foundry](https://book.getfoundry.sh/getting-started/installation)
- Node.js (for dependencies)
- Base Sepolia RPC access

### Installation
```bash
# Install dependencies
forge install

# Build contracts
forge build

# Run tests
forge test
```

### Base Sepolia Deployment
```bash
# Deploy to Base Sepolia
make deploy-verify

# Or manually
forge script script/Deploy.s.sol --broadcast --rpc-url $RPC_URL --private-key $PRIVATE_KEY --via-ir
```

### Available Commands

| Command | Description |
|---------|-------------|
| `forge build` | Compile contracts with Via-IR optimization |
| `forge test` | Run test suite |
| `forge fmt` | Format Solidity code |
| `forge snapshot` | Generate gas usage snapshots |
| `make deploy-verify` | Deploy and verify on Base Sepolia |
| `anvil` | Start local development node |

## 📚 Smart Contract Documentation

### Core Protocol
- **[How It Works](./HowItWorks.md)** - Complete protocol overview and mechanics
- **[Architecture Diagram](./HowItWorks.md#architecture)** - Visual system design

### Contract Details
- **[LendingPool Factory](./LendingPoolFactory.md)** - Pool creation and management
- **[LendingPool](./LendingPool.md)** - Individual lending pool implementation  
- **[PositionFactory](./PositionFactory.md)** - Position creation and tracking
- **[Position](./Position.md)** - Individual trading position logic

### Deployment & Configuration
- **[Deployment Scripts](./script/)** - Automated deployment on Base Sepolia
- **[Configuration](./config.json)** - Network and contract configurations
- **[Environment Setup](./.env.example)** - Required environment variables

## 🔗 Related Documentation
- **[Main LibreFi README](../README.MD)** - Project overview and features
- **[Base Network Docs](https://docs.base.org/)** - Base blockchain documentation
- **[Foundry Book](https://book.getfoundry.sh/)** - Development framework guide 