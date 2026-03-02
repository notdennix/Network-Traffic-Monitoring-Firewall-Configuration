****🎯**Objectives** 

To simulate a real world network environment to:

- monitor and analyze traffic using Security onion
- configure and manage firewall rules via pfSense
- generate test traffic and simulate attacks using kali Linux

🛠️ Tools & Technologies Used

- **Virtualization:** VMware Workstation
- **Firewall:** pfSense
- **Monitoring/Detection:** Security Onion
- **Attack Simulation:** Kali Linux

 

### 📋 **Steps Taken**

### 1. **Environment Setup**

- Installed pfSense as a VM with 2 NICs (WAN/LAN)
- Installed Security Onion with appropriate NIC configuration
- Installed Kali Linux and ensured network connectivity

1. Set up and Configuration 
- Configured firewall interface and firewalls rules on pfsense
- Build an active directory lab for monitoring
- Added a user to an active directory domain

1. Installing splunk for security monitoring

It is one of the most widely used SIEMs in the Cybersecurity industry. Splunk essentially aggregates logs and datasets from various data sources and correlates all that information for easy searching, parsing & indexing.

- download Ubuntu server and install server using default profile
- installed openSSH server
- forward windows event logs to splunk using universal forwarder.
