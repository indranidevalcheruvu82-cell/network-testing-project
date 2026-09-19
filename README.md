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
