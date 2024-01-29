# User Stories & Use Cases: Supply Chain DApp Frontend

## Introduction

This document outlines various user stories and use cases for the Supply Chain Decentralized Application (DApp). These narratives provide insight into the functionality of the application from the perspective of different users, offering a clear picture of the application's capabilities and interactions.

## User Stories

### As a Farmer

1. **Harvesting Produce**
   - **Description**: I want to record the harvesting of my produce, specifying details like the farm's name and location.
   - **Use Case**: Upon harvesting, I enter the produce details into the DApp and submit the information to the blockchain.

2. **Processing Produce**
   - **Description**: After harvesting, I need to process the produce and update its status on the blockchain.
   - **Use Case**: I select the harvested produce and mark it as processed on the DApp.

3. **Packing Produce**
   - **Description**: Once processed, I want to pack the produce and update its status.
   - **Use Case**: I choose the processed produce and indicate that it has been packed using the DApp.

4. **Selling Produce**
   - **Description**: I need to list my packed produce for sale and set a price.
   - **Use Case**: I provide the UPC and price for the packed produce and list it for sale on the blockchain through the DApp.

### As a Distributor

1. **Buying Produce**
   - **Description**: I want to buy produce from farmers at the listed price.
   - **Use Case**: I find available produce, confirm the price, and complete the purchase transaction using the DApp.

2. **Shipping Produce**
   - **Description**: After buying, I need to ship the produce to retailers.
   - **Use Case**: I update the shipping status of the bought produce in the DApp, signaling it's en route to retailers.

### As a Retailer

1. **Receiving Produce**
   - **Description**: I need to confirm the receipt of produce shipped by distributors.
   - **Use Case**: Upon receiving the produce, I update its status to 'Received' in the DApp.

### As a Consumer

1. **Purchasing Produce**
   - **Description**: I want to purchase produce from retailers.
   - **Use Case**: I browse available produce, choose what I want, and complete the purchase through the DApp.

### As an Administrator

1. **Managing User Roles**
   - **Description**: As an admin, I need to assign or revoke roles (farmer, distributor, retailer, consumer) to users.
   - **Use Case**: I can add or remove users from specific roles using admin functionalities in the DApp.

2. **Toggling Contract State**
   - **Description**: For maintenance or emergencies, I need to toggle the active state of the smart contract.
   - **Use Case**: I use the admin panel in the DApp to activate or deactivate the contract as needed.

3. **Transferring Ownership**
   - **Description**: If required, I need to transfer ownership of the contract to another address.
   - **Use Case**: Through the admin panel, I input the new owner's address and transfer contract ownership.

## Conclusion

These user stories and use cases demonstrate the versatile functionality of the Supply Chain DApp from various user perspectives. The application facilitates a range of actions, from harvesting to purchasing, all recorded transparently on the blockchain. Each role within the supply chain has distinct capabilities within the DApp, ensuring a comprehensive and user-friendly experience.
