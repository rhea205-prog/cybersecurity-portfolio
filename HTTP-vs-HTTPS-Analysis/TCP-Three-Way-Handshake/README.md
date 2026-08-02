# TCP Three-Way Handshake Analysis

## Scenario

A security analyst analyzed network traffic to observe how TCP connections are established between a client and a server.

## Objective

Capture and analyze the TCP three-way handshake using Wireshark.

## Tools Used

- Wireshark
- Windows 11
- Npcap

## Skills Demonstrated

- TCP Analysis
- Packet Capture
- Network Communications
- Wireshark

## Display Filter Used

tcp

## Findings

## Findings

The packet capture successfully identified TCP SYN packets used to initiate TCP connections.

Using the display filter:

tcp.flags.syn == 1

I observed the beginning of the TCP three-way handshake between a client and remote web servers over HTTPS (TCP port 443).

The handshake consisted of:

- SYN
- SYN-ACK
- ACK

This process establishes a reliable TCP connection before encrypted application data is transmitted.

## Lessons Learned



## Lessons Learned

- Learned how TCP connections are established.
- Used Wireshark display filters to locate SYN packets.
- Identified the beginning of TCP communication.
- Improved understanding of how secure web traffic begins.
<img width="1186" height="473" alt="image" src="https://github.com/user-attachments/assets/aec56bb8-9969-42a3-b008-da08cb3568ea" />
