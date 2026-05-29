# Course 2 — Play It Safe: Manage Security Risks

## Key Concepts

**CISSP 8 Security Domains applied to SOC:**
- Security & Risk Management: understanding threat actors, 
  risk types and security frameworks
- Asset Security: classifying and protecting organizational assets
- Security Operations: day-to-day SOC activities, log monitoring, 
  incident triage and escalation

**NIST Cybersecurity Framework (CSF):**
- Identify: asset inventory, risk assessment
- Protect: access controls, security policies
- Detect: continuous monitoring, SIEM alerts, anomaly detection
- Respond: incident response playbooks, containment, escalation
- Recover: system restoration, post-incident documentation

**SIEM in Practice:**
- Aggregates logs from multiple sources into a single platform
- Enables correlation of events across endpoints, network and cloud
- SOC N1 analyst uses SIEM to: monitor dashboards, triage alerts,
  identify false positives, escalate confirmed incidents

**Playbooks:**
- Step-by-step guides for responding to specific incident types
- Ensure consistent, documented response regardless of analyst
- Common playbooks: phishing, malware, unauthorized access, DDoS

**Audit Logs — what to look for:**
- Failed login attempts (brute force pattern)
- Privilege escalation events
- Off-hours access to sensitive systems
- Large data transfers to external destinations

## SOC Relevance
The NIST CSF Detect and Respond phases are the core of SOC N1 
operations. Every alert received goes through the same cycle:
identify the event → correlate with context → classify severity 
→ follow playbook → escalate or close with documentation.
