# Protocol Agreements - Representing Real Property Rights On-Chain 📄

This repository contains the legal agreements for **The Deed Protocol**. These agreements formalize and enforce real property rights on-chain, ensuring that transactions related to real estate are legally binding and transparent. By leveraging smart contract technology, Protocol Agreements provide a secure, immutable, and accessible way to manage legal documents for real estate transactions.

## Overview

The Protocol Agreements repository is designed to bridge the gap between traditional legal frameworks and decentralized real estate transactions. It offers a suite of legal agreements that define property rights, ownership transfers, and other critical legal processes. These agreements are intended to work seamlessly with the Protocol Smart Contracts, ensuring that legal and operational aspects of real property transactions are fully integrated.

## Key Components

### 1. Agreement Templates

These templates form the core of our legal framework, outlining standardized contracts for various aspects of real property management. The templates are designed to be:

- **Legally Binding:** Crafted to meet regulatory requirements and provide enforceable legal contracts.
- **Modular and Extensible:** Easily customizable to accommodate different types of property transactions, such as sales, leases, and mortgages.
- **Interoperable:** Designed to work in concert with on-chain asset representations, ensuring consistency between legal documentation and blockchain data.

### 2. Agreement Registry

The Agreement Registry contract maintains a tamper-proof record of all executed legal agreements:

- **Immutable Record Keeping:** Once an agreement is recorded on-chain, it cannot be altered, ensuring transparency and trust.
- **Easy Verification:** Stakeholders can verify the authenticity and details of an agreement directly from the blockchain.
- **Efficient Management:** The registry handles the creation, storage, and retrieval of legal agreements, simplifying the management process for all parties involved.

### 3. Digital Signatures and Execution

To ensure that all parties formally agree to the terms, Protocol Agreements incorporate mechanisms for:

- **Digital Signatures:** Secure methods for capturing consent and acknowledgment from all involved parties.
- **Automated Execution:** Integration with smart contracts to trigger automated processes (e.g., transfer of ownership) once the legal agreements are executed.

### 4. Integration with The Deed Protocol

Protocol Agreements are tightly integrated with other components of The Deed Protocol ecosystem, including:

- **DeedNFT:** Ensuring that the legal ownership represented in an agreement is directly linked to the corresponding NFT.
- **FundManager and Validator Contracts:** Coordinating with financial and validation components to ensure comprehensive real estate transaction management.

## Features

- **Legally Binding On-Chain Documentation:** Ensure that real property rights are enforced with the same rigor as traditional legal contracts.
- **Immutable and Transparent:** Store and manage legal agreements on the blockchain for unparalleled security and trust.
- **Customizable and Extensible Templates:** Adapt agreements to meet the specific needs of different property transactions.
- **Seamless Ecosystem Integration:** Designed to work effortlessly with the other core components of The Deed Protocol.

## Installation and Setup

### Prerequisites

- **Node.js v16+**
- **Hardhat:** For compiling and testing the smart contracts.
- **Solidity ^0.8.20:** The version used for the smart contracts.
- A suitable development environment for smart contract development.

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Deed3Labs/Protocol-Agreements.git
   cd Protocol-Agreements
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Compile the Contracts:**

   ```bash
   npx hardhat compile
   ```

4. **Run Tests:**

   ```bash
   npx hardhat test
   ```

## Usage

### Deploying Legal Agreements

To deploy the legal agreements to your desired network, use the provided Hardhat deployment scripts. Ensure that your `hardhat.config.js` is properly configured for the target network:

```bash
npx hardhat run scripts/deploy.js --network <network-name>
```

### Interacting with Agreements

Once deployed, you can interact with the agreements using their designated functions. For example, you can:

- **Record a New Agreement:** Submit a new legal agreement for a property transaction.
- **Verify Agreement Authenticity:** Retrieve and validate an agreement from the registry.
- **Execute Agreement Actions:** Trigger processes such as ownership transfers or release of funds once all parties have signed.

Integrate these functionalities into your dApp to provide a seamless user experience that combines legal rigor with blockchain transparency.

## Testing

To ensure that all agreements and their integrations function as intended, run the comprehensive test suite provided:

```bash
npx hardhat test
```

Tests cover key functionalities such as agreement creation, digital signature verification, registry operations, and integration with other protocol components.

## License

The Protocol Agreements repository is licensed under the **CC0-1.0**. For additional details, please refer to the [LICENSE](LICENSE) file.
