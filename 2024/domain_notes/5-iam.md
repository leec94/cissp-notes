# Domain 5: Identity and Access Management (IAM)
## Table of Contents
- [Domain 5: Identity and Access Management (IAM)](#domain-5-identity-and-access-management-iam)
  - [Table of Contents](#table-of-contents)
  - [Topics](#topics)
  - [Notes](#notes)
      - [Authentication Services Ports](#authentication-services-ports)
  - [References](#references)

## Topics
- Asset controls
  - information
  - system
  - devices 
  - facilities 
  - applications 
  - services
- Identification and authentication strategy of people, devices, and services
  - groups and roles
  - Authentication
  - Authorization 
  - Accounting
  - AAA
    - MFA
    - Passwordless authentication
  - session management
  - registration of identity
  - proving of identity
  - establishment of identity
  - federated identity management (FIM)
  - credential management systems
    - password vault
  - SSO
  - Just-in-Time
- Federated identity with third party service
  - on-prem
  - cloud
  - hybrid
- Authorization mechanisms
  - RBAC
  - rule based access controls
  - MAC
  - DAC
  - ABAC
  - risk based access control 
  - access policy enforcement 
    - policy decision point
    - policy enforcement point 
- Identity management lifecycle
  - account access review
    - user
    - system
    - service
  - provisioning and deprovisioning 
    - on/offboarding 
    - transfers
  - role definition and transition 
    - people assigned to new roles
  - privilege escalation 
    - use of sudo and auditing its use
  - service accounts management
- Implement authentication systems

## Notes
- Notes from Mike Chappelle Linkedin Learning
- authentication, authorization, and accounting (AAA)
- identification
  - usernames
- authentication 
- authorization
- accounting
- something you know
  - passwords, passphrases, passkeys, security question
- something you are 
  - biometric authentication
  - examples: fingerprint, eye scan, facial recognition, voiceprints
- something you have
  - physical possession of a device
  - examples: smartphone with authentication app, authentication key fob
- biometric techniques 
- false acceptance: system misidentifiers an individual as an authorized user
  - false acceptance rate (FAR)
- false rejection: system fails to recognize an authorized user
  - false rejection rate (FRR)
- crossover error rate (CER): point in which equal false acceptance and false rejection rates
- multifactor authentication
- HOTP
- TOTP
- password authentication protocol (PAP): does not use any encryption, not secure
- CHAP: encrypted alternative to PAP. uses challenge value and password is hashed
  - MS-CHAP and MS-CHAPv2: both are insecure
- federation 
- SSO: single login screen that creates a session that persists across other systems 
  - shibboleth: open source that works in federated situations
- federated identity management
- trust characteristics
  - direction 
    - one way: a trusts v, but b does not trust a
    - two way: a and b both trust each other
  - transitivity
    - transitive: trust relationships transfer across domains
    - nontransitive: trust relationships do not transfer across domains
- RADIUS: centralized approach for AAA for enterprises
  - Remote Authentication Dial-In User Service
  - radius client
  - radius server
  - disadvantages: uses UDP, does not encrypt the whole sequence
- Kerberos: ticket based authentication system that allows users to authenticate to a centralized service, then use tickets to gain access to distributed services
  - ticket granting ticket
  - authentication server
  - ticket granting server (TGS)
- lightweight directory access protocol (LDAP): provides the means to query a centralized directory service such as Microsoft AD
- NTLM: NT LAN manager, was used before kerberos. depends on hash-based challenge-response protocol. has weak encryption and pass the hash
  - pass the hash: allows the use of credentials from one system to gain access to another
- security assertion markup language (SAML): allows SSO within a web browser across a variety of systems
  - benefits: true SSO experience for end users, no credential access for service providers
  - identity provider: provides the proof of identity, usually the end user's employer, school, or other account provider
- identity-as-a-service (IDaaS) providers: allows organizations to move IAM to the cloud
- directory integration: synchronizes with org's existing on-prem or cloud-based directory to obtain user info
- app integration: replaces auth services for many SaaS products, simplifying user and admin experience
- OAuth: authorization protocol 
- OpenID connect: authentication protocol
- digital certificates and key based authentication
  - certificate authorities create digital certificates for public keys used in authentication  
  - uses: server to server connections, SSH connections, smart cards (CAC/PIV), network access (802.1x)
- passwordless authentication
  - benefits: phishing resistance, simplicity for users, reduced management overhead, physical control of authentication objects
  - challenges: account lockout and cost of security keys
- security keys
- accountability: every action taken on a system can be traced back to an individual user without any ambiguity, and without allowing the user to deny responsibility for that action
  - identification and authentication
  - logging
- session management: uses timeouts and screen savers to disconnect user sessions that have gone idle, preventing an unauthorized individual from taking control of an abandoned user session
- timeouts: disconnects user session after a predetermined time, or inactivity. can also require reauthentication for sensitive activities. 
  - screensaver is common timeout mechanism
- least privilege
- segregation of duties 
- job rotation
- mandatory vacation
- account types: user, privileged, guest, shared, service 
- group policy object (GPO): applies configuration settings to users and computers
- password policies: length, expiration, lockout policies, and disablement for unused accounts 
  - current NIST guidance says complex passwords should be allowed, not required, as long as MFA is used 
  - NIST says that passwords should not expire
- password recovery mechanisms: allow users to reset passwords self service, relieves help desk burden
- roles: groups permissions to allow shared security settings, such as windows security groups
  - benefits: simplifies account management, may assign permissions to new users by adding a role to the user, and admin may remove permissions from deparding users by removing the role. removes the need for shared accounts 
- account monitoring: 
  - inaccurate permissions
  - attestation: formal approval of user privileges
  - unauthorized use: illegitimate actions by legitimate users
  - other violations: impossible travel, unusual network location logins, unusual time-of-day logins, deviations from normal behavior, deviations in volume of data transferred
- user account audits: 
  - pull list of account permissions, review, make necessary adjustments, and prioritize review of users with job changes
- geotagging
- geofencing: alerts admins to devices leaving defined boundaries
- provisioning: after onboarding, admins create authentication credentials and grant appropriate authorization
- deprovisioning: during offboarding, admins disable accounts and revoke authorizations at the appropriate time
- routine workflow: disables accounts on a scheduled basis for planned departures
- emergency workflow: immediately suspends access when user is unexpectedly terminated
- privilege creep: users accumulate privileges as they transfer between roles, violating the principle of least privilege














#### Authentication Services Ports

| Services    | Port |
| ----------- | ---- |
| Kerberos    | 88   |
| LDAP        | 389  |
| Secure LDAP | 636 |



## References