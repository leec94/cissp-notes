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
- logging
  - network or netflow data, DNS, system, application, authentication, VoIP, dump files, vuln scans 
- syslog: provides a logging standard
  - message components:
    - header: timestamp, source address
    - facility: source of message on sending system, between 0 and 23
      - 0 is from kernel, 1 is user level message, 2 is from mail service
    - severity: importance value from 0 to 7
    - message: details of the situation
  - syslog versions
    - syslog: original standard rarely used today
    - syslog-ng: added security and delivery enhancements in 1998
    - rsyslog: further enhancements in 2004
    - journalctl: uses binary journal format
- nxlog: centralizes management of disparate logs
- - SIEM: central, secure collection point for logs, and detects patterns that other systems might miss
- security orchestration automation response (SOAR): enhanced version of a SIEM
- playbooks: process focused responses to security events, including both human and automated actions
- runbooks: automated responses to security events that execute immediately and aid human investigators
- continuous monitoring
  - maps to risk tolerance
  - adapts to ongoing needs 
  - actively involves management
- security monitoring: NIST SP 800-137 process
  - define: define a continuous monitoring strategy based upon risk tolerance that maintains clear visibility into assets, vulnerabilities, threats and business impact
  - establish: outline the metrics and monitoring assessment frequencies
  - implement: collect the metrics, perform the assessments, and build reports in an automated way
  - analyze/report
  - respond
  - review/update
- anomaly analysis: detects outlier data points 
- behavioral analysis: detects unusual user activity
- availability analysis: provides uptime info
- endpoint monitoring: monitor processor, memory, and file system activity
- user and entity behavior analytics (UEBA): compares user activity to individual baselines
- code reviews: peer analysis to assess code
- fagan inspection: formalized, 6 step code review process
  - planning: preparing materials, identifying participants, and scheduling the review
  - overview: assigning roles to participants and providing an overview of the software
  - preparation: participants independently examine code for potential defects
  - meeting: during inspection meeting, reviewers discuss and formally identify any code defects
  - rework: code developers correct any defects identified during inspection
  - follow up: leader verifies that defects were resolved and completes project documentation
- static testing: uses automated techniques to analyze code for errors and security flaws without actually executing the code
- software composition analysis (SCA): identifies use of open source software libraries
- dynamic testing: executes code to verify that it's functioning correctly and doesn't have security flaws
- synthetic transactions: scripted sets of input provided to code
- interactive testing: allows tester to interact with software and guide the process as the test is underway
- benchmarks: ensure that code tests cover relevant standards
- fuzzing: software testing technique that feeds software many different input values in an attempt to cause an unpredictable state or unauthorized access
- interface testing: API, UIs, and physical interface testing
  - network interface testing: ensures reliable interactions between system components
- misuse case testing: evaluates software from attacker's perspective
  - examples: unexpected input, missing input, injection attacks, unavailable funds
- test coverage analysis
  - variable types include use cases, functions, lines of code, and conditional branching
- test coverage: percentage of software tested, or "cases tested" / "total cases"
- software development kits (SDKs): provides programming resources
- APIs: allow interaction with remote services
- mitigate software risks: input validation, encrypt sensitive data, enforce least privilege, and test all code prior to deployment
- sandboxing: isolates development code
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

