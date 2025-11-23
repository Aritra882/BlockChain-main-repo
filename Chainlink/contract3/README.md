⏱️ Time-Based Automated Smart Contract – Deployment & Automation Details

This repository contains a Time-Based Automated Smart Contract deployed on the Ethereum Sepolia Testnet, integrated with Chainlink Automation for fully autonomous execution.

The smart contract is designed to run functions automatically based on a time schedule using Chainlink’s Decentralized Automation Network.

📸 Deployment & Automation Screenshots
1️⃣ Contract Deployment Transaction (Etherscan)
![Deployment Screenshot](./d08533d5-0c04-475b-828c-5a14a581fb0c.png)

2️⃣ Chainlink Automation Registration Dashboard
![Chainlink Automation Screenshot](./d1096bf9-4979-4ed4-b695-467463b7bfc4.png)

🔗 Important Links & Transaction Details
🧾 Contract Creation Transaction

Hash:
0x3234578721c90cc152467eaff16572cb9a7f4d28723f64b6e700c087f3f4622e

Etherscan Link:
https://sepolia.etherscan.io/tx/0x3234578721c90cc152467eaff16572cb9a7f4d28723f64b6e700c087f3f4622e

⚡ Chainlink Automation Upkeep

Upkeep Dashboard:
https://automation.chain.link/sepolia/58940883390771574198771126679452779206023451837648542190189626912417482379233

This page shows:

Upkeep ID

Trigger type (Time-based)

Cron expression: */5 * * * * (runs every 5 minutes)

LINK balance

Forwarder address

Next projected execution times

🧭 Smart Contract Overview

This smart contract is built to demonstrate Chainlink Time-Based Automation.
It allows a function to run automatically on fixed time intervals without manual interaction.

Key Features

🔹 Automated Execution
Uses Chainlink Automation with CRON scheduling to call a function every 5 minutes.

🔹 Reliable & Decentralized
Execution is handled by a decentralized network of Chainlink Automation Nodes.

🔹 Gas-Optimized Design
Functions and upkeep checks are lightweight to reduce gas consumption.

🔹 Event Logging
Each automated execution emits events for on-chain tracking.

🔹 Beginner-Friendly Structure
Perfect for learning Automation workflows, CRON expressions, and upkeep design.

🛠 How It Works

1)The contract implements Chainlink Automation interfaces.

2)Chainlink nodes periodically call checkUpkeep() to determine if execution is needed.

3)After the configured time interval passes, nodes call performUpkeep().

4)The contract executes your logic (e.g., increment counter, send value, trigger event).

5)The Chainlink dashboard logs each execution.

✍️ Author

Aritra Hazra
Blockchain Developer | Smart Contract Engineer
