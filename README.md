# Aradbase-Sigma

Aradbase-Sigma is a research focused repository containing behavior-based Sigma rules developed from Aradbase-YARA malware detection research.

---

## Purpose

This project aims to support:

- Malware research  
- Threat hunting  
- Detection engineering  
- SOC monitoring & SIEM correlation  
- DFIR (Digital Forensics & Incident Response)  
- Educational use  

---

## Scope

Rules in this repository primarily target:

- Malware behaviors  
- Persistence techniques  
- Command & Control (C2) activity  
- Credential access  
- Lateral movement  
- Ransomware behavior  
- Suspicious and anomalous activities  

Coverage evolves alongside the threat landscape and detection research.

---

## Relationship to Aradbase-YARA

Aradbase-Sigma extends the Aradbase detection research ecosystem by translating malware research and static detection concepts from **Aradbase-YARA** into behavior-based Sigma detections.

This enables broader visibility across SIEM and log-based detection environments.

---

## Repository Structure

```text
rules/
├── malware/
├── persistence/
├── credential_access/
├── lateral_movement/
├── ransomware/
└── generic/
```

---

## Disclaimer

This repository is intended for **research and defensive purposes only**.

Detection accuracy is not guaranteed. Users should validate rules within their own environments and SIEM implementations.

---

## Contributions

Contributions are welcome. Please ensure rules are:

- Relevant and tested  
- Clearly written  
- Low-noise / low false-positive (best effort)  
- Properly documented when applicable  

---

## License

Specify your preferred license (e.g., MIT / Apache 2.0).
