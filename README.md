# Development of Security Framework for E-Healthcare Using Blockchain

## Project Overview

This project aims to develop a secure framework for e-healthcare systems using blockchain technology. By leveraging blockchain's decentralized nature and cryptographic security, we aim to ensure data integrity, confidentiality, and availability in healthcare applications.

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Frontend Design](#frontend-design)
- [Contributors](#contributors)
- [Screenshots](#screenshots)


## Introduction

The primary goal of this project is to create a secure, decentralized application (DApp) for managing healthcare records. The application ensures that only authorized users have access to sensitive health data, while maintaining transparency and immutability of records through blockchain technology.

## Technologies Used

- **Blockchain:** Ethereum
- **Development Environment:** Ganache
- **Framework:** Truffle
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Solidity (for smart contracts)
- **Others:** Metamask, IPFS

## Project Structure

```
project-root/
│
├── contracts/             # Smart contracts
├── migrations/            # Truffle migration files
├── src/                   # Frontend source code
│   ├── components/        # React components
│   ├── App.js             # Main React component
│   └── index.js           # Entry point for React
├── test/                  # Test files for smart contracts
├── build/                 # Compiled contracts
├── public/                # Public assets for frontend
├── package.json           # Node.js dependencies
├── truffle-config.js      # Truffle configuration
└── README.md              # Project README
```

## Setup and Installation

### Prerequisites

- Node.js
- Truffle
- Ganache
- Metamask

### Installation Steps

1. **Clone the repository:**
   ```
   git clone https://github.com/your-repo-url.git
   cd project-root
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Start Ganache:**
   Open Ganache and create a new workspace.

4. **Compile and deploy smart contracts:**
   ```
   truffle compile
   truffle migrate
   ```

5. **Run the frontend application:**
   ```
   npm start
   ```

## Usage

1. Open your browser and navigate to the application URL.
2. Connect your Metamask wallet to the application.
3. Use the application to manage healthcare records securely.

## Frontend Design

The frontend part of the project was designed using HTML/CSS/JS. The design includes various components that handle user interactions, data display, and blockchain integration.

### Key Features:

- User-friendly interface for managing healthcare records.
- Secure authentication and authorization using Metamask.
- Real-time data updates with blockchain integration.

## Contributors

- **Frontend Development:** Ashwarya
- **Backend Development:** Jithendra G
- **Smart Contract Development:** Gaurav Singh
- **Testing and Deployment:** Keerthi Reddy

## Screenshots

Screenshots of the frontend design can be found in the `screenshots` folder.
