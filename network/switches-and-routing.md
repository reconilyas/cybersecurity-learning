# Switches & Routing Fundamentals

---

# The Switch

A switch is an Ethernet networking device that connects multiple devices within a Local Area Network (LAN).

Unlike a hub, a switch forwards data only to the intended destination.

### Characteristics
- Uses MAC addresses
- Connects multiple devices in a LAN
- Reduces unnecessary network traffic
- Improves network performance

---

## Multilayer Switch

A multilayer switch operates at both:

- Layer 2 (Data Link Layer)
- Layer 3 (Network Layer)

It can make forwarding decisions using:
- MAC addresses
- IP addresses

---

## Content Switch

A content switch forwards traffic based on the content of network packets instead of only IP addresses.

### Purpose
- Distributes requests to the appropriate server
- Improves performance and availability
- Often used as a load-balancing device

---

# Routing

## Router

A router connects different networks and forwards packets between them.

### Functions
- Routes traffic between networks
- Maintains a routing table
- Uses ARP to resolve IP addresses into MAC addresses on local networks

---

## Static Routing

Static routing uses manually configured routes.

### Characteristics
- Routing table is configured manually
- Simple to implement in small networks
- Can lead to errors if routes are configured incorrectly
- Does not automatically adapt to network changes

---

# Routing Terms

## Hop Count
The number of routers (hops) a packet passes through before reaching its destination.

---

## Cost
A routing metric that represents the preferred path.

Lower cost usually means a better route.

---

## Latency
The time required for data to travel from the source to the destination.

Lower latency means faster communication.

---

## Convergence
The process of updating routing tables after a network change.

A network is considered converged when all routers have accurate and consistent routing information.

---

## 🧠 Summary

Switches manage communication within a local network using MAC addresses, while routers connect different networks using IP addresses. Understanding switching, routing, and routing metrics is fundamental for networking and cybersecurity.
