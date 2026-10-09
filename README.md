# AgentPay Core 🤖💳

AgentPay is a lightweight, open-source micro-transaction and escrow middleware built specifically for the emerging agentic economy. It provides the financial plumbing, boundary firewalls, and cryptographic identity tracking necessary for autonomous AI agents to safely buy, sell, and negotiate with other agents globally.

## 🚀 Core Architecture

* **Sub-Cent Escrow Settlement:** A secure internal middleware ledger built to handle instant machine-to-machine micro-payments down to a fraction of a cent.
* **Session-Based Budget Firewalls:** Programmable spending boundaries that actively prevent autonomous bots from falling into infinite API billing loops or suffering prompt-injection exploits.
* **Know Your Agent (KYA):** Cryptographic public/private key identity tracking that ensures absolute machine-to-machine trust protocols before data settlement.
* **Automated Data Attestation:** Integrated validation gateways that verify data payloads are uncorrupted before releasing escrowed token balances to vendor bots.

## 🛠️ Standalone Local Simulation (The Testing Harness)

This repository includes a fully functional, zero-dependency testing environment. Developers can spin up a localized loop featuring three autonomous mock agents (`Agent_Buyer`, `Agent_Vendor_Alpha`, and `Agent_Vendor_Beta`) to observe them dynamically register, verify signatures, request data payloads, and trade fractional token credits in real-time.

*Step-by-step terminal execution scripts, cloud sandbox deployment guides, and configuration modules will be pushed to main this week.*

---

## ⚖️ Legal, Licensing, & Production Use
This framework is published under a strict **Business Source License (BSL 1.1)**. 

### 🔴 Permitted Use:
* You are 100% legally permitted to copy, modify, test, and run this code locally for educational, simulation, and non-commercial development purposes for free.

### 🚫 Commercial & Production Restrictions:
* Utilizing this code protocol, its cryptographic framework, or its structural middleware logic to process real-world production transaction volume or live digital currency settlement is strictly prohibited without a verified, commercial `AGENTPAY_API_KEY` issued by the Licensor. 

*This license automatically transitions to a standard open-source Apache 2.0 license exactly 36 months from the initial publication date.*
