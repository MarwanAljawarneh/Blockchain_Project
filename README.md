# Money Transfer Application Using Blockchain

## Overview
This project implements a secure money transfer application leveraging blockchain technology to facilitate reliable and efficient transactions between multiple clients. The application employs a client-server architecture using TCP connections, developed with Python, socket programming, and multithreading.

## Features
- **Blockchain Security:** Ensures transaction integrity and security by leveraging blockchain technology.
- **Client-Server Architecture:** Supports multiple clients connecting to a centralized server, allowing for real-time transactions.
- **Multithreading for Scalability:** Each client connection operates on a separate thread, enabling concurrent transactions between clients.

## Technical Details
- **Languages and Tools:** Python, Socket Programming, TCP/IP, Multithreading
- **Modules:** 
  - `socket` for network communication
  - `threading` for handling multiple clients simultaneously
- **Scalability Consideration:** While the current design uses a new thread per client connection, which is effective for smaller scales, future scalability might require optimization to handle a larger number of clients, such as using an event-driven approach or thread pooling.

## Setup and Usage
1. **Clone the Repository:**
   - Run the command: `git clone <repository_url>`
   - Change to the directory: `cd <repository_name>`

2. **Run the Server:**
   - Execute: `python server.py`

3. **Run the Client:**
   - Execute: `python client.py`

4. **Perform Transactions:** Once clients are connected, they can execute transactions which will be securely recorded on the blockchain.
