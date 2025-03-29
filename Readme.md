# WebSocket App

## Overview
This WebSocket app enables real-time, bidirectional communication between the server and connected clients. It is designed to demonstrate the use of WebSocket technology for efficient data exchange.

## How It Works
1. The server establishes a WebSocket connection with clients.
2. Clients can send messages to the server, and the server can broadcast messages to all connected clients.
3. The communication is event-driven, ensuring low latency and efficient data transfer.

## How to Start the Server
1. Navigate to the project directory:
    ```bash
    cd "/c:/My Projects/Websocket-app"
    ```
2. Install dependencies (if applicable):
    ```bash
    npm install
    ```
3. Start the WebSocket server:
    ```bash
    npm start
    ```
4. The Websocket will run at `ws://localhost:8080` by default

## How to Connect as a Client
1. Run the `index.html` in live server and visit it.
2. Visit the client application at:
    ```
    http://localhost:3000
    ```
    (Replace `3000` with the port specified in your server configuration.)
3. Interact with the WebSocket server through the client interface.
4. Share the interface link `http://your-ipv4-address:3000` to the fellows who connected to the same Network to chat

## Quick Start Guide
1. Start the server. The server will run at a specific IP address.
2. Update the `index.html` file with the server's IP address.
3. Open `index.html` using a live server.
4. Access the interface and share the link with others on the same network to start chatting.

- **Note:** Contributions are welcome! Feel free to submit a pull request to improve this project.
- If you find this repository helpful, please star it for future reference. Thank you!

Enjoy real-time communication with the WebSocket app!