# ISMS Scope Statement

## Organization

BlueSky Technologies (Fictional) is a SaaS technology company with approximately
600 employees. The organization provides cloud-based software services to
enterprise customers.

## Scope Statement

This Information Security Management System (ISMS) covers the information security
processes, technologies, and controls that support BlueSky Technologies' cloud-based
SaaS platform and associated production environment.

The ISMS scope includes:

- Identity and access management through Okta
- IT service management and change management through ServiceNow
- Cloud infrastructure hosted on AWS
- Information security risk management processes
- Access control processes
- Change management processes
- Security monitoring and operational security processes

## Boundaries

The ISMS applies to the production environment supporting BlueSky's SaaS platform
and enterprise customers.

Corporate IT services that do not directly support the production environment are
outside the ISMS scope, except where they have a security dependency with in-scope
systems, such as identity and access management through Okta.

## Internal and External Context (Clause 4.1)

### External Context

BlueSky operates in the enterprise SaaS market where customers expect strong
information security practices and assurance over protection of their data.

External factors affecting the ISMS include:

- Customer contractual security requirements
- Data protection and regulatory obligations
- Cloud service provider dependencies
- Evolving cybersecurity threats

### Internal Context

Internal factors affecting the ISMS include:

- Cloud-native technology environment
- Engineering-driven development model
- Dependence on identity management and cloud infrastructure
- Need for effective access governance and security operations

## Interfaces and Dependencies

The ISMS has dependencies with:

- AWS as the cloud infrastructure provider under a shared responsibility model
- Okta for identity and access management
- ServiceNow for IT service management and change workflows
- Third-party SaaS applications integrated with enterprise identity systems

## Related Portfolio References

- ITGC Audit Scope: `02-Audit-Planning/README.md`
- Company Technology Environment: `01-Company-Profile/README.md`
- Existing ITGC Control Testing: `04-User-Access-Management/`,
  `05-Change-Management/`, `06-Computer-Operations/`
