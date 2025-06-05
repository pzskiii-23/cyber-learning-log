# Basic Networking Commands (Linux)

## IP and Routes

```bash
ip a         # Show network interfaces and IP addresses
ip route     # Show routing table
cat /etc/resolv.conf   # Show DNS server config
```

## Connectivity Testing

```bash
ping 127.0.0.1       # Test local loopback
ping 8.8.8.8         # Test external connectivity (Google DNS)
ping google.com      # Test DNS and network
traceroute 8.8.8.8   # Show path to an external IP (if installed)
```

**What I learned:**
- How to check network configuration in a Linux VM.
- How NAT works in VirtualBox (my IP: 10.0.2.15, gateway: 10.0.2.2).
- How to test local, LAN, and Internet connectivity.
- How to interpret ping and traceroute results.

**What was tricky:**
- Understanding why traceroute in VirtualBox NAT doesn't show full route (expected in labs).
- Reading and understanding `/etc/resolv.conf` and how DNS is managed.

**Summary:**
Mastering these basic network commands is crucial for any IT/cybersecurity role. They are the foundation for troubleshooting and verifying connectivity in any environment.
