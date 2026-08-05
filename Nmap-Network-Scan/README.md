# Nmap Network Scan

## Scenario

A security analyst used Nmap to identify active hosts and discover open ports on a target system.

---

## Objective

Perform a basic network scan and identify common network services.

---

## Tools Used

- Nmap
- Windows 11
- Command Prompt

---

## Skills Demonstrated

- Network Scanning
- Port Enumeration
- Service Detection
- Reconnaissance

---

## Command Used

```bash
nmap -sV scanme.nmap.org
```

---

## Findings

## Findings

The Nmap service scan successfully identified active services running on the target host.

Open services discovered included:

- SSH (22/tcp)
- HTTP (80/tcp)
- Nping Echo (9929/tcp)
- Elite Service (31337/tcp)

The scan also detected that the target was running a Linux operating system and identified the versions of several services.

---

## Lessons Learned

- Nmap can quickly identify open ports.
- Service detection helps identify software versions.
- Network scanning is an important first step during security assessments.

---

## Screenshot

<img width="924" height="516" alt="image" src="https://github.com/user-attachments/assets/06547588-e015-4e42-a803-77a5da49468e" />

