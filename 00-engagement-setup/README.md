# Engagement Setup

This phase defines the operational preparation conducted before active enumeration begins.

The objective is to eliminate ambiguity, confirm scope, structure documentation, and establish a disciplined workflow prior to interacting with target systems.

---

## 1. Scope Validation

Before any testing activity:

- Confirm authorized IP ranges, domains, and subdomains
- Identify explicitly excluded systems
- Validate testing window and time restrictions
- Clarify whether credentialed testing is permitted (test credentials if provided)
- Determine if denial-of-service testing is prohibited

Output:
A clearly documented and validated scope boundary.

---

## 2. Rules of Engagement

Establish operational constraints:

- Permitted attack vectors
- Social engineering restrictions (if applicable)
- Authentication testing limits
- Data handling expectations
- Reporting timelines

Output:
Documented operational boundaries aligned with authorization.

---

## 3. Target Inventory Confirmation

Create an initial target inventory:

- IP ranges
- Servers
- Identify Production environment location (public or private)
- Identify Testing evironment location
- Installed OS
- Host primary purpose
- Host primary software
- Web applications
- Domain controllers
- VPN endpoints
- Cloud assets (if in scope)

Output:
Initial asset list to guide structured enumeration.

---

## 4. Documentation Structure

Define note-taking structure before testing:

- Directory structure for findings
- Naming conventions
- Evidence storage format
- Screenshot and artifact organization
- Reproducibility checklist

Output:
Consistent documentation workflow for the engagement.

---

## 5. Time Allocation Strategy (OSCP-Relevant)

For time-constrained assessments:

- Allocate time per target category
- Set enumeration time thresholds
- Define pivot triggers if progress stalls
- Schedule re-enumeration checkpoints

Output:
Time-managed engagement plan that reduces wasted effort.

---

## Completion Criteria

Engagement setup is complete when:

- Scope is confirmed
- Documentation framework is prepared
- Testing constraints are understood
- Initial targets are organized
- Time strategy is defined
