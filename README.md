# Network Scanning using Nmap

## Internship Task Submission

This repository contains my internship task on network reconnaissance using **Nmap**. The objective of this task was to identify active hosts, discover open ports, and analyze the services running on a target machine in a controlled environment.

## Objective

* Perform network scanning using Nmap.
* Identify live hosts.
* Discover open TCP ports.
* Analyze exposed network services.
* Document the findings.

## Tools Used

* **Nmap 7.95**
* Operating System: **[Your OS]**
* Target Environment: **Local Virtual Network / Lab Environment**

## Scan Command

```bash
nmap 192.168.56.1
```

## Scan Results

| Port | State | Service                 |
| ---- | ----- | ----------------------- |
| 135  | Open  | MSRPC                   |
| 139  | Open  | NetBIOS Session Service |
| 445  | Open  | Microsoft-DS (SMB)      |

### Observations

* The target host is reachable.
* Three TCP ports were found open.
* The exposed services indicate the target is likely running a Windows operating system.
* Most other TCP ports were filtered, suggesting firewall protection.

## Project Structure

```text
.
├── README.md
├── scan-results/
│   └── nmap_scan.txt
└── screenshots/
    └── scan_output.png
```

## Learning Outcomes

* Understanding of basic network reconnaissance.
* Familiarity with Nmap scanning techniques.
* Interpretation of port scan results.
* Identification of common Windows network services.

## Disclaimer

This project was performed in a controlled lab environment for educational and internship purposes only. All scans were conducted on systems for which authorization was granted.

## Author

**Your Name**

GitHub: https://github.com/gokul-cyber-77
