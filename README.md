# Arca-WDK: Secure Agentic Treasury

This project implements the **Financial Audit Stream** for "El Arca de Alan" using the **Tether Wallet Development Kit (WDK)**.

## Overview
This agent is part of a multi-stream ecosystem (PDT Architecture) designed to provide autonomous but audited financial agency.

### Core Features
- **Inflow Monitoring:** Uses Tether WDK to watch for USDT/USDC deposits.
- **Automated Invoicing:** Generates structured Markdown receipts for every transaction.
- **Security Guardrail:** Strictly **Read-Only**. The agent code contains no private keys and is physically incapable of initiating outflows.

## Built for Tether Hackathon Galactica
This repository demonstrates how to integrate Tether's WDK with an "Agentic Firewall" philosophy.

## How to Run
```bash
npm install
npx ts-node index.ts
```

## License
Apache 2.0
