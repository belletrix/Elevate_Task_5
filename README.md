## Objective
Capture live network traffic and identify basic protocols and traffic types using Wireshark.

## Tools Used
- Wireshark (Version: 4.x)

## Procedure

1. Installed Wireshark and launched the tool.
2. Started capture on active network interface (Wi-Fi).
3. Generated traffic by browsing websites and pinging google.com.
4. Captured packets for approximately 1 minute.
5. Filtered packets using Wireshark filters:
   - `http`
   - `dns`
   - `tcp`
6. Identified the following protocols in the capture:
   - HTTP: Web traffic to example.com
   - DNS: Domain resolution requests
   - TCP: Underlying transport for HTTP
7. Exported the capture as `network_capture.pcap`.

## Summary of Findings

| Protocol | Purpose                         | Example Packet |
|----------|----------------------------------|----------------|
| HTTP     | Website data transfer            | example.com GET request |
| DNS      | Resolving domain names to IPs    | Query for google.com |
| TCP      | Transport layer communication    | TCP handshake (SYN, SYN-ACK, ACK) |

## Outcome
Successfully captured and analyzed network packets. Developed understanding of protocol layers and packet structure using Wireshark.
