---
title: CIA Triad
---

### Confidentiality:

  **Data confidentiality** (confidential information is not made available of disclosed to unauthorized individuals)
  
  **Privacy** (individuals have control or influence over the collection and storage of information related to them as well as who can access and disclose the information)
	  - Student grade information is an asset whose confidentiality is considered to be highly important
	  - Regulated by FERPA in USA Family Educational Rights and Privacy
	  - Australian is APPs Australian Privacy Principle
### Integrity:

**Data integrity** (information and programs are only accessed and changed in a specific manner and by authorized people)

**System Integrity** (system is free of unauthorized manipulation of the system)
	  - Patient information stored in a database – inaccurate information could result in serious harm or death to a patient and expose the hospital to massive liability
	  - A Web site that offers a forum to registered users to discuss some specific topic would be assigned a moderate level of integrity
### Availability

Assures that the systems work promptly and service is not denied to authorized users
**DDoS (Ping ICMP)** ICMP is a protocol (Internet Control Message Protocol)
	  - The more critical a component or service, the higher the level of    availability required Example: Stock Exchange Website
	  - A moderate availability requirement is a public Web site for a university
### Two more extra in CIA triad:
##### Authenticity: 

Verifying that users are who they say they are and that each input arriving at the system is from a trusted source
##### Accountability:

The security goal that basically keeps track/log of what each entity does so that the we can hold a entity accountable

### Risk Level

**High:** Severe or catastrophic adverse effect on organizational operations, organizational assets, or individuals

**Moderate:** Expected to have a serious adverse effect on organizational operations, organizational assets, or individuals 

**Low:** Expected to have a limited adverse effect on organizational operations, organizational assets, or individuals

### OSI Security Architecture:

**OSI(Open Security Interconnection):** 7 layers that help us understand how messages travel(Standard steps to follow to send messages made by ISO)

**Security Attack:** Any attack that compromises the security of information

**Security Mechanism:** A process that is designed to detect, prevent, or recover from attacks (algorithms)

**Security service:** A set of security mechanisms that are made for counter attack and enhance the entire organizations transfers and access of the network

### Security Attacks

**Passive attacks:** Learns and makes use of the system information but never changes or affects the system

**Active attacks:** Alters the system resources to affect their operation

**RFC 4949(Internet Security Glossary, Version 2):** A comprehensive 334-page document providing standardized definitions, abbreviations, and explanations for information system security terminology

**X.800(Security architecture for Open Systems Interconnection (OSI) for CCITT applications):** A foundational 1991 international standard defining the security architecture for Open Systems Interconnection (OSI)

#### Active Attacks

**Masquerade:** Impersonation of a different entity(Involves one of the other forms of attack as well)

**Replay:** Includes the passive capture of data and its transmissions to reproduce an unauthorized effect(reuses the transmissions)

**Modification of messages:** Some portion of a legitimate message is altered, or messages are delayed or reordered to produce an unauthorized effect (changes messages from $10 to $1000 in between transmissions)

**Denial of Service:** Prevents normal use of management or communication facilities Ex. messages or emails

### X.800 Service Categories

- **Authentication:** Makes the recipient know that the message is from the person its supposed to be from. Also makes sure that the connect between two entities is not being tampered with.
- **Access control:** Being able to control who has access to host systems and applications through communications links. Each entity is identified at the first attempt of connection and is given its own set of protocols to be able to access the stuff it needs
- **Data confidentiality:** The protection of data and communications from passive attacks and spyware. Making sure the data is not getting out or leaking anywhere. Protecting the traffic in a network from being analyzed 
- **Data integrity:** Makes sure the data received is exactly the same as it was when it was sent from the sender
- **Nonrepudiation(Accountability):** Holds both entities accountable and prevents them from saying "I didn't do it"

#### Difference between Security Services and Mechanisms is services is what protection we want vs how we get that protection

**Availability Service** is a service making sure the service is always accessible from authorized users. Protects against DDOS attack



