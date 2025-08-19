# NetPractice 

<img width="850" height="500" alt="image" src="https://github.com/user-attachments/assets/c0dd5a86-f841-4924-874a-ee4a35126933" />

### Description

NetPractice is a 42 project that teaches networking basics through practical exercises. It involves configuring small-scale networks to enable device communication using IPv4 addresses, subnet masks, and routing tables. The project consists of 10 levels, each focusing on IP allocation, subnetting, and routing to ensure proper connectivity without overlaps.


### Key Concepts

- **IP Address**: Identifies devices on a network (IPv4, e.g., `192.168.1.1`). Split into network and host parts.
- **Subnet Mask**: Defines network and host portions (e.g., `255.255.255.0` or `/24`). Determines IP range.
- **Switch**: Connects devices within the same network.
- **Router**: Links multiple networks, with interfaces having non-overlapping IP ranges.
- **Routing Table**: Specifies packet destinations (e.g., `0.0.0.0/0` for default) and next-hop addresses.

### Usage

#### Requirements
- Web-based interface (provided by 42)
- Browser (preferably Google Chrome)

#### Instructions
1. Open the NetPractice interface:
   ```shell
   cd path/to/netpractice && open index.html
   ```
2. Enter your username and configure IP addresses, subnet masks, and routing tables for each level.

#### Example
To connect two clients in the same network:
- Assign IPs like `104.96.23.1` and `104.96.23.2` with mask `/24`.
- Exclude network (`104.96.23.0`) and broadcast (`104.96.23.255`) addresses.

### Levels Overview

- **Level 1**: Assign IPs in the same network.
- **Level 2**: Use CIDR notation (e.g., `/30`) for subnet masks.
- **Level 3**: Configure switches for single-network setups.
- **Level 4**: Set up routers for multi-network communication.
- **Level 5**: Use default routes in routing tables.
- **Level 6**: Connect to the internet with public IPs.
- **Level 7**: Avoid IP range overlaps.
- **Level 8**: Subdivide network ranges for multiple devices.
- **Level 9**: Configure complex routing for internet access.
- **Level 10**: Manage large networks with non-overlapping ranges.

### Notes

- No compilation is required; the project uses a web-based interface for configuration.
- Adheres to 42's Norm, focusing on manual configuration without restricted function limits.
