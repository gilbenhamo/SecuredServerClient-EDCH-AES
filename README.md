# Secured Client-Server Connection
This project demonstrates a secure client-server connection implemented in Python, utilizing a handshake,
key exchange, and encryption. The connection is established using a TCP socket, 
and the encryption is achieved through ECDH key exchange and AES encryption.

## Description
This project focuses on creating a secure client-server connection by implementing the following components:

### Socket
A simple TCP connection is established between the client and the server.

### Key Exchange with ECDH
- Private and public keys are generated for both the client and server.
- Each side sends its public key to the other, allowing them to create a shared key.

### Encryption with AES
- The client sends a text message to the server.
- The server encrypts the text message and sends it back to the client.
- The client then decrypts the received message.

## Requirements
- Python 3.9 (or above)
- Ensure that you have installed all the packages listed in the "requirements.txt" file.

## Setup and Usage
1. Install Python 3.9 or a compatible version on your system.
2. Install the required packages listed in the "requirements.txt" file by running the following command:
    ```
    pip install -r requirements.txt
    ```
3. Set up the server and client scripts by following the instructions in their respective files.
4. Execute the server script on the server-side.
5. Execute the client script on the client-side.
6. The client and server will establish a secure connection using ECDH key exchange and AES encryption.

## Author
- [Gil Ben Hamo](https://github.com/gilbenhamo)




