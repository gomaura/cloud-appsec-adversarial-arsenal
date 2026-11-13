**Cloud-Appsec-adversarial-arsenal**: Tools, Recon Scripts & Research

A curated collection of custom offensive security tools, lightweight reconnaissance scripts, and technical write-ups covering Cloud, Active Directory, Web/API, and AI attack surfaces.

**Disclaimer:** All tools and write-ups in this repository are strictly for authorized security testing, educational research, and defensive hardening.



**Repository Structure**

### `/tools` — Custom Scanners & Recon Scripts
Lightweight, single-purpose utilities built to identify specific misconfigurations and logic flaws without noisy automated scanning.
* **`/recon`** — Subdomain enumeration, asset discovery, and tech-stack fingerprinting scripts.
* **`/cloud-audit`** — Targeted scripts for enumerating AWS IAM privileges, Entra ID app permissions, and exposed metadata/storage endpoints.
* **`/web-api`** — Custom fuzzers and checks for BOLA/IDOR, JWT misconfigurations, and rate-limit testing.

### `/write-ups` — Lab Walkthroughs & Attack Paths
Detailed technical breakdowns demonstrating manual exploitation, post-exploitation, and remediation strategies.
* **`/active-directory`** — End-to-end internal domain compromise paths (ADCS abuse, delegation, Kerberos attacks).
* **`/cloud-and-k8s`** — Privilege escalation chains across AWS, Azure, and Kubernetes environments.
* **`/web-and-mobile`** — Complex business logic vulnerabilities, SSRF-to-cloud-credentials, and mobile traffic interception.
* **`/ai-llm`** — Exploiting prompt injection and insecure agent tool integrations.


## Tooling Standards
Every script published in this repository adheres to the following principles:
1. **Minimal Dependencies:** Built primarily in Python, Bash, or PowerShell for easy deployment during engagements.
2. **Low Noise / High Signal:** Designed to validate specific hypotheses rather than blindly spraying payloads.
3. **Clear Output:** Structured terminal and JSON/Markdown output ready to be dropped directly into assessment reports.
