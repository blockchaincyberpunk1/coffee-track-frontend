# Installation Guide for Supply Chain DApp Frontend

This guide provides detailed instructions on how to set up and run the frontend of the Supply Chain DApp on your local machine.

## Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (version 12.x or above)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)
- A web browser (preferably Google Chrome) with [MetaMask](https://metamask.io/) extension installed

## Step-by-Step Installation

### 1. Clone the Repository

First, clone the project repository from GitHub to your local machine. Open a terminal and run:

```bash
git clone https://github.com/blockchaincyberpunk1/coffee-track.git
cd coffee-track/frontend
 ```

### 2. Install Dependencies

Navigate to the frontend directory and install the required npm packages:

```bash
   npm install
   ```

This command will install all the dependencies defined in package.json.

### 3. Configuration

Ensure that the app.js file in the scripts folder is correctly configured to interact with the deployed smart contract. Specifically, verify the supplyChainAbi and supplyChainAddress are correctly set.

### 4. Running the Application

Once the installation is complete and the configuration is set, you can start the application:
  - Open the index.html file in a browser or set up a local server.

## Troubleshooting Common Issues

- **Missing Dependencies**: If you encounter errors related to missing modules, try re-running npm install.
- **MetaMask Connection Issues**: Ensure MetaMask is installed and logged in. If problems persist, try resetting the account in MetaMask.
- **Network Mismatch**: The DApp and MetaMask should be on the same Ethereum network. Verify the network settings in MetaMask.
- **Browser Compatibility**: If the DApp doesn't work in your browser, try switching to Google Chrome.

## Troubleshooting Common Issues

For additional help or if you encounter specific issues not covered in this guide, please reach out to our support team at [svolcov.blockchaindeveloper@gmail.com].