# Django Performance WG

## Scope of responsibilities

The performance working group is responsible for improving the performance of the Django project, including the main `django/django` codebase and other packages under the Django project umbrella. Additionally, they act as an advisory team to other groups both within the Django project and wider community.

The duties of the working group are:

- Review performance-related PRs across first-party Django projects
- Assisting the Triage and Review team with benchmarks for relevant tickets
- Provide performance guidance on Django features and APIs
- Help maintain Django's performance documentation and best-practice guidance
- Assist with development and maintenance of performance-related packages in the Django ecosystem
- Provide performance advice to Django package maintainers when requested
- Mentor new contributors interested in Django performance
- Advise community members in improving the performance of their Django applications
- Run or support performance-focused sessions in DjangoCon sprints
- Maintenance of the existng `django-asv` benchmark suite
- Act as an advisory board to the Steering Council when deciding on performance-related enhancements

Performance-related security issues, such as time-based DoS, are not in scope, and are instead handled by the Security Team in the first instance (as currently). However, the Performance WG are available for assistance (triage, benchmark development) if necessary, however this is not a requirement. If the Performance WG discover a performance-related security issue (either themselves or through an issue report), they must report it to the Security Team through existing processes.

Changes to Django and related packages proposed by the Performance WG follow the standard processes for changes, such as DEPs or the `new-features` repository. Final say for inclusion remains with the Steering Council, Merger team or Fellows as relevant. The pursuit of performance must never be at the cost of Django's core values, such as stability, ease of use, maintainability and developer experience.

## Initial membership

- Chair:
- Co-Chair:
- Board Liaison (must be an active Board member; may be the same as Chair/Co-Chair):
- Other members:

## Future membership

### Who is eligible to join?

Any DSF member is eligible to join. The only requirement is that they bring something to the team. Either experience optimising large codebases, working at large scale with Python or Django, or experience maintaining performance-critical components for / of Django (for example WSGI/ASGI servers, DDT, profilers).

Because of the nature of performance investigations, both within Django and the wider Python ecosystem, it's expected joining this working group may be in high demand. For that reason, once the working group is at a reasonable capacity it may not be open for new formal members. The form will remain open to act as an expression of interest.

To mitigate people engaged community members feeling "left out", the vast majority of discussions should be happening in the open (see [Communication](#communication) below). This enables anyone to contribute to discussions and suggest improvements, without needing to be a formal member of the group.

To avoid unnecessary member churn, WG members are expected to sit for at least 1 release cycle (around 9 months). As a volunteer group, this is not a strict requirement.

### How do people who want to join sign up / volunteer / express interest?

A form will be made available in a public space (once created this will be linked to here also).

This form will include questions confirming:

- their DSF membership
- why they want to join
- what experience and skills they bring to the role
- their capacity over the next ~12 months to fulfil the needs of the WG

The form is for expression of interest - there should be no expectation around response time or guarantees of membership. Membership may not be on a first-come-first-served basis. Instead, the WG Chairs are encouraged to fill any gaps within the skill set of the group.

### How will decisions on adding/removing members be handled?

The working group will self-manage members, with a majority vote (50% + 1) to approve or deny no members. The WG will vote internally on new Chair / Co-Chairs at least once per release cycle.

There is no fixed capacity or target for number of volunteers. Chairs are responsible for ensuring the group is sufficiently staffed.

## Budget

As currently defined, the working group will not need any allocated budget. 

Any future change in scope (for example, infrastructure for performance testing) will be discussed with the Board. 

## Communication

- A mailing list `performance-wg@djangoproject.com`
- A public channel in the DSF Slack, intended for working group operational discussions
- A public `#performance` channel in the Django Discord
- A new "Performance" topic under "Django Internals" on the Django Forum
- A `performance-wg` group on GitHub, for convenient mentioning

Meetings: A monthly catch up for the team to review and triage incoming tickets which require further discussion and consider ideas from the group and wider community. These meetings are internal to the group (invite only), however minutes will be published publicly shortly afterwards. The Steering Council and Fellows are considered to have a standing invitation.

Whilst synchronous communication is often needed for larger discussions, asynchronous public discussions should be preferred where possible.

## Reporting

The working group will provide quarterly reports to the DSF board summarizing activities in the current quarter and goals for the upcoming quarter.

## Appendix: What is "Performance"?

"Performance" is a loaded term by design. In this context, it refers to:

- HTTP request / response times
- ORM query efficiency
- Cache efficacy
- Idle / load resource (CPU, memory, IO) usage, both client and server side
- [Core Web Vitals](https://web.dev/articles/vitals)
- Import time / start-up latency

It does not refer to:

- Performance of other metrics covered by existing WGs
- Search engine ranking
- Developer experience
- `django` package install size or speed

Neither of these lists should be considered exhaustive.
