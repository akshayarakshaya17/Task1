ELEVATE_LABS-TASK1
For Kali Linux, you can follow these steps:(I HAVE ALREADY DONE THESE WHILE INITIALLY PRACTICING NMAP SO THE SCREENSHOTS UPLOADED ARE OF MY PREVIOUS PROJECT )

Step 1: Ensure Nmap is Installed

Open Terminal in Kali Linux.
Type sudo apt-get update && sudo apt-get install nmap to ensure Nmap is installed.
Step 2: Find Local IP Range

Type ifconfig or ip addr show to find your local IP address.
Note down the IP range (e.g., 192.168.1.0/24).
Step 3: Run Nmap Scan

Type sudo nmap -sS 192.168.1.0/24 (replace with your IP range).
Press Enter to run the TCP SYN scan.
Step 4: Note Down IP Addresses and Open Ports

Review the scan results.
Note down IP addresses and open ports.
Step 5: Analyze Packet Capture with Wireshark (Optional)

Install Wireshark if not already installed: sudo apt-get install wireshark.
Capture packets during the Nmap scan using Wireshark.
Analyze the packet capture.
Step 6: Research Common Services

Research common services running on open ports.
Identify potential vulnerabilities.
Step 7: Identify Potential Security Risks

Identify potential security risks based on open ports and services.
Consider closing unnecessary ports or restricting access.
Step 8: Save Scan Results

Use the -oN option to save scan results as a text file: sudo nmap -sS 192.168.1.0/24 -oN scan_results.txt
Use other output options (-oX, -oG) as needed.
RELATED SCREENSHOTS Screenshot 2025-06-23 105803 Screenshot 2025-06-23 105729 Screenshot 2025-06-23 105713 Screenshot 2025-06-23 105659 Screenshot 2025-06-23 105628 Screenshot 2025-06-23 105612 Screenshot 2025-06-23 105557 Screenshot 2025-06-23 105539 Screenshot 2025-06-23 094959 Screenshot 2025-06-23 105644# Task1
