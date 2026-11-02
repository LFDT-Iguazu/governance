[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Iguazu Governance

This repository holds the governance documents of [Iguazu](https://github.com/LFDT-Iguazu),
an [LF Decentralized Trust](https://www.lfdecentralizedtrust.org/) project, and the
declarative configuration of the LFDT-Iguazu GitHub organization.

Project-wide documents live here, and every Iguazu repository links to them by
reference, so they only need to be updated in one place.

## What is here

- [Iguazu Technical Charter](Iguazu%20Technical%20Charter%20FINAL%2009-21-2026.pdf): the
  responsibilities and procedures of the project and its Technical Steering Committee (TSC).
- [MAINTAINERS.md](MAINTAINERS.md): the maintainers of all Iguazu repositories, who are the
  TSC voting members, and how maintainers are added and removed.
- [SECURITY.md](SECURITY.md): the security vulnerability disclosure policy and the security team.
- [community_meeting_agendas/](community_meeting_agendas/): agendas and notes of the
  Iguazu community calls.
- [config.yaml](config.yaml): GitHub teams, memberships and repository access, applied by
  [CLOWarden](https://github.com/cncf/clowarden).
- [LICENSE](LICENSE): Apache License 2.0.

## Technical Steering Committee

The TSC is responsible for the technical oversight of the project, as defined in the
[Charter](Iguazu%20Technical%20Charter%20FINAL%2009-21-2026.pdf). The TSC voting members
are the maintainers listed in [MAINTAINERS.md](MAINTAINERS.md).

TSC decisions are taken by consensus where possible. When a vote is needed, each voting
member has one vote; votes at a meeting require a quorum of at least 50% of the voting
members and a majority of those in attendance, and electronic votes (for example, PR
approvals) require a majority of all voting members (Charter, Section 3).

## Community calls

Iguazu holds a monthly community call that is open to everyone. Agendas and notes are
kept in [community_meeting_agendas/](community_meeting_agendas/); to propose a topic,
open a pull request against the agenda of the next call.

## Communication

- Discord: the `#iguazu-general` channel on the
  [LF Decentralized Trust Discord server](https://discord.lfdecentralizedtrust.org/).
- GitHub: issues and pull requests in the [LFDT-Iguazu](https://github.com/LFDT-Iguazu)
  repositories.

## Making changes

All changes are made through pull requests with a DCO sign-off (`git commit -s`).

- Changes to `config.yaml` are validated by CLOWarden on the pull request and applied
  as soon as the pull request is merged. Changes to the `iguazu-maintainers` team must
  match [MAINTAINERS.md](MAINTAINERS.md).
- Changes to the maintainers list follow the process in [MAINTAINERS.md](MAINTAINERS.md).
