# seattle-ops-102d10DiscussionsRead-Class-07
seattle-ops-102d10DiscussionsRead: Class 07



# Readings: Network Connectivity



## SSH Protocol

1. What is the Secure Shell (SSH) Protocol?
The SSH protocol (also referred to as Secure Shell) is a method for secure remote login from one computer to another. It provides several alternative options for strong authentication, and it protects communications security and integrity with strong encryption. It is a secure alternative to the non-protected login protocols (such as telnet, rlogin) and insecure file transfer methods (such as FTP).
2. What are the typical uses of the SSH protocol?
   
*providing secure access for users and automated processes

*interactive and automated file transfers

*issuing remote commands

managing network infrastructure and other mission-critical system components.
3.How does the SSH protocol work?
4. How is the data kept safe when transmitted between the SSH client and server? SSH protocol uses strong symmetric encryption and hashing algorithms to ensure the privacy and integrity of the data that is exchanged between the client and server.
5. What is SFTP?
SFTP (SSH File Transfer Protocol) is a secure file transfer protocol. It runs over the SSH protocol. It supports the full security and authentication functionality of SSH.

All Questions sited from sites below
Tatu Ylonen: SSH - Secure Login Connections over the Internet.
Proceedings of the 6th USENIX Security Symposium, pp. 37-42, USENIX, 1996.
 
https://www.ssh.com/academy/ssh/protocol

https://www.ssh.com/academy/ssh/sftp-ssh-file-transfer-protocol#:~:text=SFTP%20(SSH%20File%20Transfer%20Protocol)%20is%20a%20secure%20file%20transfer%20protocol.%20It%20runs%20over%20the%20SSH%20protocol.%20It%20supports%20the%20full%20security%20and%20authentication%20functionality%20of%20SSH.


## RDP
1. What is RDP? he Remote Desktop Protocol allows remote users to see and use Windows on a device in another location. Key peripherals like your keyboard and mouse are shared with the remote machine, allowing you to use and control it as if you were sat right in front of it. And how to use it
2. What is Windows Remote Desktop Connection? RDP is a Windows-only protocol, and you can only establish remote connections using RDP with Windows PCs and Windows Server installations that support it. Not all versions of Windows do—Windows 10 Home, for instance, can only be used as a client to connect to other Windows Remote Desktops, not the other way around.
3. What is the RDP port number?RDP is no different, and the RDP port (port 3389) is well known and regularly scanned for exploits. If you plan to use Windows Remote Desktop over the internet, you need a strategy in place to secure it.

All questions sited from site below 
https://www.comparitech.com/net-admin/what-is-rdp/

