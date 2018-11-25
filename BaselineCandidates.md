# IoT Capabilities Baseline Candidates

Add intro here. This is where we could explain what each field means for each capability.

## Table of Contents<a name="toc">
* [Capability 1: The IoT device can be identified both logically and physically.](#capability-1)
* Capability 4: The IoT device’s software and firmware can be updated using a secure, controlled, and configurable mechanism.
* Capability 5: The IoT device’s configuration can be securely changed by authorized users when needed, including restoring a secure default configuration, and unauthorized changes to the IoT device’s configuration can be prevented.
* Capability 7: Local and remote access to the IoT device and its interfaces can be controlled.
* Capability 9: The IoT device can use cryptography to secure its stored and transmitted data.
* Capability 10: The IoT device can use well-known and standardized protocols for all layers of the device’s transmissions.
* Capability 11: The IoT device can log the pertinent details of its security events and make them accessible to authorized users and systems.

*** 
### Capability 1:<a name="capability-1"> The IoT device can be identified both logically and physically. 

Evaluation Criteria:
* Utility: The ability to monitor a network and identify rogue devices requires, in part, the ability to identify those devices and their functions. Additionally, the connection between physical and logical identity is important towards on-the-ground risk mitigations in real networks (e.g., physically replacing a compromised device). Important for the scale and diversity of IoT devices and networks to help identify devices on the network and what security is important for them at that layer. Therefore, this capability is fundamental to many approaches and aspects of security.
* Dependency: Asset management, access management, vulnerability management
* Verifiability: Easily verified by looking for logical and physical identifiers.

NIST Cybersecurity Framework 1.1 Subcategories:
*	ID.AM-1: Physical devices and systems within the organization are inventoried
*	ID.AM-2: Software platforms and applications within the organization are inventoried
*	PR.AC-1: Identities and credentials are issued, managed, verified, revoked, and audited for authorized devices, users and processes
*	PR.DS-3: Assets are formally managed throughout removal, transfers, and disposition
*	PR.MA-1: Maintenance and repair of organizational assets are performed and logged, with approved and controlled tools
*	PR.MA-2: Remote maintenance of organizational assets is approved, logged, and performed in a manner that prevents unauthorized access	

Draft SP 800-53 Revision 5 Controls:
*	CM-8, System Component Inventory
*	IA-3, Device Identification and Authentication
*	PE-20, Asset Monitoring and Tracking

References to Selected IoT Guidance Documents:
*	[BITAG](#bitag): 7.2, 7.6
*	[CSA1](#csa1): 5.2.1.1, 5.3.1, 5.3.4
*	[CSA2](#csa2): 11, 14
*	[CTIA](#ctia): 4.13
*	[ENISA](#enisa): PS-10, TM-21
*	[GSMA](#gsma): CLP11_5.2.1, CLP13_6.6.2, 6.8.1, 6.20.1, 8.11.1
*	[IIC](#iic): 7.3, 8.5
*	[IoTSF](#iotsf): 2.4.14.3-4, 2.4.8.1
*	[UKDDCMS](#ukddcms): 4

[Return to Table of Contents](#toc)
***
## References

Selected IoT Guidance Documents:
* BITAG:<a name="bitag"> Broadband Internet Technical Advisory Group (BITAG), "Internet of Things (IoT) Security and Privacy Recommendations," November 2016, <https://www.bitag.org/documents/BITAG_Report_-_Internet_of_Things_(IoT)_Security_and_Privacy_Recommendations.pdf> 
* CSA1:<a name="csa1"> Cloud Security Alliance (CSA) Mobile Working Group, “Security Guidance for Early Adopters of the Internet of Things (IoT),” April 2015, <https://cloudsecurityalliance.org/download/new-security-guidance-for-early-adopters-of-the-iot/>
* CSA2:<a name="csa2"> CSA IoT Working Group, “Identity and Access Management for the Internet of Things,” September 2015, <https://cloudsecurityalliance.org/download/identity-and-access-management-for-the-iot/>
* CTIA:<a name="ctia"> CTIA, “CTIA Cybersecurity Certification Test Plan for IoT Devices, Version 1.0,” August 2018, <https://api.ctia.org/wp-content/uploads/2018/08/CTIA-IoT-Cybersecurity-Certification-Test-Plan-V1_0.pdf>
* ENISA:<a name="enisa"> European Union Agency for Network and Information Security (ENISA), “Baseline Security Recommendations for IoT in the context of Critical Information Infrastructures” [12]
* GSMA:<a name="gsma"> Groupe Spéciale Mobile Association (GSMA), “GSMA IoT Security Assessment”  [13]
* IIC:<a name="iic"> Industrial Internet Consortium (IIC), “Industrial Internet of Things Volume G4: Security Framework” [14]
* IoTSF:<a name="iotsf"> IoT Security Foundation (IoTSF), “IoT Security Compliance Framework, Release 1.1” [15]
* OTA:<a name="ota"> Online Trust Alliance (OTA), “IoT Security & Privacy Trust Framework v2.5” [16]
* UKDDCMS:<a name="ukddcms"> United Kingdom Government Department for Digital, Culture, Media & Sport (DCMS), “Secure by Design: Improving the cyber security of consumer Internet of Things” [17]
