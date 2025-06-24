# Automating "NetCorp's" Network
# Introducing NetCorp: A Fictional Company
NetCorp is a medium-sized company with a growing network infrastructure. They have multiple office locations, a data center, and are increasingly relying on cloud services. Their network supports a variety of business-critical applications, including email, file sharing, video conferencing, and customer relationship management (CRM) software.

## NetCorp's Network Infrastructure

NetCorp's network consists of a mix of devices from different vendors, including Cisco, Juniper, and Arista. They have routers, switches, firewalls, and wireless access points distributed across their various locations.

- **Headquarters:** The headquarters is the largest site and houses the main data center. It has a core network consisting of high-end Cisco routers and switches, providing connectivity for all internal services.
- **Branch Offices:** NetCorp has several branch offices connected to the headquarters via MPLS circuits. Each branch office has a Juniper router and a few Cisco switches.
- **Data Center:** The data center hosts the company's servers and applications. It uses a combination of physical servers and virtual machines running on VMware. The network in the data center is primarily Arista equipment.
- **Cloud Infrastructure:** NetCorp uses AWS and Azure for some of their applications and services. They have VPN connections between their on-premises network and their cloud environments.

## Specific Automation Goals for NetCorp

NetCorp has identified several specific areas where they want to implement network automation:

- **Configuration Management:** Automate the configuration of network devices, including routers, switches, and firewalls.
- **Compliance Management:** Ensure that network devices are compliant with security policies and industry regulations.
- **Network Monitoring:** Implement automated monitoring to detect and respond to network issues in real-time.
- **Provisioning:** Automate the provisioning of new network devices and services.
- **Troubleshooting:** Automate common troubleshooting tasks to reduce the time it takes to resolve network issues.

