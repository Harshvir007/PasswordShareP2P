I've created a secure P2P password sharing tool in Java with the following features:
Key Features:

Peer-to-Peer Connection: Direct connection between two peers (no central server)
Encryption: Uses Diffie-Hellman key exchange + AES-128 encryption
Dual Mode: Can act as server or client
GUI Interface: Simple Swing-based interface
Auto-Copy: Received passwords automatically copy to clipboard

How to Use:

Start a Server (Peer 1):

Enter a port (default: 5000)
Click "Start Server"
Wait for connection


Connect as Client (Peer 2):

Enter server's host and port
Click "Connect"


Share Passwords:

Once connected, enter a password
Click "Send Password"
The password is encrypted and sent to the peer



Security:

Diffie-Hellman key exchange establishes a shared secret
AES encryption with CBC mode
Each message uses a unique initialization vector
Passwords are encrypted before transmission

To Run:

bashjavac P2PPasswordShare.java

java P2PPasswordShare


Run two instances to test the connection between peers!RetryClaude does not have the ability to run the code it generates yet.
