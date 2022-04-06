---
layout: default
---


## [Palo Alto Networks: Cortex XDR](https://www.youtube.com/watch?v=Mx93xlfVF34)

[//]: #  There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

## Cortex reimagines SecOps to stop successful attacks: 
## What is XDR?
Extended detection and response or XDR is a new approach to threat detection and response that provides holistic protection against cyberattacks, unauthorized access and misuse. Coined by Nir Zuk, Palo Alto Networks CTO, in 2018, XDR breaks down traditional security silos to deliver detection and response across all data sources.

According to analyst firm Gartner, XDR is “a SaaS-based, vendor-specific, security threat detection and incident response tool that natively integrates multiple security products into a cohesive security operations system.” The definition of XDR from Forrester Research is a bit more expansive:  “The evolution of EDR, which optimizes threat detection, investigation, response, and hunting in real time. XDR unifies security-relevant endpoint detections with telemetry from security and business tools such as network analysis and visibility (NAV), email security, identity and access management, cloud security, and more. It is a cloud-native platform built on big data infrastructure to provide security teams with flexibility, scalability, and opportunities for automation.”


## How Does XDR Work?
XDR solutions bring a proactive approach to threat detection and response. It delivers visibility across all data, including endpoint, network, and cloud data, while applying analytics and automation to address today’s increasingly sophisticated threats. With XDR, cybersecurity teams can:
* Identify hidden, stealthy and sophisticated threats proactively and quickly
* Track threats across any source or location within the organization
* Increase the productivity of the people operating the technology
* Get more out of their security investments
* Conclude investigations more efficiently 

![](https://i.ytimg.com/vi/x7yhRu6HGw4/maxresdefault.jpg)

## Cortex XDR Architecture
The Cortex XDR architecture varies slightly between the product versions but includes several standard components. Both editions rely on the Cortex Data Lake and are designed to correlate your log data across your devices.

Basic platform components include:

#* Cortex XDR app—a user interface (UI) that provides visibility into your Data Lake. From this UI, you can triage and investigate alerts, take action for remediation, and define your detection and response policies.
#* Cortex Data Lake—a storage resource for cloud-based logging that is designed to hold your log data from all sources. The Data Lake centralizes your data, enabling the XDR engine to correlate events and create alerts.
## Advanced platform components include:

* Analytics engine—a security service that uses network and endpoint data to detect and respond to threats. It applies behavioral analytics to identify both known and unknown threats through comparison to known and accepted user or device behaviors.
* Next-generation firewalls—virtual or on-premise firewalls that you can use to enforce secure traffic policies in your network. These firewalls include machine learning technologies to help detect known and unknown threats.
* Prisma Access and GlobalProtect—services you can use to extend your firewall protections to remote and mobile users. These services enable you to forward remote traffic logs to your Data Lake to allow joint correlation with local logs.
* External firewalls and alerts—through integration, you can ingest external firewall logs and alerts into your Cortex XDR system. This is possible through the Cortex XDR API. These data points can then be combined with your Cortex data to provide more context for events and enable more thorough response.
* Cortex XDR agents—software installed on endpoints that are used to collect and forward data. These agents can also perform local analyses and can consume WildFire threat intelligence for improved detection of threats. All collected data is also sent to the Data Lake for joint analysis.
Different XDR security solutions offer different architectures. For information about McAfee XDR or Cisco XDR check out our in-depth guides.

![](https://www.paloaltonetworks.com/content/dam/pan/en_US/images/products/cortex/cortex-data-lake.png?imwidth=480)

## Cortex XDR Key Capabilities: 
Cortex XDR provides several key capabilities, designed to secure an organization’s networks and devices.

## Safeguard assets with endpoint protection

Cortex XDR provides endpoint protection against malware, fileless attacks, ransomware, and exploits. Any downloaded files are examined by an analysis engine with AI capabilities.

Additionally, behavioral analyses help identify and stop malicious data transfers or processes. Organizations can also integrate with Palo Alto Networks WildFire malware prevention service for increased security and protection.

## Securely manage USB devices

Cortex XDR includes Device Control, a feature designed to monitor and secure USB access to devices. The feature is agentless. It enables organizations to restrict device usage according to endpoint, type, vendor, or Active Directory identities. Device control also enables organizations to limit read and write permissions according to USB device ID.

## Protect endpoint data with host firewall and disk encryption

Firewalls and disk encryption protect endpoints from malicious traffic and reduce the damage done if attackers bypass firewalls. The Cortex XDR firewall provides controls for inbound and outbound communications.

Disk encryption can be directly integrated with BitLocker and organizations can encrypt and decrypt data on endpoint devices. Firewall and encryption settings are managed from the UI console.

## Hunt for threats

The Cortex XDR Pro version includes optional features for managed threat hunting and features for manual hunting. Threat hunting can help uncover insider threats, targeted attacks, and hidden malware. It requires carefully searching through system and event data to identify suspicious or malicious activity.

The manual features included in Cortex XDR enable organizations to use flexible search features to identify a range of indicators of compromise (IOCs) or behavioral indicators of compromise (BIOCs). IOCs or BIOCs are threat signatures, hashes, addresses, or metadata used to identify known threats.

Managed options provide 24/7 support with dedicated threat hunting experts. These hunters search through an organization’s data and provide detailed threat reports on their findings.

## Natively integrate with Cortex XSOAR

Cortex XSOAR (security orchestration, automation, and response) is a solution that can be integrated into Cortex XDR. SOAR solutions are designed to enable automated responses to, typically low-level threats, and can help significantly speed response time.

The Cortex XSOAR solution enables organizations to define automation playbooks for incident response. These playbooks can be used to define actions across 370 third-party tools. Playbooks can also ingest incident data, access alerts, and update Cortex XDR incident fields.

## Beyond XDR Security With Cynet’s Autonomous Breach Protection
Cynet 360 is an autonomous breach protection platform that works in three levels, providing XDR, SOAR, and 24/7 MDR in one unified solution. Cynet natively integrates these three services into an end to end, fully-automated breach protection.

## Cynet’s XDR layer includes the following capabilities:

* Endpoint protection—multilayered protection against malware, ransomware, exploits and fileless attacks.
* Network protection—protecting against scanning attacks, MITM, lateral movement and data exfiltration.
* User protection—preset behavior rules coupled with dynamic behavior profiling to detect malicious anomalies.
* Deception—wide array of network, user, file decoys to lure advanced attackers into revealing their hidden presence.


### I hope this was useful as IoT get deeper and deeper in our lifes.


```
Thank you readers, and wait for next week blog
For Contact e-mail me at ramirez368@hotmail.com

```
