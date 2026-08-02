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

A packet capture showed encrypted TLS traffic generated while visiting secure websites. Although the packet contents could not be be read, the source and destination IP addresses, packet sizes, and connection information remained visible.

## Lessons Learned

- HTTPS uses TLS encryption.
- Encrypted traffic protects sensitive data.
- Wireshark can still analyze metadata from encrypted communications.
