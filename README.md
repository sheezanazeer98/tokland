# RealEstate Smart Contract

The `RealEstate` smart contract is designed to tokenize real estate assets as Non-Fungible Tokens (NFTs) on the Ethereum blockchain. This approach not only modernizes property transactions but also integrates blockchain's reliability and security.

## Key Features

- **Tokenization of Real Estate**: Properties are converted into unique digital assets (NFTs), making it easier to trade and manage real estate on a digital platform.

- **IPFS for Metadata Storage**: Utilizes InterPlanetary File System (IPFS) to store and retrieve metadata about the properties, ensuring data integrity and availability.

- **Automated Asset Minting**: Streamlines the issuance of new tokens by automatically minting and assigning metadata at the time of token creation, simplifying the entry of properties into the market.


## Installation

```shell
npx hardhat compile
npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost
```