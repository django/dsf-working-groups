# Browser Platform Working Group

## Scope of responsibilities

Ensure Django stays aligned with evolving browser platform standards (ECMAScript/TypeScript and runtimes, DOM/browser APIs, and CSS) so first-party features and community integrations remain current and robust. HTTP and server-side transport concerns are out of scope.

- Propose long-term browser platform adoptions (e.g., importmaps, native ES modules, modern CSS features) via DEPs to the Steering Council/Board.
- Define and oversee a multi-release roadmap; review frontend feature proposals and ensure alignment with the roadmap.
- Implement regression-hardening strategies for frontend assets (tests, benchmarks, CI checks) to reduce breakage when browsers or dependencies change.
- Maintain guidelines and linting rules to flag outdated patterns (e.g., legacy jQuery usage) and recommend supported alternatives.
- Coordinate with third parties (browser vendors, framework authors, standards bodies) on interoperability concerns and upcoming changes.
- Oversee third-party frontend dependencies, vendoring decisions, and integrations, including deprecation/removal plans.
- Support Fellows and other WGs (e.g., Security, Website) on frontend matters and incident response.
- Prepare and support grant applications or SoC proposals tied to roadmap milestones.

## Initial membership

- Chair: TBD (seeking a DSF member with modern frontend experience)
- Co-Chair: TBD
- Board Liaison (must be an active Board member; may be the same as Chair/Co-Chair): TBD (requested)
- Other members: initial volunteers to be recruited from DSF members and experienced external frontend maintainers.

## Future membership

- Eligibility: open to DSF members and non-member contributors with relevant frontend/platform experience and familiarity with Django's release process.
- How to join: self-nominate via the WG mailing list or GitHub PR comments; requests are acknowledged in the next scheduled meeting.
- Decision process: direct membership model — new members approved by simple majority (50%+1) of current members; Chair/Co-Chair changes elected by the WG. The Board Liaison retains a veto on membership changes if risks to DSF oversight are identified.

## Budget

- Initial request: modest discretionary budget (e.g., up to $5k/year) for prototype work, CI/tooling experiments, small bounties, and occasional standards/interop outreach. Larger grants or SoC sponsorships to be scoped and approved case-by-case with Board review.
- Allocation: budget to be requested annually; expenditures reported in regular updates.

## Comms

- Mailing list (requested): `browser-platform-wg@djangoproject.com`.
- Private Discord channel on the Django server for synchronous discussions; public updates shared on the forum.
- Meetings: monthly synchronous meeting; ad-hoc sessions for roadmap checkpoints and DEP drafting.

## Reporting

- Written report to the Board (and Steering Council liaison) quarterly, summarizing roadmap status, upcoming DEPs, risks, and budget spend.
- Brief status note after each major roadmap milestone or DEP decision.
