# Exposed Files and Sensitive Credentials Scanner

[![Exposed Files Scanner](https://img.shields.io/badge/TAVARDT-Attack%20Surface-5b3cf5.svg)](https://tools.tavardt.com/uk/exposed-files-scanner/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

CLI attack surface scanner for automated discovery of exposed environment variables, database backups, git metadata, and secret leakage.

Developed and maintained by the offensive security and attack surface division of **TAVARDT United Kingdom**.

***

## Attack Surface Discovery Scope

* **Environment Secrets and API Keys**: Inspection for exposed `.env`, `.env.local`, and `.env.production` files.
* **Version Control Metadata**: Detection of accessible `/.git/HEAD` and `/.git/config` paths.
* **Database Backups and Dumps**: Discovery of sensitive database exports such as `backup.sql`, `dump.sql`, and `database.sql`.
* **Infrastructure Orchestration**: Verification of public `docker-compose.yml` assets and server disclosures via `phpinfo.php`.
* **Regulatory Alignment**: Designed in alignment with NCSC Vulnerability Management Guidelines and Cyber Essentials Standards.

***

## Installation and Quick Start

Requires Python 3.8 or higher. Built strictly using the Python standard library with zero third-party packages.

```bash
git clone https://github.com/TAVARDT-UK/exposed-files-scanner-uk.git
cd exposed-files-scanner-uk
python scanner.py company.co.uk
```

To export results in structured JSON format:

```bash
python scanner.py company.co.uk -json
```

***

## Online Web Diagnostics

For automated surface monitoring and detailed vulnerability analysis, access the official web diagnostic suite:

* **Exposed Files and Secrets Scanner**
* **TAVARDT United Kingdom Corporate Portal**

***

## Enterprise Attack Surface Consulting

For penetration testing, vulnerability remediation, and zero-trust perimeter defense in United Kingdom, contact **TAVARDT United Kingdom**.

***

© 2026 TAVARDT. All rights reserved.
