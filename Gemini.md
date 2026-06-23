# Workspace Automation Rules & Style Guide

## Repository Architecture
* `/` (Root): Core landing hub and main configuration arrays.
* `/writeups/` (DFIR/CTF): Standalone operational logs and challenge walkthrough layouts.

## Artifact Formatting Rules
* **Theme Alignment:** Maintain the dark terminal SOC dashboard aesthetic across all generated documents.
* **Front-Matter Structure:** Lead standalone reports with standard operational case metadata blocks:
```yaml
  ---
  Category: Digital Forensics & Incident Response (DFIR)
  Tactics: [Staging, Exfiltration, Anti-Forensics, etc.]
  Case Date: YYYY-MM-DD
  Platform: Blue Team Labs Online (BTLO)
  ---