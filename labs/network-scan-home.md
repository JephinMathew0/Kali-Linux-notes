# Network Scan – Local Environment

## 🎯 Objective
To discover devices and open ports within a local network.

---

## 🛠️ Tool Used
- Nmap

---

## ⚙️ Commands Used

### 1. Discover live hosts
nmap -sn 192.168.1.0/24

### 2. Scan specific device
nmap -sV 192.168.1.1

---

## 📊 Findings
- Multiple devices detected on network
- Router identified at 192.168.1.1
- Open ports: 80 (HTTP), 443 (HTTPS)

---

## 🔍 Analysis
This scan helps identify active devices and services running in a local network environment.

---

## 🧠 Conclusion
Local network scanning is essential for understanding network structure and identifying potential security risks.
