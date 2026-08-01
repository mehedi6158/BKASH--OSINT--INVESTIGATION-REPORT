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

*** Can't find 104.18.13.30 in-addr.arpa: Non-existent domain

---

## Geolocation
- Geo Location : Global (Cloudflare Anycast)
- Hosting Provider : Cloudflare, Inc.
- Origin Server Location : Unknown (Protected by Cloudflare)
----

## Hosting Provider
- Hosting Provider : Cloudflare, Inc.
- ASN              : AS13335
- IP Address       : 104.18.13.30

---

## Observation
The target IP address belongs to Cloudflare, Inc. (AS13335) and is routed through Cloudflare's global Anycast network. No public PTR record was identified.
---

## Analysis
The website is protected by Cloudflare's reverse proxy service. Therefore, the visible IP does not reveal the origin hosting provider or the actual server location, limiting direct infrastructure attribution.


## SSL/TLS Analysis

### Certificate Details

| Field | Value |
|:-----------------------------|:--------------------------------|
| Certificate Status |Valid (Trusted) |
| Common Name (CN) |	www.bkash.com|
| Subject Alternative Names (SAN) | www.bkash.com, bkash.com|
| Issuer |GlobalSign Extended Validation CA - SHA256 - G3 |
| Signature Algorithm |	SHA256withRSA |
| Public Key Algorithm |RSA|
| Public Key Size |2048 bits |
| Serial Number |7ff427e6a7ae764a68569bdf |
| Valid From |	Wed, 23 Jul 2025 |
| Expiry Date |	Mon, 24 Aug 2026 |


---

### TLS Versions

| Protocol | Status |
|:---------|:-------|
| TLS 1.0 |Not Supported |
| TLS 1.1 |Not Supported |
| TLS 1.2 |Supported |
| TLS 1.3 |Supported |

---

### Cipher Suites

| TLS Version | Cipher Suite | Encryption | Forward Secrecy |
|:------------|:------------------------------------------------|:---------------------|:-----------------|
| TLS 1.3 | TLS_AES_128_GCM_SHA256 | AES-128 GCM | Yes |
| TLS 1.3 | TLS_AES_256_GCM_SHA384 | AES-256 GCM | Yes |
| TLS 1.3 | TLS_CHACHA20_POLY1305_SHA256 | ChaCha20-Poly1305 | Yes |
| TLS 1.2 | TLS_ECDHE_RSA_WITH_AES_128_GCM_SHA256 | AES-128 GCM | Yes |
| TLS 1.2 | TLS_ECDHE_RSA_WITH_CHACHA20_POLY1305_SHA256 | ChaCha20-Poly1305 | Yes |
| TLS 1.2 | TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384 | AES-256 GCM | Yes |

### SSL/TLS Security Features

| Feature | Status |
|:----------------------------|:----------------|
| HSTS | Enabled / Disabled |
| OCSP Stapling | Enabled  |
| Forward Secrecy | Supported |
| Session Resumption | Supported |
| Certificate Transparency | Enabled |
---
### Observation
The target website uses a valid and trusted SSL/TLS certificate, supports modern TLS versions (TLS 1.2 and TLS 1.3), implements secure cipher suites, and enables multiple security features, including Forward Secrecy, OCSP Stapling, and Certificate Transparency.
---
### Analysis
Overall, the SSL/TLS configuration is strong and aligns with current security best practices. The deployment of modern protocols, robust encryption algorithms, and secure TLS features reduces the risk of interception and protocol-based attacks while ensuring confidential and authenticated communication.

# HTTP/HTTPPS Security Analysis 

## HTTP Response Headers

| Header | Value |
|:--------------------------------|:--------------------------------|
| HTTP Version |HTTP/1.1 |
| HTTP Status Code |403 Forbidden |
| Server |cloudflare |
| Date |Thu, 30 Jul 2026 |
| Content-Type |text/html; charset=UTF-8 |
| Content-Length |Not Present |
| Cache-Control |private, max-age=0, no-store, no-cache, must-revalidate, post-check=0, pre-                        check=0 |
| ETag |Not Present |
| Last-Modified | |
| Location (If Redirect) | |

## HTTP Security Headers

| Security Header | Status |
|:--------------------------------------------|:----------------|
| Strict-Transport-Security (HSTS) |Missing |
| Content-Security-Policy (CSP) |Present (Configuration Warning) |
| X-Frame-Options |Present |
| X-Content-Type-Options |Present (nosniff) |
| Referrer-Policy |Present (same-origin) |
| Permissions-Policy | Not Observed |
| Cross-Origin-Resource-Policy (CORP) |Present |
| Cross-Origin-Opener-Policy (COOP) | Not Observed |
| Cross-Origin-Embedder-Policy (COEP) | Not Observed |

## HTTP Methods

| HTTP Method | Status |
|:----------------|:----------------|
| GET |Could Not Be Determined |
| POST | Could Not Be Determined|
| HEAD |Could Not Be Determined |
| OPTIONS |Could Not Be Determined |
| PUT |Could Not Be Determined |
| DELETE |Could Not Be Determined |
| TRACE |Could Not Be Determined |
| CONNECT |Could Not Be Determined |

*** Scan Result

- Host--	www.bkash.com
- Port--	443/tcp
- State--	Open
- Service--	SSL/HTTP
- HTTP Server--	Cloudflare HTTP Proxy
 
 ## HTTP Redirection

| Item | Value |
|:--------------------------------|:--------------------------------|
| HTTP → HTTPS Redirect |Could Not Be Verified |
| Redirect Status Code |301 Moved Permanently |
| Redirect Target |https://www.bkash.com/ |
| HSTS Enabled |Present (Strict-Transport-Security: max-age=31536000) |


### Observation

The website implements multiple HTTP security mechanisms, including Cloudflare protection, HSTS, X-Frame-Options, Referrer-Policy, and X-Content-Type-Options. Automated requests return HTTP 403 Forbidden, indicating active security controls.

### Analysis

The observed security headers and Cloudflare protection indicate a well-secured web infrastructure. Automated reconnaissance is restricted, reducing information exposure and improving resistance against common web-based attacks.

# Web Technology Stack Identification

## Technology Overview
| **Category**                    | **Technology** |
| ------------------------------- | -------------- |
| Front-end Framework             |  React              |
| Back-end Framework              |  Not Detected              |
| JavaScript Libraries            | jQuery 3.7.0, Bootstrap.js, Socket.IO, lodash, Moment.js,                                                 Slick JS, core-js             |
| CSS Framework                   | Bootstrap.js               |
| Browser APIs                    | HTML5 History API, Intersection Observer               |
| Real-time Communication         |Socket.IO                |
| Content Management System (CMS) | Atlassian Cloud               |
| Developer Tools                 | Postman               |
## Analytics & Tracking Technologies
| **Category**             | **Technology** |
| ------------------------ | -------------- |
| Web Analytics            | Google Analytics 4 (GA4), Microsoft Clarity               |
| Marketing Analytics      | Facebook Domain Insights             |                
| Conversion Tracking      |Facebook Pixel, Google Conversion Linker, Google AdWords Conversion,                                TikTok Conversion Tracking Pixel                |
| Tag Management           |  Google Tag Manager (GTM), Global Site Tag (gtag.js)              |
| Advertising Technologies | DoubleClick.net, Facebook Custom Audiences, Google Remarketing,                      TikTok Pixel               |

## Third-Party Integrations
| **Category**        | **Technology** |
| ------------------- | -------------- |
| Social Integration  | Facebook SDK, Facebook for Websites, TikTok Embed               |
| Media Integration   | TikTok Embed, YouTube Link               |
| API Integration     | Google Font API, Socket.IO               |
| Payment Integration |Not Detected                |
| Mapping Services    | Not Detected               |
| Customer Support    |Not Detected                |

## Security Technologies
| Category            | Technology      |
| ------------------------ | -------------------- |
| Transport Security  | HSTS, SSL by Default |
| SSL/TLS Certificate  | GlobalSign EV        |
| Email Authentication | SPF, DMARC           |
| Email Security      | PowerDMARC           |

## Infrastructure Technologies
| Category                       | Technology                                              |
| ---------------------------------- | ----------------------------------------------------------- |
| Web Hosting                    | Cloudflare Hosting, Oracle Cloud                            |
| Content Delivery Network (CDN) | Cloudflare CDN, Cloudflare, CDNJS, jsDelivr, GStatic, UNPKG |
| DNS Provider                  | Cloudflare DNS                                              |
| DNS Security                  | DNSSEC                                                      |
| IP Support                    | IPv6                                                        |


### Observation
React is used as the front-end framework.
Cloudflare provides DNS, CDN, hosting, and security services.
Google Analytics 4, Microsoft Clarity, and Google Tag Manager are used for analytics.
Facebook Pixel and Google Ads Conversion Tracking are used for marketing and conversion tracking.
HSTS, GlobalSign EV, SPF, DMARC, and DNSSEC are implemented to enhance security.

### Analysis
The detected technologies indicate a modern, secure, and performance-oriented web architecture. The website combines Cloudflare infrastructure, React, analytics platforms, and standard security mechanisms to support availability, user analytics, and secure communications
