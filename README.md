# Apillon Bot

## Overview

The Apillon Bot is a command-line interface (CLI) tool that interacts with the Apillon API to perform various tasks related to managing NFT collections, uploading files to storage, and managing website hosting. This README provides an overview of the bot, how to install and use it, and other relevant information.

## Features

- **Mint NFT**: Mint new NFTs by specifying the collection UUID, target address, and quantity.
- **Upload Storage**: Upload files to storage by providing the bucket UUID.
- **Get Uploaded URL**: Generate upload URLs for files associated with a website UUID, and end the upload session.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/dante4rt/apillon-bot.git
   ```

2. Navigate to the project directory:

   ```bash
   cd apillon-bot
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Usage

Before using the Apillon Bot, make sure you have obtained your authorization token from Apillon. You will be prompted to enter this token when running the bot for the first time.

To start the bot, run:

```bash
node index.js
```

Follow the prompts to select an action and provide any required inputs such as UUIDs, addresses, or quantities.

## Configuration

You can customize the behavior of the bot by modifying the `apillon.js` file. Update the API endpoints, request headers, and other settings as needed.
