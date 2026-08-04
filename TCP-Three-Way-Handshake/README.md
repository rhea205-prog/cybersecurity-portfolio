# HTTP vs HTTPS Analysis

## Scenario

A security analyst captured network traffic to compare encrypted and unencrypted web communications.

## Objective

Capture HTTPS traffic using Wireshark and analyze how encrypted communications appear during a packet capture.

## Tools Used

- Wireshark
- Windows 11
- Npcap

## Skills Demonstrated

- Packet Capture
- HTTPS Analysis
- TLS Analysis
- Network Traffic Analysis

## Display Filters Used

- tls
- tcp

## Findings


A packet capture of HTTPS traffic showed encrypted TLSv1.2 and QUIC communications generated while browsing secure websites.

The analysis revealed:

- Encrypted TLS application data
- QUIC protocol traffic
- Secure communication over port 443
- Source and destination IPv6 addresses

Although the encrypted packet contents could not be viewed, Wireshark successfully displayed metadata such as IP addresses, protocols, ports, packet sizes, and timestamps.

No suspicious encrypted traffic was observed during this investigation.
## Lessons Learned


- Learned how to capture HTTPS traffic using Wireshark.
- Identified TLSv1.2 encrypted communications.
- Observed QUIC traffic used by modern web applications.
- Understood that HTTPS encrypts the contents of communications while leaving packet metadata visible.
- Gained hands-on experience analyzing encrypted network traffic.
- Move TCP three-way handshake project
