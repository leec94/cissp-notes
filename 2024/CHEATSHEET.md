# Overview

Notes I want to add to my cheatsheet on exam day. As of 3/29/2026, this is my cheatsheet from my Sec+ cheatsheet but will add onto it as my studying progresses.

## Cheatsheet Notes

#### Ports and protocols 
HTTP (80), HTTPS (443), SSH (22), Telnet (23), FTP (21), SMTP (25), DNS (53), DHCP (67/68)

#### Insecure vs Secure protocols
| Insecure             | Secure                               |
|----------------------|--------------------------------------|
| HTTP (port 80)       | HTTPS (port 443)                     |
| FTP (port 20,21)     | SFTP / FTPS (port 990)               |
| Telnet (port 23)     | SSH/SCP/SFTP (port 22)               |
| SMTP (port 25)       | SMTPS (port 465)                     |
| POP3 (port 110)      | POP3S (port 995)                     |
| NNTP (port 119)      | NNTPS (port 563)                     |
| IMAP (port 143)      | IMAPS (port 993)                     |
| SNMP (port 161,162)  | SNMPv3 (port 161, 162, 10161, 10162) |


#### RAID levels 

|         | Stripe | Mirrored | Parity             | Minimum Drives |
|---------|--------|----------|--------------------|----------------|
| RAID 0  | yes    | no       | no                 | 2              |
| RAID 1  | no     | yes      | no                 | 2              |
| RAID 5  | yes    | no       | yes, distributed   | 3              |
| RAID 6  | yes    | no       | yes, 2 distributed | 4              |
| RAID 10 | yes    | yes      | no                 | 4              |

#### Risk calculations 
```
SLE = AV * EF
ALE = SLE * ARO 
```

#### Secure encryption protocols
- **Hash**: SHA-256 (good), MD5 (bad)​
- **Symmetric**: AES (good), DES (bad)​
- **Asymmetric**: RSA, ECC
- **Wireless** WPA3 (good), WEP,WPA2 (bad)

#### Incident response phases
Preparation, Identification, Containment, Eradication, Recovery, and Lessons Learned