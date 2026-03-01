# Module 5: Networking Fundamentals

> Core networking concepts including LAN/WAN, wireless standards, addressing, virtualization, and cloud computing.

---

# 1. Network Types

## LAN (Local Area Network)
- Covers small geographic area (home, office, building)
- High speed
- Privately managed

## WAN (Wide Area Network)
- Connects multiple LANs
- Large geographic coverage
- Often ISP-managed

## PAN (Personal Area Network)
- Very short range (e.g., Bluetooth devices)

---

# 2. Network Devices

## Router
- Connects LAN to WAN
- Routes traffic between networks
- Often includes firewall + Wi-Fi

## Switch
- Connects devices inside a LAN
- Uses MAC addresses
- Can be managed or unmanaged
- May support VLANs and PoE

## Modem
- Converts digital signals ↔ analog signals
- Connects network to ISP

## Access Point (AP)
- Provides wireless access to wired network
- Multiple APs = extended wireless coverage

---

# 3. Network Media & Tools

## Cable Types
- Twisted Pair (Cat5e, Cat6)
- Coaxial
- Fiber optic

## Tools
- Crimping tool – attach RJ45 connector
- Punch down tool – terminate cables to patch panel
- Cable tester – verify cable functionality
- Tone generator & probe – locate cables

---

# 4. Network Addressing

## MAC Address
- 48-bit physical address
- Assigned to NIC
- Hexadecimal format
- Used within LAN

## IP Address

### IPv4
- 32-bit
- Example: 192.168.1.1
- ~4 billion addresses

### IPv6
- 128-bit
- Massive address space
- Hexadecimal format

### Assignment
- Static (manual)
- Dynamic (DHCP)

---

# 5. Network Ports (CompTIA Important)

| Port | Protocol | Purpose |
|------|----------|----------|
| 21   | FTP      | File Transfer |
| 22   | SSH      | Secure Remote Access |
| 23   | Telnet   | Unsecure Remote Access |
| 25   | SMTP     | Sending Email |
| 53   | DNS      | Name Resolution |
| 80   | HTTP     | Web Traffic |
| 443  | HTTPS    | Secure Web |

---

# 6. Wireless Networking

## Frequency Bands

### 2.4 GHz
- Longer range
- Slower
- More interference

### 5 GHz
- Faster
- Shorter range
- Less congestion

### 6 GHz (Wi-Fi 6E)
- Higher speeds
- More channels
- Modern devices required

---

## Wi-Fi Standards (IEEE 802.11)

| Standard | Band |
|----------|------|
| 802.11b/g | 2.4 GHz |
| 802.11n | 2.4 / 5 GHz |
| 802.11ac | 5 GHz |
| 802.11ax (Wi-Fi 6/6E) | 2.4 / 5 / 6 GHz |

---

## Wireless Security

### WEP
- Deprecated
- Easily cracked

### WPA / WPA2
- AES encryption
- Secure standard

### WPA3
- Strongest modern security
- Recommended

---

# 7. Network Performance

## Latency (Ping)
- Measured in milliseconds (ms)
- Lower = better
- Important for gaming & VoIP

## Signal Problems

### Attenuation
- Signal weakens over distance

### Interference
- Caused by microwaves, phones, nearby Wi-Fi

---

# 8. Network Models

## Client-Server
- Dedicated server
- Centralized management
- Enterprise standard

## Peer-to-Peer
- No dedicated server
- Small networks only

---

# 9. Virtualization

## What It Does
- Runs multiple OS on one physical machine
- Uses Virtual Machines (VMs)

## Components
- Host machine
- Hypervisor
- Guest OS

## Hypervisor Types

### Type 1 (Bare Metal)
- Installed directly on hardware
- Enterprise use

### Type 2
- Installed on host OS
- Used for labs and learning

---

# 10. Cloud Computing

## Service Models

### SaaS
- Software via browser
- Provider manages everything

### PaaS
- Development platform
- No hardware management

### IaaS
- Rent servers, storage, networking

---

## Deployment Models

- Public Cloud
- Private Cloud
- Hybrid Cloud
- On-Premises

---

# Key Takeaways

- Routers connect networks; switches connect devices.
- MAC = physical address, IP = logical address.
- WPA3 is current Wi-Fi security standard.
- Latency affects real-time applications.
- Virtualization enables efficient hardware usage.
- Cloud computing reduces hardware ownership costs.

---

**End of Module 5**
