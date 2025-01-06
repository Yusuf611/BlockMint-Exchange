# Decentralized Trading Platform using HyperSDK

## Overview
This project demonstrates the creation of a decentralized trading platform environment using HyperSDK. It allows you to mint tokens, create assets, and perform cryptocurrency exchanges using a decentralized order book.

## Features
- **Mint Tokens:** Create your own tokens.
- **Asset Creation:** Define new assets on the blockchain.
- **Decentralized Exchange:** Perform crypto-token exchanges.
- **Monitoring:** Watch all blockchain activities in real-time.

## Requirements
- **GoLang** (latest version)
- **HyperSDK** (included in the repository)
- Bash shell
- Unix/Linux environment

## Setup Instructions

### Step 1: Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/Decentralized-Trading-Platform.git
cd Decentralized-Trading-Platform

```
### Step 2: Install Dependencies
```bash
go mod tidy
```

### Step 3: Configure Project Constants
Edit the file consts/consts.go and specify:

Token Name
Symbol

### Step 4: Register Asset Actions
Modify registry/registry.go to include Create_Asset and Mint_Asset actions.

### Step 5: Start the Project
Run the following commands:

```bash
chmod +x ./scripts/*.sh
./scripts/run.sh
```
### Step 6: Resolve Common Errors
Permission Denied: Use chmod a+rwx <filename> and dos2unix ./scripts/run.sh.
Go Path Misconfigured: Add Go binary to PATH:
```bash
export PATH=$PATH:$(go env GOPATH)/bin
```
### Step 7: Additional Commands
Build the project: ./scripts/build.sh
Monitor chain activity: ./build/token-cli chain watch
Mint tokens: ./build/token-cli action mint-asset
Create an order: ./build/token-cli action create-order
For more commands, refer to Hyper-SDK_Project_Step-By-Step_Commands_Run.txt.

## Video Demo  
[Watch the Project Demo](https://www.loom.com/share/b3995f7eba454c0c8914cf03b142f870)  

