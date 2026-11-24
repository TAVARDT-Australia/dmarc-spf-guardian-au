# DMARC, SPF and DKIM Guardian | TAVARDT Australia

[![Technical Audit](https://img.shields.io/badge/TAVARDT-Email%20Security-5b3cf5.svg)](https://tools.tavardt.com/au/dmarc-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

DNS email authentication auditor for spoofing mitigation, sender verification, and alignment with ACSC Essential Eight and ISM controls.

Developed and maintained by the cybersecurity and infrastructure defense division of **TAVARDT Australia**.

***

## Features and Verification Capabilities

* **DMARC Policy Enforcement**: In-depth inspection of enforcement directives (reject, quarantine, and none), subdomain policy (sp), and percentage enforcement rate (pct).
* **SPF Record Audit**: Validation of authorized sender mechanisms, DNS query lookup limits, and strict enforcement qualifiers (-all vs ~all).
* **DKIM Signature Verification**: Cryptographic public key verification across specified DNS selectors.
* **Forensic and Aggregate Reporting**: Verification of aggregate (rua) and forensic (ruf) feedback loops.
* **Regulatory and Standards Compliance**: Designed in alignment with Australian Cyber Security Centre (ACSC) Essential Eight and Information Security Manual (ISM).

***

## Installation and Quick Start

Requires Python 3.8 or higher. Built strictly using the Python standard library with zero external dependencies.

```bash
git clone https://github.com/TAVARDT-Australia/dmarc-spf-guardian-au.git
cd dmarc-spf-guardian-au
python guardian.py enterprise.com.au
```

To test a specific DKIM selector or export results in structured JSON format:

```bash
python guardian.py enterprise.com.au -selector mail -json
```

***

## Online Web Diagnostics

For continuous perimeter monitoring and graphical reporting, access the official web diagnostic suite:

* **DMARC and Email Authentication Checker**
* **TAVARDT Australia Corporate Portal**

***

## Enterprise Defense Consulting

For dedicated cybersecurity architecture, threat modeling, and incident readiness in Australia, contact **TAVARDT Australia**.
