# Arca-WDK: Secure Agentic Treasury

This project implements the Financial Audit Stream for "El Arca de Alan" using the **Tether Wallet Development Kit (WDK)**.

## Tether WDK
The integration leverages the Tether WDK for real-time tracking of USDC/USDT deposits on Polygon. This allows the agent to monitor its treasury in a non-custodial manner.

## ERC-4337 Policies
To ensure maximum security, the agent follows strict on-chain and off-chain policies. The treasury is strictly read-only, and unauthorized signature attempts are blocked at the SDK level.

## Core Features
- **Automated Invoicing**: Generates PDF/JSON proofs of received funds.
- - **Audit Logs**: Transparent trail of all treasury interactions.
  - 
