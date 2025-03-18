# CoffeeChain: Blockchain Logistics Platform

CoffeeChain is a blockchain-based supply chain management platform designed to enhance transparency and traceability within the coffee logistics process. It simulates a decentralized ledger system using Django and smart contract principles to track the journey of coffee from producer to consumer.

## Features

- **Blockchain Simulation**: Mimics blockchain operations to log immutable records of coffee supply chain events.
- **Supply Chain Actors**: Supports multiple actors like Producer, Processor, Distributor, and Retailer.
- **Event Tracking**: Track supply chain transactions such as shipping, receiving, and processing.
- **Smart Contract Logic**: Automates validation of transactions within the simulated blockchain network.
- **User Interface**: Django-powered web app to interact with the blockchain and manage supply chain records.
- **Testing Suite**: Selenium-based tests for UI and functionality verification.
- **Containerization**: Docker support for easy deployment and environment consistency.

## Tech Stack

- Python
- Django
- Docker
- SQLite
- Selenium (for automated testing)


## 🧩 Project Structure
```
/CoffeeChain/
├── blockchain/           # Blockchain logic and smart contract simulation
├── supplychain/          # Django app for supply chain workflows
├── tests/                # Selenium-based automated tests
├── Dockerfile            # Docker configuration
├── docker-compose.yml    # Docker Compose setup
├── manage.py
└── README.md
```

## How It Works

1. **Transaction Simulation**: Each event (e.g., a shipment) is recorded as a block on the blockchain.
2. **Role-Based Actions**: Users take on roles (Producer, Processor, etc.) and perform transactions within their permissions.
3. **Immutable Ledger**: The blockchain log ensures a tamper-proof history of events across the coffee supply chain.

## Setup Instructions

1. Clone the repository:
   ```
   git clone https://github.com/Jrap-bit/CoffeeChain.git
   cd CoffeeChain
   ```
2. Build and run using Docker Compose:
   ```
   docker-compose up --build
   ```
3. Access the app at:
   ```
   http://localhost:8000
   ```
