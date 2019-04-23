# RFC: Request For Comments
This repository is the common space where Moda Tech can come together to both solicit and provide comments on proposed system design and improvements. Through the course of executing on projects, individuals and squads will be designing systems both big and small; as they formulate those plans, they can submit a RFC here and receive feedback on the design.

## Goals

### Collaboration
Building technology is more of an art than people may realize; there are often many ways to accomplish the same thing. When making design decisions, it can be beneficial to get outside opinions and talk through those decisions. Furthermore, as an organization we want to build systems in a coherent manner; by discussing design, we can be clear about standard best practices, generally follow them, and also be clear about why we choose to not follow them when the need arises. This process is something that naturally will require input/thinking/collaboration across squads.


### Transparency
As an active member of Moda Tech, it is inevitable that people will need to look at systems that they did not build - this could be as a reference/example, or as part of taking on ownership, or as part of troubleshooting/debugging. When looking at unfamiliar systems, it can be difficult to identify exactly why certain design decisions were made. Inserting a RFC into the process of designing systems will help make it clear why a system was built the way it was. As mentioned above, it will also make it clear why a decision was made to go against standard best practices, when we're consciously trialing technologies, backup plans, etc.


### Education
The RFC helps ramp up the skills of individuals in a number of different directions. Most obviously a RFC will benefit the requester, as commenters point out things that might not have been thought about and the system design gets refined and improved. But RFCs also help people who are not necessarily commenting - they can see the expertise that commenters bring to the conversation, how they think about systems, what solutions and improvements they suggest. In this way, Moda Tech can lift its skills by giving experienced engineers the forum through which to indirectly educate less experienced engineers.

## Process

### For requesters
1. Design your system.
2. Write the RFC using the [standard template](TEMPLATE.md).
3. Place the RFC file in an applicable subdirectory of [RFCs](RFCs). If more than one category is applicable, add a symlink in other category directories, pointing back to the source RFC file. Add subdirectories (representing categories) as necessary.
4. Submit a PR with the RFC.
5. Add any specific individuals/groups from which you would like to receive comments. How do you know whom to add? Good candidates include:
  * [CODEOWNERS](CODEOWNERS) (will be automatically added)
  * [Guilds](https://github.com/orgs/ModaOperandi/teams?query=guild)
  * [Squads](https://github.com/orgs/ModaOperandi/teams?query=squad)
  * Individuals that you know have expertise
6. Address any/all comments by updating the RFC/PR with further commits.
7. Optionally extend the duration if needed.
8. At the end of the duration, update the Resolution section of the RFC to indicate whether the proposal was accepted, declined, or shelved until a future date.
9. Merge the PR to master; this indicates that the RFC is closed. All RFCs should be merged to master regardless of resolution, for visibility.


### For commenters
1. Setup Github notifications to get notified of PRs.
2. Alternatively add yourself to [CODEOWNERS](CODEOWNERS) if you would like to limit notifications to certain topics, based on directory structure.
3. Join a [Guild](https://github.com/orgs/ModaOperandi/teams?query=guild) that is focused on an area in which you have interest or expertise. Feel free to read more about [Guilds at Moda](https://github.com/ModaOperandi/agora#guilds).
4. Comment on PRs.
5. Review - approve or request changes - to indicate your opinion on the proposal.


## Opt-ins
It is up to you to opt-in to any/all conversations around RFCs. You can do this either on a global level by using Github notifications on PRs or you can use [CODEOWNERS](CODEOWNERS) to get automatically added as a reviewer on RFCs only in certain categories.

On the whole, it is recommended that _most_ people pay attention to RFCs, but we understand that not everyone will have the bandwidth to comment on all RFCs; this is totally fine and people should participate at whatever level makes sense for them and their deliverables. Thus participation is driven by opting-in (as above); the opt-in strategy can even vary for individuals over time and it is up to them to tweak their opt-ins as necessary.

On the opposite end, requesting comments is also opt-in; Moda Tech is using the RFC format not as a gatekeeper for building systems and it is not the intention to add red tape or blockers to software development. It will remain highly subjective when a RFC is appropriate, but culturally (for the reasons listed above) we should favor submitting RFCs over not.


## Public vs Private
This forum is intentionally private (as opposed to [Agora](https://github.com/ModaOperandi/agora)) because discussions here may touch upon designs and decision-making that should remain internal to Moda Operandi.


## One final note
This is a living document/process. If we discover parts of the process that aren't working, anyone can update the process, submit a PR, and drive a conversation around the proposed improvement.
