                                     wireshark Network Traffic Analysis 

This repository contains the results of my Wireshark-based network traffic analysis conducted as part of a Cyber Security internship task.
The objective was to capture real network packets, filter them by protocol, analyze their structure, and export the data for further study.

The analysis followed these major steps:

    1. Starting Wireshark
Wireshark was already installed on my Linux system. I launched it from the terminal/application menu.

    2. Choosing the Active Network Interface
I connected my laptop to my mobile hotspot and selected the wlan0 interface, which was actively sending and receiving packets.

    3. Capturing Network Traffic
Live capture was started on wlan0.
To generate traffic, I browsed websites such as testphp.vulnweb.com and performed multiple searches.

    4. Stopping the Capture
After about a minute of browsing, I returned to Wireshark and stopped the capture using the stop button.

    5. Applying Protocol Filters
I filtered packets by protocol and analyzed key traffic:

DNS – Domain resolution queries
ARP – IP-to-MAC address mapping
TCP – Three-way handshake packets
HTTP – Plaintext POST requests

Screenshots for each protocol are included in the repository.

    6. Protocol Analysis

Each protocol was analyzed with its own summary and explanation:
DNS AAAA query analysis
ARP reply mapping local IP to MAC
TCP SYN/ACK handshake packet
HTTP POST request with form data

All findings were documented for clarity.

    7. Exporting the Capture

After completing the analysis, the capture was saved and exported as a .pcap file for future reference or deeper inspection.

    8. Summary of Findings

All captured protocols were analyzed and explained, with screenshots included in the repository for verification and demonstration.
The final .pcap file and protocol summaries provide a complete view of the network behavior during the session.

    📁 Repository Contents

/screenshots – DNS, ARP, TCP, and HTTP packet screenshots
capture.pcap – Exported Wireshark packet capture
README.md – Documentation of the entire task

    ✔ Outcome

This task demonstrates the ability to perform:
Live packet capturing
Protocol-based filtering

Packet-level analysis

Data export for further cyber-forensics work
