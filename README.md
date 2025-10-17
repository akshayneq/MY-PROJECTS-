# Rental Verification System - One-Click Semi-Online (Modern UI)

This project is a semi-online demo that deploys contracts to the **Sepolia testnet** using your Alchemy/Infura API key and a test wallet private key. It includes a modern Tailwind UI and a local backend that interacts with the deployed contract.

## Requirements

- Node.js v18+ and npm
- MetaMask (with Sepolia test ETH)
- Alchemy (or Infura) API key for Sepolia
- A Sepolia test wallet private key (only use a test account)

## Quick steps

1. Extract the ZIP to a folder (e.g., `C:\Users\you\Documents\rental-verification-modern`).
2. Double-click `setup.bat` and follow prompts. This will create a `.env` file with your keys and install dependencies.
3. Double-click `start-all.bat` to deploy the contract to Sepolia and run backend + frontend.
4. Open http://localhost:5173 in your browser.

**Notes:** The scripts will prompt for your Alchemy/Infura API key and a test wallet private key. Do not use a mainnet account with funds you care about.
