# Engagement Setup

This phase defines the operational preparation conducted before active enumeration begins.

The objective is to eliminate ambiguity, validate authorization boundaries, structure documentation, and establish a disciplined workflow prior to interacting with target systems.

---

## 1. Scope Validation

Before any testing activity:

- Confirm authorized IP ranges, domains, and subdomains
- Identify explicitly excluded systems or network segments
- Validate testing window and time restrictions
- Clarify whether credentialed testing is permitted and validate provided accounts
- Determine if denial-of-service testing is prohibited
- Identify third-party or externally hosted assets if applicable

Output:
A clearly documented and validated scope boundary.

---

## 2. Rules of Engagement

Establish operational constraints:

- Permitted attack vectors
- Social engineering restrictions (if applicable)
- Authentication testing limits
- Data handling expectations
- Defined communication channels and escalation procedures
- Reporting deadlines and deliverable format

Output:
Documented operational boundaries aligned with authorization.

---

## 3. Target Inventory Confirmation

Organize known or client-provided assets:

- Client-provided IP ranges and domains
- Known production vs non-production segmentation
- Identified server roles (if disclosed)
- Known web applications
- Identity or domain infrastructure (if disclosed)
- VPN or remote access infrastructure
- Cloud or hybrid assets in scope
- Domain Controllers

Output:
Initial asset list to guide structured enumeration.

---

## 4. Documentation Structure

Define documentation standards prior to testing:

- Directory structure for engagement artifacts
- Naming conventions for findings
- Evidence storage format
- Screenshot and artifact organization
- Screenshots must show command execution, full output, and system context (hostname, user, privilege level)
- Reproducibility checklist

Output:
Consistent documentation workflow for the engagement.

---

## 5. Time Allocation Strategy

For time-constrained assessments:

- Allocate time per target category
- Set enumeration time thresholds
- Establish pivot criteria when progress stalls
- Schedule re-enumeration checkpoints
- Define escalation plan for technical blockers

Output:
Structured time allocation plan that reduces inefficiency and reactive decision-making.

---

## Completion Criteria

Engagement setup is complete when:

- Scope is confirmed
- Rules of engagement are documented
- Point-of-contact and communication methods are defined
- Documentation framework is prepared
- Initial target inventory is structured
- Time strategy is established
