# LibreFi: Permissionless Margin Trading on Base

LibreFi is a cutting-edge noncustodial leveraged trading platform built on **Base**, Coinbase's Layer 2 scaling solution. Leveraging Base's low fees, fast transactions, and Ethereum security, LibreFi introduces an efficient and flexible trustless mechanism that revolutionizes margin trading. The protocol enables permissionless risk management, unrestricted market creation, and oracle-agnostic pricing. Users benefit from enhanced leverage options, optimized interest rates, and dramatically reduced gas fees thanks to Base's infrastructure. Built as a simple, immutable, and governance-minimized base layer, it serves as a robust foundation for the next generation of DeFi applications on Base.

### 🚀 Key Features

- **Permissionless listing of any coins (including meme coins)**: List and trade without approvals on Base's fast, low-cost network
- **Permissionless pool creation**: Create lending pools with your own parameters anytime, leveraging Base's efficient infrastructure
- **Margin trading with leverage**: Open and manage leveraged long/short positions with minimal gas costs
- **Base-optimized architecture**: Built specifically for Base's EVM compatibility and performance characteristics
- **Oracle-agnostic pricing**: Flexible price feed integration supporting multiple oracle providers
- **Reduced gas fees**: Leverage Base's Layer 2 scaling for cost-effective trading operations

## 🌐 Live Demo

Experience LibreFi in action with our [frontend demo]() deployed on Base Sepolia testnet.

## 📊 Base Sepolia Deployment

**Contract Addresses on Base Sepolia:**
- **MockUniswapRouter**: `0x4d6aa2ccee914096689bba75b7bf73899484bcf7`
- **Vault**: `0x30d0ae6ec1a3ff9361bb2f27e69d5092e5b109f2`
- **MockFactory**: `0x687d9a0df2f0d2aed2b575438b13ec33bd45fce4`
- **LendingPoolFactory**: `0x95dfafa355a6ef8583738951e4eb5f2282d83068`
- **PositionFactory**: `0xa4bb3796be77185b0028eb0751b9f259f9bba3eb`

**Network**: Base Sepolia Testnet  
**Explorer**: [BaseScan Sepolia](https://sepolia.basescan.org/)

## 🏗️ Architecture

LibreFi consists of multiple repositories, each handling a distinct part of the ecosystem:

### 📁 Repository Structure
- **`/contracts/`** - Smart contracts and deployment scripts (this repository)
- **`/frontend/`** - Web interface and user experience

### 🔧 Smart Contract Documentation
For detailed technical documentation about the smart contracts, see the [contracts README](./contracts/README.md):

- **[How It Works](./contracts/HowItWorks.md)** - Core protocol mechanics
- **[LendingPool Factory](./contracts/LendingPoolFactory.md)** - Pool creation system
- **[LendingPool](./contracts/LendingPool.md)** - Individual lending pools
- **[PositionFactory](./contracts/PositionFactory.md)** - Position management
- **[Position](./contracts/Position.md)** - Individual trading positions

## 💡 Why Base?

**LibreFi chose Base as its foundation for several compelling reasons:**

- **Cost Efficiency**: Base's Layer 2 scaling reduces transaction costs by up to 99% compared to Ethereum mainnet
- **Speed**: Sub-second transaction finality enables responsive trading experiences
- **Security**: Inherits Ethereum's security through optimistic rollup technology
- **Developer Experience**: Full EVM compatibility means seamless integration with existing tools
- **Ecosystem**: Part of Coinbase's ecosystem, providing access to millions of potential users
- **Future-Proof**: Built for scalability and ready for Base's upcoming features

## 🔧 Technical Implementation

- **Smart Contracts**: Deployed on Base Sepolia testnet with full verification
- **Oracle Integration**: Chainlink price feeds for accurate market data
- **Gas Optimization**: Via-IR compilation for reduced contract size and gas costs
- **Security**: Comprehensive testing and audit-ready codebase
- **Modularity**: Clean separation of concerns for easy maintenance and upgrades

## 🎯 Hackathon Impact

This project demonstrates:
- **Innovation**: Novel approach to permissionless margin trading
- **Technical Excellence**: Clean, well-documented, and optimized smart contracts
- **Real-World Application**: Practical solution for DeFi trading needs
- **Base Integration**: Showcases Base's capabilities for complex DeFi protocols
- **Scalability**: Architecture designed for growth and adoption

## 🚀 Quick Start

1. **Connect to Base Sepolia**: Add Base Sepolia testnet to your wallet
2. **Get Test ETH**: Use Base Sepolia faucet for test tokens
3. **Interact with Contracts**: Use the deployed contract addresses above
4. **Explore**: Visit [BaseScan](https://sepolia.basescan.org/) to view verified contracts

## 📖 Documentation Structure

### For Users & Judges
- **This README** - Project overview, features, and deployment info
- **Contract Addresses** - Live deployment details on Base Sepolia
- **Quick Start** - How to interact with the protocol

### For Developers
- **[Contracts README](./contracts/README.md)** - Technical setup and development
- **[How It Works](./contracts/HowItWorks.md)** - Detailed protocol mechanics
- **Individual Contract Docs** - Specific implementation details

### For Hackathon Evaluation
- **Innovation** - Novel permissionless margin trading approach
- **Technical Excellence** - Clean, optimized, and well-documented code
- **Base Integration** - Leverages Base's unique advantages
- **Real-World Impact** - Practical DeFi solution with growth potential

## 📈 Future Roadmap

- **Mainnet Deployment**: Deploy to Base mainnet for production use
- **Advanced Features**: Additional trading tools and risk management options
- **Community Governance**: Decentralized decision-making for protocol upgrades

## Licenses

LibreFi is not yet licensed. The licensing details will be updated once finalized. LibreFi's codebase follows the licensing terms specified in `LICENSE`. Ensure compliance with the relevant license conditions when contributing or integrating with the protocol. However, files within the following directories may also be licensed under GPL-2.0-or-later