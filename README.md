SnowPhantomX

This Python application provides a graphical user interface (GUI) for various network and hacking functionalities, designed for educational and testing purposes in cybersecurity and ethical hacking.

Features
IP Lookup

Perform a lookup of detailed information about an IP address using the ipinfo.io API.
Network Stress Test

Send multiple HTTP requests to stress-test a URL with customizable parameters (number of requests, delay, and concurrent workers).
DNS Lookup

Resolve domain names to their corresponding IP addresses.
Traceroute

Perform a traceroute to a specified target to track the path taken by packets across an IP network.
Port Scan

Scan a range of ports on a specified IP address to check for open ports.
Get Public and Private IP Addresses

Retrieve and display both the public and private IP addresses of the local machine.
Start/Stop Network Traffic Monitoring

Monitor network traffic in real-time, displaying bytes sent/received and packets sent/received.
Get Network Interfaces Info

Fetch information about network interfaces, including IP addresses and netmasks.
Exit

Close the application.
Requirements
Python 3.x
Required Python packages (install using pip install <package_name>):
tkinter (GUI toolkit)
requests (HTTP library)
psutil (system and process utilities)
netifaces (network interfaces information)
scapy (for traceroute functionality)
Usage
Clone the repository or download the multitool_gui.py file.

Install the required Python packages if not already installed:

bash
Kopiera kod
pip install tkinter requests psutil netifaces scapy
Run the application:

bash
Kopiera kod
python multitool_gui.py
Use the GUI to select the desired functionality and input parameters where required.

View outputs and results in the scrolling console within the GUI.

Notes
This tool is intended for educational purposes to demonstrate basic functionalities used in ethical hacking, network analysis, and cybersecurity.
Always ensure you have permission to perform tests or actions on any systems or networks.
Modify and expand upon these functionalities based on your learning goals and interests in ethical hacking and cybersecurity.
