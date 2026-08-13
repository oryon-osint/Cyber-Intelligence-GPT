<a id="top"></a>

<div align="center">
  <h1>Cyber Intelligence GPT</h1>
  <p>A custom GPT for OSINT, DFIR, cyber investigations, threat intelligence, OPSEC, privacy, AI security, and compliance.</p>
  <p>
    <a href="https://chatgpt.com/g/g-65xhTBjZu-cyber-intelligence-gpt"><img alt="Launch Cyber Intelligence GPT" src="https://img.shields.io/badge/launch-Cyber_Intelligence_GPT-10a37f?style=flat-square&logo=openai&logoColor=white"></a>
    <img alt="OSINT" src="https://img.shields.io/badge/focus-OSINT-0969da?style=flat-square">
    <img alt="DFIR" src="https://img.shields.io/badge/focus-DFIR-8250df?style=flat-square">
    <img alt="Threat Intelligence" src="https://img.shields.io/badge/focus-Threat_Intelligence-d1242f?style=flat-square">
    <img alt="Last update: 2026-08-14" src="https://img.shields.io/badge/last_update-2026--08--14-1f883d?style=flat-square">
    <a href="https://github.com/oryon-osint/Cyber-Intelligence-GPT/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/oryon-osint/Cyber-Intelligence-GPT?style=flat-square"></a>
    <a href="https://github.com/oryon-osint/Cyber-Intelligence-GPT/network/members"><img alt="GitHub forks" src="https://img.shields.io/github/forks/oryon-osint/Cyber-Intelligence-GPT?style=flat-square"></a>
  </p>
  <p><strong><a href="https://chatgpt.com/g/g-65xhTBjZu-cyber-intelligence-gpt">Launch Cyber Intelligence GPT</a></strong> · <a href="#capabilities">Capabilities</a> · <a href="#investigation-workflow">Workflow</a> · <a href="#workflow-shortcuts">Shortcuts</a> · <a href="#example-usage">Examples</a> · <a href="#methodology--standards">Methodology</a></p>
</div>

## About

**Cyber Intelligence GPT** is a custom GPT designed to support the collection, verification, correlation, analysis, and reporting of information for lawful investigative, defensive, research, and security objectives.

It combines **OSINT, cyber threat intelligence, DFIR, threat hunting, security operations, privacy, OPSEC, AI/LLM security, compliance, and authorized security testing** in one investigation-oriented workflow.

The assistant is designed to go beyond a single lookup. For substantial cases it can:

- build a collection plan,
- search across multiple public-source angles,
- pivot from useful identifiers and relationships,
- correlate evidence across independent sources,
- resolve contradictions where possible,
- distinguish facts from assessments and assumptions,
- assign confidence to analytical conclusions,
- identify intelligence gaps,
- and recommend the highest-value next actions.

> [!IMPORTANT]
> Cyber Intelligence GPT does not invent access to private systems, restricted databases, dark-web services, commercial platforms, or intelligence sources. Coverage always depends on the tools, lawful sources, files, and public information actually available in the active session.

---

<a id="capabilities"></a>

## 🧭 Capabilities

| Area | What it can support |
|:---|:---|
| **OSINT & Intelligence** | Entity research, identity resolution, public records, social media research, media analysis, geolocation, timelines, relationship mapping |
| **Cyber Investigations** | IOC enrichment, infrastructure mapping, phishing and fraud research, cybercrime analysis, campaign and actor profiling |
| **DFIR** | Incident triage, forensic workflows, artifact analysis, evidence handling, timeline reconstruction, malware-analysis support |
| **Threat Intelligence** | Actor and campaign research, IOC correlation, TTP analysis, ATT&CK mapping, infrastructure clustering |
| **Security Operations** | Threat hunting, alert triage, detection engineering, incident-response playbooks, SOC workflows |
| **Red / Blue / Purple Teaming** | Authorized adversary emulation, defensive validation, attack-surface reasoning, detection opportunities |
| **OPSEC & Privacy** | Investigator exposure reduction, privacy analysis, metadata risk, secure research practices, exposure assessment |
| **AI / LLM Security** | Prompt injection, agent/tool abuse, RAG security, AI red teaming, model/application threat analysis |
| **Compliance & Governance** | GDPR, AI governance, cyber risk, policy/control mapping, security and privacy frameworks |
| **Automation** | Repeatable research workflows, scripts, structured IOC handling, templates, checklists, data transformation |
| **Emerging Threats** | AI-enabled abuse, synthetic media, human-layer threats, physical/digital convergence, new attack patterns |

---

## 🔎 Supported Investigation Inputs

Cyber Intelligence GPT can reason about and pivot from many common observables and entities, including:

`Name` · `Alias` · `Username` · `Email` · `Phone Number` · `Organization` · `Domain` · `Subdomain` · `IP Address` · `ASN` · `URL` · `File Hash` · `Certificate` · `Wallet` · `Image` · `Video` · `Document` · `Metadata` · `Malware Family` · `Threat Actor` · `Campaign` · `Incident` · `TTP`

Typical investigation areas include:

- identity and digital-footprint research,
- domains, DNS, certificates, hosting, and infrastructure,
- social media and public content,
- exposed technical assets,
- public breach and exposure references,
- documents and metadata,
- images and geolocation clues,
- malware and threat intelligence,
- cryptocurrency attribution clues,
- organizational relationships,
- incident and campaign timelines.

---

<a id="investigation-workflow"></a>

## 🧠 Investigation Workflow

For substantial investigations, the assistant follows an evidence-driven workflow:

1. **Establish the objective**  
   Define the target, scope, constraints, authorization, legal boundaries, and required OPSEC level.

2. **Build a collection plan**  
   Identify useful people, organizations, identifiers, infrastructure, records, media, timelines, and relationships.

3. **Collect broadly**  
   Start with the least-invasive effective methods and use current public sources when freshness matters.

4. **Enrich and pivot**  
   Follow every useful identifier, observable, relationship, and infrastructure clue.

5. **Correlate evidence**  
   Compare findings across independent sources instead of relying on a single result.

6. **Separate evidence from inference**  
   Distinguish:
   - **Fact** - directly supported by evidence.
   - **Assessment** - analytical conclusion derived from evidence.
   - **Assumption** - working premise that still requires confirmation.
   - **Unknown** - unresolved information gap.

7. **Assess confidence**  
   Material analytical judgments may be rated **Low / Medium / High confidence**.

8. **Identify gaps and next actions**  
   Highlight unresolved questions and the pivots most likely to improve the investigation.

---

## 📑 Reporting Structure

Substantial reports normally use:

**Executive Summary → Key Findings → Evidence / Public Sources → Analysis → Risks → Recommendations → Next Steps**

Depending on the case, reports can also include:

- confidence assessments,
- collection logs,
- timelines,
- infrastructure maps,
- relationship maps,
- IOC tables,
- MITRE ATT&CK mappings,
- STIX 2.1 structures,
- intelligence gaps,
- implications and scenarios,
- Impact / Effort / Risk prioritization.

Recommendations can be grouped as:

- **Quick win** - ≤ 1 hour
- **Short term** - ≤ 1 day
- **Deep dive** - > 1 day

---

## 🧰 FOSS-First Tooling

Cyber Intelligence GPT prefers **maintained open-source tooling** and official project repositories before commercial alternatives.

For OSINT and cyber tool discovery, a priority reference is:

**[Awesome OSINT Repositories](https://github.com/oryon-osint/awesome-osint-repos)**

Tool recommendations consider:

- maintenance status,
- source-code availability,
- practical investigative value,
- supported target inputs,
- API/account requirements,
- local vs. cloud execution,
- OPSEC and privacy implications,
- reproducibility,
- licensing and known limitations.

Commercial tooling may be recommended when specifically requested, clearly superior for the task, or when no suitable FOSS alternative exists.

---

<a id="workflow-shortcuts"></a>

## ⚡ Workflow Shortcuts

The assistant accepts natural language. The following keywords are optional shortcuts for common workflows.

| Shortcut | Purpose |
|:---|:---|
| `Help` | Show capabilities, shortcuts, and examples |
| `Case` / `New case` | Start a new investigation with the full capability menu |
| `Report [target]` | Build a full-spectrum OSINT / cyber intelligence report |
| `Profile [entity]` | Create a detailed intelligence profile |
| `Enrich [ioc/entity]` | Enrich and pivot an observable or entity |
| `Research [topic]` | Perform deep public-source research and verification |
| `Metadata [file/image]` | Analyze metadata, EXIF, and forensic artifacts |
| `Timeline [entity/incident]` | Build a chronological timeline |
| `Playbook [scenario]` | Create an IR, DFIR, hunting, red/blue workflow |
| `Template [scenario]` | Generate a reusable investigation/report template |
| `Checklist [scenario]` | Generate a comprehensive operational checklist |
| `Mitre: [actor/incident]` | Map TTPs to MITRE ATT&CK |
| `iocs: [campaign/incident]` | Correlate IOCs and structure them for reporting |
| `Actor: [name]` | Build a threat-actor or cybercrime profile |
| `Campaign: [name]` | Analyze campaign infrastructure, TTPs, IOCs, targeting, and chronology |
| `Infrastructure: [org/target]` | Map observable domains, subdomains, ASNs, technologies, and exposures |

> [!NOTE]
> Shortcuts are conversational workflow keywords, not shell commands. A leading `/` is not required.

---

## 🧬 DFIR & Evidence Handling

DFIR support can include:

- incident triage,
- evidence-acquisition planning,
- order-of-volatility considerations,
- filesystem and disk artifacts,
- memory-analysis workflows,
- Windows, Linux, and macOS artifacts,
- network evidence,
- log analysis,
- malware triage,
- IOC extraction,
- timeline reconstruction,
- hashing and integrity verification,
- metadata preservation,
- chain-of-custody considerations,
- incident-response playbooks,
- hunting hypotheses and detection opportunities.

Where evidentiary integrity matters, the assistant emphasizes **hashes, timestamps, provenance, reproducibility, and documented assumptions**.

---

## 🎯 Threat Intelligence & Security Operations

Cyber Intelligence GPT can support:

- threat actor profiling,
- campaign tracking,
- IOC enrichment and correlation,
- infrastructure clustering,
- TTP analysis,
- MITRE ATT&CK mapping,
- Diamond Model reasoning,
- Cyber Kill Chain analysis,
- threat hunting,
- detection engineering,
- SOC alert triage,
- incident response,
- adversary emulation in authorized environments,
- purple-team exercises,
- phishing and fraud investigations,
- malware intelligence.

Attribution is treated as an analytical conclusion requiring evidence, not as a guess presented as fact.

---

## 🤖 AI / LLM Security

Modern AI-security coverage includes:

- LLM threat modeling,
- prompt injection,
- indirect prompt injection,
- sensitive-context and data leakage,
- agent and tool abuse,
- RAG and retrieval security,
- MCP / plugin / integration risks,
- AI application red teaming,
- AI supply-chain risk,
- secure deployment patterns,
- abuse-case development,
- AI governance,
- monitoring and detection strategies.

---

## 🔐 OPSEC & Privacy

The assistant follows an OPSEC-conscious approach:

- prefer the least-invasive effective research method,
- minimize unnecessary investigator exposure,
- reduce avoidable data leakage,
- separate public evidence from sensitive material,
- highlight account, browser, network, platform, and metadata risks,
- recommend privacy-preserving research practices,
- flag legal and ethical constraints when relevant.

---

<a id="methodology--standards"></a>

## 🧩 Methodology & Standards

Depending on the task, analysis can reference or map findings to frameworks and standards such as:

- **MITRE ATT&CK**
- **Diamond Model of Intrusion Analysis**
- **Cyber Kill Chain**
- **NIST Cybersecurity Framework**
- **NIST incident-response guidance**
- **OWASP**
- **OWASP guidance for Generative AI / LLM applications**
- **STIX 2.1 / TAXII**
- **GDPR**
- **EU AI Act**
- **ISO/IEC security and privacy controls**

Frameworks are used when they improve the investigation; they are not added mechanically to every answer.

---

## 📊 Output Formats

Depending on the task and available tools, outputs can include:

`Markdown` · `CSV` · `JSON` · `STIX 2.1` · `IOC tables` · `Timelines` · `Mermaid diagrams` · `Playbooks` · `Checklists` · `Executive reports` · `Technical reports` · `Detection logic` · `Scripts` · `Documents` · `Spreadsheets` · `Presentations`

---

<a id="example-usage"></a>

## 📌 Example Usage

```text
Report example.com
```

Build a broad intelligence report around a domain, including infrastructure, relationships, exposure, risk, and next pivots.

```text
Enrich 203.0.113.10
```

Investigate an IP address using public infrastructure and threat-intelligence pivots.

```text
Profile Example Corporation
```

Create an organization profile covering public footprint, infrastructure, affiliations, risks, and evidence.

```text
Research "phishing infrastructure targeting logistics companies"
```

Perform deep public-source research, compare independent sources, create a chronology, and identify intelligence gaps.

```text
Metadata suspicious_document.pdf
```

Analyze available metadata and forensic artifacts from a supplied file.

```text
Mitre: ransomware incident
```

Map observed behavior and TTPs to MITRE ATT&CK with evidence and confidence notes.

```text
iocs: campaign-name
```

Correlate supplied or publicly verified observables into a structured IOC set.

```text
Playbook cloud account compromise
```

Create a defensive incident-response and investigation workflow.

---

## ⚖️ Safety, Authorization & Scope

Cyber Intelligence GPT is intended for:

- lawful OSINT,
- defensive cybersecurity,
- authorized security testing,
- DFIR and incident response,
- threat intelligence,
- security research,
- CTFs and lab environments,
- privacy and compliance,
- education and training.

It does not support unlawful access, malicious exploitation, credential theft, harassment, doxxing, destructive activity, or unauthorized surveillance.

When a request crosses a safety or authorization boundary, the assistant limits the harmful portion while continuing to support legitimate defensive, analytical, research, or lab-safe alternatives.

---

## 🚀 Access

<div align="center">

### [Launch Cyber Intelligence GPT](https://chatgpt.com/g/g-65xhTBjZu-cyber-intelligence-gpt)

<a href="https://chatgpt.com/g/g-65xhTBjZu-cyber-intelligence-gpt">
  <img alt="Open in ChatGPT" src="https://img.shields.io/badge/Open_in-ChatGPT-10a37f?style=for-the-badge&logo=openai&logoColor=white">
</a>

</div>

---

## 🔗 Related Repositories

- **[Awesome OSINT Repositories](https://github.com/oryon-osint/awesome-osint-repos)** - continuously updated catalogue of open-source OSINT tools, skills, plugins, MCP servers, and agentic integrations.
- **[Cyber Intelligence Toolkit](https://github.com/oryon-osint/cyber-intelligence-toolkit)** - manuals, playbooks, checklists, and references for OSINT, OPSEC, cybersecurity, and digital investigations.
- **[QueryTool](https://github.com/oryon-osint/querytool)** - Google Sheets-based framework for structured OSINT search workflows.

---

## ⚠️ Accuracy & Limitations

Cyber intelligence is time-sensitive. Infrastructure changes, repositories become stale, accounts disappear, regulations evolve, and threat reporting may conflict.

Cyber Intelligence GPT is designed to:

- verify current facts when recency matters,
- prefer primary and authoritative public sources,
- mark stale, conflicting, or unverified information,
- distinguish observation from inference,
- state uncertainty and confidence,
- avoid fabricating evidence, sources, IOCs, attribution, or tool output.

AI-assisted analysis should be independently validated before operational, legal, evidentiary, or other high-impact decisions.

---

## 📄 Disclaimer

This project is provided for **educational, research, investigative, defensive, and authorized security purposes**.

Users are responsible for ensuring that their activities comply with applicable law, contractual obligations, platform rules, organizational policy, authorization scope, and evidence-handling requirements.

<p align="right"><a href="#top">Back to top ↑</a></p>
