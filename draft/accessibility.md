# Accessibility Team

This charter supersedes [DEP 11: Accessibility Team](https://github.com/django/deps/blob/main/final/0011-accessibility-team.rst). The Accessibility Team encourages projects maintained by the Django Software Foundation to be accessible to as many people as possible, particularly those with disabilities that make using the web more difficult.

## Scope of responsibilities

The remit of the Accessibility Team shall include all user-facing components
of projects maintained by the Django Software Foundation. This includes but is
not limited to:

- User-facing parts of Django, such as default HTML output in forms and such,
  and the Django admin and its default theme, HTML, and UI components.
- All websites and other software projects maintained by the DSF, such as the
  Django website, projects' documentation, Django Snippets, the issue tracker, etc.

The responsibilities of the Accessibility Team are expected to change over time, and are to be decided by consensus of the team, with input from the Technical Board as required. To begin, several areas have been identified:

- Deciding on any relevant accessibility guidelines to follow, such as WCAG,
  and at which conformance level.
- Implementing automated testing to catch issues, working with the ops
  team as needed to integrate this into CI processes.
- Coordinating regular manual accessibility audits on all relevant projects.
- Coordinating the fixing of accessibility issues and the improvement of the
  accessibility in general in Django and associated projects.
- Writing and maintaining documentation relating to accessibility, such as
  a statement of commitment to accessibility issues, and contribution
  guidelines.
- Reviewing accessibility fixes, improvements and other tickets that may affect
  accessibility of any relevant project.

Many of these duties can be undertaken by any contributor, not only by the Accessibility Team, however the Accessibility Team exists to coordinate this work and to step in where contributors are not available and support those who lack the knowledge to do so themselves.
Accessibility Team members shall be added to a team in the GitHub organization with read access to relevant repositories, so that they may be requested to review pull requests, at the discretion of the author, reviewer, or other party.


## Initial membership

- Chair: Tom Carrick
- Co-Chair: Thibaud Colas
- Board Liaison (must be an active Board member; may be the same as Chair/Co-Chair): Sarah Abderemane
- Steering Council Liaison (must be an active Steering Council member; may be the same as Chair/Co-Chair): Tim Schilling
- Other members:
  - Eliana Rosselli
  - Marijke Luttekes
  - Saptak Sengupta
  - Sarah Abderemane
  - Thibaud Colas
  - Tom Carrick
  - Tushar Gupta

## Future membership

## TODO: Define the part that's similar to the CoC committee

The team shall not have a fixed size, but instead will grow and shrink
organically as members choose to leave, and when new members are deemed to be
required by the rest of the team. Membership of the team works similarly to the
`Code of Conduct Committee <https://github.com/django/code-of-conduct/blob/main/membership.md>`_.
New members shall be chosen from a list of volunteers, or if there is a lack
of volunteers, an advertisement will be published on the Django website.
Priority will be given to volunteers who, in no particular order:

- Have disabilities that make using the web and/or web development more
  difficult.
- Have relevant, positive contributions or expertise in the field.
- Have a record of contributing to Django.

Members shall remain in the team for a fixed-term of 9 months, after which
they must opt-in to remain on the team for another term. They may also leave
on their own volition at any time and for any reason. Membership will also be
terminated by:

- Becoming disqualified due to actions taken by the Code of Conduct committee
  of the Django Software Foundation.
- A vote of the Steering Council, or full consensus of the rest of the
  Accessibility Team, if the team is considered too large, the person is not
  making positive contributions, or any other sound reason.

## Budget

No budget is required currently. Spending opportunities will be reviewed at least annually. Any changes will be communicated to the

## Comms

The Accessibility team operates in several areas:
- [Accessibility Forum category](https://forum.djangoproject.com/c/internals/accessibility/26)
- Public #accessbility channel on [Django Discord server](https://chat.djangoproject.com)
- Private channel on [Django Discord server](https://chat.djangoproject.com)
- A private Google Drive folder and Group in the DSF Google workspace

The Accessibility team can be tagged specifically in the following areas:

- The [@accessibility](https://forum.djangoproject.com/groups/accessibility) Forum group tag
- As a [GitHub team](https://github.com/orgs/django/teams/accessibility) in the Django org

The team will meet on a monthly basis via Google Meet, Zoom or a similar platform.

## Reporting

The team will post [public meeting notes](https://forum.djangoproject.com/t/accessibility-team-meeting-notes/26133)
to the forum. This serves as the reporting to the DSF Board
and Steering Council. The team will also produce an annual report
that will be shared with the Django community.
