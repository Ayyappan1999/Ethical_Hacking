# Ports

In networking, a port is a logical connection point that is used to identify a specific process or application on a device, such as a computer or server. 

## TOTAL PORTS = 65535

* Ports are identified by numbers ranging from 0 to 65535. 
* Certain well-known port numbers are reserved for specific applications or services,  Such as
<pre>
    -> Port 80 for HTTP (web browsing) &
    -> Port 443 for HTTPS (secure web browsing).
</pre>

There are two types of ports in networking:
<pre>
1. Physical Ports: These are the physical connections on a device that allow it to connect to a network. 
   Examples include Ethernet ports, USB ports, and serial ports.
2. Logical Ports: These are the software-based ports that are used to identify a specific application or service running on a device. 
   Examples include TCP and UDP ports.
</pre>


There are `65,536` ports available for use in networking, with port numbers ranging from `0 to 65535`. The ports are divided into three ranges:

### 1. Well-known Ports: 
   * Port numbers from 0 to 1023 are reserved for well-known services and protocols. 

Some examples include:
- Port 21: FTP (File Transfer Protocol)
- Port 22: SSH (Secure Shell)
- Port 25: SMTP (Simple Mail Transfer Protocol)
- Port 80: HTTP (Hypertext Transfer Protocol)
- Port 443: HTTPS (Secure HTTP)

### 2. Registered Ports: 
   * Registered ports are a range of TCP/UDP port numbers from 1024 to 49151. 
   * They are assigned by the Internet Assigned Numbers Authority (IANA) to applications or services that have been registered with them.
   * The IANA assigns registered port numbers to applications or services that are widely used and likely to be installed on many systems. 
   * The assignment of a registered port number ensures that different applications or services can use different port numbers and avoid conflicts with other applications or services.

Here are some examples of registered ports and their associated applications or services:

- Port 1433: Microsoft SQL Server
- Port 1521: Oracle database
- Port 3306: MySQL database
- Port 3389: Remote Desktop Protocol (RDP)
- Port 5432: PostgreSQL database
- Port 5900: Virtual Network Computing (VNC)
- Port 8080: HTTP Alternate (used for web proxies or caching servers)

### 3. Dynamic/Private Ports: 
   * Dynamic/Private ports are TCP/UDP port numbers from 49152 to 65535. 
   * They are also known as ephemeral ports or temporary ports because they are allocated dynamically by the operating system to client applications or services when they initiate a network connection.
   * These ports are used for temporary connections, and they are not registered with the IANA or for applications that require multiple connections, such as peer-to-peer file sharing.
   * They are available for use by any application or service on a first-come, first-served basis.

Here are some examples of dynamic/private ports and their associated applications or services:

- Port range 49152-65535: Microsoft Windows RPC (Remote Procedure Call)
- Port range 49152-65535: BitTorrent file sharing
- Port range 49152-65535: Skype voice and video chat
- Port range 49152-65535: Apple Bonjour service
- Port range 49152-65535: UPnP (Universal Plug and Play) protocol


Here's a table of important ports and their associated protocols:
```
|-------------|------------------------------|
| Port Number | Protocol                     |
|-------------|------------------------------|
| 20, 21      | FTP (File Transfer Protocol) |
| 22          | SSH (Secure Shell)           |
| 23          | Telnet                       |
| 25          | SMTP (Simple Mail Transfer Protocol) |
| 53          | DNS (Domain Name System)     |
| 67, 68      | DHCP (Dynamic Host Configuration Protocol) |
| 69          | TFTP (Trivial File Transfer Protocol) |
| 80          | HTTP (Hypertext Transfer Protocol) |
| 110         | POP3 (Post Office Protocol 3) |
| 143         | IMAP (Internet Message Access Protocol) |
| 161         | SNMP (Simple Network Management Protocol) |
| 443         | HTTPS (Hypertext Transfer Protocol Secure) |
| 445         | SMB (Server Message Block)   |
| 465         | SMTPS (Simple Mail Transfer Protocol Secure) |
| 3389        | RDP (Remote Desktop Protocol) |
| 119         | NNTP (Network News Transfer Protocol)|
| 123         | NTP (Network Time Protocol)          |
| 389         | LDAP (Lightweight Directory Access Protocol) |
| 636         | LDAPS (Lightweight Directory Access Protocol Secure) |
| 993         | IMAPS (Internet Message Access Protocol Secure) |
| 995         | POP3S (Post Office Protocol 3 Secure)|
| 6660-6669   | IRC (Internet Relay Chat)            |
| 3306        | MySQL                                |
| 5432        | PostgreSQL                           |
| 1433        | MS SQL Server                        |
| 1521        | Oracle Database                      |
| 1723        | PPTP (Point-to-Point Tunneling Protocol) |
| 1701        | L2TP (Layer 2 Tunneling Protocol)    |
| 1194        | OpenVPN                              |
| 5060, 5061  | SIP (Session Initiation Protocol)    |
| 5222        | XMPP (Extensible Messaging and Presence Protocol) |
| 5900-5903   | VNC (Virtual Network Computing)      |
| 1883        | MQTT (Message Queuing Telemetry Transport) |
| 8883        | MQTTS (Message Queuing Telemetry Transport Secure) |
|------------------------------------------------------------------|
```
