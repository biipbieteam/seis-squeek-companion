# SEIS Squeek Companion

A non-custodial SqueekChain companion application for the SEIS TERMINAL ecosystem.

## Project Objective

Build a functional, responsive Web3 application that helps SqueekChain users connect their wallets, explore verified on-chain assets, and organize their personal Squeek NFT collections.

This project is developed independently from the existing SEIS TERMINAL production application.

## Technology

- React + Vite
- JavaScript
- ethers v6
- Responsive CSS
- EIP-1193 wallet integration

## Required Features

### 1. Wallet Connection
- Connect an EIP-1193-compatible wallet.
- Display the connected wallet address.
- Detect account and network changes.
- Support SqueekChain network switching with explicit user approval.
- Handle disconnected and unsupported-network states.

### 2. SqueekChain Integration
- Research and use verified SqueekChain network configuration.
- Read native wallet balances through a verified RPC.
- Display transaction explorer links where supported.
- Never invent RPC URLs, contract addresses, or blockchain data.

### 3. Squeek NFT Workspace
- Display verified NFT ownership data when an appropriate data source is available.
- Allow users to create and manage personal NFT watchlists.
- Support searching, filtering, and organizing saved collections.
- Allow users to export or share watchlists.
- Clearly distinguish on-chain data from user-created watchlist entries.

### 4. User Interface
- Dark Web3 terminal design.
- Responsive desktop and mobile layouts.
- Dashboard, Wallet, Collections, and Settings sections.
- Clear loading, error, and empty states.

## Security Requirements

- Never request or store seed phrases or private keys.
- Do not include API secrets in client-side code.
- Do not deploy smart contracts or initiate transactions without explicit approval.
- Validate external data.
- Never modify the existing SEIS TERMINAL production application.

## Deliverables

- Complete React/Vite application.
- Working wallet connection and network detection.
- Functional interactive NFT watchlist.
- Verified blockchain integrations where available.
- Build instructions and documentation.
- Production-ready static build suitable for IPFS hosting.

## Acceptance Criteria

The application must compile successfully and provide usable interactive functionality. Any unsupported SqueekChain integration must be clearly documented instead of simulated or presented as working.

## Future Integration

This module may later be integrated into SEIS TERMINAL, but no changes to the production repository or website are authorized in this Job.
