# Kali NetHunter on Samsung Galaxy S9 (No Monitor Mode)

This project documents the setup, usage, and tools available on a **Samsung Galaxy S9** running **Kali NetHunter**, specifically in a setup **without monitor mode** (due to unsupported WiFi chipset or kernel limitations).

---

## 📱 Device Info

- **Device**: Samsung Galaxy S9 (codename: `starlte`)
- **NetHunter Type**: Full version
- **WiFi Mode**: No Monitor Mode support
- **Kernel**: LineageOS-based custom kernel

---

## ✅ Tools That Work Without Monitor Mode

Even without monitor mode, many powerful tools still work for recon, exploitation, and network manipulation:

### 🛰️ Networking & Recon
- `nmap` – Network scanning and port enumeration
- `netdiscover` – ARP-based live host detection
- `whois` – Domain/IP information
- `dnsenum`, `dnsrecon` – DNS recon
- `recon-ng` – Recon framework
- `theHarvester` – Email, domain, and name harvesting

### 🔐 Password & Bruteforce
- `hydra` – Brute force login (FTP, SSH, HTTP, etc.)
- `medusa` – Fast brute force tool
- `john` – Password cracking
- `hashcat` – GPU-accelerated password cracker (if supported)

### 🧠 Exploitation & Social Engineering
- `metasploit-framework` – Full exploitation framework
- `msfvenom` – Payload generator
- `evilginx2` – Phishing & man-in-the-middle attack platform
- `social-engineer-toolkit (SET)` – Social engineering attacks

### 🧰 Network Manipulation & MITM
- `bettercap` – MITM framework (works without monitor mode if using ARP spoofing)
- `sslstrip` – HTTPS downgrade attacks
- `ettercap` – ARP poisoning and sniffing

### 📡 Wireless Recon (Limited)
- `wifite` (limited function)
- `airmon-ng`, `airodump-ng` – Can list interfaces, but monitor mode not available
- `Wifipumpkin3` – Fake AP, captive portal attacks (⚠️ monitor not required, but works better with)

---

## 🚫 Limitations

- ❌ `aircrack-ng`, `airodump-ng`, `aireplay-ng`: Limited or **not usable** without monitor mode
- ❌ `fluxion`: Not usable without monitor mode
- ❌ Wireless packet injection not available

---

## 🛠️ Workarounds / Suggestions

- Use an **external USB WiFi adapter** that supports monitor mode + OTG
- Combine with **Raspberry Pi** as a remote pentesting node via SSH
- Focus on social engineering, phishing, or internal network attacks via USB Ethernet

---

## 📸 Screenshots

*(Add your terminal screenshots, tool outputs, or NetHunter GUI here if you’d like)*

---

## 🧠 Credits

This setup and usage guide was created by [Nguyen Van Khang](https://github.com/vankhangk4) for the Vietnamese pentesting community.
****
