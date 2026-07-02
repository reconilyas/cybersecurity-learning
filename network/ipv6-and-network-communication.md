# IPv6 & Network Communication

---

## 🌍 IPv6 Basics

IPv6 is the successor to IPv4 and provides a much larger address space.

### Characteristics
- 128-bit address length
- Written in hexadecimal
- Divided into **8 groups**
- Each group contains **4 hexadecimal digits (16 bits)**

Example:

A470:0000:A2F5:0000:7E5A:0000:0000:0000

---

## IPv6 Address Rules

### Leading Zeros
Leading zeros in any group can be omitted.

Example:

2001:0DB8:0000:0001

becomes

2001:DB8:0:1

---

### Consecutive Zeros

One consecutive sequence of zero groups can be replaced with `::`.

Example:

2001:0DB8:0000:0000:0000:FF00:0042:8329

becomes

2001:DB8::FF00:42:8329

> Note: `::` can only be used **once** in a single IPv6 address.

---

## Network Communication Modes

### Simplex
- One-way communication only
- Example: FM radio

---

### Half-Duplex
- Communication in both directions, but only one direction at a time
- Example: Walkie-talkie

---

### Full-Duplex
- Devices can transmit and receive simultaneously
- Example: Telephone call

---

## Connection Services

### Connectionless Service
- No connection is established before sending data
- Faster, but delivery is not guaranteed
- Example: UDP

---

### Connection-Oriented Service
- A connection is established before data transmission
- Reliable communication with acknowledgments
- Example: TCP

---

## 🧠 Summary

IPv6 expands the available IP address space by using 128-bit hexadecimal addresses. Understanding IPv6 notation, communication modes, and connection services is essential for modern networking and cybersecurity.
