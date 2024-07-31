# Swisstronik Deploy Private NFT

## Description

This repository contains scripts and configurations for deploying a private NFT contract using Swisstronik. The contract allows for the creation and management of NFT tokens privately on the Swisstronik network.

## Prerequisites

Ensure you have the following requirements before getting started:

- **Node.js**: Version 14 or higher. [Download Node.js](https://nodejs.org/).
- **npm**: Typically installed with Node.js.
- **Hardhat**: A framework for Ethereum smart contract development. [Hardhat Documentation](https://hardhat.org/getting-started/).
- **Swisstronik CLI**: Install the Swisstronik CLI if needed for deployment on the Swisstronik network. [Swisstronik CLI Installation](https://www.swisstronik.com/docs/cli).

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yfndx/swisstronik-deploy-private-nft.git
    cd swisstronik-deploy-private-nft
    ```

2. **Install Dependencies**

    ```bash
    npm install
    ```

## Configuration

1. **Set Environment Variables**

    Create a `.env` file in the root directory of the project and add the following information:

    ```
    SWISSTRONIK_API_KEY=your_swisstronik_api_key
    PRIVATE_KEY=your_private_key
    ```

2. **Configure Hardhat**

    Adjust the Hardhat configuration file (`hardhat.config.js`) if necessary, especially regarding network and account settings.

## Deployment

To deploy the private NFT contract to the Swisstronik network, use the following command:

```bash
npx hardhat run scripts/deploy.js --network swisstronik
