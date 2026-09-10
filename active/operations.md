# Operations Team

## Scope of responsibilities

The Operations (Ops) Team is responsible for managing the DSF's core infrastructure, hosting and software-as-a-service providers, and sensitive matters such as credentials. The dedicated team helps limit attack surface area and limit impact of incidents.

The Ops team manages several platforms:
- The server running [djangoproject.com](https://djangoproject.com) and [Django's Trac instance](https://code.djangoproject.com/)
- The [Jenkins server for CI](https://djangoci.com/)

The application repositories for [djangoproject.com](https://github.com/django/djangoproject.com) and [code.djangoproject.com](https://github.com/django/code.djangoproject.com) are public, while their production infrastructure is managed through private GitHub Ansible repositories.

The Ops team also helps manage several applications due to their privileged access:

- The [Django GitHub organization](https://github.com/django)
- The [DjangoCon GitHub organization](https://github.com/djangocon)
- Hosting providers
- Content Delivery Network
- Secret management
- Django's domains, DNS records, certificates, and email services, including email addresses and distribution lists

Ops requests commonly involve:

- granting, changing, or removing access to services;
- investigating and restoring unavailable services;
- deploying or updating existing services; and
- setting up new tools for Django teams and working groups.

The Ops team is able to make the following decisions based on their judgement:

- Software and OS upgrades (major and minor)
- Updates to or migrations between established service providers
- Performance improvements
- Bug fixes
- Backwards compatible changes
- Access control requests
- DNS changes

The Ops team will request Board approval before moving forward any other decision.

## Current membership

- [Optional] Board Liaison (must be an active Board member; may be the same as Chair/Co-Chair):
- Members:
    - Jacob Walls
    - Mariusz Felisiak
    - Markus Holtermann
    - Natalia Bidart
    - Sarah Boyce
    - Tobias McNulty

## Future membership

The team manages its own membership by invitation. If the team needs to make a call for volunteers, it will be posted on the [djangoproject.com blog](https://www.djangoproject.com/weblog/) and the [Django Forum](https://forum.djangoproject.com).

The membership will operate as follows:
- Django Fellows are included in the Ops team mailing list for awareness, and are invited to be part of the Ops team, in which case they begin with the [onboarding period](#onboarding)
- A Django Fellow contract termination removes the person from the Ops team
- There should be at least three members at all times
- There is no upper limit to the number of members
- Each year, every member will need to reaffirm their membership with the team

### Qualifications

The primary qualification for Ops team members is trust. The person must be trusted with the highest level of access in the community. This means they need to have a steady, extensive track record of good decision-making and dedication to the community.

From a technical perspective members are expected to have knowledge in the following areas:

- DevOps experience (Ansible, AWS, OpenStack)
- DNS management
- Linux server administration
- Docker/Podman
- PostgreSQL

### Onboarding

Invited candidates, including new Fellows, first complete a 3-month onboarding period during which they shadow the team, familiarize themselves with Django's infrastructure, and get a feel for the requests the team receives, before their membership is made official. During this period, they are added to:

- the Ops Slack channel;
- the Ops email distribution list; and
- the regular Ops team meeting.

They are also granted read-only access to the private Ansible infrastructure repositories.

There is no expectation that team members will understand every service or respond to every request. All non-Fellow members of the team are volunteers, and we understand that availability is limited. If a candidate member identifies an area where they feel able to help, they should ask for the relevant access. Access to the most sensitive services (such as root-level access to the team's password manager, hosting providers, or backend servers) will **not** be granted during the onboarding period.

After the onboarding period, the candidate can express whether or not they're interested in applying for official membership on the team. If so, the current team will vote on whether to promote them to a full team member.

## Budget

The Ops team manages USD $100,000-plus worth of infrastructure through in-kind donations from DSF sponsors.

There is no dedicated budget at this time, but funds can be requested from the Board.

## Comms

The team can be contacted via the [ops@djangoproject.com](mailto:ops@djangoproject.com) email.

The team can be mentioned in the following ways:

- [GitHub team](https://github.com/orgs/django/teams/ops-team)

The team meets monthly via Meet.

The team has private channels on the [DSF Slack instance](django-dsf.slack.com) and the [Django Discord server](https://chat.djangoproject.com) (our primary and backup internal channels, respectively).

## Reporting

The team does not produce reports at this time.
