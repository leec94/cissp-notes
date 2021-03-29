# ISC2 CISSP Study Guide, Seventh Edition

- [ISC2 CISSP Study Guide, Seventh Edition](#isc2-cissp-study-guide-seventh-edition)
  - [Chapter 1](#chapter-1)
  - [Chapter 11](#chapter-11)
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

## Chapter 1

## Chapter 11

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

- _logical topology_: grouping of networked systems into trusted collectives
- _physical topology_: ...

#### Ring

#### Bus

#### Star

#### Mesh