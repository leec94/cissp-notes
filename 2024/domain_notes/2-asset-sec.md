# Domain 2: Asset Security
## Table of Contents
- [Domain 2: Asset Security](#domain-2-asset-security)
  - [Table of Contents](#table-of-contents)
  - [Topics](#topics)
  - [Notes](#notes)
  - [References](#references)

## Topics
- Information and assets
  - Data classification 
  - Asset classification
- Asset handling 
- Provisioning assets
  - Data and asset ownership
  - Asset inventory
    - tangible
    - intangible
    - Asset management 
- Data lifecycle
  - Data roles
    - Owners
    - Controllers
    - Custodians 
    - Processors
    - Users/subjects
  - Data collection
  - Data location 
  - Data maintenance 
  - Data retention 
  - Data remanence 
  - Data destruction 
- Asset retention
  - End of Life (EOL)
  - End of Support 
- Data security controls and compliance
  - Data states 
    - In use
    - In transit
    - At rest
  - Scoping and tailoring
  - Standards selection
  - Data protection methods 
    - Digital Rights Management (DRM)
    - Data Loss Prevention (DLP)
    - Cloud Access Security Broker (CASB)
## Notes
- Notes from Mike Chappelle Linkedin Learning
- Data at rest: data stored for later use on storage media
- Data in transit: data being sent over a network between two systems
- Data in use: Data being actively used in a system's memory
- Big data: the use of datasets much larger than those that may be handled by conventional data processing and analytic techniques
- Data classification: programs establish the basis for other information and asset handling requirements
- Data lifecycle policy
  - Data retention policy: specifies the minimum and/or maximum periods that an organization will retain different data elements 
  - Data disposal policy: describes proper techniques for destroying data that is no longer needed by the organization
- Physical descruction: like device shredders and degaussers 
- Data security roles:
  - Data owners: business leaders with overall responsibility for data. They set policies and guidelines for their data sets. GDPR refers to this role as data controllers
  - Data steward: handle day-to-day 
  - Data custodian: actually store and process information
  - Data users: work with info in their jobs on day to day basis
  - Data subject: individuals referred to
  - Data processors: handle info on behalf of the org
- Data lifecycle
  - Create: org creates new data, either in the cloud or in an on-prem system
  - Store: data is moved into a storage repo for retention and later use
  - Use: data is viewed and/or processed by individuals and systems
  - Share: data is shared with other employees, customers, and partners
  - Archive: moved from active storage to long-term storage repos
  - Destroy: when no longer needed
- Data sanitization techniques
  - clearing: overwrites sensitive info 
  - purging: more advanced techniques, degaussing
  - destroying: completely obliterates media through shredding, pulverizing, melting, or burning. Like shredding, pulping, burning
- security baselines: set of minimum standards for systems
  - can be customized 
- security standards
  - government agencies: NIST 
  - independent organizations: CIS, like hardened images
  - venders create their own of their products
  - Microsoft Security Compliance Toolkit (SCT)
- cloud security: should be the same as servers
  - encryption, access control
- data classification policy: assigns information into categories, known as classifications, which determines storage, handling, and access requirements

| Military classification | Business Classification |
| ----------------------- | ----------------------- |
| Top Secret              | Highly Sensitive        |
| Secret                  | Sensitive               |
| Confidential            | Internal                |
| Unclassified            | Public                  |

- label requirements: identify sensitive information consistently
- information rights management (IRM)
- digital rights management (DRM): provides the owners of intellectual property with the technical means to prevent the unauthorized use of their content through the use of encryption technology
- host-based DLP: uses software agents installed on a single system
- network-based DLP: scans network transmissions for sensitive information
- cloud-based DLP: as a managed security service
- change management: ensures that an organization follows a standard process for requesting, reviewing, approving, and implementing changes to information systems
  - versioning: assigns numbers to each version
  - diagrams: important for troubleshooting and incident investigations
- request for changes (RFC): submission and documentation of a change with description, impact, risk assessment, schedule, and more
- baselines: provides a configuration snapshot
- asset management: lifecycle approach
- media management: use to track highly sensitive information
- Device enumeration: probes the network looking for devices that are not actively managed.
- end of life terms
  - end of sale: no longer offered for purchase, but vendor will support existing customers
  - end of support: vendor will reduce or eliminate support for existing users of the product
  - end of life (EOL): vendor will no longer provide any support or updates for the product
- product tampering: unauthorized alteration of products
- counterfeits: products made without authorization
- implants: unauthorized hardware or software embedded in a legitimate product for covert surveillance or control 
- supply chain controls
  - silicon root of trust
  - physically unclonable functions
  - software bill of materials (SBOM)
- 


## References