This repository contains a custom SSH Server and Reverse SSH Client built using Python's paramiko library. The system enables secure, remote command execution over an SSH connection.

Features
- Custom SSH Server: Handles client authentication, command dispatch, and output retrieval.
- Reverse SSH Client: Connects to the server, executes commands locally, and sends the results back.
- Secure Communication: Encrypted SSH connection for secure data transfer.
  
Usage
Run the SSH Server:
python3 ssh_server.py

Run the Reverse SSH Client:
python3 reverse_ssh_client.py

Follow the prompts to establish a connection and start executing commands.
