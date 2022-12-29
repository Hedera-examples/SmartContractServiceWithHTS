# HederaSCWithTokenService

Public repository which shows how one can integrate Solidity smart contract with Hedera Token service.

All right granted by MIT license.

## Environment setup

Run following commands to setup you development environment

1. npm init
2. npm i @hashgraph/sdk
3. npm i dotenv
4. npm i -g solc

Log in (or register) on [Hedera Portal](https://portal.hedera.com/login) and write your Account ID, public/private key, treasuryID to .env file.

Compile Solidity smart contract with following command:
solcjs --bin YourSoliditySmartContract.sol

For more information about this subject, look at:

- [Official Hedera article](https://hedera.com/blog/how-to-deploy-smart-contracts-on-hedera-part-2-a-contract-with-hedera-token-service-integration)
- [Official Hedera tutorial video](https://www.youtube.com/watch?v=QK7FfeNHMSQ)

# About Hedera

Hedera is a distributed ledger for building and deploying decentralized applications and microservices. You can use Hedera’s network services– Consensus, Tokens, Smart Contracts, and File Service–atop the [hashgraph consensus algorithm](core-concepts/hashgraph-consensus-algorithms/), to build applications with high throughput, fair ordering, and low-latency consensus finality in seconds without relying on centralized infrastructure.

The network is made up of permissioned nodes run by the [Hedera Governing Council](https://hedera.com/council), a group of term-limited enterprises that lead the network's direction. Over time the network will [move to a permissionless model](https://www.youtube.com/watch?v=QTNNYeSks-s).

Ready to submit your first transaction to a Hedera network? Visit our [Getting Started ](getting-started/introduction.md)section to learn the basics of how to create an account and transfer HBAR :boom: .

## What is Hashgraph?

Hashgraph is a distributed consensus algorithm and data structure that is fast, fair, and secure. This indirectly creates a trusted community, even when members do not necessarily trust each other. Hedera is the only authorized public network to use hashgraph. You can learn more about the consensus algorithm [here](core-concepts/hashgraph-consensus-algorithms/).

## Hello Future Roadmap

Hedera has an audacious but simple vision: to build a trusted, secure, and empowered digital future for all. Take a look at our development [roadmap](https://hedera.com/roadmap) for a glimpse into the future.
