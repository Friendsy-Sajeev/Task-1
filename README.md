# Task-1

 🔍 *Nmap Network Scanning Project*

This task demonstrates how to perform a basic network scan using **Nmap** to identify live hosts, open ports, running services, and associated security risks on a local network (`192.168.1.0/24`).

---

✅ Project Steps

1. 🛠 Install Nmap
Download and install Nmap from the [official website](https://nmap.org/download.html) or install via terminal:
''bash''
sudo apt update
sudo apt install nmap

2.Find your local IP address using:
''bash''
nmap 192.168.1.0/24

3.Run nmap -sS 192.168.1.0/24 on bash to perform TCP SYN scan.

4..Note down IP addresses and open ports found - This shows the number of ip addresses and open ports in our network.

5.Analyze packet capture with Wireshark
#Search wireshark on kali linux
#after opening it, press the start option to start the packet capturing.
#Analyze it.

6..Research common services running on those ports.
By scanning nmap 192.168.1.0/24, we can find the open ports and common services related to it. Observe them.

7.Identify potential security risks from open ports
Search each and every ports on the internet to know more about the security risks associated with the open ports.
