# Blockchain Demo

This project demonstrates a **P2P Blockchain Network Simulation** using HTML and JavaScript. The application enables users to explore blockchain concepts such as transactions, mining, validation, and consensus across multiple nodes in a distributed network.

## Features

### **P2P Blockchain Network**
- Each node represents an independent participant in the network.
- Nodes maintain a ledger, validate transactions, and broadcast updates.

### **Key Functionalities**
1. **Add Transactions**
   - Select a sender, receiver, and specify the amount.
   - Add the transaction to the **Mempool** for processing.

2. **Mine Blocks**
   - Create new blocks by solving the cryptographic puzzle (Proof of Work).
   - Transactions in the Mempool are added to the block during mining.

3. **Validate Chain**
   - Check the integrity of the blockchain.
   - Verifies that each block references the correct hash of the previous block.

### **Node Information**
- Each node displays:
  - **Index, Timestamp, Nonce, and Hash** of the latest block.
  - **Transactions** in the current block.
  - **Previous Hash** linking to the preceding block.
  - **Balances** of all participants in the network.
  - **Pending Transactions** in the Mempool.
  - **Mining CPU Time** and **Validation Status**.

### **Broadcast and Synchronization**
- All nodes synchronize with each other to achieve consensus.
- Balances and the blockchain are updated across the network.

### Genesis Block
- Each node starts with a genesis block:
  - **Index:** 0
  - **Timestamp:** `2023-01-01T00:00:00Z`
  - **Transactions:** None
  - **Nonce:** 0
  - **Hash:** Predefined value (`522521ef...`)
  - **Previous Hash:** `0`

## Usage

1. Open the HTML Page.
2. Interact with individual nodes:
   - Add transactions.
   - Mine new blocks.
   - Validate the blockchain.
3. Observe how the network synchronizes data.

## Technologies Used
- **HTML** for structure.
- **CSS** for styling.
- **JavaScript** for blockchain logic and interactivity.

## Future Improvements
- Implement real-time communication using WebSockets.
- Add support for additional consensus algorithms (e.g., Proof of Stake).
- Enhance UI for better visualization of block and chain data.

## License
This project is licensed under the MIT License. See `LICENSE` for more details.

Enjoy exploring the world of blockchain with this demo! 🚀