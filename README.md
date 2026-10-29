# B084 Week 1 - Cybersecurity Lab Setup
Student: Kiplimo Kelvin - Networkwalks B084

1.Overview
This repo documents my Week 1 lab setup for Cybersecurity.

2.Lab Setup
- Host: Windows 11 Pro (planning to downgrade to Windows 10 Pro due to crashes)
- Virtualization: Oracle VirtualBox
- Guest VM: Kali Linux from kali.org (VirtualBox Pre-built 3.9GB)
- Network: NAT Network - NatNetwork 10.0.0.0/24
- Tools: Wireshark, Nmap, ping
 3. Steps Completed
1. Installed VirtualBox
2. Downloaded and Imported Kali Linux VM (File > Import Appliance)
3. Created NAT Network: 10.0.0.0/24 via File > Tools > Network Manager
4. Set VM Adapter to NAT Network > NatNetwork
5. Verified with ip a and ping
6. Installed Wireshark: sudo apt install wireshark -y
7. Exported VM as .ova backup to prevent data
