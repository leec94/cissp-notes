# Domain 1: Security and Risk Management
## Table of Contents
- [Domain 1: Security and Risk Management](#domain-1-security-and-risk-management)
  - [Table of Contents](#table-of-contents)
  - [Topics](#topics)
  - [Notes](#notes)
  - [More Notes](#more-notes)
      - [tables](#tables)
  - [References](#references)

## Topics
- Ethics
  - ISC2 Code of Professional Ethics
  - Organizational code of ethics
- Security concepts
  - Confidentiality
  - Integrity
  - Availability
  - Authenticity
  - Non-repudiation
- Security governance principles
  - Security to business alignment
  - Organizational processes
    - acquisitions
    - divestitures
    - governance committees
  - Org roles and responsibilities 
  - Security control frameworks
    - International Organization for Standardization (ISO)
    - National Institute of Standards and Technology (NIST)
    - Control Objectives for Information and Related Technology (COBIT)
    - Sherwood Applied Business Security Architecture (SABSA)
    - Payment Card Industry (PCI)
    - Federal Risk and Authorization Management Program (FedRAMP)
  - Due care/Due Diligence
    - due care: responsible protection of assets. aligns what security should be doing with what the org should be doing
    - due diligence: ability to *prove* due care
- Legal and compliance
  - Cybercrimes and data breaches
  - Licensing and Intellectual Property (IP)
  - Import/export controls
  - Transborder data flow
  - Privacy issues 
    - General Data Protection Regulation (GDPR)
    - California Consumer Privacy Act
    - Personal Information Protection Law
    - Protection of Personal Information Act
  - Other legal requirements and industry standards
- Investigation types
  - Administrative
  - Criminal 
  - Civil 
  - Regulatory
  - Industry standards
- Security policy, standards, procedures, guidelines
  - Security policy
  - Standard
  - Procedure
  - Guideline
- Business Continuity requirements
  - Business impact analysis (BIA)
  - External dependencies
- Personnel security
  - Candidate screening + hiring
  - Employment agreements 
  - Onboarding, transfers, terminations
  - Vendor, consultant, contractor
- Risk Management
  - Threat and vulnerability identification
  - Risk analysis
  - Risk response 
  - Security controls
    - Preventative, detection, corrective
  - Control assessments
  - Continuous monitoring and measurement
  - Reporting
  - Continuous improvement
    - risk maturity model (RMM)
      - ad hoc: chaotic starting point
      - Preliminary: loose attempts to follow risk management processes, but each department may perform risk assessment uniquely
      - Defined: common or standardized risk framework be adopted organization-wide
      - Integrated: risk management operations are integrated into business processes, metrics are used to gather effectiveness data, and risk is considered an element in business strategy decisions
      - Optimized: risk management focuses on achieving objectives rather than just reacting to external threats, increasing strategic planning toward business success rather than just avoiding incidents, and reintegrating lessons learned into the risk management process
  - Risk frameworks (overlaps with security control frameworks above)
    - International Organization for Standardization (ISO)
    - National Institute of Standards and Technology (NIST)
    - Control Objectives for Information and Related Technology (COBIT)
    - Sherwood Applied Business Security Architecture (SABSA)
    - Payment Card Industry (PCI)
- Threat modeling 
- Supply Chain Risk Management (SCRM)
  - Acquisition of products and services risks from suppliers
    - Product tampering
    - Counterfeits
    - Implants
  - Risk mitigations
    - third-party assessment and monitoring
    - minimum security requirements
    - service level requirements
    - silicon root of trust
    - physically unclonable function
    - software bill of materials
- Security education 
  - Methods to increase awareness and training
    - Social engineering
    - Phishing
    - Security champions
    - Gamification 
  - Content reviews to include emerging technologies and trends (like crypto, AI, blockchain)
  - Program effectiveness evaluation

## Notes
- Notes from Mike Chappelle Linkedin Learning
  - Security Fundamentals
    - TODO
  - Security Governance: seeks to compare the security processes and infrastructure used within the organization with knowledge and insight obtained from external sources
    - security leader vs business leader 
      - questions should consider both perspectives 
    - committees
      - information governance committee
      - risk management committee
      - board of directors
    - integrating security governance
      - ensure governing bodies understand risks and controls
      - inform governing bodies of security incidents 
      - provide audit reports to governing bodies
    - other governance situations
      - corporate acquisitions 
      - corporate divestitures
    - roles
      - CISO: most senior info sec role
    - due care: fulfill legal responsibilities and professional best practices
    - due diligence: taking reasonable measures to investigate security risks 
    - control and risk frameworks
      - Control Objectives for IT (COBIT): business-focused control framework covering IT and related technologies
        - developed by ISACA, used by auditors
        - principles
          - Provide Stakeholder Value
          - Holistic Approach
          - Dynamic Governance System
          - Governance Distinct from Management
          - Tailored to Enterprise Needs 
          - End-to-End governance System
      - ISO Standard
        - ISO 27001: cybersecurity control objectives
        - ISO 27002: more detail, cybersecurity control implementation 
        - ISO 27701: privacy controls
        - ISO 31000: risk management programs
      - NIST 
        - NIST 800-53: building a security program
          - for federal agencies
        - NIST Cybersecurity Framework (CSF)
          - common language for cybersecurity risk
        - NIST Risk Management Framework (RMF)
          - in NIST 800-37
          - risk management as ongoing progress
        - Federal Risk and Authorization Management Program (FedRAMP): certifies cloud service providers for US federal government use
      - Sherwood Applied Business Security Architecture (SABSA): integrating security into business strategies 
  - Compliance and Ethics
    - PI
    - SPI
    - PHI
    - IP: intellectual property
    - SD: sensitive data
    - direct identifiers: name, address, gov ID, biometric data, other uniquely identifying no
    - indirect identifiers
    - GDPR: the goat of privacy laws
      - went into effect 2018 
      - EU privacy regulation
      - applies to data controllers and data processors
      - Data Protection Officer (DPO): role specifically for GDPR, responsible for ensuring the org applies the laws to protect individuals' data
      - data controllers: organizations that determine the purposes and meaning of personal data processing
      - data processor: organizations that process information on behalf of data controllers
      - requires "right to notice" of data collection and processing 
      - businesses must obtain "consent" from data subjects
      - data subjects may retract consent at any time
      - "right of erasure" of personal information or "right to be forgotten" 
      - "right to access" personal information 
      - "right to rectification" to correct inaccurate information
      - "right to restriction" of data processing activities 
      - "right to portability" of personal information between providers
      - "right to opt out" of certain data processing activities and automated decision making
      - transferring data outside EU, 3 ways
        - Standard Contractual Clauses
        - Binding Corporate Rules (for large orgs)
        - Safe Harbor Agreements (Privacy Shield) - Invalid from Schrems II as of 2020
    - Gramm-Leach-Bliley Act (GLBA): US privacy regulation
    - Children's Online Privacy Protection Act (COPPA)
    - California Privacy Laws
      - California Financial Information Privacy Act (SB-1)
        - expands upon federal GLBA
        - restricts financial institution sharing of customer information
        - shifts to an opt-in consent process
      - California Electronic Communications Privacy Act (CalECPA)
        - in 2015
        - builds upon ECPA
        - if law enforcement wants to access private info
          - Access to service provider records: 
            - requires a search warrant or court order in criminal cases
            - requires a subpoena in non-criminal cases
          - Access to electronic devices:
            - requires a search warrant, wiretap order, consent of the customer, or certification of an emergency situation
      - California Consumer Privacy Act (CCPA)
        - right to know what information is collected
        - right to know how information is shared
        - right to opt out of information sharing
        - right to review information
        - right to request deletion of information
        - also includes a private right of action if biz doesn't maintain reasonable security procedures
      - California Data Broker Law
        - in 2019
        - requires annual registration with the attorney general
        - requires the attorney general publish registrations on their website
      - California Privacy Rights Act (CPRA)
        - in Jan 2023
        - new category of sensitive information sensitive personal information (SPI)
        - right to correct inaccurate information
        - right to limit use and disclosure of sensitive personal information 
        - right to information about automated decision-making
        - right to opt-out of automated decision making
    - OECD: international org for standards and policies like privacy
      - OECD Privacy Principles: Collection Limitation, Data Quality, Purpose Specification, Use Limitation, Security Safeguards, Openness, Individual Participation, Accountability
    - PIPEDA: Canada privacy regulation
    - Personal Information Protection Law: China privacy regulation
    - Protection of Personal Information Act: South Africa privacy regulation
    - Personal Data Protection Law #25,326 (PDPL): Argentina privacy regulation
    - Personal Information Protection Act (PIPA): South Korea privacy regulation
    - Privacy Act and Australian Privacy Principles (APPs): Australia privacy regulation
    - PCI DSS
    - HIPAA
    - Personally Identifiable Information (PII): any information that can by traced back to an individual
    - Protected Health Information (PHI): Individually identifiable health records governed under HIPAA
    - Privacy Impact Assessment (PIA): determines if personal data is being protected appropriately 
      - Steps:
        1.  Identified the need for a DPIA
        2.  Describe the data processing
        3.  Assess necessity and proportionality
        4.  Consult interested parties
        5.  Identify and assess risks
        6.  Identify measures to mitigate risks
        7.  Sign off and record outcomes
        8.  Monitor and review
    - Data Protection Impact Assessments (DPIA)
    - Generally accepted privacy principles (GAPP): outlines 10 components of data privacy to design privacy programs
      - developed by a bunch of accounting and auditing associations, AICPA, CICA, ISACA, IIA
      - GAPP components
        1. Management
        2. Notice
        3. Choice and Consent
        4. Collection
        5. Use, Retention, and Disposal
        6. Access
        7. Disclosure to Third Parties
        8. Security
        9. Quality
        10. Monitoring and Enforcement
    - National data privacy laws
      - EU: GDPR
      - Canada: Personal Information Protection and Electronic Documents Act (PIPEDA)
        - can exchange info with GDPR
      - Brazil: Brazil General Data Protection Law (LGPD)
      - China: Personal Information Protection Law (PIPL)
        - in 2021
        - explicit restrictions on data processing 
        - explicit restrictions on data transfer outside of China
        - stringent penalties for non-compliance
      - South Africa: Protection of Personal Information Act (PPIA)
        - in 2020
        - obtaining explicit consent for processing personal data
        - rights to access and correct personal information
        - obligation to notify the regulator and affected individuals in the case of a data breach
    - Computer crimes 
      - Computer Fraud and Abuse Act (CFAA)
        - makes hacking a criminal activity
        - prohibits unauthorized access to computer systems 
        - prohibits the creation of malicious code
      - Electronic Communications Privacy Act (ECPA)
        - restricts government interception of communications 
      - Identity Theft and Assumption Deterrence Act (ITADA)
        - makes identity theft a federal crime
    - software licensing 
      - Software License Agreement types
        - Enterprise License Agreements (ELAs): detailed contracts negotiated between the software vendor and the customer
        - End User License Agreements (EULAs): agreements presented to the user as they install or activate the software
      - license durations
        - perpetual licenses: allow indefinite use for a one-time fee
        - subscription licenses: require monthly or annual payments
      - license use types
        - concurrent use licenses: allow a specified number of users to access the software at the same time
        - named user licenses: allow specifically named users to access the software whenever they wish
      - license pricing types
        - freeware: software released for use without charge
        - open source software: software that may be freely used, distributed, and modified under the terms of an open source license. Examples like GNU, GPL, and MIT licenses
      - cloud service license agreements: cover use of software as a SaaS application
    - intellectual property
      - copyrights: protects creative works against theft
        - granted to creator automatically
        - provided for 70 years beyond the creator's death
        - covered works move to public domain after expiration
      - trademarks: protects words and symbols like brand names and slogans
        - granted upon registration
        - provided for renewable 10 year periods 
        - granted contingent upon active use in commerce
        - can be considered abandoned after 5 years of non use
      - patents: protects inventions
        - requirements: novelty, usefulness, non-obviousness
        - generally last 20 years
        - require public disclosure of the invention
      - trade secrets
        - secret alternative to patent protection
    - import and export controls 
      - export controls: restrict flow of goods and data
      - Wassenaar Arrangement: put in place to manage the risk that cryptography poses, while still facilitating trade. allows certain countries to exchange and use cryptography systems of any strength, while also preventing the acquisition of these items by terrorists.
        - Participating members can exchange cryptography of any strength, but countries that are not a member are excluded from data exchange
      - International Traffic in Arms Regulations (ITAR)
        - covers "defense articles"
        - controls export of items like missiles, rockets, bombs, or anything else from US Munitions List
      - Export Administration Regulations (EAR)
        - covers "dual use" technologies
        - focuses on commercial-use related items like computers, lasers, marine items, and more
      - Office of Foreign Assets Control (OFAC)
        - covers sanctioned countries
    - transborder data flow: restricts transfer of data across country borders, ex: GDPR
    - privacy: the state or condition of being free from being observed or disturbed by other people
    - data breaches
      - consequences: reputational damage, identity theft, fines, intellectual property theft
      - industry specific regulations
        - HIPAA for healthcare information
        - Sarbanes-Oxley Act (SOX) for public companies
        - PCI DSS for credit card records 
      - jurisdiction specific regulations
        - geo related such as GDPR
      - common PII elements
        - social security numbers
        - driver's license numbers
        - bank account numbers
        - and more
      - common requirements 
        - notifying affected individuals
        - informing government agencies
        - notice to general public
        - offer compensation and/or credit monitoring services
      - many data breach notification laws include exceptions for encryption information
    - ethics
      - ISC2 Code of Ethics: https://www.isc2.org/ethics
        - canons
          - Protect society, the common good, necessary public trust and confidence, and the infrastructure
          - Act honorably, honestly, justly, responsibly, and legally
          - Provide diligent and competent service to principals
          - Advance and protect the profession
        - ISC2 members are required to report breaches of the code of ethics to ISC2 for investigation  
        - charges of violations of canons 1 or 2 can be brought by anyone, changes of violation 3 may only be brought by a principal with an employer/contractor relationship with the accused, charges of canon 4 permits any certified or licensed professional to subscribes to a code of ethics to bring charges
  - Security Policy
    - policies 
      - provide the foundation for a security program
      - written carefully over a long period of time
      - require compliance from all employees
      - approved at the highest levels of the organization
      - policy criteria
        - foundational authority for data security efforts
        - clear expectations for data security responsibilities 
        - guidance for requesting access to information
        - process for granting policy exceptions
      - data storage policies
        - appropriate storage locations
        - access control requirements
        - encryption requirements
      - data transmission policies
        - appropriate data transmissions
        - encryption requirements
        - acceptable transmission mechanisms
      - data lifecycle policies
        - data retention policies: specify the minimum and/or maximum period that an organization will retain different data elements
        - data disposal policies: describe proper techniques for destroying data that is no longer needed by an organization
      - cloud policies: should address what data may be used in the cloud and how the organization approves cloud services
    - standards 
      - provide specific details of security controls
      - derive their authority from policies
      - follow a less rigorous approval process 
      - require compliance from all employees
      - example: CIS Benchmarks list of images
    - procedures 
      - outlines step-by-step process for an activity
      - must be followed by employees
    - guidelines
      - provides security advice to the organization
      - follow best practices from industry
  - Business Continuity Planning (BCP)
    - also known as continuity of operations planning (COOP)
    - defining BCP scope
      - what business activities will the plan cover?
      - what systems will it cover? 
      - what controls will it consider?
    - business impact assessment (BIA): identify and prioritize risks
      - output is list of risks to a business
    - redundancy
      - single point of failure analysis: identifies and removes SPOFs
      - succession planning
    - availability
      - high availability: uses multiple systems to protect against service failure
      - fault tolerance: makes a single system resilient against technical failures
      - load balancing: spreads demand across systems
      - uninterruptible power supplies (UPSs): supplies battery power to devices during brief disruptions
      - power distribution units (PDUs)
      - redundant array of inexpensive disks (RAID) 
        - RAID 1
        - RAID 5: disk striping with parity
        - fault tolerant strategy, not backup
      - network redundancy
        - multiple internet service providers
        - NIC teaming
  - Personnel Security
    - handle policy violations carefully, clearly
    - clear policies around personal resources and company data
    - education: best defense against social engineering attacks
    - insider threat: 25% of data breaches are from insider threats 
    - hiring process
      - preemployment screening: checks the background of potential employees
        - can include checks of criminal record, sex offender registry, reference checks, education and employment verification, credit checks
      - employment agreements
        - nondisclosure agreements (NDA)
        - return of information and physical assets at termination
      - include security at orientation sessions
      - employee transfer
        - ensure they're trained for new role
        - ensure old privileges have been properly revoked
      - offboarding
        - exit interview
        - revoke access promptly
        - retrieve organization property
      - minimization: collect minimal information and store only as long as its needed
      - limit access: limit access to as few employees as possible
      - encryption: uses cryptography to render info unreadable decryption
      - masking: removes portions of sensitive info to reduce sensitivity
    - social media policies
      - prevent account hijacking, use multifactor authentication
      - can use social media management tools
      - adopt social media policy
  - Risk Management
    - risk assessment
      - identify scope in advance
      - threat: any potential danger to an asset. external force jeopardizing security
      - risks: combination of threat and vulnerability to the asset
      - vulnerability: weaknesses in security controls that could be exploited by an attacker
      - threat vector: specific methods that threats use to exploit a vulnerability
      - likelihood: probability that a risk will occur due to a given threat or vuln being present
      - impact: amount of expected damage, extent to which an asset would be negatively affected
      - risk treatments
        - Avoid: don't do the risky thing
        - Transfer: purchase an insurance policy 
        - Mitigate: Implement controls to reduce risk
        - Accept: owner of an asset accepts a certain level of risk
      - risk analysis types:
        - qualitative: uses subjective ratings to evaluate risk likelihood and impact
          - rankings like low/medium/high
        - quantitative: uses objective numeric ratings to evaluate risk likelihood and impact
      - asset valuation techniques 
        - original cost
        - depreciated cost 
        - replacement cost 
      - exposure factor (EF): expected percentage of damage to an asset if it occurred
      - single loss expectancy (SLE): expected dollar loss if a risk occurs. SLE = AV * SLE
      - annualized rate of occurrence (ARO): number of times a risk is expected to occur each year
      - annualized loss expectancy (ALE): expected dollar loss from a risk in any given year. ALE = SLE * ARO
      - mean time to failure (MTTF): average time a nonrepairable component will last
      - mean time between failures (MTBF): average time gap between failures of a repairable component
      - mean time to repair (MTTR): average time required to return a repairable component to service
      - exposure: presence of a vulnerability when a related threat exists
      - risk: a calculation of the probability of occurrence and the level of damage that could be caused if an exposure is realized
      - risk management/treatment: process of systematically analyzing potential responses to each risk and implementing strategies to control those risks appropriately 
      - risk management strategies
        - risk avoidance: changes the org's business practices
        - risk transference: shifts the impact of a risk to another organization 
        - risk mitigation: reduces the likelihood or impact of the risk
        - risk acceptance: accepts the risk without taking further action
      - risk profile: the full set of risks facing an organization
      - levels of risk
        - inherent risk: risks that exist before any controls are put in place
        - residual risk: risks after controls are applied
        - control risk: new risks from the controls themselves
      - risk appetites 
        - expansionary risk appetite: a willingness to take on higher levels of risk
        - neutral risk appetite: balanced approach to risk
        - conservative risk appetite: focuses on maintaining stability and protecting assets 
      - risk threshold: level at which a risk becomes unacceptable
      - risk tolerance: the organization's ability to withstand risks and continue operations
      - security controls: procedures and mechanisms that an org puts in place to manage security risks
      - defense in depth: multiple controls for one objective
      - security control types
        - preventive: stop a security issue from occurring in the first place
        - detection: identify that a potential security issue has taken place
        - corrective: remediate security issues that have already occurred
      - technical controls: use technology to achieve security control objectives
      - operational controls: use human driven processes to manage technology in a secure manner
      - management controls: improve the security of the risk management process itself
      - control failures
        - false positive errors: control inadvertently triggers when it should not
        - false negative errors: control fails to trigger in a situation where it should
    - continuous security monitoring: maintaining ongoing awareness of information security, vulnerabilities, and threats to support organizational risk management decisions 
      - maps to risk tolerance
      - adapts to ongoing needs 
      - actively involves management
    - monitoring process
      - define
      - establish
      - implement
      - analyze/report
      - respond
      - review/update
    - anomaly analysis: detects outlier data points
    - behavioral analysis: detects unusual user activity with signatures or heuristic analysis
    - availability analysis: provides uptime information
    - continuous tuning: maintains effective controls
    - risk management framework
      - NIST RMF phases
        - Prepare: identifying key stakeholders, establishing an organizational risk management strategy, and preparing the necessary resources and infrastructure to support the framework implementation
        - Categorize: categorize the system and the information processed, stored, and transmitted by the system based on an analysis of the impact of loss
        - Select: choosing the appropriate security controls and privacy controls based on the system categorization
        - Implement: focuses both on deploying the selected controls and on documenting how each control is implemented
        - Assess: assess the controls to determine if the controls are implemented correctly, operating as intended, and producing the desired outcomes with respect to satisfying the security and privacy requirements
        - Authorize: authorize the system or common controls based on a determination that the risk to organizational operations and assets, individuals, other organizations, and the Nation is acceptable
        - Monitor: monitor the system and the associated controls on an ongoing basis to include assessing control effectiveness, documenting changes to the system and environment of operation, conducting risk assessments and impact analyses, and reporting the security and privacy posture of the system
      - NIST SP 800-37
        - steps in managing risks:
          1. Categorize - information system
          2. Select - security controls
          3. Implement - security controls
          4. Assess - security controls
          5. Authorize - information systems
          6. Monitor - security controls
    - risk visibility and reporting
      - risk register: tracks risk information. contains description, category, risk owner, probability + impact, risk rating, and risk management actions
      - risk register information sources
        - risk assessment results
        - audit findings
        - team member output
        - threat intelligence
      - threat intelligence: shares risk information 
      - reporting types
        - internal reporting: provides updates to management on status and effectiveness of risk management activities
        - external reporting: meets requirements for providing information to regulators, investors, customers, and partners
  - Threat Modeling
    - Open source intelligence
    - criteria for threat intelligence sources
      - timeliness
      - accuracy
      - reliability
    - threat indicators
    - sharable formats for threats
      - cyber observable eXpression (CybOX): provides schema to classify different threats 
      - structured threat information eXpression (STIX): representation of the elements as defined by CyBOX
      - trusted automated eXchange of intelligence information (TAXII): a way to exchange STIX threat information
      - OpenIOC: standard to share threat information, by Fireeye Mandiant
    - sharing threats
      - information sharing and analysis centers (ISACs): share industry specific security info in confidential manner across orgs 
    - threat research
      - reputational threat research: based on their use of IP address, email address, domains, etc. used previously in attacks
      - behavioral threat research: identify potentially malicious actors based upon the similarity of their behaviors to past attackers
    - identifying threats
      - asset focus: using asset inventory as basis
      - threat focus: how specific threats may affect each info system
      - service focus: impact of various threats on a specific focus
    - automating threat intelligence
      - data enrichment
      - SOAR to enhance SIEM
      - machine learning for automated creation of malware signatures
    - threat hunting: organized, systematic approach to seek out indicators of compromise on a network using expertise and analytic techniques
    - Visual, Agile, and Simple Threat (VAST): threat modeling concept that integrates threat and risk mgmt into and Agile programming env on a scalable basis
    - Damage, Reproducibility, Exploitability, Affected Users, and Discoverability (DREAD): flexible threat rating system based on the answers to 5 main questions about a threat 
    - Process for Attack Simulation and Threat Analysis (PASTA): 7 stage threat modeling methodology 
    - STRIDE: threat categorization scheme by Microsoft
      - Spoofing
      - Tampering
      - Repudiation
      - Information Disclosure
      - Denial of Service (DoS)
      - Elevation of Privilege
  - Reduction analysis: also known as decomposing the application, system, or environment
  - 5 key concepts of decomposition
    - trust boundaries
    - dataflow paths
    - input points
    - privileged operations
    - details about sec stance and approach
  - Supply Chain Risk Management
    - vendor management life cycle  
      - vendor selection
      - onboarding
      - monitoring
      - offboarding
    - life cycle considerations
      - socialize with your team
      - present to stakeholders
      - schedule weekly or monthly metrics meetings
      - hold yourself accountable
    - ISO 27036: covers supplier relationships
    - nondisclosure agreements (NDAs): protect confidentiality of information
    - service level requirements (SLRs): specific requirements that a customer has for any aspect of a vendor's service performance
    - service level agreement (SLA): written contract with vendor and customer that describes the conditions of service
    - memorandum of understanding (MOU)
    - memorandum of agreement (MOA)
    - business partners agreement (BPA)
    - master service agreement (MSA)
    - work order (WO) or statement of work (SOW)
    - System and Organization Control (SOC) reports: offer an alternative approach to evaluating providers
    - SOC types
      - SOC 1: provides assurance required for customer financial audits
      - SOC 2: provides detailed assurance of confidentiality, integrity, and availability controls
      - SOC 3: provides high level, public reporting for confidentiality, integrity, an availability controls
      - Type I report: describes the controls that the service provider has in place and an opinion on the suitability of those controls
      - Type II report: includes the same information as a Type I report along with the results of control testing by the auditor 
    - SOC standards by geo
      - SSAE 18 applies in the US
      - ISAE 3402 applies internationally
  - Awareness and Training
    - Security education programs
      - security training: provide knowledge to protect org's security
      - security awareness: keep lessons learned during training top of mind
        - can test success by simulated phishing training for example, or gamification or CTFs
        - security champions
    - compliance programs: to comply with laws, regulations, standards 
      - include in security training
      - GLBA: financial institution law
      - HIPAA: healthcare regulation
      - PCI DSS: payment standards 
      - Lanham Act: regulates issuance of trademarks to protect intellectual property
      - Copyright act: creates mechanics for issuing and enforcing copyrights 
      - Digital Millennium Copyright Act (DMCA): requirements for online service providers when handling copyright complaints received from third parties
    - measuring effectiveness
      - security awareness surveys
      - phishing simulations

## More Notes
- From Destination CISSP eBook
- auditing: critical for establishing accountability, records activities that users perform and events that occur in the system
- nonrepudiation: individuals cannot deny that they took an action
- authorization: granting rights, permissions, and privileges to perform tasks or activities with a resource
- authentication: validation of an identity that has been asserted to the system
- authentication
- ISC2 Code of Ethics Preamble
  - The safety and welfare of society and the common good, duty to our principals, and to each other, requires that we adhere, and be seen to adhere, to the highest ethical standards of behavior
  - Therefore, strict adherence to this Code is a condition of certification
- ISC2 Code of Professional Ethics
  1. Protect society, the common good, necessary public trust and confidence, and the infrastructure
  2. Act honorably, honestly, justly, responsibly, and legally
  3. Provide diligent and competent service to principals
  4. Advance and protect the profession
- accountability vs responsibility
  - only one person or group or entity can be accountable
  - accountability cannot be delegated
  - responsibility can fall on multiple people
  - responsibility can be delegated
- GDPR principles
  - lawfulness, fairness, transparency
  - purpose limitation
  - data minimization 
  - accuracy 
  - storage limitation 
  - integrity and confidentiality 
  - accountability 
- OECD: org that made guidelines for privacy 
- Plan-Do-Check-Act (PDCA) cycle: for security improvement, also deming cycle
  - Plan: assess and create policies
  - Do: implement policies 
  - Check: monitor performance
  - Act: corrective and preventive measures 
- risk treatments
  - avoid
  - transfer
  - mitigate
  - accept
- security policy development steps
  - initial and evaluation
  - development
  - approval
  - publication
  - implementation
  - maintenance
- vertical enactment: industry-specific legal and regulatory compliance. like hipaa for healthcare, pci dss and glba for financial, and fisma for government
- horizontal enactment: Applies broadly across multiple industry boundaries—or all industries in a given jurisdiction—regardless of what the company does. Ex:GDPR and CCPA

#### tables

intellectual property

|              | Protects                                                                        | Disclosure Required | Term of Protection   | Protects Against                       |
| ------------ | ------------------------------------------------------------------------------- | ------------------- | -------------------- | -------------------------------------- |
| Trade Secret | Business Information                                                            | No                  | Potentially infinite | Misappropriation                       |
| Patent       | Functional innovations, Novel idea/inventions                                   | Yes                 | Set period of time   | Making, using, or selling an invention |
| Copyright    | Expression of an idea embodied in a fixed medium (books, movies, songs, etc.)   | Yes                 | Set period of time   | Copying or substantially similar work  |
| Trademark    | Color, sound, symbol, etc. used to distinguish one product/company from another | Yes                 | Potentially infinite | creating confusion |

Data Roles 

| Role            | Description                                                                                                         |
| --------------- | ------------------------------------------------------------------------------------------------------------------- |
| Data owner      | Accountable for protection of data                                                                                  |
| Data custodian  | needs clearly defined responsibilities for protecting data. needs tools, training, resources, and input from owners |
| Data processors | needs clearly defined responsibilities, processes personal data on behalf of controller / owner                     |
| Data subject    | Individual to whom personal data relates |

Policies to Guidelines 

| Policy Type | Description                                        |
| ----------- | -------------------------------------------------- |
| Policies    | Corporate laws, goals and objectives of entire org |
| Standards   | Specific info related to solutions                 |
| Baselines   | Defined minimal implementation levels              |
| Procedures  | Step-by-step instructions                          |
| Guidelines  | Recommendations or suggestions                     |

Risk Formulas 

| Risk Calculations |
| ----------------- |
| ALE = SLE X ARO   |
| SLE = AV*EF       |

Control Types 

| Control      | When   | Description               |
| ------------ | ------ | ------------------------- |
| Directive    | Before | ex. policies              |
| Deterrent    | Before | ex. security camera signs |
| Preventive   | Before | ex. fences                |
| Detective    | After  | ex.smoke alarm            |
| Corrective   | After  | ex. sprinklers going off  |
| Recovery     | After  | ex. using data backups    |
| Compensating | Before | ex. using HIPS when NIPS are used |

## References
