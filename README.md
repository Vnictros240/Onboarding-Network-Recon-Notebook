# Onboarding-Network-Recon-Notebook

A **non-coding, resource-first onboarding repository** for Network & Firewall Administrators.  
This repo is designed to accelerate situational awareness, operational judgment, and administrative effectiveness in the first 30 days at a new organization.

This is a **Table of Contents–driven knowledge system**, not a software project.

---

## Purpose

This repository exists to help an administrator:

- Build an accurate mental model of the network and firewall environment
- Understand *intent*, not just configuration
- Reduce risk before making changes
- Communicate clearly with engineers, managers, and auditors
- Automate repetitive administrative work safely

By Day 30, a contributor should understand:
- Where trust boundaries exist
- Why traffic flows the way it does
- Which risks matter most
- How changes actually get approved and deployed

---

## Repository Structure (Table of Contents)

The directory structure **is the table of contents**.  
Every directory represents a phase of understanding or operational capability.

Onboarding-Network-Recon-Notebook/
├── README.md
├── 00-Operating-Principles/
├── 01-Access-and-Orientation/
├── 02-Network-Landscape/
├── 03-Firewall-Policy-Landscape/
├── 04-Traffic-and-Behavior/
├── 05-Risk-and-Failure-Patterns/
├── 06-Change-and-Governance/
├── 07-Documentation-and-Mental-Model/
├── External-Resources/
├── Productivity/
├── Automation/
└── 30-Day-Readiness-Assessment.md


---

## Core Onboarding Sections

### [00-Operating-Principles](./00-Operating-Principles/)
How to think before touching production systems.

- Operating discipline
- Risk-first mindset
- Observation before optimization

---

### [01-Access-and-Orientation](./01-Access-and-Orientation/)
How visibility and authority are granted.

- Read-only vs write access
- Change windows
- Escalation paths
- Tooling inventory

---

### [02-Network-Landscape](./02-Network-Landscape/)
How the network is segmented and trusted.

- Zones and VLANs
- Routing domains
- On-prem vs cloud
- Trust boundaries

---

### [03-Firewall-Policy-Landscape](./03-Firewall-Policy-Landscape/)
How intent is translated into enforcement.

- Zone-to-zone policy intent
- Management plane access
- VPN and remote access posture
- NAT and egress design

---

### [04-Traffic-and-Behavior](./04-Traffic-and-Behavior/)
What the business actually uses.

- Top talkers
- High-volume services
- Repeated blocks
- Time-based patterns

---

### [05-Risk-and-Failure-Patterns](./05-Risk-and-Failure-Patterns/)
Where the system is fragile.

- Any/Any rules
- Legacy dependencies
- Incident history
- Single points of failure

---

### [06-Change-and-Governance](./06-Change-and-Governance/)
How safety is enforced socially and procedurally.

- Change management
- Approval paths
- System ownership
- Informal rules that matter

---

### [07-Documentation-and-Mental-Model](./07-Documentation-and-Mental-Model/)
How understanding is made reusable.

- Functional flow documentation
- Risk classification
- Business ownership mapping
- Diagrams and summaries

---

## Supporting Capability Sections

### [External-Resources](./External-Resources/)
Curated **free and paid learning resources** for continuous development.

Topics:
- Vendor documentation
- Firewall platform training
- Networking fundamentals refreshers
- Security and compliance references
- Incident response and logging education

This directory is intentionally tool-agnostic and evergreen.

---

### [Productivity](./Productivity/)
Templates that reduce friction and cognitive load.

Includes:
- Configuration documentation templates
- Hardware upgrade email templates
- Software update notifications
- Change Management meeting invitations
- Maintenance window communications
- Post-change validation checklists

Goal:  
Spend less time writing emails and more time making correct decisions.

---

### [Automation](./Automation/)
Automation ideas and tooling references for **administrative work**, not core product development.

This directory documents:
- Internal scripts
- External paid tools
- Low-code and no-code automation
- Safe automation boundaries

#### Automation Domains

**PowerShell**
- User and access audits
- Device inventory pulls
- Log collection helpers

**Python**
- Report generation
- Config comparison
- Log parsing
- Documentation automation

**Microsoft 365 / Power Automate**
- Change approval workflows
- Ticket creation
- Scheduled reporting
- Notification routing

**Playwright (Web Automation & Analysis)**

Use cases documented here include:

- Automated dashboard and report extraction
- Scheduled PDF or CSV exports
- Network request and API behavior analysis
- Visual regression for internal tools
- Price and asset monitoring
- File organization automation
- Secure auto-login workflows (where permitted)

Playwright is treated as:
- A productivity multiplier
- A reconnaissance and visibility tool
- A way to reduce manual browser-driven work

**Webhooks & Microsoft Teams**
- Change notifications
- Alert enrichment
- Workflow status updates
- Incident coordination

---

## [30-Day-Readiness-Assessment.md](./30-Day-Readiness-Assessment.md)

A self-evaluation checkpoint.

If you can answer the questions in this document calmly and confidently, you are ready to:
- Make changes safely
- Defend decisions
- Propose improvements
- Mentor the next hire

