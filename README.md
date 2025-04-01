# Fake product identification system
Main-Project

### Fake Product Identification System Using Blockchain

#### Overview

Welcome to the final year project repository for the **Fake Product Identification System Using Blockchain**. This innovative project leverages blockchain technology to address the pervasive issue of counterfeit products in the market. By integrating a secure, decentralized ledger, our system ensures the authenticity and traceability of products, providing a robust solution for consumers, manufacturers, and retailers alike. Developed by ,
Anjal Mohammed V.(KNR20CS013)
Fatih Abdul Fattah(KNR20CS027)
Jyothish P. S.(KNR20CS033)
Mohammed Waseem(KNR20CS036)
Sreeraj E. K.(LKNR20CS075)

#### Project Description

The Fake Product Identification System is designed to offer a transparent and tamper-proof mechanism for verifying the authenticity of products. The system utilizes blockchain technology to create an immutable record of product information from production to sale. Here’s a brief overview of how it works:

1. **Product Registration**: Manufacturers register their products on the blockchain, creating a unique identifier for each item. This information includes product details, manufacturing date, and batch number.

2. **Tracking and Verification**: As the product moves through the supply chain, each transaction is recorded on the blockchain. Retailers and consumers can scan a product's unique QR code to access its blockchain history and verify its authenticity.

3. **Fraud Detection**: By comparing the scanned data against the blockchain ledger, the system identifies counterfeit products and alerts users to potential fraud.

#### Key Features

- **Immutable Ledger**: Ensures that once product information is recorded, it cannot be altered or tampered with.
- **Decentralized Verification**: Reduces reliance on a central authority, minimizing the risk of data manipulation.
- **Real-time Tracking**: Provides up-to-date information on a product’s journey through the supply chain.
- **User-Friendly Interface**: Allows consumers and retailers to easily verify product authenticity using a mobile app.

#### Technologies Used

- **Blockchain**: For secure and transparent data recording.
- **Smart Contracts**: To automate product registration and verification processes.
- **QR Codes**: For easy product scanning and information retrieval.
- **Mobile Application**: For user interaction and real-time verification.

#### Getting Started

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/Jyothish007/Main-Project.git
   ```

2 **Go to the project folder, open terminal there and run following command to install required node_modules**:-
```
npm install
```
3. **Compile contract source files. (Compilation and deployment can be done using truffle migrate)**:-
```
truffle compile
```
4. **Open Ganache, (to setup local blockchain)**
    - crerate new workspace
    - add truffle-config.js  in truffle project 
    - change port to 7545 in server settings (same as port in truffle-config.js)
5. **In chrome, open metamask **
   - add new test network using  
        - NETWORK ID (i.e. 5777 ,from Ganache Server settings) 
        - RPC SERVER (i.e HTTP://127.0.0.1:8545 ,from Ganache Server settings)
        - CHAIN CODE (i.e. 1337)
   - import account using private key of any account from local blockchain available in Ganache.
6. **In terminal, run following commands**:-
- Run migrations to deploy contracts.
```
truffle migrate
```
- To start a server and it will open a homepage (index.html) file in the default browser.
```
npm run dev 
``` 
7. **Login to metamask ,and connect the added account to local blockchain (i.e.localhost:3000)**
8. **Interact with website**
