  # IDS, IPS & IPsec Security

---

# IDS (Intrusion Detection System)

An IDS is a security system that monitors network traffic and detects suspicious activity.

### Characteristics
- Passive system (does not block attacks)
- Sends alerts to the administrator when an attack is detected

---

## IDS Detection Methods

### 🔹 Signature-Based Detection
- Detects known attacks
- Uses a database of attack signatures (historical data)

---

### 🔹 Behavior-Based (Anomaly-Based) Detection
- Detects unusual behavior or traffic patterns
- Focuses on abnormal activity instead of known signatures

---

# IPS (Intrusion Prevention System)

An IPS is similar to IDS but more advanced.

### Characteristics
- Active (reactive) system
- Detects and blocks attacks automatically
- Sends alerts to administrators
- Provides real-time protection

---

### IDS vs IPS

| IDS | IPS |
|-----|-----|
| Detects only | Detects + prevents |
| Passive | Active |
| Sends alerts | Blocks attacks |

---

# IPsec (Internet Protocol Security)

IPsec is a suite of protocols used to secure communication over IP networks.

### Purpose
- Secures communication between users and servers
- Creates encrypted tunnels over networks (similar to VPNs)
- Protects data confidentiality and integrity

---

## IPsec Protocols

### 🔹 AH (Authentication Header)
- Provides authentication and integrity
- Protects IP packets from tampering
- Does NOT encrypt data

---

### 🔹 ESP (Encapsulating Security Payload)
- Provides encryption + authentication
- Secures the payload of IP packets
- Ensures confidentiality and integrity

---

## IPsec Policies
IPsec policies define:
- What traffic should be secured
- How it should be encrypted
- Which devices are allowed to communicate

---

## 🧠 Summary

IDS detects attacks and alerts administrators, while IPS detects and blocks attacks in real time. IPsec secures network communication using encryption and authentication through protocols like AH and ESP.
