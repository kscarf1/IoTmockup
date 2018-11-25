# IoT Capabilities Baseline Candidates

Add intro here. This is where we could explain what each field means for each capability.

## <a name="toc">Table of Contents
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

[NIST Cybersecurity Framework 1.1](#nistcsf) Subcategories:
*	ID.AM-1: Physical devices and systems within the organization are inventoried
*	ID.AM-2: Software platforms and applications within the organization are inventoried
*	PR.AC-1: Identities and credentials are issued, managed, verified, revoked, and audited for authorized devices, users and processes
*	PR.DS-3: Assets are formally managed throughout removal, transfers, and disposition
*	PR.MA-1: Maintenance and repair of organizational assets are performed and logged, with approved and controlled tools
*	PR.MA-2: Remote maintenance of organizational assets is approved, logged, and performed in a manner that prevents unauthorized access	

[Draft SP 800-53 Revision 5](#sp80053) Controls:
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
* ENISA:<a name="enisa"> European Union Agency for Network and Information Security (ENISA), “Baseline Security Recommendations for IoT in the context of Critical Information Infrastructures,” November 2017, <https://www.enisa.europa.eu/publications/baseline-security-recommendations-for-iot>
* GSMA:<a name="gsma"> Groupe Spéciale Mobile Association (GSMA), “GSMA IoT Security Assessment,” 2017, <https://www.gsma.com/iot/iot-security-assessment/>
* IIC:<a name="iic"> Industrial Internet Consortium (IIC), “Industrial Internet of Things Volume G4: Security Framework,” 2016, <https://www.iiconsortium.org/IISF.htm>
* IoTSF:<a name="iotsf"> IoT Security Foundation (IoTSF), “IoT Security Compliance Framework, Release 1.1," December 2017, <https://www.iotsecurityfoundation.org/best-practice-guidelines/>
* OTA:<a name="ota"> Online Trust Alliance (OTA), “IoT Security & Privacy Trust Framework v2.5,” June 2017, <https://otalliance.org/system/files/files/initiative/documents/iot_trust_framework6-22.pdf>
* UKDDCMS:<a name="ukddcms"> United Kingdom Government Department for Digital, Culture, Media & Sport (DCMS), “Secure by Design: Improving the cyber security of consumer Internet of Things,” March 2018, <https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/686089/Secure_by_Design_Report_.pdf>

Selected NIST Security Documents:
* Cybersecurity Framework:<a name="nistcsf"> “Framework for Improving Critical Infrastructure Cybersecurity, Version 1.1,” April 16, 2018, <https://doi.org/10.6028/NIST.CSWP.04162018>
* SP 800-53:<a name="sp80053"> Draft NIST SP 800-53 Revision 5, “Security and Privacy Controls for Information Systems and Organizations,” August 2017, <https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/draft>
  
[Return to Table of Contents](#toc)
