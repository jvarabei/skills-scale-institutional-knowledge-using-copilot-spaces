# OctoAcme — Stakeholder Communication Map

## Purpose
Define clear communication patterns with stakeholders to ensure the right information reaches the right people at the right time. This map helps avoid over/under-communication and ensures accountability.

## When to use
- At project initiation to plan stakeholder engagement
- When stakeholder needs change during the project
- As a reference for team members on communication expectations

---

## Stakeholder Communication Matrix

### Format
For each stakeholder group, define:
- **What**: Information they need
- **When**: Frequency and timing
- **How**: Communication method
- **Who**: Responsible for communication

---

## Communication by Stakeholder Type

### Sales Stakeholders

**What they need:**
- Feature release dates and readiness
- Competitive differentiators and positioning
- Customer-facing impacts (breaking changes, migrations)
- Beta/early access opportunities
- Known issues and workarounds

**Communication Pattern:**
- **Frequency**: Monthly updates + ad-hoc for deal blockers
- **Format**: Email summary with links to detailed docs
- **Owner**: Product Manager (PdM)
- **Escalation**: Project Manager for timeline questions

**Key Touchpoints:**
- Monthly product update email
- Quarterly roadmap review meeting
- Ad-hoc requests via Slack #sales-requests channel
- Release announcements 2 weeks before GA

---

### Support Stakeholders

**What they need:**
- Release notes and user-facing changes
- Known issues and troubleshooting guides
- Documentation updates
- Bug fix status and timelines
- Feature education and demos

**Communication Pattern:**
- **Frequency**: Per release + weekly bug triage
- **Format**: Release notes, documentation, demo sessions
- **Owner**: Technical Writer (release notes), PM (bug triage)
- **Escalation**: Scrum Master for critical bugs

**Key Touchpoints:**
- Weekly bug triage meeting
- Release notes published 1 week before release
- Demo sessions for major features
- Documentation updates on release day
- Slack #support-feedback channel monitored daily

---

### Compliance Stakeholders

**What they need:**
- Features affecting data privacy, security, or regulations
- Architecture or data flow changes
- Audit trail and logging changes
- Third-party integrations and data sharing
- Approval checkpoints before release

**Communication Pattern:**
- **Frequency**: Per feature requiring review (typically quarterly)
- **Format**: Formal review document + approval meeting
- **Owner**: Project Manager (coordination), Product Manager (content)
- **Escalation**: Product Lead for timeline conflicts

**Key Touchpoints:**
- Compliance review kickoff at project planning
- Design review for features with compliance impact
- Pre-release compliance approval gate
- Incident communication for security issues
- Quarterly compliance checkpoint meeting

---

### Executive/Sponsor Stakeholders

**What they need:**
- High-level project status (on track / at risk)
- Major milestones achieved
- Escalations and decisions needed
- Business impact and metrics
- Resource or budget changes

**Communication Pattern:**
- **Frequency**: Monthly executive summary
- **Format**: One-page status + optional deep-dive meeting
- **Owner**: Project Manager
- **Escalation**: Product Lead or Engineering Director

**Key Touchpoints:**
- Monthly executive status report
- Quarterly business review (QBR) presentation
- Immediate notification of major risks or blockers
- Project completion summary and retrospective highlights

---

### Engineering/Cross-Team Stakeholders

**What they need:**
- Technical dependencies and integration points
- API changes and breaking changes
- Infrastructure needs (database, services)
- Testing and QA coordination
- Deployment windows and rollback plans

**Communication Pattern:**
- **Frequency**: Weekly during active development
- **Format**: Technical sync meetings, design docs, RFCs
- **Owner**: Tech Lead or Senior Developer
- **Escalation**: Scrum Master for blockers, PM for prioritization

**Key Touchpoints:**
- Weekly technical sync meeting
- Design review for shared components
- Dependency tracking in project board
- Pre-release deployment coordination
- Post-release monitoring review

---

## Communication Cadence Summary

| Frequency | Format | Attendees | Owner |
|-----------|--------|-----------|-------|
| **Daily** | Standup (15 min) | Delivery team | Scrum Master |
| **Weekly** | Status sync (30 min) | PM, PdM, Tech Lead | Project Manager |
| **Weekly** | Bug triage (30 min) | Eng, Support, PdM | Project Manager |
| **Bi-weekly** | Sprint review/demo | Team + stakeholders | Scrum Master |
| **Monthly** | Stakeholder update | PM, stakeholders | Project Manager |
| **Quarterly** | Roadmap review | Execs, product, eng | Product Manager |
| **Ad-hoc** | Escalations | As needed | Project Manager |

---

## Communication Channels by Purpose

| Purpose | Channel | Response SLA |
|---------|---------|--------------|
| Urgent blockers | Slack + mention | 2 hours |
| General questions | Slack channel | Same day |
| Status updates | Email + project board | N/A (push) |
| Decisions needed | Slack + meeting | 24-48 hours |
| Documentation | GitHub/Confluence | N/A (self-serve) |
| Formal approvals | Email + meeting | Per project plan |

---

## Stakeholder Onboarding Checklist

When adding new stakeholders mid-project:
- [ ] Identify their role type and information needs
- [ ] Add to appropriate communication channels (email, Slack)
- [ ] Share relevant project documentation and artifacts
- [ ] Set expectations for communication frequency and format
- [ ] Introduce to key team members
- [ ] Add to stakeholder register in project documentation

---

## Tips for Effective Stakeholder Communication

- **Be proactive**: Share status before stakeholders ask
- **Be consistent**: Use the same format and schedule
- **Be concise**: Respect stakeholder time with clear, brief updates
- **Be transparent**: Share risks and bad news early
- **Be accessible**: Make documentation easy to find
- **Be responsive**: Honor the response SLAs
- **Tailor content**: Different stakeholders need different levels of detail
- **Use visuals**: Dashboards and charts communicate faster than text
- **Close the loop**: Confirm stakeholders received and understood critical information
- **Collect feedback**: Ask stakeholders if communication meets their needs

---

## Project-Specific Customization

Use this template as a starting point. Customize based on:
- Project size and complexity
- Stakeholder availability and preferences
- Regulatory or compliance requirements
- Team distribution (remote/co-located)
- Organizational communication norms

Document your project-specific communication plan in the project charter or README.
