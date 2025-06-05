# Networking DAY 3 Recap

- Practiced basic Linux networking commands to inspect interfaces, routes, DNS, and connectivity.
- Tested local, LAN, and Internet connectivity in a VirtualBox VM.

## Example Commands

```bash
ip a                # Show network interfaces and IP addresses
ip route            # Show routing table
cat /etc/resolv.conf   # Show DNS server config

ping 127.0.0.1      # Test local loopback
ping 8.8.8.8        # Test external connectivity (Google DNS)
ping google.com     # Test DNS and network
traceroute 8.8.8.8  # Show path to an external IP (if installed)

```

**What was easy**
- Checking IP addresses, gateways, and using ping to test connectivity.

**What I learned**
- How to check and interpret network configuration in Linux.

- The basics of NAT in VirtualBox (example: my IP is 10.0.2.15, gateway is 10.0.2.2).

- How to troubleshoot network issues and read outputs of key networking tools.