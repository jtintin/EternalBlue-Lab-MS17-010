# 🛡️ EternalBlue Lab – Exploiting MS17-010 with Metasploit

This lab demonstrates the full exploitation process of the **MS17-010 (EternalBlue)** vulnerability in a Windows 7 SP1 virtual machine using Kali Linux tools.

## 🔧 Tools Used
- Kali Linux
- Metasploit Framework
- Nmap
- ARP-Scan
- Ping
- Windows 7 SP1 (vulnerable)

## 📋 Steps Performed
1. Network reconnaissance (`ip add`, `arp-scan`)
2. OS fingerprinting via TTL (`ping`)
3. Port and service scanning (`nmap`)
4. Vulnerability detection (`nmap --script vuln`)
5. Exploitation with Metasploit (`ms17_010_eternalblue`)
6. Remote access via Meterpreter

## 📸 Evidence
See `/evidencias` folder for screenshots of each step.

## 📄 Technical Report
PDF report available in `/informe-tecnico`.

## 🧠 Key Learnings
- Identifying vulnerable systems in a local network
- Using Metasploit for controlled exploitation
- Writing clear technical documentation
