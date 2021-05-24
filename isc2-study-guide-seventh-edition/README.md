# ISC2 CISSP Study Guide, Seventh Edition

- [ISC2 CISSP Study Guide, Seventh Edition](#isc2-cissp-study-guide-seventh-edition)
  - [Chapter 1: Security Governance](#chapter-1-security-governance)
  - [Chapter 2: Personnel Security and Risk Management](#chapter-2-personnel-security-and-risk-management)
  - [Chapter 3: Business Continuity Planning](#chapter-3-business-continuity-planning)
  - [Chapter 4: Laws, Regulations, and Compliance](#chapter-4-laws-regulations-and-compliance)
  - [Chapter 5: Protecting Security of Assets](#chapter-5-protecting-security-of-assets)
  - [Chapter 6: Cryptography and Symmetric Key Algorithms](#chapter-6-cryptography-and-symmetric-key-algorithms)
  - [Chapter 7: PKI and Cryptographic Applications](#chapter-7-pki-and-cryptographic-applications)
  - [Chapter 8: Principles of Security Models, Design, and Capabilities](#chapter-8-principles-of-security-models-design-and-capabilities)
  - [Chapter 9: Security Vulnerabilities, Threats, and Countermeasures](#chapter-9-security-vulnerabilities-threats-and-countermeasures)
  - [Chapter 10: Physical Security Requirements](#chapter-10-physical-security-requirements)
  - [Chapter 11: Secure Network Architecture and Securing Network Components](#chapter-11-secure-network-architecture-and-securing-network-components)
    - [Cabling](#cabling)
      - [Coaxial Cable](#coaxial-cable)
      - [Baseband and Broadband Cables](#baseband-and-broadband-cables)
      - [Twisted-Pair](#twisted-pair)
      - [Conductors](#conductors)
    - [Network Topologies](#network-topologies)
      - [Ring](#ring)
      - [Bus](#bus)
      - [Star](#star)
      - [Mesh](#mesh)
    - [Wireless Communications and Security](#wireless-communications-and-security)
      - [Cell Phones](#cell-phones)
      - [Bluetooth](#bluetooth)
      - [Cordless Phones](#cordless-phones)
      - [Mobile Devices](#mobile-devices)
    - [LAN Technologies](#lan-technologies)
      - [Ethernet](#ethernet)
      - [Token Ring](#token-ring)
      - [FDDI](#fddi)
      - [Subtechnologies](#subtechnologies)
      - [LAN Media Access](#lan-media-access)
  - [Chapter 12](#chapter-12)
    - [Secure Communications Protocols](#secure-communications-protocols)
    - [Authentication Protocols](#authentication-protocols)
    - [Secure Voice Communications](#secure-voice-communications)
    - [Email Security](#email-security)
      - [Email Security Issues](#email-security-issues)
      - [Email Security Solutions](#email-security-solutions)
    - [Dial-Up Protocols](#dial-up-protocols)
    - [Centralized Remote Authentication Services](#centralized-remote-authentication-services)
    - [VPN](#vpn)
    - [VLAN, Virtual LAN](#vlan-virtual-lan)
    - [Virtualization](#virtualization)
    - [Network Address Translation](#network-address-translation)
    - [Switching Technologies](#switching-technologies)
    - [Prevent or Mitigate Network Attacks](#prevent-or-mitigate-network-attacks)
  - [Chapter 13: Managing Identity and Authentication](#chapter-13-managing-identity-and-authentication)
    - [subject vs object](#subject-vs-object)
    - [Access Control](#access-control)
      - [access control types](#access-control-types)
    - [CIA Triad](#cia-triad)
    - [Identification terms](#identification-terms)
    - [authentication factors](#authentication-factors)
    - [passwords](#passwords)
    - [smartcard and tokens](#smartcard-and-tokens)
    - [Multifactor authentication](#multifactor-authentication)
    - [implementing identity management](#implementing-identity-management)
    - [Centralized Access Control](#centralized-access-control)
    - [LDAP: lightweight directory access protocol](#ldap-lightweight-directory-access-protocol)
      - [Kerberos](#kerberos)
        - [Ticket logon process](#ticket-logon-process)
        - [Steps to access an object](#steps-to-access-an-object)
    - [SSO](#sso)
      - [Federated Identity Management](#federated-identity-management)
        - [Markup Languages](#markup-languages)
      - [Other SSO Examples](#other-sso-examples)
      - [Credential management systems](#credential-management-systems)
      - [Integrating Identity services](#integrating-identity-services)
      - [AAA Protocols](#aaa-protocols)
    - [Identity and Access Provisioning Lifecycle](#identity-and-access-provisioning-lifecycle)
  - [Chapter 14: Controlling and Monitoring Access](#chapter-14-controlling-and-monitoring-access)
    - [Authorization Mechanisms](#authorization-mechanisms)
      - [Defining requirements with a security policy](#defining-requirements-with-a-security-policy)
      - [RBAC methods](#rbac-methods)
      - [Rule-based access control methods](#rule-based-access-control-methods)
      - [Mandatory Access Control](#mandatory-access-control)
      - [Access control attacks](#access-control-attacks)
    - [prevent or mitigate access control attacks](#prevent-or-mitigate-access-control-attacks)
  - [Chapter 15: Security Assessment and Testing](#chapter-15-security-assessment-and-testing)
    - [design and validate assessment and test strategies](#design-and-validate-assessment-and-test-strategies)
    - [conduct security control testing](#conduct-security-control-testing)
    - [collect security process data](#collect-security-process-data)
    - [analyze and report test outputs](#analyze-and-report-test-outputs)
    - [conduct or facilitate internal third party audits](#conduct-or-facilitate-internal-third-party-audits)
  - [Chapter 16: Managing Security Operations](#chapter-16-managing-security-operations)
  - [Chapter 17: Preventing and Responding to Incidents](#chapter-17-preventing-and-responding-to-incidents)
  - [Chapter 18: Disaster Recovery Planning](#chapter-18-disaster-recovery-planning)
  - [Chapter 19: Incidents and Ethics](#chapter-19-incidents-and-ethics)
  - [Chapter 20: Software Development Security](#chapter-20-software-development-security)
  - [Chapter 21: Malicious Code and Application Attacks](#chapter-21-malicious-code-and-application-attacks)

## Chapter 1: Security Governance

## Chapter 2: Personnel Security and Risk Management

## Chapter 3: Business Continuity Planning

## Chapter 4: Laws, Regulations, and Compliance

## Chapter 5: Protecting Security of Assets

## Chapter 6: Cryptography and Symmetric Key Algorithms

## Chapter 7: PKI and Cryptographic Applications

## Chapter 8: Principles of Security Models, Design, and Capabilities

## Chapter 9: Security Vulnerabilities, Threats, and Countermeasures

## Chapter 10: Physical Security Requirements

## Chapter 11: Secure Network Architecture and Securing Network Components

### Cabling

#### Coaxial Cable

_coaxial cable_: center core of copper wire surrounded by a layer of insulation, then surrounded by a conductive braided shielding and encased in a final insulation sheath. not used as much anymore, now twisted-pair is the more popular alternative.

- Types
  - _thinnet_: or 10Base2, connected systems to backbond trunks of thicknet cabling, spans distances of 185 meters and throughput up to 10 Mbps
  - _thicknet_: or 10Base5, can span 500 meters and throughput up to 10 Mbps
- Problems
  - Bending coax cable past max arc
  - deploying coax cable past max recommended length
  - not properly terminating the ends of the coax cable with a 50 ohm resistor

#### Baseband and Broadband Cables

_Baseband_: can transmit only one single signal at a time

- most cables are baseband cables

_Broadband_: can transmit multiple signals simultaneously

![network cabling naming convention](chap-11/networkcablenamingconvention.png)

| Type                 | Max Speed | Distance      | Difficulty of Installation | Susceptibility to EMI | Cost      |
| -------------------- | --------- | ------------- | -------------------------- | --------------------- | --------- |
| 10Base2              | 10 Mbps   | 185 meters    | Medium                     | Medium                | Medium    |
| 10Base5              | 10 Mbps   | 500 meters    | High                       | Low                   | High      |
| 10Base-T (UTP)       | 10 Mbps   | 100 meters    | Low                        | High                  | Very low  |
| STP                  | 155 Mbps  | 100 meters    | Medium                     | Medium                | High      |
| 100Base-T/100Base-TX | 100 Mbps  | 100 meters    | Low                        | High                  | Low       |
| 1000Base-T           | 1 Gbps    | 100 meters    | Low                        | High                  | Medium    |
| Fiber-optic          | 2+ Gbps   | 2+ kilometers | Very High                  | None                  | Very High |

#### Twisted-Pair

_twisted-pair_: four pair wires twisted around each other and sheathed in PVC insulator.

- each wire pair is twisted at a different length so signals traveling over the pairs cannot cross across pairs. the tighter the twist the more resistent the cable is to internal and external interference and crosstalk, and capacity for throughput is greater.
- Types
  - _STP: shielded twisted-pair_, the metal foil wrapper around the wires underneath the external sheath.
  - _UTP: unshielded twisted-pair_, without the foil. refers to 10Base2, 100Base-T, or 1000Base-T, all outdated.
- Problems
  - wrong category of twisted-pair cable for high-throughput networking
  - deloyinh twisted-pair longer than max recommended length
  - using UTP in environments with significant interference

_UTP categories_

| UTP Category | Throughput | Notes                                                                                     |
| ------------ | ---------- | ----------------------------------------------------------------------------------------- |
| Cat 1        | Voice Only | Not suitable for networks but usable by modems                                            |
| Cat 2        | 4 Mbps     | Not suitable for most networks                                                            |
| Cat 3        | 10 Mbps    | Mostly used in 10Base-T Ethernet networks                                                 |
| Cat 4        | 16 Mbps    | Mostly used in Token Ring networks                                                        |
| Cat 5        | 100 Mbps   | Used in 10Base-TX, FDDI, and ATM networks                                                 |
| Cat 5e       | 100 Mbps   | Enhanced Cat 5 to protect against crosstalk. used by 100Base-T and 1000Base-T deployments |
| Cat 6        | 1,000 Mbps | Used in high-speed networks                                                               |
| Cat 7        | 10 Gbps    | Used on 10 gigabit-speed networks                                                         |

#### Conductors

- Types
  - _Copper_: one of the best and least expensive
  - _Plenum cable_: does not release toxic fumes when burned
  - _fiber-optic cable_: transmits pulses of light rather than electricity.
- Terms
  - _maximum length_: point where level of degradation could interfere with transmission of data.
  - _attenuation_: degradation of signal
  - _repeater_: signal amplification device, boosts the signal strength of an incoming data stream and rebroadcasts it through its second port
  - _concentrator_: same as repeater but it has more than two ports.
    - use of more than four repeaters in a row is discouraged, 5-4-3 rule

### Network Topologies

- _logical topology_: grouping of networked systems into trusted collectives.

#### Ring

- _ring topology_: connects each system as points on a circle. only one system can transmit data at a time. if one segment of the loop is broken, all communication around the loop ceases.
  - _token_: digital hall pass that travels around the ring until a system grabs it. traffic management is performed by a token.

![ring topology](chap-11/ring.gif)

#### Bus

- _bus topology_: connects each system to a trunk cable. all systems on the bus can transmit data simultaneously, which can result in collisions. when data is transmitted, all systems on the network can hear the data. if a single segment fails, communications on all other segments continue uninterrupted. the central trunk line remains a single point of failure.
- rarely used today, because it must be terminated at both ends and any disconnection can take down the entire network.

- Types
  - linear bus: single trunk line with all systems directly connected to it
  - tree bus: single trunk line with branches that can support multiple systems

![bus topology](chap-11/bustopol.gif)

#### Star

- _star topology_: centralized connection device, hub or switch. each system is connected to the central hub by a dedicated segment. if one segment fails, the other segments can continue to function. the central hub is a single point of failure.
- uses less cabling than other topologies, and makes identifying damaged cables easier
- logical bus and logical ring can be implemented as a physical star
  - Ethernet: bus-based but can be deployed as a physical star
  - Token Ring: ring-based but can be deployed as a physical star using MAU
    - MAU: multistation access unit, allows for cable segments to be deployed as a star while internally the device makes logical ring connections

![star topology](chap-11/star.gif)

#### Mesh

- _mesh topology_: connects systems to other systems using numerous paths. provides redundant connections to systems, allowing multiple segment failures without seriously affecting connectivity
  - full mesh topology: connects each system to all other systems on the network
  - partial mesh topology: connects many systems to many other systems.

![mesh topology](chap-11/mesh.gif)

### Wireless Communications and Security

- _frequency_: a measurement of the number of wave oscillations within a specific time and identified using the unit Hertz (Hz), or oscillations per second
  - radio waves have a frequency between 3 Hz and 300 GHz
- _spread spectrum_: communication occurs over multiple frequencies at the same time. a message is broken into pieces and each piece is sent at the same time but at a different frequency, effectively parallel communication.
- _FHSS_: Frequency Hopping Spread Spectrum, early implementation of the spread spectrum concept, but transmits data in a series while constantly changing the frequency in use
- _DSSS_: Direct Sequency Spread Spectrum, employs all the available frequencies simultaneously in parallel to provide a higher rate of data throughput than FHSS. also uses chipping code to allow a receiver to reconstruct data even if parts of the signal were distorted because of the interference.
- _OFDM_: Orthogonal Frequency-Division Multiplexing, employs a digital multicarrier modulation scheme that allows for a more tightly compacted transmission. The modulated signals are perpendicular (orthogonal) thus do not cause interference with each other

#### Cell Phones

Cell Phone Technology Categories

- May be missing 5G technologies, this chart is from 2015

| Technology                     | Generation |
| ------------------------------ | ---------- |
| NMT                            | 1G         |
| AMPS                           | 1G         |
| TACS                           | 1G         |
| GSM                            | 2G         |
| iDEN                           | 2G         |
| TDMA                           | 2G         |
| CDMA                           | 2G         |
| PDC                            | 2G         |
| HSCSD                          | 2.5G       |
| GPRS                           | 2.5G       |
| W-CDMA                         | 3G         |
| TD-CDMA                        | 3G         |
| UWC                            | 3G         |
| EDGE                           | 3G         |
| DECT                           | 3G         |
| UMTS                           | 3G         |
| HSPDA                          | 3.5G       |
| WiMax - IEEE 802.16            | 4G         |
| XOHM (Brand name of WiMax)     | 4G         |
| Mobile Broadband - IEEE 802.20 | 4G         |
| LTE (Long Term Evolution)      | 4G         |

- _WAP_: Wireless Application Protocol, a functioning protocol stack. Suite of protocols working together to connect from cell phone to the Internet.
  - Example of protocol is WTLS, Wireless Transport Layer Security, similar to SSL or TLS
  - NOT the same as WAP, wireless access point, when used in relation to 802.11
  - end-to-end encryption is not possible because of CALEA wiretapping mandate
  - _CALEA_: Communications Assistance for Law Enforcement Act

#### Bluetooth

- _Bluetooth_: also IEEE 802.15, personal area networks (PANs), is where primary device scans 2.4 GHz radio frequencies for available devices, then 4 digit PIN "authorizes" the pairing. Range is 30 to 100 ft.
  - attacks
    - _bluejacking_: allows an attacker to transmit SMS-like messages to your device
    - _bluesnarfing_: allows hackers to connect to your Bluetooth device and extract information from them
    - _bluebugging_: grants hackers remote control over the feature and functions of a Bluetooth device
  - suggestions:
    - use Bluetooth for activities that are not sensitive or confidential
    - when possible change the default PIN on your devices
    - do not leave your device in discovery mode
    - always turn of Bluetooth when it's not in active use

#### Cordless Phones

- can use any unlicensed frequencies: 900MHz, 2.4GHz, or 5 GHz. Signal is rarely encrypted so eavesdropping is easy with a frequency scanner.

#### Mobile Devices

- suggestions
  - keep nonessential information off portable devices
  - run a firewall and antivirus product if available
  - keep the system locked and/or encrypted if possible
  - check that all desired security features are operating as expected on any device allowed to connect o the organization's network

### LAN Technologies

#### Ethernet

- _ethernet_: shared media LAN technology. Uses broadcast and collision domains
  - can support full-duplex communications and usually employs twisted-pair cabling
  - most often deployed on star or bus topologies
  - based on IEEE 802.3 standard
  - Terms
    - _broadcast domain_: physical grouping of systems where all the systems in the group receive a broadcast sent by a single system in the group.
    - _collision domain_: groupings of systems within which a data collision occurs if two systems transmit simultaneously.
    - _data collision_: takes place when two transmitted messages attempt to use the network medium at the same time. it causes one or both messages to be corrupted
    - _frames_: individual units of Ethernet data

#### Token Ring

- _token ring_: employs a token-passing mechanism to control which systems can transmit data over the network medium
  - the token travels in a logical loop among all members of the LAN 
  - can be deployed on ring or star network topologies 
  - rarely used today because of performance limitations, higher cost, and increased difficulty in deployment and management 
  - ring-based but can be deployed as a physical star using MAU

#### FDDI

- _FDDI_: Fiber Distributed Data Interface, high speed token-passing technology that employs two rings with traffic flowing in opposite directions 
  - often used as a backbone for large enterprise networks 
  - _CDDI_: Copper Distributed Data Interface, uses twisted pair cables, uses less-expensive, distance limited, and slower
    - more vulnerable to interference and eavesdropping

#### Subtechnologies

- _analog_: continuous signal that varies in frequency, amplitude, phase, voltage, etc.
- _digital_: on/off pulses of discontinuous electrical signals
- _synchronous_: relies on a timing mechanism 
- _asynchronous_: relies on stop and start delimiter bit to manage the transmission of data
- _baseband_: support only a single communication channel
- _broadband_: can support multiple simultaneous signals
- _broadcast_: communication to all possible recipients
- _multicast_: communication to multiple specific recipients
- _unicast_: only to a single recipient

#### LAN Media Access

- _CSMA_: Carrier-Sense Multiple Access
  - does not directly address collisions
- _CSMA/CA_: Carrier-Sense Multiple Access with Collision Avoidance
  - examples: appletalk and 802.11
  - attempts to avoid collusions by granting only a single permission to communicate at any given time
  - needs a primary system, to respond to requests and grants permission to send data transmissions
- _CSMA/CD_: Carrier-Sense Multiple Access with Collision Detection
  - example: ethernet
  - responds to collisions by having each member of the collision domain wait a random period of time before starting the process over 
- _token passing_: LAN media access technology that communicates using a digital token. 
- _polling_: LAN media access technology that performs communications using a primary / secondary configuration. 
  - SDLC, Synchronous Data Link Control, uses polling
  - inverse of the CSMA/CA method

## Chapter 12

### Secure Communications Protocols
- SKIP: 
- swIPe: 
- S-RPC: 
- SSL: 
- TLS: 
- SET: 

### Authentication Protocols
- _CHAP_: Challenge Handshake Authentication Protocol
- _PAP_: Password Authentication Protocol
  - offers no form of encryption, transmits usernames and passwords in the clear
- _EAP_: Extensible Authentication Protocol

### Secure Voice Communications
- VoIP: Voice over Internet Protocol
- PBX: private branch exchange
- Social Engineering
- Fraud and Abuse
  - _phreakers_: malicious actors that abuse phone systems
    - Tools
      - _Black boxes_: manipulates line voltages to steal long-distance services
      - _Red boxes_: simulates tones of coins being deposited into a pay phone
      - _Blue boxes_: simulated 2600 Hx tones to interact directly with telephone network trunk systems 
      - _White boxes_: used to control the phone system
  - DISA: Direct Inward System Access 
    - designed to help manage external access and external control of a PBX by assigning access codes to users

### Email Security
- SMTP: Simple Mail Transfer Protocol
  - Sendmail: most common SMTP server for Unix systems
  - Exchange: most common SMTP server for Microsoft systems
- POP3: Post Office Protocol version 3
- IMAP: Internet Message Access Protocol '

#### Email Security Issues
- Spoofing
- DoS
- Mail-bombing

#### Email Security Solutions
- S/MIME: 
- MOSS: 
- PEM: 
- DKIM: 
- PGP: Pretty Good Privacy 

### Dial-Up Protocols
- _PPP_: Point-to-Point Protocol
- _SLIP_: Serial Line Internet Protocol

### Centralized Remote Authentication Services 
- _RADIUS_: Remote Authentication Dial-In User Service
- _TACACS+_: Terminal Access Controller Access-Control System

### VPN
- tunneling: network communications process that protects the contents of protocol packets by encapsulating them in packets of another protocol
- PPTP: Point-to-Point Tunneling Protocol
- L2F: Layer 2 Forwarding Protocol
- L2TP: Layer 2 Tunneling Protocol
- IPSec: IP Security Protocol
  - AH: Authentication Header, provides authentication, integrity, and nonrepudiation
  - ESP: Encapsulating Security Payload, provides encryption to protect the confidentiality of transmitted data


| VPN Protocol | Native Authentication Protection | Native Data Encryption | Protocols Supported | Dial-Up Links Supported | Number of Simultaneous Connections |
| ------------ | -------------------------------- | ---------------------- | ------------------- | ----------------------- | ---------------------------------- |
| PPTP         | Yes                              | No                     | PPP                 | Yes                     | Single point-to-point              |
| L2F          | Yes                              | No                     | PPP/SLIP            | Yes                     | Single point-to-point              |
| L2TP         | Yes                              | No (can use IPSec)     | PPP                 | Yes                     | Single point-to-point              |
| IPSec        | Yes                              | Yes                    | IP only             | No                      | Multiple                           |

### VLAN, Virtual LAN

- _VLAN_: used to logically segment a network without altering its physical topology
- VLAN vs subnet
  - VLANs are created by switches, subnets are created by IP address and subnet mask assignments 

### Virtualization 

-_software-defined networking_: separates the infrastructure layer from the control layer, and removes the traditional networking concepts of IP addressing, subnets, routing, etc. from needing to be programmed into hosted applications. directly programmable, network virtualization 

-SAN: storage area network, combines multiple individual storage devices into a single consolidated network-accessible storage container. 

### Network Address Translation 

- NAT: converts internal IP addresses into public IP addresses for transmission over the Internet
- PAT: port address translation 
- private IP addresses
- stateful NAT
- static NAT: 
- dynamic NAT: 
- APIPA: automatic private IP addressing, assigns an IP address to a system in the event of a DHCP assignment failure 
  - primarily a feature of Windows 
  - APIPA assigns each failed DHCP client with an IP address from range 169.254.0.1 to 169.254.255.254

### Switching Technologies
- circuit switching: dedicated physical pathway is created between the two communicating parties
- packet switching: the message is broken up into small segments and sent across the intermediary networks to the destination


| Circuit Switching            | Packet Switching             |
| ---------------------------- | ---------------------------- |
| Constant traffic             | Bursty traffic               |
| Fixed known delays           | Variable delays              |
| Connection oriented          | Connectionless               |
| Sensitive to connection loss | Sensitive to data loss       |
| Used primarily for voice     | Used for by any type of data |

- virtual circuit: 
  - PVCs: permanent virtual circuits
  - SVCs: switched virtual circuits
- WAN: wide area network
  - dedicated line: one that is indefinitely and continually reserved for use by a specific customer
  - nondedicated line: requires a connection to be established before data transmission can occur 
  - DSL: digital subscriber line, exploits the upgraded telephone network to grant consumers speeds from 144 Kbps to 6 Mbps (or more) 
  - ISDN: Integrated Services Digital Network, fully digital telephone network that supports both voice and high-speed data communications
    - formats of ISDN service:
      - BRI: Basic Rate Interface, offers a connection with two B channels and one D channel 
      - PRI: Primary Rate Interface, offers consumers a connection with multiple 64 Kbps B channels and a single 64 Kbps D channel 

| Technology                             | Connection Type | Speed                    |
| -------------------------------------- | --------------- | ------------------------ |
| Digital Signal Level 0 (DS-0)          | Partial T1      | 64 Kbps up to 1.544 Mbps |
| Digital Signal Level 1 (DS-3)          | T1              | 1.544 Mbps               |
| Digital Signal Level 3 (DS-3)          | T3              | 44.736 Mbps              |
| European digital transmission format 1 | E1              | 2.108 Mbps               |
| European digital transmission format 3 | E3              | 34.368 Mbps              |
| Cable modem or cable routers           |                 | 10+ Mbps                 |

  - WAN connection technologies
    - WAN switch: 
    - CSU/DSU: channel service unit/data service unit 
    - DTE/DCE: data terminal equipment/data circuit-terminating equipment 
  - X.25: older packet switching technology that was widely used in Europe
    - predecessor to Frame Relay
  - Frame Relay: 
  - ATM: asynchronous transfer mode
  - SMDS: switched multimegabit data service 
  - SDLC: synchronous data link control
  - HDLC: high-level data link control
  - HSSI: high speed serial interface 
  - PPP: Point-to-point protocol 

### Prevent or Mitigate Network Attacks
- DoS: denial-of-service
  - exploiting a vulnerability in the hardware or software
  - attacks that flood the victim's communication pipeline with garbage network traffic 
  - safeguards 
    - add firewalls, routers, and intrusion detection systems (IDSs)
    - maintain good contact with your service provider
    - disable echo replies on external systems 
    - disable broadcast features on border systems 
    - block spoofed packets from entering or leaving your network
    - keep all systems patched with the most current security updates from vendors 
    - consider commercial DoS protection like CloudFlare's DDoS mitigation or Prolexic
- eavesdropping: listening to communication traffic for the purpose of duplicating it 
- impersonation: or masquerading
- replay attacks
- modification attacks
- ARP spoofing: provides false MAC addresses for requested IP addressed systems to redirect traffic to alternate destinations
- DNS poisioning
  - solution: upgrade DNS to DNSSEC
    - DNSSEC: Domain Name Secrity System Security Extensions 
- Hyperlink spoofing

## Chapter 13: Managing Identity and Authentication 

### subject vs object
- subject: active entity that accesses an object to receive information about or modify objects.  
  - "user"
- object: passive entity that provides information to active objects. 
  - examples: files, databases, computers, programs, processes, printers, and storage media

### Access Control

overall access control steps
1. identify and authenticate users or other objects attempting to access resources
2. determine whether the access is authorized
3. grant or restrict access based on the subject's identity
4. monitor and record access attempts

#### access control types 

- preventive: attempts to stop unauthorized activity from occurring
  - examples: fences, locks, biometrics, mantraps, lighting, alarm systems, separation of duties policies, job rotation policis, data classification, penetration testing, etc. 
- detective: attempts to discover or detect unwanted or unauthorized activity.
  - operates after the fact and can discover the activity only after it has occurred
  - examples: security guards, motion detectors, recording and reviewing of events captured by security camera or CCTV, job rotation policies, etc. 
- corrective: modifies the environment to return systems to normal after an unwanted or unauthorized activity has occurred 
  - attempts to correct any problems that occurred as a result of a security incident 
  - examples: terminating malicious activity or rebooting a system, antivirus solutions that can remove or quarantine a virus, backup and restore plans, etc. 
- deterrent
- recovery: attempts to repair or restore resources, functions, and capabilities after a security policy violation 
  - an extension of corrective controls but have more advanced or complex abilities 
  - examples: backup and restores, fault-tolerant drive systems, system imaging, server clustering, antivirus software, database or virtual machine shadowing
- directive: attempts to direct, confine, or control the actions of subjects to force or encourage compliance with security policies 
  - examples: security policy requirements, posted notifications, escape route exit signs, monitoring, supervision, and procedures 
- compensation: provides an alternative when it isn't possible to use a primary control, or to increase the effectiveness of a primary control 
  - examples: security policy dictating use of smartcards, and the company issuing hardware tokens to employees as a compensating control, stringer than just a username and password 

categories by how they are implemented
- administrative: policies and procedures defined by an organization's security policy and other regulations or requirements
  - examples: policies, procedures, hiring practices, background checks, classifying and labeling data, etc. 
- logical/technical controls: hardware or software mechanisms used to manage access and to provide protection for resources and systems
  - examples: authentication methods, encryption, constrained interfaces, access control lists, protocols, firewalls, routers, intrusion detection systems, and clipping levels 
- physical controls: physical mechanisms deployed to prevent, monitor, or detect direct contact with systems or areas within a facility
  - examples: guards, fences, motion detectors, locked doors, sealed windows, lights, etc. 

### CIA Triad
- confidentiality
- integrity
- availability

### Identification terms
- identification: process of a subject claiming an identity. all subjects must have unique identities
- authentication: verifies the identity of the subject by comparing one or more factors against a database of valid identities 
- authorization: subjects are granted access to objects based on proven identities 
  - indicates who is trusted to perform specific operations 
- accountability: users and other subjects can be held accountable for their actions when auditing is implemented
  - auditing: the process of tracking and recording subject activities within logs 
  - does not require effective authorization 

### authentication factors 
- Type 1: something you know
  - examples: password, PIN, passphrase
- Type 2: something you have 
  - examples: smartcard, hardware token, memory card, USB drive
- Type 3: something you are or something you do
  - examples: fingerprints, voice prints, retina patterns, iris patterns, face shapes, palm topology, hand geometry 

### passwords 
- type 1 authentication 
- PBKDF2: password-based key derivation function 2, hashing algorithm 
- strong password factors
  - maximum age
  - password complexity
  - password length
  - password history 
- other password type things
  - password phrases
  - cognitive passwords: series of questions about facts or predefined responses that only the subject should know 

### smartcard and tokens
- smartcard 
  - PIV: personal identity verificatino cards
  - CAC: common access cards 
- token: password generating device that users can carry with them 
  - synchornous dynamic password tokens
  - asynchronous dynamic password tokens
- biometrics 
  - in type 3: something you are
  - types
    - fingerprints
    - face scans
    - retina scans
    - iris scans 
    - palm scans 
    - hand geogetry 
    - heart/pulse patterns 
    - voice pattern recognition
    - signature dynamics 
    - keystroke patterns 
  - error rates
    - type 1 error: when a valid subject is not authenticated
      - FRR: false rejection rate
    - type 2 error: when an invalid subject is authenticated
      - FAR: false acceptance rate
    - CER: crossover error rate 
      - ERR: equal error rate, same as CER
      - used as a standard assessment value to compare the accuracy of different biometric devices 
      - ![CER point](chap-13/cer.jpg)
  - biometric registration
    - enrollment: subject's biometric factor is sampled and stored in the device's database
      - reference profile: or reference template, it is the stored sample
    - throughput rate: the amount of time the system requires the scan a subject and aprove or deny access 
  
### Multifactor authentication
- two-factor authentication: requires two different factors to provide authentication
- SSO: single sign on
  - reduces the number of accounts required for a subject 
device authentication 
- BYOD policy
- device fingerprinting
- tools
  - IdP: SecureAuth Identity Provider

### implementing identity management
- centralized access control: all authorization verification is performed by a single entity within a system
  - can be managed by a small team, administrative overhead is lower
- decentralized access control: various entities located throughout a system performs authorixation verification 
  - often requires several teams or multiple individuals 
  - administrative overhead is higher because changes must be implemented across numerous locations 
  - maintaining consistency across a system is more difficut as the number of access control points increases 
  - changes made to any individual access control point need to be repeated at every access point 
  
### Centralized Access Control

### LDAP: lightweight directory access protocol

#### Kerberos
- KDC: key distribution center
- TGS: ticket granting service
- TGT: ticket-granting ticket
- Ticket: 

##### Ticket logon process
1. The user types a username and password into the client
2. the client encrypts the username with AES for transmission to the KDC
3. the KDC verifies the username against a database of known credentials
4. the KDC generates a symmetric key that will be used by the client and the Kerberos server. It encrypts this with a hash of the user's password. The KDC also generates an encrypted time-stamped TGT
5. The KDC then transmits the encrypted symmetric key and the encrypted time-stamped TGT to the client
6. The client installs the TGT for use until it expires. The client also decrypts the symmetric key using a hash of the user's password. 

##### Steps to access an object
1. The client sends its TGT back to the KDC with a request for access to the resource
2. The KDC verifies that the TGT is valid and checks its access control matrix to verify that the user has sufficient privileges to access the requested resorce
3. The KDC generates a service ticket and sends it to the client
4. The client sends the ticket to the server of service hosting the resource
5. The server or service hosting the resource verifies the validity of the ticket with the KDC
6. Once identity and authorization is verified, Kerberos activity is complete. The server or service host then opens a session with the client and begins communications or data transmission 

### SSO 
#### Federated Identity Management
- Federated identity management is a form of SSO for users to access resources over the Internet 
- federation: can be composed of multiple unrelated networks within a single university campus, multiple organizations sharing resources, or any other group that can agree on a common federated identity management system. Members of the federation match user identities within an organization to federated identities 
- federated identity systems often use SAML, security assertion markup language, or SPML to have a common language. 

##### Markup Languages
- HTML: Hypertext Markup Language
- XML: Extensible Markup Language
- SAML: Security Assertion Markup Language
- SPML: Service Provisioning Markup Language
- XSCML: Extensible Access Control Markup Language

#### Other SSO Examples
- scripted access 
- SESAME: secure european system for applications in a multivendor environment
- Kryptoknight
- OAuth
- OpenID

#### Credential management systems
- Windows Credential Manager tool 
- KeePass
- 1Password
- BitWarden
- Lastpass

#### Integrating Identity services
- IDaaS
  - examples: Google and Office 365

#### AAA Protocols
- protocols that use the access control elements of identification, authentication, authorization, and accountability to ensure that users have valid credentials to authenticate and verify that the user is authorized to connect 
- Examples
  - RADIUS: Remote Authentication Dial-In User Service
    - used by many ISPs. users can access the ISP from anywhere and the ISP server forwards the user's connection request to the RADIUS server
  - TACACS+: Terminal Access Controller Access-Control System
    - TACACS, alternative to RADIUS
    - Then XTACACS, created by Cisco
    - finally TACACS+, open publically documented protocol, most commonly used of the three protocols
      - encrypts all of the authentication information 
      - TCP port 49
  - Diameter
    - enhanced version of RADIUS
    - uses TCP 3868

### Identity and Access Provisioning Lifecycle
- provisioning 
- account review
- account revocation 

## Chapter 14: Controlling and Monitoring Access
- permissions
- rights
- privileges
### Authorization Mechanisms 
- implicit deny
- access control matrix
- capability tables
- constrained interface
- content-dependent control
- context-dependent control
- need to know
- least privilege
- separation of duties and responsibilities 

#### Defining requirements with a security policy 
- security policy: document that defines the security requirements for an organization
  - physical access controls
  - logical/technical access controls
  - administrative access controls

- discretionary access control: DACs, allows the owner, creator, or data custodian of an object to control and define access to that object. access control is based oon the discretion or decision of the owner 
  - implemented using access control lists (ACLs) on objects 
  - owners make their own changes 

- nondiscretionary access controls: centrally administered 
  - less flexible 
  - examples: rule-based, role-based, lattice-based access controls 
  - 
#### RBAC methods
- role based access control: controls based on a subject's role 
  -  also task-based
  -  prevents privilege creep 
  - useful in dynamic environments with frequent personnel changes 

- privilege creep: tendency for privileges to accrue to users over time as their roles and access needs to change

- task-based access control: TBAC, each user is assigned to an array of tasks. focus is on controlling access by assigned tasks rather than by user identity 

#### Rule-based access control methods
- rule-based access control: rule-BAC, uses a set of rules to determine what can and can't occur on a system 
  - these models have global rules that apply to all subjects 
  - example: firewall 

- attribute-based access control: ABAC, uses policies that include multiple attributes for rules
  - type of rule-BAC, but more specific
  - example: policies for software-defined wide area network (SD-WAN)

#### Mandatory Access Control
- mandatory access control (MAC): relies on classification labels, representing a security domain 
  - lattice based MAC model 
  - prohibitive rather than permissive, and uses implicit deny philosophy, so if users are not specifically granted access to data, then the system denies them access to associated data 
  - more secure than DAC but not as flexible or scalable 
  - example: US military and lables of Confidential, Secret, Top Secret 
  - classifications within a MAC model
    - hierarchical environment: levels of classification
    - compartmentalized environment: no relationship between one security domain and another
    - hybrid environment: combines both hierarchical and compartmentalized concepts so each hierarchical level can contain subdivisions that are isolated from the rest of the security domain 


#### Access control attacks
- key risk management steps: 
  - identifying assets, asset value
  - identifying threats, threat modeling (focused on assets, attackers, or software)
  - identifying vulnerabilities (vulnerability analysis)

- common access control attacks
  - access aggregation attacks
  - password attacks 
  - dictionary attacks
  - brute-force attacks
  - birthday attack
  - rainbow table attacks
  - sniffer attacks
  - spoofing attacks
    - email spoofing
    - phone number spoofing
  - social engineering attacks
    - phishing
    - spear phishing
    - whaling 
    - vishing 
  - smartcard attacks
  - Denial-of-Service attacks

### prevent or mitigate access control attacks 
- controls to help protect attacks
  - control physical access to systems
  - control electronic access to files
  - encrypt password files
  - create strong password policy 
  - use password masking
  - deploy multifactor authentication
  - use account lockout controls
  - use last logon notification 
  - educate users about security 

## Chapter 15: Security Assessment and Testing
- three major components of security assessment program
  - security tests
    - verify that a control is functioning properly
    - examples: automated scans, tool-assissted pen tests, and manual attempts to undermine security
  - secuity assessments
    - comprehensive reviews of the security of a system, application, or other tested environment
    - risk assessment to identify vulnerabilities in the tested environment and make recommendations if needed
    - examples: security testing tools, thoughtful review of threat environment, current and future risks, and value of the targeted environment 
    - main work: assessment report addressed to management that contains the results of the assessment in nontechnical language and concludes with specific recommendations for improving the security of the tested environment
    - for internal use only 
  - security audits
    - similar to assessments but must be performed by independent auditors 
    - demonstrating effectiveness of controls to a third party. provides an impartial, unbiased view of the state of security controls 
    - types of audits
      - internal audits
        - performed by an organization's internal audit staff and intended for internal audiences 
      - external audits
        - by an outside auditing firm 
        - high degree of external validity because the auditors performing the assessment have no conflict of interest with the organization itself 
### design and validate assessment and test strategies
- vulnerability assessments 
  - vulnerability scans 
    - types:
      - network discovery scans 
        - techniques:
          - TCP SYN scanning
          - TCP connect scanning
          - TCP ACK scanning
          - Xmas scanning
      - network vulnerability scans
        - probes targeted system or network for the precense of known vulnerabilities
      - web application vulnerability scan
        - look for known vulnerabilities in web applications
        - when to scan:
          - scan when beginning to perform web vulnerability scanning for the first time to detect issues with legacy applications
          - scan new application before moving it into a production environment for the first time
          - scan any modified application before code changes move into production
          - scan all applications on a recurring basis 
      - penetration testing
        - attempts to exploit systems 
        - example process
          - perform basic reconnaissance
          - network discovery scans 
          - network vulnerability scans 
          - web application vuln scans 
          - use of exploit toools to attempt to defeat system security
          - manual probing and attack attempts
        - types
          - white box penetration test
          - gray box penetration test
          - black box penetration test
  

| TCP Protocol         | Port Number |
| -------------------- | ----------- |
| FTP                  | 21          |
| SSH                  | 22          |
| Telnet               | 23          |
| SMTP                 | 25          |
| DNS                  | 53          |
| HTTP                 | 80          |
| POP3                 | 110         |
| NTP                  | 123         |
| HTTPS                | 443         |
| Microsoft SQL Server | 1433        |
| Oracle               | 1521        |
| H.323                | 1720        |
| PPTP                 | 1723        |
| RDP                  | 3389        |


### conduct security control testing
### collect security process data 
### analyze and report test outputs
### conduct or facilitate internal third party audits

## Chapter 16: Managing Security Operations

## Chapter 17: Preventing and Responding to Incidents

## Chapter 18: Disaster Recovery Planning

## Chapter 19: Incidents and Ethics

## Chapter 20: Software Development Security

## Chapter 21: Malicious Code and Application Attacks
