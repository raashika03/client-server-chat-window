# client-server-chat-window

### This's a Chat Application developed using *Socket programming* & *Tinkter* in python.
\
It's features:
- [x] GUI based Chat application implemented using **tinkter library** in python
- [x] Admin role has been provided with kick & ban facility. Kick means one can rejoin after kicking out. But on banning one can't rejoin.
- [x] Encryption decryption has been implemented from client to server side using **Symmetric-key** implemented using **fernet library in cryptography module** in python.
- [x] File transfer has been implemented from client to server side but has not been linked to GUI. It's separate for now.

**File structure**
- gui_server.py & gui_client.py - for gui, admi role, & encryption-decryption
- ft_server.py & ft_client.py - for file transfer via terminal not GUI
- edamontology/readme.md - file to be transferred from client to server
- key.text - stores the generated key for symmetric encryption & decryption.
#### Images showing the features

 1. Chat Window of four clients showing kick and ban functionality
 \
 \
![Chat Window](https://raw.githubusercontent.com/raashika03/client-server-chat-window/main/chat-window.png)


 2. Server side message on the terminal
 \
 \
![Server Terminal](https://raw.githubusercontent.com/raashika03/client-server-chat-window/main/server-terminal.png)


 3. Client Terminal for admin & Window for admin
 \
 \
![Admin Client Terminal](https://raw.githubusercontent.com/raashika03/client-server-chat-window/main/admin-client-terminal.png)


 4. Window for admin password
 \
 \
![Admin Password Window](https://raw.githubusercontent.com/raashika03/client-server-chat-window/main/admin-pass.png)
