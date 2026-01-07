# CORE - Network Security Labs 

Hands-on network security labs documented as **PDF write-ups** with screenshots and validation evidence.  
Focus: configuration → testing → proof via packet captures, counters, and protocol inspection.

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

### Platform and Emulator
<p align="left">
  <img src="https://cdn.simpleicons.org/ubuntu/E95420" height="42" alt="Ubuntu" />
  <img src="https://cdn.simpleicons.org/linux/FCC624" height="42" alt="Linux" />
  <img src="https://cdn.simpleicons.org/virtualbox/183A61" height="42" alt="VirtualBox" />
  <img src="https://img.shields.io/badge/CORE-Emulator-2E77BC?style=for-the-badge" height="42" alt="CORE Emulator" />
</p>

### Traffic Analysis and Validation
<p align="left">
  <img src="https://cdn.simpleicons.org/wireshark/1679A7" height="42" alt="Wireshark" />
  <img src="https://img.shields.io/badge/tcpdump-Traffic%20Capture-111827?style=for-the-badge" height="42" alt="tcpdump" />
</p>

### Security Tooling
<p align="left">
  <img src="https://cdn.simpleicons.org/openssl/721412" height="42" alt="OpenSSL" />
  <img src="https://img.shields.io/badge/iptables-Firewall%20%26%20NAT-374151?style=for-the-badge" height="42" alt="iptables" />
  <img src="https://img.shields.io/badge/dnsmasq-DHCP%20%26%20DNS-374151?style=for-the-badge" height="42" alt="dnsmasq" />
  <img src="https://img.shields.io/badge/hping3-Test%20Traffic-374151?style=for-the-badge" height="42" alt="hping3" />
  <img src="https://img.shields.io/badge/IPsec-setkey%20(AH%2FESP)-374151?style=for-the-badge" height="42" alt="setkey / IPsec" />
  <img src="https://img.shields.io/badge/aircrack--ng-WEP%2FWPA%20Labs-374151?style=for-the-badge" height="42" alt="aircrack-ng" />
</p>

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

## Quick navigation
Start with **Lab 00** to reproduce the environment, then open any lab PDF for full steps, screenshots, and validation evidence.
