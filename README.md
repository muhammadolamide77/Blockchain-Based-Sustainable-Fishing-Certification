# Blockchain-Based Sustainable Fishing Certification

## Overview

This project implements a blockchain-based certification system for sustainable fishing practices. By leveraging blockchain technology, we create a transparent, immutable record of the entire fishing supply chain - from vessel registration to consumer purchase. The system provides verifiable sustainability credentials that consumers can trust while helping fishing operations demonstrate their commitment to environmental responsibility.

## System Architecture

The system consists of four primary smart contracts:

1. **Vessel Registration Contract**: Records and verifies fishing vessel details, ownership, and equipment
2. **Catch Documentation Contract**: Tracks fish species, quantities, locations, and methods
3. **Processing Verification Contract**: Monitors the chain of custody from catch to consumer
4. **Sustainability Certification Contract**: Issues verifiable eco-friendly credentials based on compliance

## Key Features

- **Transparency**: All fishing activities are recorded on an immutable blockchain
- **Traceability**: Complete chain of custody from ocean to consumer
- **Verification**: Third-party auditors can validate sustainability claims
- **Consumer Trust**: End users can verify the sustainability of their seafood purchases
- **Regulatory Compliance**: Built-in mechanisms to ensure adherence to fishing regulations
- **Fraud Prevention**: Cryptographic security prevents tampering with records

## Getting Started

### Prerequisites

- Node.js (v16.0+)
- Truffle Suite
- Ganache (for local development)
- MetaMask or similar Web3 wallet
- Access to target blockchain network (Ethereum, Polygon, etc.)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/blockchain-fishing-certification.git
   cd blockchain-fishing-certification
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Compile smart contracts:
   ```
   truffle compile
   ```

4. Deploy contracts to your chosen network:
   ```
   truffle migrate --network [network_name]
   ```

## Smart Contract Details

### Vessel Registration Contract

Records essential details about fishing vessels including:
- Vessel ID and name
- Registration number
- Owner information
- Vessel specifications (length, capacity, etc.)
- Fishing gear types and quantities
- Licensing information

### Catch Documentation Contract

Tracks fishing activities including:
- Catch date and time
- GPS coordinates of fishing location
- Species caught
- Quantities (by weight)
- Fishing methods used
- Environmental conditions
- Vessel ID reference

### Processing Verification Contract

Monitors the chain of custody including:
- Processing facility information
- Processing date and methods
- Product transformation tracking
- Quality control checkpoints
- Transportation details
- Batch and lot numbers

### Sustainability Certification Contract

Issues verifiable sustainability credentials based on:
- Adherence to quotas
- Avoidance of protected species
- Use of sustainable fishing methods
- Compliance with local regulations
- Reduction of bycatch
- Minimization of environmental impact

## Usage

### For Fishing Operations

1. Register your vessel using the Vessel Registration interface
2. Record catches in real-time through the mobile application
3. Document processing and transportation events
4. Receive sustainability certifications based on verified practices

### For Consumers

1. Scan product QR codes to access blockchain records
2. View the complete history of your seafood purchase
3. Verify sustainability credentials
4. Make informed purchasing decisions

### For Regulators and Auditors

1. Access comprehensive fishing activity records
2. Verify compliance with regulations
3. Validate sustainability claims
4. Generate compliance reports

## API Documentation

The system provides REST APIs for interacting with the smart contracts:

- `POST /api/vessels`: Register a new fishing vessel
- `GET /api/vessels/{id}`: Retrieve vessel information
- `POST /api/catches`: Record a new catch
- `GET /api/catches/{id}`: Retrieve catch information
- `POST /api/processing`: Record processing events
- `GET /api/certifications/{id}`: Verify sustainability certification

## Future Enhancements

- Integration with IoT devices for automated data collection
- AI-powered analysis of fishing patterns for sustainability insights
- Integration with international fishing regulation databases
- Enhanced consumer-facing applications for product verification
- Tokenization of sustainability credits for incentivizing eco-friendly practices

## Contributing

We welcome contributions to this project. Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Submit a pull request with a detailed description of your changes

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For more information, please contact:
- Email: info@sustainablefishingblockchain.org
- Website: https://sustainablefishingblockchain.org
