# 🍪 CookieJar

CookieJar is a decentralized application that allows whitelisted members to withdraw a set amount of ETH periodically from a communal "jar" on the Optimism network.

![CookieJar Banner](https://i.imgur.com/D9HuS9J.png)

## 🌟 Project Overview

CookieJar consists of two main components:

1. **Smart Contract**: A Solidity contract deployed on the Optimism network that manages the whitelist, admin privileges, and withdrawal functionality.
2. **Frontend Application**: A React-based web interface that allows users to connect their wallets and interact with the smart contract.

## 🚀 Getting Started

The project is divided into two main directories:

- `/contract` - Contains the Solidity smart contract code and deployment instructions
- `/frontend` - Contains the React frontend application

Each directory has its own README with detailed instructions:

- [Contract README](/contract/README.md) - Instructions for deploying and interacting with the smart contract
- [Frontend README](/frontend/README.md) - Instructions for setting up and deploying the frontend application

## 🔑 Environment Variables

To run this project, you will need to obtain and configure the following environment variables:

1. `VITE_INFURA_KEY` - An API key from Infura for connecting to Ethereum networks
2. `VITE_CONTRACT_ADDRESS` - The address of your deployed CookieJar contract
3. `VITE_WALLET_CONNECT_PROJECT_ID` - A project ID from WalletConnect for wallet integration

The Frontend README provides detailed instructions on how to obtain these values.

## 🛠️ Quick Start

### Setup Contract

1. Deploy the smart contract to Optimism following the instructions in the [Contract README](/contract/README.md)
2. Note the deployed contract address for frontend configuration

### Setup Frontend

1. Install dependencies: `npm install`
2. Create a `.env` file with your environment variables
3. Start the development server: `npm run dev`

## 📱 Features

- **Contract Features**:

  - Whitelist management for authorized withdrawals
  - Admin controls for emergency situations
  - Periodic withdrawal limits (30 days between withdrawals)
  - Customizable withdrawal amount

- **Frontend Features**:
  - Wallet connection via multiple providers
  - User-friendly interface for withdrawals
  - Real-time status updates
  - Responsive design for mobile and desktop

## 🌐 Live Demo

A demo version of this application is available at: [https://cookiejar.example.com](https://cookiejar.example.com)

Contract deployed on Optimism: [0xE9D12E97bd19376c93c73198c2f64eAbE246912b](https://optimistic.etherscan.io/address/0xE9D12E97bd19376c93c73198c2f64eAbE246912b)

## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
#   c o o k i e - j a r - i n s t r u c t i o n s  
 