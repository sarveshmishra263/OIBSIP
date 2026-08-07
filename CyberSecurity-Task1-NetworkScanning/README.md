# Basic Network Scanning Using Nmap

## OASIS INFOBYTE – Cyber Security Internship

### Task 1

This project demonstrates how to perform basic network scanning using Nmap on a Windows 11 system. The scan identifies active hosts, open ports, running services, and operating system information.

## Objective

To understand the fundamentals of network reconnaissance by using Nmap to identify network services and analyze open ports on a local machine.

## Tools Used

- Windows 11
- Nmap 7.99
- Command Prompt

## Commands Used

### Check Nmap Version

```cmd
nmap --version
```

### Find IP Address

```cmd
ipconfig
```

### Basic Scan

```cmd
nmap <IP_ADDRESS>
```

### Service Detection

```cmd
nmap -sV <IP_ADDRESS>
```

### OS Detection

```cmd
nmap -O <IP_ADDRESS>
```

### Save Scan Results

```cmd
nmap <IP_ADDRESS> -oN scan_results.txt
```

## Project Files

| File | Description |
|------|-------------|
| README.md | Project overview |
| Report.md | Detailed project report |
| scan_results.txt | Nmap scan output |
| screenshots | Screenshots of execution |

## Author

**Sarvesh Mishra**

## Internship

OASIS INFOBYTE – Cyber Security Internship
