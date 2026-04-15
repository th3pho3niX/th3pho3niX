# Phoenix Kern

IT Specialist in Training (System Integration) - building a modular security homelab for hands-on experience in network security, monitoring, and automation.

---

## About

I'm currently completing a retraining program (Umschulung) as a Fachinformatiker for System Integration at GFN GmbH in Freiburg, Germany. My focus areas are network infrastructure, system administration, and IT security.

Outside of coursework, I run a multi-node homelab that serves as a practical environment for security monitoring, threat detection, and workflow automation. The lab is fully documented and version-controlled.

**Certifications:** Google Cybersecurity Certificate · Cisco Cybersecurity Essentials · TryHackMe Cybersecurity 101 · Scrum Master

**Currently working toward:** Cisco CyberOps Associate · CompTIA Security+ · TryHackMe SOC Level 1

---

## Homelab Architecture

A segmented network environment built for security operations and automation:

- **Firewall / Router:** Mini-PC (Intel N100) running OPNsense — VLAN management, Suricata IDS/IPS, DNS, VPN
- **Security Core (Raspberry Pi 5):** Wazuh Manager, Suricata, Zeek, Pi-hole, n8n automation
- **VPN Bastion (Raspberry Pi 4):** WireGuard, Fail2Ban, SSH-key-only access
- **Analysis Workstation (MacBook Pro):** Wireshark, Volatility, Autopsy, Kali/Parrot VMs
- **Dev / Documentation (Acer TravelMate):** Obsidian, GitHub, VS Code, Ollama (local LLMs)

All workflows are documented in Obsidian and versioned through GitHub. Automation pipelines run via n8n with Markdown export, hash validation, and Telegram alerting.

---

## Projects

### macbook-ubuntu-t2
Ubuntu 24.04 LTS installation on MacBook Pro 2018 (T2 chip) — covers T2 drivers, LUKS encryption, WLAN firmware, fan control, and performance logging.
→ [Repository](https://github.com/th3pho3niX/macbook-ubuntu-t2)

### Homelab Documentation *(in progress)*
Structured guides covering the full homelab stack: network architecture, security zones, n8n workflows, coding standards, incident response playbooks, and system glossary.

---

## Tools & Technologies

**Infrastructure:** OPNsense · Ubuntu Server · Raspberry Pi · Docker · Ansible  
**Security / SIEM:** Wazuh · Suricata · Zeek · Pi-hole · OpenVAS  
**Forensics:** Wireshark · Volatility 3 · Autopsy · Sysmon  
**Automation:** n8n · Python · Bash · GitHub Actions  
**Documentation:** Obsidian · Markdown · Git  

---

## Contact

- LinkedIn: [phoenix-kern](https://www.linkedin.com/in/phoenix-kern/)
- TryHackMe: [pho3niX](https://tryhackme.com/p/pho3niX)
