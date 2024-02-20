## Table of Contents
1. [Overview](https://github.com/getfunds/Final-Project?tab=readme-ov-file#overview)
2. [Features](https://github.com/getfunds/Final-Project?tab=readme-ov-file#features)
3. [Getting Started](https://github.com/getfunds/Final-Project?tab=readme-ov-file#getting-started)
4. [Installation](https://github.com/getfunds/Final-Project?tab=readme-ov-file#installation)
5. [Usage](https://github.com/getfunds/Final-Project?tab=readme-ov-file#usage)
6. [Programs](https://github.com/getfunds/Final-Project?tab=readme-ov-file#programs)
7. [Contributions](https://github.com/getfunds/Final-Project?tab=readme-ov-file#contributions)

## Overview

The Dapp is a single-page application that utilizes programs to implement user reviews, storing them on-chain in the Solana blockchain. Users will have the ability to add, update, and view reviews, making them visible to everyone.

## Features

- Users are able to Add reviews.
- Users are able to Update reviews.
- Users are able to View all reviews.
- All reviews are stored on-chain.
- Solana Wallet Integration: Connect your Solana wallet to participate directly.

## Getting Started

Follow these steps to set up the project locally
1. Node.js: Ensure Node.js is installed. Download it from [nodejs.org](https://nodejs.org/).
2. Make sure you have a Solana compatible wallet. You can create one from [Phantom](https://phantom.app/), [SolFlare](https://solflare.com/) or any wallet of your choice.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/getfunds/Final-Project.git

2. Navigate to the project directory:
   ```bash
   cd Final-Project
3. Install required npm packages:
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```
   ## Usage
   1. Start the development server:
      ```bash
      npm run dev
    2. Open your web browser and navigate to http://localhost:3000 to access the DApp.
    3. Connect your Solana wallet (e.g., Phantom , SolFlare) to the DApp.
    4. Add or update reviews for restaurants and Browse reviews by others
   ## Programs
   The programs in this project deployed on Solana Blockchain are used to interact with the Blockchain and process reviews. Through programs users add and update reviews.

- **lib.rs**: used to create transactions, add and update reviews.
- **instruction.rs**: Defines as the instruction data to execute the programs.
- **state.rs**: Oversees the basic state of the program and handles some common errors.
- 
  ## Contributions
  
- Contributions to this project are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature/bug fix.
3. Make changes and test thoroughly.
4. Commit with clear and concise messages.
5. Push changes to your fork.
6. Submit a pull request describing your changes.
