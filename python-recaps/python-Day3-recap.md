# Python DAY 3 Recap

- Created a Python script to check if a given port is well-known (e.g., 22 for SSH, 80 for HTTP).
- Used dictionaries to map port numbers to service names.
- Practiced input, conditional logic, and simple error handling.

## Example Code

```python
known_ports = {
    21: 'FTP port',
    22: 'SSH port',
    23: 'Telnet port',
    25: 'SMTP port',
    53: 'DNS port',
    80: 'HTTP port',
    110: 'POP3 port',
    143: 'IMAP port',
    443: 'HTTPS port',
    3389: 'RDP port'
}

def port_get():
    port = int(input("What is your port? "))
    if port in known_ports:
        print(f"That's {known_ports[port]}!")
    else:
        print("Unknown port")

port_get()

**What was easy**
- Working with dictionaries, basic input/output.

**What was tricky**
- Handling cases when the port is not found, and using get() method.

**What I learned**
- How to use Python for simple automation in networking/security tasks.