# DSF Working Groups

## About working groups

Working groups are the primary way work gets done at the DSF. The DSF Board delegates certain powers to working groups, which can then act on behalf of the DSF without Board votes/approvals on every specific item. For example, a Grants Working Group could have authority to directly issue financial grants, subject to certain limits, without the need for the full Board to approve each individual grant.

## Joining a Working Group

Want to help out? Yay! Each working group's charter, linked below, spells out the requirements for membership and the process for joining. Generally, it's as easy as emailing the chair and asking to join (the more sensitive groups, such as the ones with spending authority, do have more stringent requirements).

## Current Active Working Groups

- [Code of Conduct](active/code-of-conduct.md) — handles reports of violations to the Django Code of Conduct.
- [DjangoCon Europe Support](active/dceu.md) — supports the organizers of DjangoCon Europe.
- [Fellowship](active/fellowship.md) — manages the operation of the Django Fellowship program.
- [Fundraising](active/fundraising.md) — coordinates fundraising efforts, particularly around corporate and major donations.
- [Social Media](active/social-media.md) — manages Django's official social media profiles.

## Forming a new Working Group

If you have an idea for a new Working Group, it's a good idea to discuss it with some/all of the DSF board ahead of a formal proposal. Remember, you'll be proposing that the Board delegate some of its powers to this new group, so socializing the proposal before you make it can help make sure your request doesn't come as a surprise. The [list of current board members is here](https://www.djangoproject.com/foundation/), and you can [contact the board as a whole using this form here](https://www.djangoproject.com/contact/foundation/).

### Proposing a working group

Once you're ready to propose a working group, start the process by creating a pull request, adding your new working group's charter. You probably want to use [the provided template](template.md) as a starting point.

Don't worry about getting it all in the first pass; you're welcome to leave some fields as "todo", and come back and edit the PR later to add that info.

Ultimately, the information that needs to be in the charter is:

- **Name** - naming things is hard but we need to call this group something
- **Scope of responsibilities** - what will the working group do?
  - What powers are you asking the board to delegate to you?
  - What actions are you proposing the WG be allowed to take directly?
  - Which actions will the WG take back to the Board for votes?
- **Initial membership** - who will be in this working group when it's first created?
  - **Every working group must have at least one active Board member**. It's best if you already know who this is. It's OK if you don't, but if nobody from the Board volunteers, we can't create your working group. We'll refer to this person as the WG's "Board Liaison".
  - **Every working group must have a Chair and Co-Chair**, please indicate who that'll be.
  - A good size for a Working Group is around 3-7 people. It's fine if you want to fall outside this range, but you may be asked about the relatively smaller/larger size.
- **Future membership** - how will membership be handled once the group is operational?
  - For most groups, having the group self-manage its membership by approving new members and electing new Chair/Co-Chairs is fine.
  - For more sensitive or powerful committees (e.g. Conduct, Grants), having the Board approve membership changes may be more appropriate.
- **Budget** - how much money does the WG need (either to spend directly, or to pass on in the form of grants or similar)?
- **Where will discussions and activities take place?** - the default is for us to make you a mailing list (`your-cool-wg@djangoproject.com`). We can also create a private text channel for you on the [Django Discord server](https://discord.gg/xcRH6mN4fa). If you want to do something else let us know.
  - We suggest synchronous meetings at least monthly. You are welcome to use a channel of your choice. If you would like, a private voice channel can be provisioned for you on the [Django Discord server](https://discord.gg/xcRH6mN4fa).
- **Reporting** - how and how often will the WG report back to the board?
  - For most groups, somewhere between a quarterly and a monthly report will be appropriate. An email summarizing that period's work to the Board is fine for most purposes.
  - Keep this lightweight; don't bog yourself down with onerous reporting requirements. Most WG reports can be just 3-5 quick bullet points.

### Decision-making

After your proposal is complete, notify the board, via your board liaison, that it's ready to be reviewed.

The board will vote on your working group, and either let you know that it's been approved, or give you feedback.

If your proposal is accepted, see the next section. If it's rejected you'll get some feedback about why. You're welcome to modify your proposal and try again!

### Final steps

Once the WG is approved, there are a few small bits of process before you can call it fully-operational:

1. **Merge the pull request**, and link the new charter above. The Board Liason should be able to do this.
2. **Spin up the mailing list** or other communication channels. Once again, the Board Liason is the person who can make this happen.
3. **Schedule and hold your first meeting!**

## Changes to Working Groups

Changes to WG membership are covered in the charter, see above.

Other substantive changes to WG membership require a Board vote. "Substantive" changes are most of what's listed on the charter -- scope of responsibilities, budget, membership decision-making process. Changes to when and how often the group meets/communicates aren't considered substantive (but please update the charter accordingly).

To make changes to a WG, open a pull request modifying the charter. If the change is substantive, the the change will go to a Board vote.

## Shutting down WGs

WGs may be spun down for many reasons. The common ones are that the WG has fulfilled its purpose or is somehow obsolete, or has simply stopped working. If there's a consensus of WG members that the WG has outlived its usefulness in one of these ways, they can shut it down. A majority vote of WG members is not enough to voluntarily shut down the WG (though, if enough members choose to resign, that could bring the membership below the numbers required to sustain the group, see below).

There are also several reasons why a WG may be forced to shut down:

- There aren't enough members to sustain the group. A WG must have, at a minimum, two members (Chair and Co-Chair), and one Board member. If membership falls below those levels, and no replacements can be found, the WG will be automatically shut down.
- The WG ceases reporting to the Board. A WG that misses two or more consecutive reporting periods in a row will generally be considered to be defunct and shut down by the Board (exceptions may be made).
- If the Board believes a WG is no longer functional, for whatever reason, they may vote to shut it down.

The process for spinning down a WG:

- If the Board doesn't already know, inform them that you're shutting down.
- If possible, issue a final report to the board.
- Move the charter to the `archive/` directory, and remove the link above.
- Archive/shut down any mailing lists or other communication channels.
