# Chapter 7: PKI and Cryptographic Applications
## Notes
  - Remote Authentication Dial-In User Service (RADIUS): centralized auth
    - used by many ISPs. users can access the ISP from anywhere and the ISP server forwards the user's connection request to the RADIUS server
  - Terminal Access Controller Access-Control System (TACACS+): alternative to RADIUS
    - TACACS
    - Then XTACACS, created by Cisco
    - finally TACACS+, open publically documented protocol, most commonly used of the three protocols
      - encrypts all of the authentication information 
      - TCP port 49
  - Diameter: enhanced version of RADIUS, uses more protocols
    - uses TCP 3868