# Basic Network Scanning Using Nmap

## OASIS INFOBYTE – Cyber Security Internship

### Task 1: Basic Network Scanning

**Name:** Sarvesh Mishra

**Track:** Cyber Security

**Task:** Basic Network Scanning Using Nmap

**Operating System:** Windows 11

**Tool Used:** Nmap 7.99

---

# 1. Objective

The objective of this project is to perform basic network reconnaissance using Nmap to identify open ports, running services, and operating system details on a Windows system.

---

# 2. Tools Used

- Windows 11
- Nmap 7.99
- Command Prompt

---

# 3. Commands Executed

### Check Nmap Version

```cmd
nmap --version
```

### Find Local IP Address

```cmd
ipconfig
```

### Basic Port Scan

```cmd
nmap 10.251.148.69
```

### Service Detection

```cmd
nmap -sV 10.251.148.69
```

### Operating System Detection

```cmd
nmap -O 10.251.148.69
```

### Save Scan Results

```cmd
nmap 10.251.148.69 -oN scan_results.txt
```

---

# 4. Scan Results

The Nmap scan completed successfully.

### Open Ports

| Port | State | Service |
|------|-------|---------|
| 135 | Open | msrpc |
| 139 | Open | netbios-ssn |
| 445 | Open | microsoft-ds |

### Observations

- Host was online and reachable.
- 997 TCP ports were closed.
- Three TCP ports were open.
- The detected services are commonly used by Microsoft Windows for remote procedure calls and file sharing.
- OS detection was attempted successfully.

---

# 5. Security Recommendations

- Keep Windows Firewall enabled.
- Disable unnecessary file sharing if not required.
- Regularly install Windows security updates.
- Restrict SMB access to trusted networks.
- Use strong passwords and enable multi-factor authentication where possible.

---

# 6. Conclusion

This project demonstrated the use of Nmap for basic network scanning on a Windows system. The scan identified active services and open ports, providing useful information for assessing the security posture of the host.

---

# References

1. https://nmap.org
2. https://nmap.org/book/
