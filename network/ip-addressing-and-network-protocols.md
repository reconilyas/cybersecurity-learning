# IP Addressing & Network Protocols

---

## 🌐 TCP (Transmission Control Protocol)

TCP is a connection-oriented protocol that provides reliable data delivery.

### Characteristics
- Connection-oriented
- Guaranteed delivery
- Flow control (limits the amount of data sent before receiving an acknowledgment)
- Error checking and retransmission
- Reliable but slower than UDP

---

## 🌍 IP (Internet Protocol)

IP is responsible for logical addressing and routing packets between networks.

### Characteristics
- Connectionless
- Best-effort delivery
- No guarantee that packets will reach the destination

---

## ⚡ UDP (User Datagram Protocol)

UDP is a lightweight transport protocol used for fast communication.

### Characteristics
- Connectionless
- Faster than TCP
- Uses checksums for basic error detection
- Does not guarantee delivery or packet order

---

## 🔄 ARP & RARP

### ARP (Address Resolution Protocol)
Maps an IPv4 address to a MAC address on a local network.

### RARP (Reverse Address Resolution Protocol)
Maps a MAC address to an IP address.

> Note: RARP is now obsolete and has been replaced by protocols such as BOOTP and DHCP.

---

## 📨 ICMP (Internet Control Message Protocol)

Used for diagnostics and error reporting.

Example:
- `ping`
- `traceroute`

---

## 👥 IGMP (Internet Group Management Protocol)

Used to manage multicast group membership in IPv4 networks.

---

## 🌐 DNS (Domain Name System)

- Default Port: **53**
- Translates domain names into IP addresses.

Example:
- `google.com` → `142.250.x.x`

---

# IP Addressing & Subnetting

## Binary AND Operation

Subnetting uses the AND operation:

| A | B | Result |
|---|---|--------|
| 1 | 1 | 1 |
| 1 | 0 | 0 |
| 0 | 1 | 0 |
| 0 | 0 | 0 |

---

## IPv4 Address Classes

| Class | Address Range | Purpose |
|-------|---------------|---------|
| A | 1.0.0.0 – 126.255.255.255 | Large networks |
| B | 128.0.0.0 – 191.255.255.255 | Medium networks |
| C | 192.0.0.0 – 223.255.255.255 | Small networks |
| D | 224.0.0.0 – 239.255.255.255 | Multicast |
| E | 240.0.0.0 – 255.255.255.255 | Experimental |

---

## Private IPv4 Address Ranges

| Class | Private Range |
|-------|---------------|
| A | 10.0.0.0 – 10.255.255.255 |
| B | 172.16.0.0 – 172.31.255.255 |
| C | 192.168.0.0 – 192.168.255.255 |

### Notes
- Used only inside private networks
- Not routable on the public Internet
- No public IP allocation is required

---

## VLSM (Variable Length Subnet Mask)

Variable Length Subnet Masking (VLSM) allows different subnet sizes within the same network, improving IP address utilization and reducing waste.

---

## 🧠 Summary

Understanding TCP, UDP, IP, ARP, DNS, ICMP, and IPv4 addressing is fundamental for networking, cybersecurity, and troubleshooting modern networks.
