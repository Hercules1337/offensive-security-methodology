# Engagement Principles

These principles guide how assessments are conducted and documented.  
They are designed to enforce discipline, reduce randomness, and improve reproducibility.

---

## 1. Enumeration Precedes Exploitation
No exploitation attempt occurs before the attack surface is clearly defined.

## 2. Assumptions Require Validation
Service behavior, access controls, and trust relationships must be confirmed through direct observation.

## 3. Misconfigurations Over Complexity
Configuration weaknesses and logic flaws are prioritized before complex exploit development.

## 4. Manual Understanding Before Automation
Automated tooling supports analysis but does not replace understanding.

## 5. Re-Enumeration After Privilege Change
Every privilege boundary crossed requires renewed enumeration.

## 6. Root Cause Over Payload
The objective is to identify why access was possible, not just how it was achieved.

## 7. Reproducibility Is Mandatory
Every finding must be documented in a way that another tester can reliably reproduce.

## 8. Impact Must Be Demonstrated
Privilege escalation and lateral movement should clearly show business or domain impact.

## 9. Documentation Is Continuous
Notes are recorded during the assessment, not reconstructed afterward.