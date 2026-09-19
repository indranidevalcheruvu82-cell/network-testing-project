# Network Testing Project – Cisco Packet Tracer

## Objective
Built and tested a small office network with 2 PCs, 1 switch, and 1 router.

## Topology
- 2 PCs (PC0, PC1)
- 1 Switch (2960-24TT)
- 1 Router (2911)

## IP Configuration
| Device | IP Address | Subnet Mask | Gateway |
|---|---|---|---|
| PC0 | 192.168.1.1 | 255.255.255.0 | 192.168.1.254 |
| PC1 | 192.168.1.2 | 255.255.255.0 | 192.168.1.254 |
| Router | 192.168.1.254 | 255.255.255.0 | – |

## Test Cases
| Test ID | Test Case | Expected | Actual | Status |
|---|---|---|---|---|
| TC01 | Normal ping PC0 → PC1 | Reply | Reply | Pass |
| TC02 | Disconnect PC1 cable | Timeout | Timeout | Pass |
| TC03 | Wrong IP on PC1 | Timeout | Timeout | Pass |
| TC04 | Regression after fix | Reply | Reply | Pass |
| TC05 | Ping gateway | Reply | Reply | Pass |

## Tools Used
- Cisco Packet Tracer
- TCP/IP, Ethernet, ICMP (ping)

## Skills Demonstrated
- Network configuration
- Functional testing
- Regression testing
- Defect documentation# network-testing-project
- screenshots of my work
- <img width="617" height="184" alt="Screenshot 2026-09-19 164642" src="https://github.com/user-attachments/assets/81bbc16f-a2eb-4a1b-b811-36f907212404" />
<img width="627" height="214" alt="Screenshot 2026-09-19 165218" src="https://github.com/user-attachments/assets/94c2539f-cf5b-41f6-95b9-7f86bc043141" />
<img width="654" height="174" alt="Screenshot 2026-09-19 165047" src="https://github.com/user-attachments/assets/64ef3db8-de24-492a-8f43-51a14ca33dc6" />

