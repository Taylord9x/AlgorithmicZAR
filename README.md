# AlgorithmicZAR
Algorithmic ZAR is a decentralized stablecoin project utilizing algorithmic mechanisms to maintain stability against the South African Rand (ZAR). The project consists of smart contracts for minting, burning, oracles for real-time data, and governance for protocol adjustments.

Code Structure
![Code Structure](https://ibb.co/stY6rnz)

Smart Contracts

    AlgorithmicZAR.sol:
        Main contract for algorithmic stablecoin.

    Oracle.sol:
        Contract for decentralized oracles providing real-time data.

    GovernanceToken.sol:
        Contract for governance token.

Deployment

To deploy the smart contracts:
    
    truffle migrate --network <network_name>
