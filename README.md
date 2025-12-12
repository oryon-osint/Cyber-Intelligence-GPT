# [OSINT360 ⌁ Cyber Intelligence GPT](https://tntpp9.short.gy/osint360-gpt)

![AI](https://img.shields.io/badge/AI-GPT5-critical)

## 🛡️ Overview

OSINT360 ⌁ Cyber Intelligence is a specialized **GPT-5.1-powered assistant** designed for **open-source intelligence (OSINT), digital forensics (DFIR), cyber investigations, ethical hacking, and operational security (OPSEC)**. It provides end-to-end support for intelligence operations, from collection and analysis to reporting and adversary profiling.

This GPT instance is optimized for:

* **OSINT collection & enrichment** (domains, IPs, usernames, social media, dark web)
* **DFIR workflows** (forensic triage, malware analysis, chain of custody)
* **Cybercrime investigations** (threat actor profiling, campaign mapping, crypto tracing)
* **Red/Blue/Purple Teaming** (adversary emulation, detection engineering, threat hunting)
* **OPSEC & Privacy** (anonymization, persona building, de-anonymization defense)
* **Compliance** (GDPR, AI Act, global cyber laws)

## ✨ Features

* **Command-based interaction** for fast execution of playbooks, reports, and checklists.
* **Structured outputs**: every report follows *Executive Summary → Key Findings → Evidence → Analysis → Risks → Recommendations → Next Steps*.
* **Tool-first approach**: always suggests open-source GitHub tools before commercial alternatives.
* **Up-to-date intelligence**: integrates live web lookups when fresh data is required.
* **Chain of custody compliance**: hashes, metadata preservation, evidence integrity.
* **Framework alignment**: MITRE ATT\&CK, Diamond Model, Cyber Kill Chain.

## 📂 Full Command Reference

### Case & Workflow

* `/help` → Show full command reference.
* `/new` → Start a new case (expanded subcategories by domain: OSINT, DFIR, Red Team, etc.).

### Reporting & Profiles

* `/report [entity]` → Full-spectrum OSINT/cyber report.
* `/profile [entity]` → Dossier profile (person, org, asset).
* `/timeline [entity]` → Exposure/events timeline.

### Enrichment & Analysis

* `/enrich [IOC|entity]` → Enrich IP, domain, email, hash, wallet.
* `/metadata [file|image]` → Extract metadata/EXIF.
* `/deepresearch [keyword]` → In-depth research across OSINT, dark web, SIGINT, HUMINT.
* `/mitre [actor|incident]` → ATT\&CK mapping of TTPs.
* `/iocs [campaign]` → IOC tables (CSV/Markdown/STIX).
* `/actor [name]` → Threat actor profile.
* `/campaign [name]` → Campaign infrastructure mapping.
* `/infrastructure [org]` → Org’s exposed infrastructure map.

### Playbooks & Templates

* `/playbook [scenario]` → IR/Red/Blue playbooks.
* `/template [scenario]` → Full investigation template.
* `/checklist [scenario]` → Step-by-step task checklist.

## 📊 Output Formats

* **Markdown / HTML** (default)
* **CSV / JSON** (for IOCs & structured data)
* **STIX 2.1** (optional export for threat intel platforms)
* **Mermaid diagrams** (infra/timeline visualization)

## ⚖️ Compliance & Ethics

OSINT360 GPT adheres to strict **OPSEC, legality, and evidentiary integrity** principles:

* Avoids disclosure of confidential sources.
* Prioritizes privacy and anonymization methods.
* Ensures all recommendations are ethical and legal.

## 📌 Example Usage

```bash
/report threatintel.com        # Generate a full-spectrum OSINT report on a domain
/enrich 192.168.100.45         # Enrich and investigate an IP address (infrastructure asset)
/profile Microsoft Corporation # Build a detailed profile of a company or organization
/metadata breach_dump.jpg      # Extract EXIF/metadata from an uploaded file or image
/deepresearch "phishing kits" # Deep dive into phishing kit research
/mitre Lazarus Group           # Map an APT group’s TTPs to MITRE ATT&CK
/checklist Digital Forensics   # Get a structured task checklist for DFIR workflows
```

### More Examples

```bash
/report john_doe               # Full OSINT report on an individual
/enrich jane.doe@example.com   # Enrich and investigate an email address
/profile @randomuser123        # Social media persona profiling
/metadata leaked_doc.pdf       # Extract metadata and analyze embedded artifacts
/actor Conti                   # Profile ransomware group
/campaign SolarWinds           # Map campaign infrastructure
/infrastructure target_org     # Map exposed infrastructure of a company
/mitre Conti Ransomware        # Map ransomware campaign TTPs to MITRE ATT&CK
/playbook Incident Response    # Get a full IR playbook for SOC teams
/template OSINT Investigation  # Generate OSINT investigation template
/checklist Threat Hunting      # Checklist for SOC and hunting teams
```

## 🚀 Access

**🔗 [Launch OSINT360 GPT](https://tnTpp9.short.gy/osint360-gpt)**  

> **PS:** Heads-up - on complex queries it may take a moment to chew through large datasets.  
> Good intel takes time 😉

## 📖 Methodology & Foundations

The model builds on best practices in **OSINT, digital forensics, red teaming, privacy engineering, and cybersecurity strategy**.
It leverages frameworks and standards including **MITRE ATT\&CK, NIST, OWASP, OWASP GenAI, GDPR, and AI Act**, with a focus on open-source tooling.

## ⚠️ Disclaimer

This model is provided for **educational, research, and defensive purposes only**.
It does **not** endorse or support any unlawful or malicious activity.

