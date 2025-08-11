# Capture-and-Analyze-Network-Traffic-Using-Wireshark
 Capture live network packets and identify basic protocols and traffic types.

https://drive.google.com/file/d/1OiiudTaoYxPZVGs2VeLdN7wG_iX41Hox/view?usp=sharing

the above link contains .pcap file

 
 Wireshark Packet Capture and Protocol Analysis

Steps Performed

1. Install Wireshark
   - Download from [https://www.wireshark.org](https://www.wireshark.org) and install with default options.

2. Start Capture
   - Open Wireshark.
   - Select the active network interface (Wi-Fi/Ethernet).
   - Click the **Start Capturing** button.

3. Generate Network Traffic
   - Browse to `https://www.example.com`.
   - Run `ping google.com` in the terminal to generate ICMP traffic.

4. Stop Capture
   - Let the capture run for about 1 minute.
   - Click the red Stop button.

5. Filter by Protocol
   - Applied Wireshark display filters:
     - HTTP: `http`
     - DNS: `dns`
     - TCP: `tcp`
     - UDP: `udp`
     - ICMP: `icmp`

6. Identify Protocols
   - Observed at least 3 different protocols in the capture:
     - HTTP – Transfers web pages between browser and server.
     - DNS – Resolves domain names to IP addresses.
     - TCP – Reliable, connection-oriented transport.
     - UDP – Fast, connectionless transport.
     - ICMP – Diagnostic protocol for network reachability.

7. Export Capture
   - Saved capture as `.pcap` for documentation and future analysis.

---

 Protocol Definitions

- HTTP (`http`) – Hypertext Transfer Protocol, used for web communication.
- DNS (`dns`) – Domain Name System, resolves domain names to IP addresses.
- TCP (`tcp`) – Transmission Control Protocol, ensures reliable data delivery.
- UDP (`udp`) – User Datagram Protocol, fast but connectionless communication.
- ICMP (`icmp`) – Internet Control Message Protocol, used for diagnostics (e.g., ping).

---

 Tools Used
- Wireshark – Network protocol analyzer for packet capture and inspection.
- Web Browser – To generate HTTP traffic.
- Ping Command – To generate ICMP traffic.
