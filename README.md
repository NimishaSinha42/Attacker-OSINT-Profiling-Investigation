# Attacker OSINT Profiling Investigation

A defensive cybersecurity lab focused on building an attacker OSINT profile from a breach-forum incident.

The investigation starts with a leaked CISO personal email and a threat-actor handle, then uses multiple OSINT pivots to discover public accounts, aliases, infrastructure, activity patterns, and indicators of compromise.

## Scenario

A CISO personal email appeared on a breach forum along with a leaked bcrypt password hash.

The threat actor posting the leak used the handle:

`0xShadowPulse`

The objective was to build an attacker OSINT profile before the threat actor could pivot from leaked credentials to a targeted attack.

## Investigation Flow

```text
Breach Leak
    ↓
Threat Actor Handle
    ↓
Username Pivot
    ↓
Profile Discovery
    ↓
Email / Domain Footprint
    ↓
Infrastructure Discovery
    ↓
Cross-Platform Correlation
    ↓
Timeline Analysis
    ↓
Attribution Confidence
    ↓
IOC Extraction
    ↓
Final Report
