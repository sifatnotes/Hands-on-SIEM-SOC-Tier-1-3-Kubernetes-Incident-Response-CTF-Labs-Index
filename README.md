# Hands-on-SIEM-SOC-Tier-1-3-Kubernetes-Incident-Response-CTF-Labs-Index
A complete collection of practical cybersecurity CTF labs covering SIEM operations (Wazuh, Elastic, Sentinel, Splunk), SOC Analyst Tier 1-3 progressions, log analysis, and Kubernetes security, monitoring, and incident response.
# SIEM Platforms, SOC Analyst Progression & Kubernetes Security CTF Labs

Welcome to the **SIEM Platforms, SOC Analyst Progression & Kubernetes Security CTF Lab Collection**. This repository serves as an organized, searchable index of hands-on security labs and Capture The Flag (CTF) exercises hosted on Learn SecByte.

This catalog bridges real-world enterprise Security Operations Center (SOC) environments with cloud-native container security, covering major SIEM technologies, multi-tiered SOC investigation workflows, and Kubernetes incident handling.

---

## Lab Collection Index

### 1. SIEM Platforms & Log Analytics
* **SIEM Fundamentals: Log Noise to Actionable Detection**  
  *Lab Link:* [https://learn.secbyte.org/ctf/siem-fundamentals-log-noise-to-actionable-detection](https://learn.secbyte.org/ctf/siem-fundamentals-log-noise-to-actionable-detection)  
  *Focus:* Understanding log ingestion pipelines, normalization, correlation rules, and reducing false-positive noise in enterprise SIEMs.

* **Logline Investigations: From Noise to Incident**  
  *Lab Link:* [https://learn.secbyte.org/ctf/logline-investigations-from-noise-to-incident](https://learn.secbyte.org/ctf/logline-investigations-from-noise-to-incident)  
  *Focus:* Raw log analysis, parsing irregular log formats, timestamp alignment, and tracking attacker footprints across system artifacts.

* **Wazuh: Detect, Triage, and Hunt**  
  *Lab Link:* [https://learn.secbyte.org/ctf/wazuh-detect-triage-and-hunt](https://learn.secbyte.org/ctf/wazuh-detect-triage-and-hunt)  
  *Focus:* Utilizing Wazuh XDR/SIEM for host-based intrusion detection, custom decoders/rules, integrity monitoring, and active threat hunting.

* **Elastic SIEM: From Ingest to Investigation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/elastic-siem-from-ingest-to-investigation](https://learn.secbyte.org/ctf/elastic-siem-from-ingest-to-investigation)  
  *Focus:* Navigating Elastic Security, querying Elastic Common Schema (ECS) data via ES|QL/KQL, building alerts, and timeline analysis.

* **Microsoft Sentinel: Detection Engineering and Incident Investigation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/microsoft-sentinel-detection-engineering-and-incident-invest](https://learn.secbyte.org/ctf/microsoft-sentinel-detection-engineering-and-incident-invest)  
  *Focus:* Authoring Kusto Query Language (KQL) detections, Sentinel analytics rules, investigation graphs, and cloud threat triage.

* **Splunk Fundamentals for Security Operations**  
  *Lab Link:* [https://learn.secbyte.org/ctf/splunk-fundamentals-for-security-operations](https://learn.secbyte.org/ctf/splunk-fundamentals-for-security-operations)  
  *Focus:* Writing Search Processing Language (SPL) queries, creating security dashboards, field extraction, and transaction mapping in Splunk.

### 2. Tiered SOC Analyst Career Progression
* **SOC Level 1: Alert Triage to Incident Verification**  
  *Lab Link:* [https://learn.secbyte.org/ctf/soc-level-1-alert-triage-to-incident-verification](https://learn.secbyte.org/ctf/soc-level-1-alert-triage-to-incident-verification)  
  *Focus:* First-line alert triage, distinguishing true vs. false positives, payload decoding, basic IP/domain OSINT enrichment, and ticket escalation.

* **SOC Level 2: Detection, Investigation, and Incident Triage**  
  *Lab Link:* [https://learn.secbyte.org/ctf/soc-level-2-detection-investigation-and-incident-triage](https://learn.secbyte.org/ctf/soc-level-2-detection-investigation-and-incident-triage)  
  *Focus:* Deep-dive forensic triage, cross-log correlation, attack vector identification, initial scoping, and authoring custom detection rules.

* **SOC Level 3: Advanced Detection, Investigation, and Incident Response**  
  *Lab Link:* [https://learn.secbyte.org/ctf/soc-level-3-advanced-detection-investigation-and-incident-re](https://learn.secbyte.org/ctf/soc-level-3-advanced-detection-investigation-and-incident-re)  
  *Focus:* Advanced adversary containment, memory artifact analysis, complex threat hunting, adversary emulation defense, and incident root cause analysis.

### 3. Kubernetes Security & Cloud-Native Incident Response
* **Kubernetes Monitoring: Securing Cluster Visibility**  
  *Lab Link:* [https://learn.secbyte.org/ctf/kubernetes-monitoring-securing-cluster-visibility](https://learn.secbyte.org/ctf/kubernetes-monitoring-securing-cluster-visibility)  
  *Focus:* Setting up cluster telemetry, monitoring API server requests, Kubelet metrics, and maintaining runtime visibility.

* **Kubernetes Logging: From Pod Noise to Incident Evidence**  
  *Lab Link:* [https://learn.secbyte.org/ctf/kubernetes-logging-from-pod-noise-to-incident-evidence](https://learn.secbyte.org/ctf/kubernetes-logging-from-pod-noise-to-incident-evidence)  
  *Focus:* Aggregating container stdout/stderr logs, parsing Kubernetes audit logs, tracking RBAC queries, and reconstructing pod breach timelines.

* **Kubernetes Incident Response: Detect, Triage, Contain**  
  *Lab Link:* [https://learn.secbyte.org/ctf/kubernetes-incident-response-detect-triage-contain](https://learn.secbyte.org/ctf/kubernetes-incident-response-detect-triage-contain)  
  *Focus:* Responding to active container escapes, rogue pod deployment, cluster privilege escalation, network policy isolation, and node containment.

---

## Learning Paths

### Path A: Multi-Platform SIEM & Detection Engineering
1. **Log Analytics Foundations:** Start with [SIEM Fundamentals](https://learn.secbyte.org/ctf/siem-fundamentals-log-noise-to-actionable-detection) and [Logline Investigations](https://learn.secbyte.org/ctf/logline-investigations-from-noise-to-incident).
2. **Platform Mastery:** Practice across platforms with [Wazuh](https://learn.secbyte.org/ctf/wazuh-detect-triage-and-hunt), [Splunk Fundamentals](https://learn.secbyte.org/ctf/splunk-fundamentals-for-security-operations), [Elastic SIEM](https://learn.secbyte.org/ctf/elastic-siem-from-ingest-to-investigation), and [Microsoft Sentinel](https://learn.secbyte.org/ctf/microsoft-sentinel-detection-engineering-and-incident-invest).

### Path B: SOC Analyst Career Path
1. **Tier 1:** [SOC Level 1: Alert Triage to Incident Verification](https://learn.secbyte.org/ctf/soc-level-1-alert-triage-to-incident-verification)
2. **Tier 2:** [SOC Level 2: Detection, Investigation, and Incident Triage](https://learn.secbyte.org/ctf/soc-level-2-detection-investigation-and-incident-triage)
3. **Tier 3:** [SOC Level 3: Advanced Detection, Investigation, and Incident Response](https://learn.secbyte.org/ctf/soc-level-3-advanced-detection-investigation-and-incident-re)

### Path C: Cloud-Native & Kubernetes Defense
1. **Cluster Telemetry:** [Kubernetes Monitoring: Securing Cluster Visibility](https://learn.secbyte.org/ctf/kubernetes-monitoring-securing-cluster-visibility)
2. **Audit & Log Forensics:** [Kubernetes Logging: From Pod Noise to Incident Evidence](https://learn.secbyte.org/ctf/kubernetes-logging-from-pod-noise-to-incident-evidence)
3. **Incident Response:** [Kubernetes Incident Response: Detect, Triage, Contain](https://learn.secbyte.org/ctf/kubernetes-incident-response-detect-triage-contain)

---

## How to Use the Labs

1. Select a practice lab from the **Lab Collection Index**.
2. Click the corresponding link to open the exercise directly on Learn SecByte.
3. Review the scenario instructions, examine the SIEM dashboard or CLI console, and complete the tasks.
4. Locate flags, author rules, or execute containment actions to finish the lab.

---

## Target Audience

* **SOC Analysts (Tiers 1–3):** Develop structured triage methodology across host, network, SIEM, and cloud environments.
* **Detection Engineers:** Master query languages including KQL, SPL, and ES|QL/KQL across enterprise SIEM platforms.
* **Cloud Security Engineers & DevSecOps:** Learn runtime security, audit log investigation, and threat containment within Kubernetes clusters.
* **Cybersecurity Students:** Build hands-on experience using industry-standard tools and platforms.

---

## Disclaimer

All lab links in this repository direct to official, interactive exercises on Learn SecByte. These materials are intended exclusively for authorized security training, skill development, and educational research. Unapproved testing or misuse of defensive toolsets against third-party environments is strictly prohibited.
