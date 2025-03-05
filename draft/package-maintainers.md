# Package Maintainers Working Group

🚧 Draft charter: this working group isn’t currently approved. The proposal requires further work, and an initial membership team.

## Scope of responsibilities

This group supports package maintainers in the Django ecosystem.
Packages are an important part of the experience of using Django, and their maintainers can benefit from different forms of support than Django contributors and users.

The goals of the group are:

- To facilitate discussions and share knowledge about common issues or tasks in package maintenance.
- To coordinate efforts to improve the health and quality of packages in the Django ecosystem.
- To advocate for the needs of package maintainers in the Django community.

This is a broad definition of the group’s remit.
Current members select specific activities to undertake based on their interests and availability.
See [Group activities](#group-activities) for examples of what the group may choose to do.

### Delegated responsibilities

With regards to Django Software Foundation responsibilities and resources, the group operates with:

- No special powers delegated by the board to the group.
- No specific "Django Software Foundation" actions the group can take directly.

Any request for funding or resources are made via existing processes outside of this group.
This can be revised in the future as and when the group identifies specific recurring needs.

## Membership

- Chair: You?
- Co-Chair: You?
- Board Liaison (must be an active Board member; may be the same as Chair/Co-Chair): You?
- Other members:
  - You?

The Chair, Co-Chair and Board Liaison manage the membership of the group. The Chair and Co-Chair animate the group’s activities. The Board Liaison relays information between the group and the Django Software Foundation Board.

### Eligibility

Membership is open to all Individual Members of the Django Software Foundation.

### How to join

To join, members must apply via the group’s [membership application form](https://www.example.com/) (to be set up once the group is up and running), sharing their motivation for joining, and expected contributions.

Membership applications are reviewed asynchronously and during meetings, after which they will be voted in by current group members (50%+1). Members will be selected for the group based on their interest in the group’s goals and ability to contribute to them.

### Membership terms

Members join the group for a 12-month term. At the end of this term, they need to opt into staying involved to keep being a member of the group.

If any member wishes to leave the group before the end of their term, they can do so without a vote.

Members can propose a vote on removing a member from the working group. This needs 50%+1 agreement.

## Budget

No allocated budget, the group makes ad-hoc requests for funding or resources as needed.

## Group communications

The group communicates asynchronously via:

- The public `#packages` channel on the Django Discord server.
- Appropriate public sections of the [Django Forum](https://forum.djangoproject.com/).
- GitHub issues and pull requests in a new `django/package-maintainers-wg` repository.
- Collaborative documents set up in the Django Software Foundation’s Google Workspace.
- A new private #package-maintainers-wg` channel on the Django Discord server for internal discussions.

The group will also offer office hours for package maintainers every month via a video call.

## Reporting

The group will share highlights from current activities on a monthly basis via a forum post.

## Appendix

### Group activities

As an illustration of the group’s remit, here are possible activities members could take part in.

#### Support Django version compatibility efforts

As Django regularly releases new versions, it’s an ongoing effort to ensure packages are compatible with new releases.

Group members can support maintainers in this effort by:

- Creating a shared calendar with Django release dates and deadlines.
- Creating communication channels for package maintainers to coordinate compatibility changes for a specific release.
- Recommending appropriate automation, such as [django-upgrade](https://github.com/adamchainz/django-upgrade) or how to set up Django pre-releases in Continuous Integration.
- Proposing additions to the Django release notes with recommendations on how to handle deprecations.

#### Share packaging best practices

The group can work on create, maintain, or curate best practices for Django package maintainers. For example, the official [Advanced tutorial: How to write reusable apps](https://docs.djangoproject.com/en/5.0/intro/reusable-apps/), or packaging-focused sections on third-party resources like [awesome-django](https://github.com/wsvincent/awesome-django).

Those best practices can cover aspects like:

- Documentation approaches and tools
- Use of the `django_` prefix for app names (see [Change reusable apps naming recommendation](https://forum.djangoproject.com/t/change-reusable-apps-naming-recommendation/25233)).
- Recommended Python, Django, browser, operating system support policies to align with those of Django itself.
- Tooling, for example how to set up Continuous Integration for Django packages.

#### Facilitate community-driven maintenance

Group members can liaise with organizations dedicated to sharing maintenance efforts, such as [Jazzband](https://jazzband.co/), [Wagtail Nest](https://github.com/wagtail-nest), or [Django Commons](https://github.com/django-commons). Or work directly with packages in need of new maintainers to find new candidates. This can involve:

- Sharing calls for new package maintainers.
- Coordinating trusted volunteer open source “roadies” familiar with package ownership transfers.
- Facilitating participation in mentoring programs such as [Google Summer of Code](https://summerofcode.withgoogle.com/) or [Djangonaut Space](https://djangonaut.space/).
- Providing support for tasks requiring very specific expertise, like funding avenues or vulnerability reports handling.
- Encouraging working on packages during contributor sprints.

### Curate training for maintainers

The group could help organize (and fund) training sessions or training material for package maintainers on relevant topics. For example anything relating to sustainability of long-term development, or product / project management (deprecation policies, user research, writing roadmaps, fundraising).

### Advance the state of the art

The group could also work on more ambitious projects to advance the state of the art in Django and Python package maintenance. For example:

- A standard to call for contributors, maintainers, or request funding via pip or a manage.py check
- Distributed code review for Django packages (see for example [crev](https://github.com/crev-dev/crev/))
- Participation in convenings such as [PackagingCon](https://packaging-con.org/), [Upstream](https://upstream.live/), etc.
