# XYZ University Chat Client

## Overview
The **XYZ University Chat Client** is a simple client application designed for secure communication over a network using TCP/IP. It utilizes AES encryption for message security and implements the Diffie-Hellman key exchange protocol for establishing a shared secret key between the client and server. This ensures that messages exchanged are kept confidential and secure from eavesdropping.

## Features
- **User Authentication**: Users can register and log in using their credentials.
- **Secure Communication**: Messages are encrypted using AES-128 in CBC mode.
- **Diffie-Hellman Key Exchange**: A secure method for the client and server to agree on a shared secret key for encryption.
- **Real-time Chat**: Users can send and receive messages in real-time.
- **Exit Option**: Users can terminate the chat session gracefully.

## Technologies Used
- **C++**: Programming language for implementing the client.
- **OpenSSL**: Library for implementing AES encryption and secure key exchange.
- **Sockets**: For network communication using TCP/IP.

## Requirements
- C++ compiler (e.g., g++, clang++)
- OpenSSL library
- Networking capability (ensure ports are open for communication)
