# Overview

Notes I want to add to my cheatsheet on exam day. As of 3/29/2026, this is my cheatsheet from my Sec+ cheatsheet but will add onto it as my studying progresses.

## Cheatsheet Notes
#### Data Roles

| Q     | Role            | Description                                                         |
| ----- | --------------- | ------------------------------------------------------------------- |
| Who   | Data Owner      | Who has access to data (classification)                             |
| What  | Data Controller | Determines what the data is used for, processes used on data        |
| When  | Data Owner      | Decides when the data is no longer useful (data destruction)        |
| Why   | Data Processor  | Processes data as told by data controller (person,org,software)     |
| Where | Data Custodian  | Where data is stored and where it is going                          |
| How   | Data Steward    | How they will ensure data quality, policies, procedures, guidelines |


#### Security Models 
- take-grant model
- Bell-LaPadula model
- Biba model
- Clark-Wilson model
- Brewer and Nash model 

| Model                 | Type       | Focus           | Rules                                                                   |
| --------------------- | ---------- | --------------- | ----------------------------------------------------------------------- |
| Bell-LaPadula         | Lattice    | Confidentiality | -Simple Security Property <br> -Star Property <br>-Strong Star Property |
| Biba                  | Lattice    | Integrity       | -Simple Integrity Property <br>-Star Integrity Property                 |
| Lipner Implementation | Lattice    |                 |                                                                         |
| Clark-Wilson          | Rule Based | Integrity       | -well-formed transactions <br>-separation of duties                                                                         |
| Brewer-Nash (Chinese Wall)          | Rule Based |   Confidentiality              |  Prevents conflicts of interest                                                                       |
| Graham-Denning        | Rule Based |                 |                                                                         |
| Harrison-Ruzzo-Ullman | Rule Based |  Integrity               |                                                                         |

#### OSI
Please Do Not Throw Sausage Pizza Away

#### IP 
Application, Transport, Internet, Network



#### Ports and protocols 
HTTP (80), HTTPS (443), SSH (22), Telnet (23), FTP (21), SMTP (25), DNS (53), DHCP (67/68)

#### Insecure vs Secure protocols
| Insecure            | Secure                               |
| ------------------- | ------------------------------------ |
| HTTP (port 80)      | HTTPS (port 443)                     |
| FTP (port 20,21)    | SFTP / FTPS (port 990)               |
| Telnet (port 23)    | SSH/SCP/SFTP (port 22)               |
| SMTP (port 25)      | SMTPS (port 465)                     |
| POP3 (port 110)     | POP3S (port 995)                     |
| NNTP (port 119)     | NNTPS (port 563)                     |
| IMAP (port 143)     | IMAPS (port 993)                     |
| SNMP (port 161,162) | SNMPv3 (port 161, 162, 10161, 10162) |


#### RAID levels 

|         | Stripe | Mirrored | Parity             | Minimum Drives |
| ------- | ------ | -------- | ------------------ | -------------- |
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

#### Access Control

| Type                         | Description                                                      | Example                   |
| ---------------------------- | ---------------------------------------------------------------- | ------------------------- |
| Rule Based                   | set of rules                                                     | rules in a firewall's ACL |
| Role Based (RBAC)            | grants access based on a subject's membership in a group or role |                           |
| Attribute Based              |    grants access based on attributes                                                              |                           |
| Mandatory Access Model (MAC) | uses labels to identify access |                           |


#### Incident response phases
##### CISSP
1. Detection
2. Response
3. Mitigation
4. Reporting
5. Recovery
6. Remediation
7. Lessons Learned
- sounds like "drumroll" 

##### NIST
1. Preparation
2. Detection and Analysis
3. Containment, Eradication, Recovery
4. Post-Incident Activity

##### SANS
1. Preparation
2. Identification
3. Containment
4. Eradication
5. Recovery
6. Lessons Learned

#### NIST List
- NIST SP 800-61: for incident response planning
- NIST 800-88: sanitization techniques