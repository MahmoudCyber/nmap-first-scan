# Nmap First Scan Report

## 1. Scan Command
nmap -sV 192.168.1.1

## 2. Scan Date
2025-08-11

## 3. Scan Result
PORT     STATE  SERVICE    VERSION
80/tcp   open   http       Apache httpd 2.4.29
443/tcp  open   https      OpenSSL 1.1.1
22/tcp   open   ssh        OpenSSH 7.6p1 Ubuntu 4ubuntu0.3

## 4. Analysis
- Port 80: Website running Apache 2.4.29, which may be outdated and could require an update.
- Port 443: Secure connection using OpenSSL 1.1.1, version appears to be up-to-date.
- Port 22: SSH service is open, ensure strong authentication is in place.

## 5. Conclusion
The scan revealed three open services, some of which may need security updates. The next step will be to check for potential vulnerabilities in these versions.
