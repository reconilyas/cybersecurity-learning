# OSI Model (Open Systems Interconnection)

---

## 🌐 What is OSI?
The OSI model was created to standardize networking and make troubleshooting easier by separating network communication into specific layers.

It helps identify where problems occur in a network (layer by layer).

---

## 🧱 OSI Model Layers

### 🔹 Layer 1 – Physical Layer
- Transmits raw bits over a medium
- Includes: fiber, copper, WiFi
- Data format: bits (1s and 0s)
- Focus: physical transmission and troubleshooting

---

### 🔹 Layer 2 – Data Link Layer
- Uses MAC (physical) addresses
- Responsible for local network communication
- Uses switches to forward data inside a network

---

### 🔹 Layer 3 – Network Layer
- Uses IP addresses
- Sends packets (datagrams)
- Connectionless delivery (does not confirm reception)
- Handles routing between networks

---

### 🔹 Layer 4 – Transport Layer
- Uses TCP / UDP
- Data is broken into segments
- Provides reliable or fast transmission

---

### 🔹 Layer 5 – Session Layer
- Establishes, manages, and ends sessions
- Controls communication between devices
- Works with session management (sometimes linked with SSL/TLS concepts)

---

### 🔹 Layer 6 – Presentation Layer
- Data formatting, encryption, compression
- Prepares data for the application layer

---

### 🔹 Layer 7 – Application Layer
- User interaction layer
- Provides services like:
  - HTTP
  - FTP
  - SMTP
  - DNS
- Works with application-level protocols and ports

---

## 🧩 OSI Layer Groups

### 🔵 Upper Layers (Application Support)
- Layer 7 → Application  
- Layer 6 → Presentation  
- Layer 5 → Session  

### 🔵 Lower Layers (Network Support)
- Layer 4 → Transport  
- Layer 3 → Network  
- Layer 2 → Data Link  
- Layer 1 → Physical  

---

## 🧠 Summary
The OSI model divides network communication into 7 layers to simplify understanding, troubleshooting, and design of networks. Each layer has a specific role in how data is transmitted from user to physical medium.
