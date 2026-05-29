# Domain 3: Security Architecture and Engineering
## Table of Contents
- [Domain 3: Security Architecture and Engineering](#domain-3-security-architecture-and-engineering)
  - [Table of Contents](#table-of-contents)
  - [Topics](#topics)
  - [Notes](#notes)
  - [References](#references)

## Topics
- Secure design principles 
  - Threat modeling 
  - Least privilege
  - Defense in depth
  - Secure defaults 
  - Fail securely 
  - Segregation of Duties (SoD) 
  - Keep it simple and small 
  - Zero trust 
  - Trust but verify
  - Privacy by design 
  - Shared responsibility 
  - Secure access service edge
- Security models
  - Biba
  - Star Model
  - Bell-LaPadula 
- Controls 
- Security capabilities of information systems
  - memory protection 
  - Trusted Platform Module (TPM)
  - encryption 
  - decryption 
- Vulnerabilities of security architectures
  - Client-based systems
  - Server-based systems
  - Database systems 
  - Cryptographic systems 
  - Industrial Control Systems (ICS)
  - Cloud-based systems
    - Software as a service (SaaS)
    - Infrastructure as a service (IaaS)
    - Platform as a Service (PaaS)
  - Distributed systems 
  - Internet of Things (IoT)
  - Microservices
    - API
  - Containerization 
  - Serverless
  - Embedded systems 
  - High-performance computing systems 
  - Edge computing systems 
  - Virtualized systems 
- Cryptographic solutions
  - cryptography life cycle
    - keys
    - algorithm selection
  - Cryptographic methods 
    - symmetric
    - asymmetric
    - elliptic curves
    - quantum
  - Public key infrastructure (PKI)
    - quantum key distribution
- Cryptanalytic attacks
  - Brute force
  - ciphertext only
  - known plaintext
  - frequency analysis
  - Chosen ciphertext 
  - Implementation attacks 
  - Side-channel
  - Fault injection 
  - Timing
  - Man-in-the-middle (MITM)
  - Pass the hash
  - Kerberos exploitation
  - Ransomware
- site and facility security controls 
  - Wiring closets/intermediate distribution facilities
  - server rooms/data centers
  - media storage facilities 
  - evidence storage 
  - restricted and work area security 
  - utilities and heating, ventilation, and air conditioning (HVAC)
  - environmental issues 
    - natural disasters
    - man-made
  - power
    - redundant
    - backup 
- Information system lifecycle
  - stakeholder needs and requirements 
  - requirements analysis
  - architectural design 
  - development/implementation 
  - integration 
  - verification/deployment 
  - operations and maintenance/sustainment
  - retirement/disposal
 
## Notes
- subject/object model: 
- fail open: failed security controls are bypassed
- fail secure or fail closed: failed security controls block access 
- isolation: 
  - examples: network segmentation, process isolation, memory segmentation, virtual machine isolation
- segmentation: 
- security models
  - multilevel security: systems designed to operate at different security levels simultaneously while enforcing confidentiality and integrity constraints that restrict access between security levels 
  - Bell-LaPadula Model: enforces confidentiality. used mostly in military applications 
    - Rules
      1. Simple Security Rule: No "read up" 
      2. *-Property: No "write-down"
  - Biba Model: enforces integrity
    - Rules
      1. Simple integrity property: No "read down"
      2. *-Integrity property: No "write up" 
- Trusted Computer System Evaluation Criteria (TCSEC) or orange book: contained DoD computer security requirements. replaced in 2005 with common criteria
- Common Criteria: unified evaluation processes across NATO countries 
- Certification: determines that a system meets security criteria. not the same as accreditation  
- Accreditation: approves use of a system in a specific environment. same as authorization 
  - accreditation decisions:
    - authorization to operate (ATO)
    - interim authorization to operate (IATO)
    - interim authorization to test (IATT)
    - denial of authorization to operate (DATO)
- segregation of duties: no individual should possess two permissions that, in combination, allow them to perform a highly sensitive action 
- two-person control (or dual control): requires the authorization of two separate individuals to carry out a sensitive action
- privacy by design principles
  1. proactive, not reactive; preventive, not remedial 
  2. privacy as the default setting 
  3. privacy embedded into design 
  4. full functionality: positive sum, not zero sum 
  5. end-to-end security full lifecycle protection 
  6. visibility and transparency: keep it open
  7. respect for user privacy: keep it user-centric
- secure default 
  - zero trust: least privilege to network access 
- information system lifecycle
  1. stakeholder needs
  2. requirement analysis
  3. architectural design
  4. development / implementation 
  5. integration 
  6. verification & validation 
  7. transition / deployment  
  8. operations & maintenance 
  9. retirement / disposal
- cloud computing security
  - cloud service provider: offers cloud computing services for sale to third parties
  - purchases cloud computing services from one or more cloud service providers 
  - cloud access security broker (CASB): provides IAM services
  - managed security service providers (MSSPs): provide security services for other organizations as a managed service
  - network-based CASB: broker intercepts traffic between the user and the cloud service, monitoring for security issues 
    - broker can block requests
  - API-based CASB: broker queries the cloud service via API 
    - broker may not be able to block requests, depending upon API capabilities
- multitenancy: shared computing resources
- isolation: users don't impact each other
- oversubscription: sold capacity exceeds actual capacity
- resource pooling: CPU and memory shared among users
- hypervisor types
  - type 1 hypervisor: hypervisor runs directly on top of the hardware, then guest operating systems on top of that
  - type 2 hypervisor: physical machine actually runs an operating system of its own, and the hypervisor runs as a program on top of that operating system. examples include VirtualBox and Parallels
- virtualization security
  - virtual machine isolation is critical
  - each server must have access to only its own memory and storage
  - VM escape attacks attempt to break out of the guest environment
- VM sprawl: unused and unmaintained servers
- virtual desktop infrastructure (VDI): provides network-based access to a desktop computing environment 
- application virtualization: streams applications to the user's desktop



## References