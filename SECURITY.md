# Hakademia Security Policy

**Version:** 1.0  
**Status:** Proposed  
**Organization:** Hakademia  
**Security Contact:** security@hakademia.dev

## 1. Our Commitment

Hakademia is committed to maintaining a secure environment for its developers, contributors, community members, and users.

Security is a shared responsibility across our Core, Ecosystem, and Community projects.

We encourage responsible vulnerability reporting and coordinated disclosure.

## 2. Scope

This policy applies to repositories and services officially maintained by Hakademia, including:

- Hakademia Core Platform and infrastructure.
- Official plugins, SDKs, and integrations.
- Official developer tools and services.
- Community repositories hosted within the organization.

Community projects may have additional security requirements or separate maintenance responsibilities.

The presence of a repository in the organization does not automatically mean it has undergone a security audit.

## 3. Reporting a Vulnerability

If you discover a potential security vulnerability, please report it privately.

**Security contact: security@hakademia.dev**

Where GitHub Private Vulnerability Reporting is enabled, you may also use the repository's **Security → Report a vulnerability** feature.

Please include, when possible:

- A clear description of the vulnerability.
- The affected repository, service, or component.
- Steps to reproduce the issue.
- The potential security impact.
- Relevant logs or proof-of-concept information, with secrets removed.
- Any suggested mitigation.

**Do not disclose unpatched vulnerabilities through public Issues, Discussions, or Pull Requests.**

Do not include passwords, access tokens, personal data, or other sensitive information in reports unless a secure method of transmission has been agreed upon.

## 4. Responsible Disclosure

We ask security researchers to:

- Act in good faith and avoid unnecessary harm.
- Limit testing to systems they own or are explicitly authorized to test.
- Avoid accessing, modifying, or extracting other users' data.
- Avoid denial-of-service attacks, destructive testing, and social engineering.
- Allow maintainers reasonable time to investigate and address confirmed vulnerabilities.
- Coordinate public disclosure with the responsible maintainers.

This policy does not grant permission to conduct security testing on Hakademia systems without authorization.

## 5. Vulnerability Handling

When a vulnerability is reported, the responsible maintainers should:

1. Acknowledge receipt when reasonably possible.
2. Assess the report and determine its validity and severity.
3. Identify affected components and versions.
4. Develop and review an appropriate fix.
5. Test the fix before release.
6. Publish an advisory when appropriate.
7. Coordinate disclosure with the reporter.

Our initial targets are:

- **Acknowledgment:** Within 3 business days.
- **Initial assessment:** Within 7 business days.

These are targets, not guaranteed response times or resolution deadlines.

## 6. Repository Access and Confidentiality

Private repositories are accessible only to authorized members and collaborators.

Members must:

- Follow the principle of least privilege.
- Use strong authentication and enable two-factor authentication.
- Protect credentials, tokens, and SSH keys.
- Avoid committing secrets to repositories.
- Respect team and repository access boundaries.
- Report suspected unauthorized access promptly.

Access to private Core repositories does not automatically extend to Ecosystem or Community members.

## 7. Dependency and Supply Chain Security

Project maintainers are encouraged to:

- Keep dependencies updated.
- Review third-party packages before adoption.
- Enable GitHub Dependabot alerts where available.
- Use automated security scanning where practical.
- Review GitHub Actions workflows and permissions.
- Avoid untrusted scripts and unnecessary privileged automation.
- Protect release and publishing credentials.

Security measures should be appropriate to each project's risk and maintenance capacity.

## 8. Security Incidents

Suspected incidents involving leaked credentials, compromised accounts, unauthorized repository access, or infrastructure compromise should be reported immediately to the security contact.

Responsible administrators should prioritize containment, credential rotation, impact assessment, recovery, and appropriate notification of affected parties.

Incident details should be shared only with people who need the information to respond effectively.

## 9. Security Advisories and Updates

For confirmed vulnerabilities, maintainers may publish GitHub Security Advisories or release notes describing:

- Affected versions.
- Security impact.
- Available fixes or mitigations.
- Upgrade instructions.
- Appropriate credit to the reporter, with their consent.

Sensitive exploitation details may be withheld until disclosure is appropriate.

## 10. Recognition

Hakademia values responsible security research.

Researchers who report valid vulnerabilities may receive acknowledgment in security advisories or project documentation, subject to their preferences and applicable disclosure requirements.

This policy does not establish a bug bounty program or promise monetary rewards.

## 11. Policy Updates

Hakademia may revise this policy as its projects and security practices evolve.

Material updates should be documented and approved by authorized organization administrators.

---

**Hakademia — Build. Compete. Create.**

*Security is a shared responsibility.*