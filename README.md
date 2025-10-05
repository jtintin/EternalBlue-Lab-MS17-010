# 🛡️ EternalBlue Lab – Exploiting MS17-010 with Metasploit

> 🇬🇧 English version below | 🇪🇸 Versión en español más abajo

---

## 🇪🇸 Versión en Español

### 🧠 Descripción
Este laboratorio demuestra el proceso completo de explotación de la vulnerabilidad **MS17-010 (EternalBlue)** en una máquina virtual con Windows 7 SP1, utilizando herramientas como Nmap, ARP-Scan y Metasploit en Kali Linux.

### 🔧 Herramientas utilizadas
- Kali Linux
- Metasploit Framework
- Nmap
- ARP-Scan
- Ping
- Windows 7 SP1 (vulnerable)

### 📋 Pasos realizados
1. Reconocimiento de red (`ip add`, `arp-scan`)
2. Identificación del sistema operativo (`ping`)
3. Escaneo de puertos y servicios (`nmap`)
4. Detección de vulnerabilidades (`nmap --script vuln`)
5. Explotación con Metasploit (`ms17_010_eternalblue`)
6. Acceso remoto con Meterpreter

### 📸 Evidencias
Ver carpeta `evidencias/` para capturas del proceso.

### 📄 Informe técnico
PDF disponible en la carpeta `informe-tecnico/`.

### 🧠 Aprendizajes clave
- Identificación de sistemas vulnerables en red local
- Uso de Metasploit en entorno controlado
- Redacción de informes técnicos

---

## 🇬🇧 English Version

### 🧠 Description
This lab demonstrates the full exploitation process of the **MS17-010 (EternalBlue)** vulnerability in a Windows 7 SP1 virtual machine using tools like Nmap, ARP-Scan, and Metasploit in Kali Linux.

### 🔧 Tools Used
- Kali Linux
- Metasploit Framework
- Nmap
- ARP-Scan
- Ping
- Windows 7 SP1 (vulnerable)

### 📋 Steps Performed
1. Network reconnaissance (`ip add`, `arp-scan`)
2. OS fingerprinting via TTL (`ping`)
3. Port and service scanning (`nmap`)
4. Vulnerability detection (`nmap --script vuln`)
5. Exploitation with Metasploit (`ms17_010_eternalblue`)
6. Remote access via Meterpreter

### 📸 Evidence
See `evidencias/` folder for screenshots of each step.

### 📄 Technical Report
PDF report available in `informe-tecnico/`.

### 🧠 Key Learnings
- Identifying vulnerable systems in a local network
- Using Metasploit for controlled exploitation
- Writing clear technical documentation
