# Security Team

The Security Team is the group of people who respond to security reports for the Django framework.

## Scope of responsibilities

The Security Team is responsible for [Django’s security policies](https://docs.djangoproject.com/en/dev/internals/security/). This includes:

- Reviewing security reports
- Evaluating and developing fixes for confirmed security issues
- Applying and backporting those fixes in coordination with Mergers and Releasers
- Communicating with reporters
- Communicating with the public about security releases
- Maintaining a list of organizations to receive pre-notifications about security releases, and making these pre-notifications
- Maintaining the DSF's status as a CVE Numbering Authority (CNA) and casting votes (or abstaining) in CNA elections
- Issue CVEs for Django and projects under the Django organization

## Membership

- Chair: Natalia Bidart
- Co-Chair: Jacob Walls
- Report triagers: 
- Steering Council Liaison (must be an active Steering Council member; may be the same as Chair/Co-Chair): Frank Wiles
- Other members:
  - Adam Johnson
  - Jake Howard
  - Mariusz Felisiak
  - Markus Holtermann
  - Michael Manfre
  - Natalia Bidart
  - Paul McMillan
  - Sarah Boyce
  - Shai Berger
  - Simon Charette
 
Note: The DSF Board President has access to the designated reporting channels for governance oversight and legal accountability. This is a longstanding practice, noted here for transparency.

Every member of the team is encouraged to participate in all aspects of the team, including reviewing security reports, developing fixes and communicating with reporters. The expectations for all team members are as follows:

- Participate in the process for at least one security report a year
 
### Role definitions

There are specific roles that have a higher level of expectations:

- **Chair / Co-Chair:** Responsible for coordinating the group, scheduling meetings, renewing the group’s membership, and ensuring that the group’s activities align with its scope and responsibilities. The Chair and Co-Chair roles should be re-elected annually by the team. The details of the election procedure are left to the team.
- **Report Triagers:** Acknowledge and triage initial reports and communicate with reporters.
- **Other Members:** Assist the Report Triagers when needed, for example when a report matches their area of expertise.

#### Report Triager

These team members are responsible for acknowledging and triaging reports initially to determine likelihood of security concern and severity. As this is a volunteer role, the Fellows will support the triagers and when necessary, handle the initial triaging.

Every member can adopt and step back as a Report Triager as their schedule allows.

The responsibilities of a Report Triager are as follows:

- Acknowledge report received
- Initial assessment
- Request help from team/experts if necessary
- For invalid reports, communicate with reporter
- Optionally for valid reports, progress to resolution (e.g. create a PR to resolve the issue)

At a minimum, a Report Triager is expected to:
- Triage 1 report a month
- Join 1 team meeting in a 6 months period

## Future membership

Any DSF member may submit a nomination, including a self-nomination, to the team's mailing list (security@djangoproject.com).
If the team needs to make a call for volunteers, it will be posted on the [djangoproject.com blog](https://www.djangoproject.com/weblog/) and the [Django Forum](https://forum.djangoproject.com). 

Nominations are approved/rejected during the team meeting.
Team members are encouraged to share their position via the mailing list before the meeting.
A nomination is approved when at least one existing Security Team member votes in favor and no member objects.
Note that there is no upper limit to the team size

New members, including new Fellows, complete a 3-month onboarding period during which all external communications (with reporters, vendors, or distributors) must be reviewed by an existing member before sending.
This ensures each report is handled consistently and no valid reports are inadvertently dismissed.

As Django Fellows are contracted to deal with security reports, all Django Fellows are automatically added to the Security Team.

## Membership management

Each year, every non-Fellow member will need to reaffirm their membership with the team.
A non-Fellow member can leave for any reason at any time. A Fellow whose contract ends is eligible to stay on the team if they would like.

### Reasons members can be removed from the team

#### Inactivity

If a member is inactive per this document’s definition, they should be removed from the team with a note of thanks and an open invitation to return.

#### Security or malicious concerns

If there is a credible security or malicious concern, a team member can report this in a private email to all other members.
If at least 2 members (including the reporter) share this concern, the team must temporarily suspend access during an investigation, notifying the individual.
If the team can't arrive at a consensus, the decision can be escalated to the DSF Board.

#### Code of Conduct disqualification

As an official Django space, the security team abides by the Code of Conduct.
As per the [Code of Conduct Enforcement Ladder](https://github.com/django/code-of-conduct/blob/main/enforcement-ladder.md), members may be temporarily suspended or permanently banned from the security team following a Code of Conduct report.

### Membership requirements

Members should possess some knowledge in most of the following topics:

- Building Django applications
- Contributing to Django
- Web applications
- Web security
- Software security
- Software performance

## Budget

No budget is required at this time. This will be reviewed at least annually.
Any changes to the budget may be requested from the board.

## Comms

The team has discussions in the following places:

1. Formal and sensitive discussions on the mailing list: security@djangoproject.com
2. Informal and team discussions on the DSF Slack in the private channel `#security-private`
3. Monthly video-conference meetings
4. A private Github repository to collect and triage all reports and to prepare patches

## Reporting

An annual report is shared with the Steering Council and the DSF Board summarizing the team's activity, areas of concern, considerations for the future and any other relevant topics.
