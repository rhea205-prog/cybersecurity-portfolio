# DNS Analysis

## Scenario

A security analyst used Wireshark to inspect DNS traffic and identify domain name lookups occurring on the network.

---

## Objective

Capture and analyze DNS queries using Wireshark.

---

## Tools Used

- Wireshark
- Windows 11
- Npcap

---

## Skills Demonstrated

- DNS Analysis
- Packet Capture
- Network Traffic Analysis
- Wireshark Filters

---

## Wireshark Filter

```
dns
```

---

## Findings

The DNS filter displayed packets used to resolve domain names into IP addresses.

Examples observed included:

- chatgpt.com
- mozilla.cloudflare-dns.com
- Microsoft services

---

## Lessons Learned

- DNS translates domain names into IP addresses.
- Wireshark makes it easy to isolate DNS traffic.
- DNS requests are one of the first network events before connecting to websites.

---

## Packet Capture

<img width="1172" height="498" alt="image" src="https://github.com/user-attachments/assets/9d1c5848-e148-4bb8-81f9-a7485b25b11a" />
