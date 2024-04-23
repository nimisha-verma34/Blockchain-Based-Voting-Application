# Decentralized Voting Application

## Introduction

This application leverages blockchain technology to provide a secure, transparent, and accessible voting system. It utilizes Ethereum smart contracts and interacts with the blockchain via the MetaMask extension.

## Prerequisites

- **Node.js**: Must be installed to run the server.
- **MetaMask Extension**: Required for interacting with the Ethereum blockchain.
- **Ethereum Account**: Necessary for deploying contracts and making transactions.
- **Ethers.js**: Used to interact with Ethereum Blockchain from JavaScript.
- **Solidity Compiler (optional)**: For compiling smart contracts locally.

## Project Structure

/project_root
|-- /public
|   |-- /images
|   |   |-- voter1.jpg
|   |   |-- voter2.jpg
|   |   `-- voter7.jpg
|   |-- index.html
|   |-- main.js
|   `-- style.css
|-- /artifacts
|   `-- contracts
|       |-- voter.sol
|       `-- voter.json
|-- package.json
|-- index.js
`-- .env


## Setup Instructions

1. **Clone Repository**
   Clone the repository to your local machine or download the source code.

2. **Install Dependencies**
   Navigate to the project root in your terminal and execute:
   ```bash
   npm install express ethers dotenv express-fileupload

3. Environment Variables
   Create a .env file in the root directory with the following content:
   ```bash
   API_URL="https://<your_ethereum_node_api>"
   PRIVATE_KEY="<your_private_key>"
   CONTRACT_ADDRESS="<deployed_contract_address>"

5. Running the Server
   Start the server using:
   ```bash
   node index.js

## Usage Guide
1. Connecting MetaMask
   Use the 'Connect MetaMask' button in the web application to connect your Ethereum wallet.
2. Casting a Vote
   Input the index of your chosen candidate and click 'Cast Vote'. This will log your vote on the blockchain.
3. Checking Voting Status
   Click the 'Check Voting Status' button to view the current voting status and results.

## Additional Information
1. Adding and Removing Candidates: Integrated into the smart contract and accessible via specific contract functions.
2. Security Considerations: Ensure the private key in the server is securely stored and not publicly exposed.
## Troubleshooting
1. Ensure all dependencies are installed and the Ethereum node API URL in the .env file is correct.
2. Check the browser console for any errors related to MetaMask or blockchain transactions.
   
