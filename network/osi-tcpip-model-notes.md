# OSI & TCP/IP Models

---

## 🌐 OSI Model (Open Systems Interconnection)

The OSI model explains how data moves through a network in 7 layers:

| Layer | Name              | Main Function |
|------|-------------------|--------------|
| 7    | Application       | Provides services and interfaces for applications |
| 6    | Presentation      | Data encoding, encryption, compression |
| 5    | Session           | Establishing, managing, and synchronizing sessions |
| 4    | Transport         | End-to-end communication and segmentation |
| 3    | Network           | Logical addressing and routing |
| 2    | Data Link         | Reliable transfer between adjacent nodes |
| 1    | Physical          | Physical transmission of data (signals, cables, wireless) |

### Examples:
- Application: HTTP, FTP, DNS, SMTP, IMAP  
- Presentation: JPEG, PNG, MIME, encryption standards  
- Session: RPC, NFS  
- Transport: TCP, UDP  
- Network: IP, ICMP, IPSec  
- Data Link: Ethernet (802.3), WiFi (802.11)  
- Physical: electrical, optical, wireless signals  

---

## 🌍 TCP/IP Model

TCP/IP stands for Transmission Control Protocol / Internet Protocol.

| OSI Layer | TCP/IP Layer | Protocols |
|----------|--------------|------------|
| 7        | Application  | HTTP, HTTPS, FTP, SMTP, DNS, SSH, Telnet |
| 4        | Transport    | TCP, UDP |
| 3        | Internet     | IP, ICMP, IPSec |
| 2        | Network Interface | Ethernet (802.3), WiFi (802.11) |

---

## 🌐 IP Addressing Basics

### Private IP Ranges:
Private IP addresses are used inside local networks:

- 10.0.0.0 – 10.255.255.255  
- 172.16.0.0 – 172.31.255.255  
- 192.168.0.0 – 192.168.255.255  

Example:
- 192.168.0.1

---

### IP Address Rules:
- IPv4 uses 4 octets  
- Each octet ranges from 0 to 255  
- Example: 192.168.1.1  

---

## 📦 How Data Moves Through Layers

1. Application data is created  
2. Transport layer adds TCP/UDP header → segment/datagram  
3. Network layer adds IP header → packet  
4. Data Link layer adds frame header/trailer → frame (Ethernet/WiFi)  
5. Physical layer transmits bits as signals  

---

## 🧠 Summary
The OSI and TCP/IP models explain how data is structured, transmitted, and delivered across networks. Understanding these models is essential for networking, cybersecurity, and troubleshooting.
