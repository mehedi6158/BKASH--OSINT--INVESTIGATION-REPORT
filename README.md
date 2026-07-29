# BKASH--OSINT--INVESTIGATION-REPORT


# Executive Summary
This report presents a comprehensive passive Open-Source Intelligence (OSINT) assessment of **bKash Limited**, one of Bangladesh's leading mobile financial service providers. The assessment examines the organization's publicly available information, including its corporate profile, official digital presence, domain registration, DNS infrastructure, SSL/TLS configuration, web technologies, IP and network infrastructure, email security, and other publicly accessible technical assets.

The investigation was conducted exclusively using passive OSINT techniques and information obtained from publicly available sources. No intrusive testing, exploitation, vulnerability scanning, or unauthorized access was performed during the assessment.

The objective of this report is to provide a structured overview of bKash Limited's publicly exposed digital footprint and technical infrastructure, identify observable security controls, and document findings based solely on publicly available information.


# Target Profile

| Field | Value |
|-------------|-----------------|
| Organization| bkash Limited|
|Domain| bkash.com|
|Website| https://bkash.com|
|Industry| Mobile Financial Services| 
|Headquarters| Shadhinata Tower,Bir Sreshtha Shaheed Jahangir Gate,Dhaka Cantonment, Dhaka 1206|
|Country | Bangladesh| 
|Assessment Type | Passive OSINT|
|Assessment Date | 28 July 2026|
|Investigator | Mehedi hasan|
|Report Version |001|

## Company Overview

bKash Limited is a leading mobile financial services (MFS) provider in Bangladesh. The company offers a wide range of digital financial services, including money transfers, merchant payments, mobile recharge, utility bill payments, cash-in and cash-out services, and other digital payment solutions through its mobile platform.

The organization serves millions of customers across Bangladesh through an extensive network of agents, merchants, and digital channels. Its official website (**bkash.com**) provides information about the company's products, services, customer support, and corporate activities.

This report focuses on the publicly accessible digital footprint and technical infrastructure associated with the organization's official online presence.

## Scope

This assessment focuses on the publicly accessible digital footprint of **bKash Limited** and its official online infrastructure. The investigation was conducted exclusively using passive Open-Source Intelligence (OSINT) techniques and information obtained from publicly available sources. The objective is to identify and document publicly observable technical information without performing any intrusive or unauthorized activities.

### Included

- Company Profile
- Official Website Assessment
- Public Digital Presence
- Domain Intelligence
- WHOIS Analysis
- RDAP Analysis
- DNS Infrastructure Analysis
- Domain Name System (DNS) Records
  - A Records
  - AAAA Records
  - NS Records
  - MX Records
  - TXT Records
  - SOA Records
  - CNAME Records
  - CAA Records
  - SPF
  - DKIM
  - DMARC
- IP Address & ASN Analysis
- HTTP Security Headers Assessment
- Web Technology Stack Identification
- SSL/TLS Certificate Analysis
- Hosting Infrastructure Review
- CDN & Web Application Firewall (WAF) Identification
- Email Security Assessment
- Certificate Transparency Review
- Publicly Available Infrastructure Information
- Public Reputation Assessment


## 5. Methodology

This assessment was conducted using passive Open-Source Intelligence (OSINT) techniques. All information was collected from publicly available sources without interacting with or attempting to gain unauthorized access to the target systems.

### Data Collection Methods

- Public Domain Registration Analysis
- WHOIS & RDAP Information Collection
- DNS Enumeration
- SSL/TLS Certificate Inspection
- HTTP Security Header Analysis
- Technology Stack Identification
- IP & ASN Intelligence
- Hosting Infrastructure Analysis
- Email Security Assessment
- Public Reputation Review

### Tools & Sources

- ICANN Lookup
- RDAP Lookup
- Web chek
- Whois.com
- Google Admin Toolbox
- DNSChecker
- MXToolbox
- SSL Labs
- SecurityHeaders
- Wappalyzer
- Netcraft
- IPinfo
- Hurricane Electric BGP Toolkit
- crt.sh
- VirusTotal


  ---

# Technical Assessment

The following sections present the technical findings collected during the passive Open-Source Intelligence (OSINT) assessment of **bKash Limited**. The analysis is based exclusively on publicly available information and focuses on the organization's externally observable digital infrastructure and security posture.

---

## Domain Intelligence

### Domain Details



## 6. Domain Intelligence

### Domain Details

| Field | Value |
|--------|-------|
| Domain Name | bkash.com |
| Top-Level Domain (TLD) | .com |
| Organization | bKash Limited |
| Registrar | PDR Ltd. d/b/a PublicDomainRegistry.com |
| Registry | Verisign |
| Registration Status | Active |
| Domain Status | clientTransferProhibited |
| Creation Date | 10 January 2010 |
| Last Updated | 18 June 2020 |
| Expiration Date | 10 January 2030 |
| DNSSEC | Signed |

### Observation

The domain is active and registered through an ICANN-accredited registrar. It has remained registered since 2010, has a valid registration period until 2030, and DNSSEC is enabled.
...

### Analysis

The domain information indicates a long-established and actively maintained domain. Security features such as `clientTransferProhibited` and DNSSEC are enabled, and no significant anomalies were identified in the publicly available registration data.
...


## Whois Details

| Field | Value |
|-------|-------|
| Domain Name | bkash.com |
| Registrar | PDR Ltd. d/b/a PublicDomainRegistry.com |
| Registrar IANA ID | 303 |
| WHOIS Server | whois.publicdomainregistry.com |
| Creation Date | 10 January 2010 |
| Updated Date | 18 June 2020 |
| Expiration Date | 10 January 2030 |
| Domain Status | clientTransferProhibited |
| Name Servers | adi.ns.cloudflare.com, hal.ns.cloudflare.com |
| DNSSEC | Signed |
| Registrar Abuse Contact | abuse-contact@publicdomainregistry.com |

### Observation

The WHOIS records confirm that the domain is actively registered through PDR Ltd. d/b/a PublicDomainRegistry.com. The registration has remained valid since 2010 and is protected by the clientTransferProhibited status. The domain is configured with Cloudflare authoritative name servers, and DNSSEC is enabled.

### Analysis

The WHOIS information indicates a long-established and actively maintained domain with a valid registration period until 2030. The presence of domain transfer protection and DNSSEC support demonstrates the implementation of standard domain security measures. No significant inconsistencies were identified in the publicly available WHOIS data.

## RDAP Details

| Field             | value                     |
| ----------------- | -------------------------------- |
| Domain Name       | bkash.com                   |
| RDAP Server       | https://rdap.verisign.com/com/v1/             |
| Registrar         | PDR Ltd. d/b/a PublicDomainRegistry.com                 |
| Registrar IANA ID | 303                   |
| Domain Status     | Active|
| Object Status     | clientTransferProhibited  |
| Creation Date     |10 January 2010           |
| Updated Date      | 18 June 2020                   |
| Expiration Date   | 10 January 2030                  |
| Name Servers      | adi.ns.cloudflare.com, hal.ns.cloudflare.com       |
| DNSSEC            | Signed               |

### Observation 

The RDAP records confirm that the domain is actively registered through an ICANN-accredited registrar. The domain has remained active since 2010, uses Cloudflare authoritative name servers, and DNSSEC is enabled.

## Analysis
The RDAP records confirm that the domain is actively registered through an ICANN-accredited registrar. The domain has remained active since 2010, uses Cloudflare authoritative name servers, and DNSSEC is enabled.

## DNS Records

| Record Type | Value | Status |
|--------------|-----------------------------------------------|---------|
| A1 | 104.18.13.30 | Present |
| A2 | 104.18.12.30 | Present |
| AAAA1 | 2606:4700::6812:c1e | Present |
| AAAA2 | 2606:4700::6812:d1e | Present |
| MX | inbound-smtp.us-east-1.amazonaws.com (Priority: 10) | Present |
| NS1 | adi.ns.cloudflare.com | Present |
| NS2 | hal.ns.cloudflare.com | Present |
| SOA | Primary NS: adi.ns.cloudflare.com (dns.cloudflare.com) | Present |
| TXT | 27 TXT Records Detected | Present |


## TXT Record Summary

| Record Type | Status | Notes |
|--------------|---------|---------------------------------------------|
| SPF | Present | Email sender policy configured |
| DKIM | Present | RSA public keys published |
| DMARC | Present | Domain email authentication policy configured |
| Google Site Verification | Present | Multiple verification records detected |
| Microsoft Verification | Present | Microsoft service verification |
| GlobalSign Verification | Present | Certificate/Domain validation records |
| Atlassian Verification | Present | Atlassian service verification |
| Cisco Verification | Present | Cisco service verification |
| Postman Verification | Present | API platform verification |
| Other TXT Records | Present | Additional verification and service records detected |


### Ovservation

The DNS analysis confirms that the domain is properly configured with IPv4 (A) and IPv6 (AAAA) records. Cloudflare is used as the authoritative DNS provider, while Amazon Web Services (AWS) is configured as the email handling platform through MX records. A total of 27 TXT records were identified, including SPF, DKIM, DMARC, BIMI, and multiple domain verification records for Google, Microsoft, GlobalSign, Atlassian, Cisco, and Postman.

### Analysis

The DNS configuration indicates a mature and professionally managed infrastructure. Cloudflare provides DNS and network protection, while email authentication mechanisms (SPF, DKIM, and DMARC) are correctly implemented to reduce email spoofing risks. The presence of multiple verification records suggests integration with several enterprise cloud services and security platforms. No significant DNS configuration anomalies were identified from the publicly available records.

# IP Information

This section analyzes the public IP addresses associated with the target domain, including network ownership, routing information, hosting infrastructure, and IP characteristice etc

---

## IPv4 Information

| Field | Value |
|--------|-------|
| IPv4 Address 1 | 104.18.13.30 |
| IPv4 Address 2 | 104.18.12.30 |
| Status | Active |

---

## IPv6 Information

| Field | Value |
|--------|-------|
| IPv6 Address 1 | 2606:4700::6812:c1e |
| IPv6 Address 2 | 2606:4700::6812:d1e |
| Status | Active |

---

## Autonomous System (ASN)

| Field | Value |
|--------|-------|
| ASN | AS13335 *(Cloudflare)* |
| Organization | Cloudflare, Inc. |

---
## Network Information

| Field | Value |
|--------|-------|
| Public IP | 104.18.13.30 |
| Origin AS | AS13335 |
| Network Owner | Cloudflare, Inc. |
| BGP Prefix | 104.18.0.0/20 |
---

## Reverse DNS (PTR)


---

## Geolocation


----

## Hosting Provider

 |

---

## Observation

---

## Analysis
