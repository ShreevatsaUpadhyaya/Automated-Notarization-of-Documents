



<!-- PROJECT LOGO -->
<br />


  # Automated Notarization Of Documents Using Blockchain


The InterPlanetary File System (IPFS) and Blockchain technologies will be used in this project to provide a safe and decentralised system for document verification. The system keeps both the hash of the documents and the actual documents in the IPFS network and Blockchain networks, respectively. This makes sure the papers can be easily recovered and confirmed by authorised persons without being tampered with or altered.

## Features

- Secure document verification using Blockchain and IPFS technologies
- Decentralized system, with no central authority or single point of failure
- Fast and easy verification process, with no need for intermediaries or third-party services
- User-friendly interface for document upload and verification
- Support for multiple document types and formats

## Requirements

- Node.js and npm installed on your system
- Ganache or any other Ethereum network client
- IPFS client (optional)

## Installation

1. Clone this repository: 
``https://github.com/ShreevatsaUpadhyaya/Automated-Notarization-of-Documents.git``


2. Install the required packages:

``cd Automated-Notarization-Of-Documents-Using-Blockchain
npm install``


3. Open the application in your browser using Liver Server Extension .


## Usage

1. The owner of the system must first add an exporter to the list of authorized parties. This is done by clicking on the "Add Exporter" button and entering the exporter's Ethereum address.
2. Upload a document to the system by clicking on the "Upload Document" button and selecting a file from your computer. The document will be encrypted and stored in the IPFS network, and its hash will be recorded in the Blockchain.

3. Verify a document by clicking on the "Verify Document" button and entering its unique identifier (hash) in the input field. The system will retrieve the document from the IPFS network, decrypt it, and compare its hash with the one recorded in the Blockchain.

4. The system will display a message indicating whether the document is authentic or not.



## Acknowledgments
- Metamask documentation
- Solidity and Web3.js documentation
- IPFS documentation
- Truffle documentation




