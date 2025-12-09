🚀 Implementing VPN Solutions – FortiGate Implementation

This project demonstrates how to build a complete VPN solution using FortiGate firewalls, GNS3, and Linux/Kali VMs.
The goal is to connect two separate LAN networks securely using two IPsec tunnels, then use SD-WAN to perform load-balancing, failover, and dynamic path selection and SSL VPN solution.

🧪 Project Overview

The goal of this lab is to simulate a real enterprise environment using:

Two FortiGate devices (FGT-HQ and FGT-Branch)

Two LAN networks

192.168.2.0/24 (Linux Host)

192.168.3.0/24 (Kali Host)

Two IPsec tunnels used as SD-WAN members

SLA performance checks

Failover and load balancing

GNS3 virtual topology & VMWare Work station

This project demonstrates:

✔ How to build IPsec tunnels between two FortiGates
✔ How to add tunnels into an SD-WAN zone
✔ How to configure SLA and health checks
✔ How to route traffic between two LAN networks
✔ How to test with Linux hosts
✔ How to configure SSL VPN on FortiGate
✔ How to troubleshoot ping failures and routing issues
✔ Building SSL VPN and access devices inside the network remotely

🛠 Technologies Used
VMWare Work station
GNS3
FortiGate VM
Linux Ubuntu
Kali Linux
FortiClient SSL VPN
SD-WAN
IPsec IKEv1/IKEv2
Static Routing
