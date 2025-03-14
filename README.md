# Java Client-Server Communication Project

This project demonstrates a basic **client-server communication** in Java using **TCP sockets**. The **server** listens for client connections and responds to messages sent by the **client**.

## Project Overview

- **Server**: A simple Java application that listens on a specified port for incoming client connections. Once a connection is made, it reads the client's messages, processes them, and responds back.
- **Client**: A simple Java application that connects to the server, sends a message, and prints the server's response.

## Requirements

- JDK 8 or higher
- An IDE such as IntelliJ IDEA or Eclipse (optional, but recommended)
- Basic knowledge of Java programming and networking

## Project Structure

- **`Client.java`**: The client-side code that connects to the server, sends a message, and prints the server's response.
- **`Server.java`**: The server-side code that listens for client connections, processes the incoming message, and responds back.

## Getting Started

### 1. Clone the Repository

Clone the project repository to your local machine using the following command:

```bash
git clone https://github.com/your-username/java-client-server-communication.git
