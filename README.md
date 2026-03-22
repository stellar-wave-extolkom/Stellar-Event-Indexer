Project Description
The Stellar-Event-Indexer is a developer tool designed to solve the problem of querying historical smart contract data. It watches specific Soroban contracts, parses event logs into human-readable formats, and exposes them via a simple API, making it easy to build dashboards and activity feeds.

Technical Architecture
Engine: Node.js environment utilizing the stellar-sdk for RPC polling.

Persistence: Prisma ORM for flexible database management.

API: A lightweight Express.js layer to serve indexed data to frontends.

🌊 Drips Wave Program
This repository is an active participant in the Drips Wave Program.

How to get involved:

Register: Set up your profile on the Drips app.

Claim an Issue:

Trivial: Adding new event types to the parser.

Medium: Improving database indexing performance.

High: Implementing Webhook support for real-time notifications.

Submit & Earn: Get paid in XLM/Drips for your open-source contributions.

Project Structure
Plaintext
├── src/
│   ├── services/    # Event listeners and log parsers
│   ├── db/          # Schema definitions and migrations
│   └── api/         # REST endpoints for data retrieval
├── scripts/         # Local environment setup
└── tests/           # Integration tests for data accuracy
