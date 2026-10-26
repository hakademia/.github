# Hakademia Governance

**Status:** Proposed policy — effective upon approval by Hakademia's organization owners  
**Version:** 1.0  
**Maintained by:** Hakademia Core Team

## 1. Purpose

Hakademia builds developer tools, coding competitions, plugins, SDKs, and community-led open-source projects. This document explains how projects are governed, how access is granted, how decisions are made, and how contributors receive recognition.

Our principles are transparency, least-privilege access, creator recognition, constructive collaboration, and responsible stewardship.

## 2. Membership and circles

Membership is assigned by organization owners. A GitHub Team identifies responsibilities; it does not by itself grant organization-wide repository creation permissions.

### Circle 1 — Core Team

Core Team members develop and maintain Hakademia's core platform, architecture, and infrastructure. Access to private Core repositories is granted only as required for their work. Core membership does not automatically confer the GitHub Organization Owner role or administrative access to every repository.

### Circle 2 — Ecosystem Team

Ecosystem members build plugins, SDKs, integrations, documentation, and supporting tools. They do not receive access to private Core repositories by default. Public repositories may be created under the organization's current member permissions. Private Ecosystem repositories require owner approval and creation through an authorized process, followed by explicit team or individual access grants.

### Circle 3 — Community Team

Community members create public projects, hackathon entries, experiments, and educational resources. They may create public repositories when enabled by the organization's settings. They do not receive access to private Core or Ecosystem repositories by default. All community projects must follow the documentation, attribution, and conduct requirements below.

### External collaborators

External collaborators may be granted access to specific repositories without becoming organization members. Their access is limited to what is needed for the contribution and can be revoked when no longer required.

## 3. Repository ownership and creation

Repositories hosted under the Hakademia GitHub organization are administered by Hakademia, subject to applicable law, licenses, and contributor agreements. Hosting a repository in the organization does **not** automatically transfer copyright or intellectual-property ownership from its authors.

- Organization owners control repository creation policies and may restrict creation, visibility changes, deletion, and transfers.
- Members must select the Hakademia organization as repository owner when creating a Hakademia project.
- Private projects require explicit authorization and appropriate access controls.
- Project creators should be granted the minimum permissions needed to maintain their repositories; administrator privileges are not automatic.
- Repository names, descriptions, and content must not misrepresent official endorsement or affiliation.

## 4. Creator recognition and attribution

Each project must identify its original creator(s), current maintainer(s), and contributors as accurately as possible.

- Include creator credit in `README.md` and maintain an `AUTHORS.md` file.
- Preserve Git history when transferring or reorganizing repositories wherever feasible.
- Distinguish the original idea or project initiation from code contributions and ongoing maintenance.
- Credit may be corrected through a documented review if attribution is disputed or inaccurate.
- No maintainer may remove legitimate attribution as retaliation or to falsely claim another person's work.

Recognition does not, by itself, grant exclusive ownership, administrative control, or copyright.

## 5. Licensing and intellectual property

Every public project must have an appropriate license chosen by the authorized rights holders. Hakademia may recommend standard open-source licenses, but a default template license does not override contributors' rights. Private projects must have clear internal terms before code is shared beyond the authorized team.

Contributors must submit work they are authorized to contribute and must respect third-party licenses, trademarks, privacy, and other rights. Any copyright assignment or contributor license agreement must be separately disclosed and accepted; it is not created by this governance document.

## 6. Project standards

Each active public project should include:

- `README.md` describing purpose, setup, usage, and project status;
- `AUTHORS.md` identifying creators and maintainers;
- `CONTRIBUTING.md` explaining how to contribute;
- `LICENSE` with accurate copyright and license details;
- a security contact or disclosure process where applicable.

Projects should use descriptive names, meaningful commits, reviewed pull requests, and an issue tracker when useful. Templates provide a starting point, not a substitute for project-specific documentation.

## 7. Access and security

- Default organization repository access should be set to **No permission**.
- Private Core access is granted explicitly and reviewed periodically.
- Use the least privilege needed: prefer `Read`, `Triage`, `Write`, or `Maintain` over `Admin` where appropriate.
- Protect important branches with pull-request review and other available repository rules.
- Do not commit credentials, tokens, private keys, personal data, or other secrets.
- Report suspected security issues privately to organization owners or a designated security contact; do not publish exploitable details before coordination.
- Organization owners may immediately suspend access to contain a security incident, followed by review.

## 8. Decisions and approvals

- **Organization-wide policy, membership, repository creation restrictions, and sensitive security decisions:** organization owners have final operational authority.
- **Core architecture and implementation:** designated Core maintainers propose and review changes; organization owners resolve escalated disputes.
- **Ecosystem and Community projects:** designated project maintainers make day-to-day technical decisions within organization policy.
- **New private Ecosystem repositories:** require approval by an organization owner or a specifically authorized delegate.

Significant decisions should be documented in issues, pull requests, or decision records whenever confidentiality permits. Decisions should explain their rationale and allow reasonable feedback.

## 9. Conduct and disputes

Members and contributors must treat others respectfully, avoid harassment and discrimination, and resolve disagreements constructively. A separate `CODE_OF_CONDUCT.md` should define reporting channels and enforcement procedures.

Attribution disputes, access disputes, or suspected policy violations should be raised privately with organization owners or an independent designated reviewer if an owner is involved. Affected parties should have an opportunity to explain their position, except where urgent safety or security action is required. Outcomes should be proportionate and documented appropriately.

## 10. Project inactivity, archiving, and removal

Project maintainers should indicate when a project is unmaintained. Organization owners may archive, transfer, or remove repositories for security, legal, or policy reasons, with notice where practicable. Attribution and license obligations continue to apply when projects are archived or moved.

## 11. Amendments

Any member may propose a governance change through an issue or pull request. Organization owners approve organization-wide policy changes after considering feedback from affected teams. Changes should include a date, a rationale, and an updated version number. Emergency security changes may take effect immediately and should be documented afterward.

---

*This policy governs collaboration and GitHub access within Hakademia. It is not a contract transferring intellectual-property rights and does not replace applicable law or separately signed agreements.*
