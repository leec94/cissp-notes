# Domain 6: Security Assessment and Testing
## Table of Contents
- [Domain 6: Security Assessment and Testing](#domain-6-security-assessment-and-testing)
  - [Table of Contents](#table-of-contents)
  - [Topics](#topics)
  - [Notes](#notes)
      - [quick ref tables](#quick-ref-tables)
      - [important stuff](#important-stuff)
  - [References](#references)

## Topics
- Sec assessment strategies 
  - Internal
    - within org control
  - External
    - outside org control
  - Third-party
    - outside enterprise control
  - Location
    - on-prem
    - cloud
    - hybrid 
- Sec control testing
  - vuln assessment
  - pen testing
    - red team
    - blue team
    - purple team
  - log reviews
  - synthetic transactions/benchmarks
  - code review and testing
  - misuse case testing 
  - coverage analysis
  - interface testing
    - user interface
    - network interface
    - application programming interface (API)
  - breach attack simulations 
  - compliance checks
- collect security process data
  - account management
  - management review and approval
  - key performance and risk indicators
  - backup verification data
  - training and awareness
  - disaster recover (DR)
  - business continuity (BR)
- analyze test output and generate report
  - remediation
  - exception handling
  - ethical disclosure
- conduct or facilitate security audits
  - internal, external, third-party, location

## Notes
- Notes from Mike Chappelle Linkedin Learning
- patching process
- vulnerability management
  - network vuln scans, application scans, and web app scans as part of vuln management program
- vulnerability scanning 
  - Enable safe checks: allows and disallows dangerous plug-in use
  - Sensitivity level: determines how likely the scanner is to detect a vulnerability and/or report a false positive
  - Plug-ins: setting that should be modified in order to limit the tests performed by vulnerability scanners to only those that affect the installed OS
- PCI DSS requirements
  - quarterly internal and external vuln scans
  - repeat scans after significant change
  - use approved scanning vendor (ASV)
  - remediate and rescan until you achieve a clean report
- FISMA requirements
  - conduct vuln scans regularly
  - analyze results of scans
  - remediate legitimate vulns
  - share info with other agencies
- asset inventory: provides starting point for vuln scanning
  - lightweight scans can be done with scanners like Nessus
- determine risk
  - impact
    - what's the highest data classification handled by the system?
  - likelihood
    - what's the network exposure?
    - what services are exposed?
  - criticality
    - what impact does the system have on business operations? 
- agent-based scanning: installs software on each target device
- credentialed scanning: uses passwords to log into systems
- scan report analysis prioritization factors
  - vulnerability severity
  - system criticality
  - information sensitivity
  - remediation difficulty
  - system exposure
- true positive
- false positive
- true negative
- false negative
- white box: known environment, attackers have full access to information before they begin the test
- gray box: partially known environment, attackers have limited info before they begin the test
- black box: unknown environment, attackers have no info about the target before they begin the test
- pen test process
  - discovery phase
  - attack phase: gain access, escalate privileges, system browsing, and install additional tools
- warflying: wardriving with drones and UAVs
- pivot: after exploiting a vuln in a system, attackers use that system as a base from which to target other systems on the same local network
- persistence: after exploiting a vuln in a system, attackers install tools on that system to allow future access, even if the initial vuln is corrected
- breach and attack simulation (BAS): platform that automates penetration testing by injecting threat indicators onto systems and networks
- zero-day vulnerability: no public knowledge or patch
- window of vulnerability: begins with the initial discovery of an issue and ends with the successful deployment of a patch 
- vulnerable disclosure options
  - share privately with vendor
  - share publicly with security community
  - keep knowledge secret for personal use or sale
- responsible disclosure: share newly discovered vulns with the vendor first, providing them with a deadline after which the vuln will be publicly disclosed
- bug bounty programs: open security testing
  - external vendors like HackerOne for example
  - self-managed vendors are an option, usually for larger organizations
- red team: attackers who will try to undermine security
- blue team: defenders who will secure the systems from attack
- white team: observers and judges who manage the exercise
- purple team: combines knowledge from the red and blue team during lessons-learned session after the exercise
- capture the flags (CTFs)
-  


#### quick ref tables

PCI DSS CVSS Scores

| CVSS Score | Severity Level | Scan results |
| ---------- | -------------- | ------------ |
| 0.0 - 3.9  | Low            | Pass         |
| 4.0 - 6.9  | Medium         | Fail         |
| 7.0 - 10.0 | High           | Fail |

#### important stuff

the average cybersec professional
![the average cybsersec professional](image-2.png)


## References

