# Network Security CORE Labs 

![Ubuntu](https://img.shields.io/badge/Ubuntu-24.04-E95420?logo=ubuntu&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Tools-FCC624?logo=linux&logoColor=black)
![CORE](https://img.shields.io/badge/CORE-Emulator-2E77BC)
![VirtualBox](https://img.shields.io/badge/VirtualBox-Lab-183A61?logo=virtualbox&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-Packet%20Analysis-1679A7?logo=wireshark&logoColor=white)
![OpenSSL](https://img.shields.io/badge/OpenSSL-TLS%2FDTLS-721412?logo=openssl&logoColor=white)
![SSH](https://img.shields.io/badge/SSH-Hardening%20%26%20Tunnels-000000?logo=gnu-bash&logoColor=white)
![iptables](https://img.shields.io/badge/iptables-Firewall%20%26%20NAT-4B5563)
![dnsmasq](https://img.shields.io/badge/dnsmasq-DHCP%20%26%20DNS-4B5563)
![aircrack-ng](https://img.shields.io/badge/aircrack--ng-WEP%2FWPA%20Labs-4B5563)

A curated set of hands-on network security labs documented as **PDF write-ups with screenshots and validations**.  
The emphasis is on practical configuration, testing, and **packet-level evidence** (Wireshark/tcpdump), using CORE Emulator.

---

## What I practiced
- DoS traffic generation and analysis (hping3) + protocol inspection (Wireshark)
- DHCP + dnsmasq configuration, isolation, and validation in emulated networks
- TLS/DTLS using OpenSSL (s_server/s_client) + handshake analysis in Wireshark
- IPsec AH/ESP using setkey (transport + tunnel modes), verified via packet captures
- SSH hardening + tunneling (local and reverse port forwarding) + traffic validation
- Firewalling and NAT with iptables, including counters/statistics and test traffic generation
- Wireless security labs (WEP/WPA) using aircrack-ng (sanitized outputs)

---

## Lab environment
- 🧪 Emulator: CORE (Common Open Research Emulator)
- 🐧 OS: Ubuntu (VirtualBox)
- 🦈 Traffic analysis: Wireshark / tcpdump
- 🔐 Crypto: OpenSSL, IPsec (setkey)
- 🧱 Network controls: iptables, dnsmasq
- 📡 Wireless: aircrack-ng (sanitized)

---

## Labs (PDF write-ups)
- [00 - CORE Installation (PDF)](labs/00-core-installation/Lab-00-CORE-Installation.pdf)
- [01 - DoS Traffic Analysis (hping3 + Wireshark) (PDF)](labs/01-dos-traffic-analysis-hping3-wireshark/Lab-01-DoS-Traffic-Analysis.pdf)
- [02 - DHCP + dnsmasq (Isolation + Wireshark validation) (PDF)](labs/02-dhcp-dnsmasq-isolation-wireshark/Lab-02-DHCP-dnsmasq-Isolation.pdf)
- [03 - TLS/DTLS (OpenSSL + Wireshark) (PDF)](labs/03-tls-dtls-openssl-wireshark/Lab-03-TLS-DTLS-OpenSSL.pdf)
- [04 - IPsec AH/ESP (setkey: transport + tunnel) (PDF)](labs/04-ipsec-ah-esp-setkey-transport-tunnel/Lab-04-IPsec-AH-ESP-setkey.pdf)
- [05 - SSH Tunneling + Port Forwarding (netcat over SSH) (PDF)](labs/05-ssh-tunneling-port-forwarding-netcat/Lab-05-SSH-Tunneling-Port-Forwarding.pdf)
- [06 - Firewall + NAT (iptables, counters, load balancing) (PDF)](labs/06-firewall-iptables-nat-loadbalancing-ddos/Lab-06-Firewall-NAT-iptables.pdf)
- [07 - Wireless (WEP/WPA cracking – sanitized) (PDF)](labs/07-wireless-wep-wpa-aircrack/Lab-07-Wireless-WEP-WPA-sanitized.pdf)

---

## Notes on sanitization and responsible use
- Wireless lab outputs are sanitized and intended for authorized, lab-only environments.
- Any credentials, private keys, and sensitive identifiers are removed or masked in the documentation.

---

## How to navigate
1. Start with **Lab 00** to reproduce the environment.
2. Open any lab PDF for full steps, screenshots, and validation evidence.
