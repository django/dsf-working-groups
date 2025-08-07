# Security Working Group

🚧 Draft charter: this working group isn't currently approved. The proposal is for establishing a formal security team to coordinate Django's security efforts.

This charter proposes the formation of an official Security Working Group to formalize and expand the security coordination efforts that have been part of Django's development process. The Security Working Group will be responsible for ensuring that Django and associated projects maintained by the Django Software Foundation maintain high security standards and respond effectively to security incidents.

## Responsibilities

This working group will focus on security aspects of the Django project. The team will be responsible for addressing security concerns, reviewing vulnerability reports, and providing guidance on security best practices throughout the Django ecosystem.

The duties of the working group are:
- Receive, triage, and respond to security vulnerability reports for Django
- Coordinate the release of security patches with the Django release team
- Review security-related pull requests across Django projects
- Provide security guidance on Django features and APIs
- Monitor the security landscape to proactively identify potential vulnerabilities
- Help maintain Django's security documentation
- Develop and maintain security-related packages in the Django ecosystem
- Provide security advice to Django package maintainers when requested
- Assist with security aspects of the djangoproject.com website
- Mentor new contributors interested in Django security
- Run or support security-focused sessions in DjangoCon sprints
- Chair, Co-Chair and Board Liaison can sign off on security decisions

## Initial membership

- Chair: TBD
- Co-Chair: TBD
- Board Liaison (must be an active Board member; may be the same as Chair/Co-Chair): TBD
- Other members:
  - TBD
  - ...

## Future membership

### Who is eligible to join? Any volunteer, or are there specific requirements?

Members must have interest in Django security and should have experience with web security concepts, particularly as they relate to Django applications. Prior experience with Django and its security mechanisms (e.g., CSRF protection, XSS protection) is highly recommended. Members should be familiar with the Django [security release process](https://docs.djangoproject.com/en/dev/internals/security/) or willing to learn.

We welcome contributors with various levels of experience, but due to the sensitive nature of security work, members should demonstrate a track record of responsible security practices. Experience with security vulnerability assessment, analysis, or remediation is a plus.

### Access granting and deployment

Initial onboarding phase where only Chair and Co-Chair have permissions to access security reports and coordinate responses. After onboarding of 6 months, other group members who have proven their expertise will be granted access to the security issue tracker and response coordination at the discretion of the chair and co-chair.

The deployment of security fixes will be coordinated with the Django release team and the ops team.

### How do people who want to join sign up / volunteer / express interest?

Individuals can express interest by opening a PR to this working group repository using a template, adding their names in the list of members along with a brief description of their security experience and motivation to join the group.

Alternatively, individuals can send an email to the Chair or Co-Chair expressing interest and outlining their qualifications and motivation.

### How will decisions on adding/removing members be handled?

Direct membership: new members may self-nominate; the WG will vote (50%+1) to approve/deny new members. The WG will vote for New Chair/Co-Chairs and decision to appoint will be based on gaining majority votes.

Members join the group for one year term. At the end of this term, they need to opt into staying involved to keep being a member of the group.

Due to the sensitive nature of security work, members who fail to adhere to responsible disclosure practices or exhibit other concerning behavior may be removed by a vote of the working group (50%+1) or by decision of the Chair and Co-Chair in consultation with the Board Liaison.

## Budget

No allocated budget.

Sums may be provided for specific activities (e.g. security audits, external consultancy, security tooling, bug bounty programs) subject to approval by the DSF board.

## Communications

- Private channel in the DSF slack for internal discussions
- Encrypted communication channels for sensitive security discussions
- Public reports of resolved security issues on the Django security page
- The Django forum sub-section "Security" of Django Internals for general security discussions

## Reporting

We'll maintain a private log of all security reports and their resolutions. Public disclosures will follow Django's established security release process.

The working group will provide quarterly reports to the DSF board summarizing activities (with sensitive details redacted as appropriate).

## Appendix

### Group activities

As an illustration of the group's remit, here are possible activities members could take part in:

#### Security Review Process

- Establish a formal process for reviewing security-related PRs across Django projects
- Create templates and checklists for security assessments
- Develop guidelines for security considerations in code reviews

#### Security Documentation Enhancement

- Regularly review and update Django's security documentation
- Create more comprehensive guides for security best practices
- Develop case studies of common security vulnerabilities and their solutions

#### Security Training

- Develop training materials for Django contributors on security topics
- Host workshops or office hours for package maintainers seeking security advice
- Prepare security-focused sessions for DjangoCon events

#### Proactive Security Measures

- Conduct periodic security reviews of Django's codebase
- Monitor CVEs and other security disclosures for relevant vulnerabilities
- Explore integration of additional security tools in the Django development process