# 🧩 Part E: Understanding Blockchain Basics

---

## 1. Local vs Real Blockchain

### 3 Differences between Hardhat Local Network and Ethereum Mainnet:

#### Hardhat Local Network:
1. Runs only on our computer locally.
2. We can run free tests.
3. used for testing.

#### Ethereum Mainnet:
1. Runs on global blockchain.
2. It costs money(gas fees).
3. Used for real transactions


### Why develop locally first?
Because it’s free and we can test and fix errors without wasting real money on gas fees.

### What changes if deployed to real Ethereum?
our contract becomes permanent, public, and costs money to deploy (gas fees).

---

## 2. Smart Contract Basics

### What is a Smart Contract?
smart contract is a program on the blockchain that runs automatically whenever the conditions are met.

### Can you edit contract code after deployment?
No, once deployed the code cannot be changed. 

### What happens if you restart your Hardhat node?
All local data is erased, so our deployed contracts disappear since it’s only temporary memory.

### How is it different from a regular program/website?
1. Smart contracts run on blockchain, not servers.  
2. They’re public, trustless, and permanent(decentralised), while websites can be edited anytime.

---

## 3. Blockchain & Our VPN Project

### Why use blockchain for a VPN?
To make the VPN decentralized, trustless, and trustworthy, so no single company controls user data.

### Advantages:
1. no central server to hack 
2. transparent and verifiable payments  
3. user ownership of identity and data

### Disadvantages:
1. slower and more expensive than normal servers  
2. hard to update once deployed  
3. requires users to understand wallets and gas fees 

### 2 Example data stored on blockchain:
1. VPN subscription details (which plan the user subscribed)
2. payment transactions 

---

## 4. Key Terms


**Blockchain** : A chain of blocks that stores data and unique hashs to identify and everyone can see but no one can change.
**Smart Contract** : code on blockchain that runs automatically when conditions are met.
**Gas** : A small fee wee pay to perform actions on blockchain.
**Wallet Address** : our blockchain account no. that we used to do transactions.
**Private Key** : a secret password that proves our ownership of wallet
**Transaction** : record of actions(send/recive crypto).
**Deployment** : uploading of smart contract on blockchain.

---