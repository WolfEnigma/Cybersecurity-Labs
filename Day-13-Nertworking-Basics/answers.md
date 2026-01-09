# Answers: Network Concepts

### 1. What is the role of DNS?
DNS (Domain Name System) translates human-readable domain names (like `google.com`) into machine-readable IP addresses (like `142.250.185.78`). Without DNS, we would need to remember numerical IP addresses for every website.

### 2. Why does `ping` sometimes fail?
- **Firewall blocking**: ICMP packets (used by ping) are often blocked.
- **Network issues**: Router problems, cable disconnection, or ISP outage.
- **Destination down**: The target server or website is offline.
- **DNS failure**: Cannot resolve the domain name to an IP address.

### 3. Difference between private and public IP
| Private IP | Public IP |
|------------|-----------|
| Used inside a local network | Used on the Internet |
| Not unique (can be reused) | Globally unique |
| Ranges: `10.x.x.x`, `192.168.x.x`, `172.16.x.x`-`172.31.x.x` | Any IP not in private ranges |
| Not routable on Internet | Routable on Internet |
| Assigned by your router | Assigned by your ISP |

### 4. Why attackers scan ports before attacks?
Port scanning identifies **open ports** and **running services** on a target system. This helps attackers:
- Find vulnerable services to exploit
- Identify the operating system and software versions
- Map the network structure
- Discover security weaknesses before launching targeted attacks

### 5. Why cloud servers rely heavily on networking?
Cloud servers are entirely dependent on networking because:
- **No physical access**: All management is remote via network
- **Distributed architecture**: Services span multiple servers/data centers
- **Scalability**: Load balancing and auto-scaling require robust networks
- **Redundancy**: Data replication across regions needs high-speed connections
- **Service delivery**: Cloud services (SaaS, PaaS, IaaS) are delivered over the Internet
