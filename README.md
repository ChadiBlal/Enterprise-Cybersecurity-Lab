[OCP-cybersecurity-lab-README.md](https://github.com/user-attachments/files/31081105/OCP-cybersecurity-lab-README.md)
# Enterprise Cybersecurity Laboratory

A documented enterprise-style cybersecurity laboratory developed during a technical internship. The project combines virtualized infrastructure, network services, centralized monitoring, intrusion detection, identity management, secure remote access, and system hardening in an isolated environment.

> This repository contains sanitized documentation and screenshots for educational and portfolio purposes. No credentials, private keys, passwords, or confidential company information are included.

## Architecture

![Cybersecurity laboratory architecture](assets/security_architecture.png)

The laboratory is organized into three main areas:

- **Production services:** Apache, PHP, MySQL, Samba, SSH, FTP, and DNS.
- **Security management hub:** Wazuh, Suricata, OpenLDAP, OpenVPN, Elasticsearch, and the Wazuh Dashboard.
- **Windows services:** Windows-based services monitored through security agents and network controls.

## Implemented Components

- Designed and configured an isolated virtual laboratory using VMware, Ubuntu, and Windows.
- Configured essential network and application services, including DNS, SSH, FTP, SMB, Apache, PHP, and MySQL.
- Deployed Wazuh for centralized security monitoring and agent management.
- Configured Suricata for intrusion detection and network-traffic analysis.
- Integrated OpenLDAP for centralized identity and authentication management.
- Configured OpenVPN for controlled and secure remote access.
- Applied system-hardening measures, access controls, secure HTTP headers, service restrictions, and permission controls.
- Tested the services and documented the architecture, configurations, and validation results.

## Selected Evidence

### Wazuh Monitoring

![Wazuh monitoring](assets/wazuh_agents.png)

### Suricata Monitoring

![Suricata monitoring](assets/suricata_monitoring.png)

## Technologies

`VMware` `Ubuntu` `Windows` `Wazuh` `Suricata` `OpenLDAP` `OpenVPN` `Apache` `PHP` `MySQL` `DNS` `SSH` `FTP` `Samba` `Linux Administration` `Network Security`

## Skills Demonstrated

This project strengthened practical skills in Linux administration, virtual-machine deployment, network-service configuration, SIEM monitoring, intrusion detection, identity management, VPN deployment, system hardening, and technical documentation.

## Responsible Use and Privacy

This project was developed and tested in an isolated laboratory environment. The repository must contain only sanitized diagrams, generic configuration examples, and non-sensitive screenshots. Internal company information, credentials, private IP addresses, VPN secrets, private keys, and proprietary documentation must not be published.

## Author

**Chadi Blal**

- GitHub: [@ChadiBlal](https://github.com/ChadiBlal)
- LinkedIn: www.linkedin.com/in/chadi-blal-01817236a
