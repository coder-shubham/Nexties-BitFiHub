# Nexties-BitFiHub

## Project Description
BitFiHub is a decentralized finance (DeFi) application that leverages Bitcoin and Zetachain to offer comprehensive financial services, including lending, borrowing, staking, yield farming, and decentralized exchange (DEX) functionalities.

## File Structure
- **backend/**: Node.js Express server to handle blockchain interactions.
- **frontend/**: React.js application for the user interface.
- **contracts/**: Smart contracts written in Solidity.
- **truffle-config.js**: Truffle configuration for compiling and deploying smart contracts.

## Setup Instructions

### Prerequisites
- Node.js
- npm
- Truffle
- Ganache

### Install Truffle and Ganache
```bash
npm install -g truffle
npm install -g ganache-cli
```

### Compile and Deploy Smart Contracts
```bash
truffle compile
truffle migrate --network development
```

### Set up Backend
```bash
cd backend
npm install
node server.js
```

### Set up Frontend
```bash
cd frontend
npm install
npm start
```

### Run Local Blockchain
```bash
ganache-cli
```

