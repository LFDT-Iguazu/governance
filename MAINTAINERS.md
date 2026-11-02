[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Maintainers / Technical Steering Committee (the "TSC")

This file is the single source of truth for the maintainers of all
[LFDT-Iguazu](https://github.com/LFDT-Iguazu) repositories. Each repository's
`MAINTAINERS.md` links here.

The role of the TSC is defined in the
[Iguazu Technical Charter](Iguazu%20Technical%20Charter%20FINAL%2009-21-2026.pdf).
Per Section 2.b of the Charter, the TSC voting members are the Project's Maintainers
listed below.

## Maintainer Scopes, GitHub Roles and GitHub Teams

| Scope | Definition | GitHub Role | GitHub Team |
| ----- | ---------- | ----------- | ----------- |
| Maintainer | The GitHub Maintain role on all project repositories | Maintain | `iguazu-maintainers` |

GitHub team membership is managed in [config.yaml](config.yaml) and must match the
list of active maintainers below.

## Active Maintainers

<!-- Please keep this sorted alphabetically by github -->

| Name | GitHub ID | Scope | LFID | Discord ID | Email | Company Affiliation |
| ---- | --------- | ----- | ---- | ---------- | ----- | ------------------- |
| Sergii Grybniak | [grybniak](https://github.com/grybniak) | Maintainer | | greebn9k | sergii@waterfall.network | Waterfall Network |
| Oleksandr Nashyvan | [on-waterfall](https://github.com/on-waterfall) | Maintainer | | nashyvan | on@waterfall.network | Waterfall Network |
| Volodymyr Mezin | [VladimirMezin](https://github.com/VladimirMezin) | Maintainer | | v.mezin | volodymyr@waterfall.network | Waterfall Network |

## Emeritus Maintainers

| Name | GitHub ID | Scope | LFID | Discord ID | Email | Company Affiliation |
| ---- | --------- | ----- | ---- | ---------- | ----- | ------------------- |

## The Duties of a Maintainer

Maintainers are expected to perform the following duties for the project repositories. The duties are listed in more or less priority order:

- Review, respond, and act on any security vulnerabilities reported against the repositories.
- Review, provide feedback on, and merge or reject GitHub Pull Requests from
  Contributors.
- Review, triage, comment on, and close GitHub Issues
  submitted by Contributors.
- When appropriate, lead/facilitate architectural discussions in the community.
- When appropriate, lead/facilitate the creation of a product roadmap.
- Create, clarify, and label issues to be worked on by Contributors.
- Ensure that there is a well defined (and ideally automated) product test and
  release pipeline, including the publication of release artifacts.
- When appropriate, execute the product release process.
- Maintain the CONTRIBUTING.md files and getting started documents to
  give guidance and encouragement to those wanting to contribute to the product, and those wanting to become maintainers.
- Contribute to the product via GitHub Pull Requests.
- Monitor requests from the LF Decentralized Trust Technical Advisory Council about the
  contents and management of LFDT repositories, such as branch handling,
  required files in repositories and so on.
- Contribute to the LFDT Project's quarterly and annual reports.

## Becoming a Maintainer

This community welcomes contributions. Interested contributors are encouraged to
progress to become maintainers. Per Section 2.c of the Charter, a Contributor may
become a Maintainer by a majority approval of the TSC. The steps are, roughly in order:

- The proposed maintainer establishes their reputation in the community,
  including authoring five (5) significant merged pull requests, and expresses
  an interest in becoming a maintainer.
- A PR is created against this file to add the proposed maintainer to the list of
  active maintainers, together with the matching change to the `iguazu-maintainers`
  team in [config.yaml](config.yaml).
- The PR is authored by the proposed maintainer or has a comment on the PR from the
  proposed maintainer confirming their interest and their willingness to be a
  long-term (more than 6 month) maintainer.
- The PR **MUST** be communicated on the project's communication channels, including
  the community call and the Discord channel. Comments of support from the community are welcome.
- The PR is merged once a majority of the TSC voting members have approved it.

## Removing Maintainers

Being a maintainer is not a status symbol or a title to be carried
indefinitely. It will occasionally be necessary and appropriate to move a
maintainer to emeritus status. This can occur in the following situations:

- Resignation of a maintainer.
- Violation of the Code of Conduct warranting removal.
- Inactivity.
  - A general measure of inactivity will be no commits or code review comments
    for one reporting quarter. This will not be strictly enforced if
    the maintainer expresses a reasonable intent to continue contributing.
  - Reasonable exceptions to inactivity will be granted for known long term
    leave such as parental leave and medical leave.
- Other circumstances at the discretion of the TSC.

A PR is created to move the maintainer to the list of emeritus maintainers and to
update [config.yaml](config.yaml) accordingly. In the case of voluntary resignation,
the PR can be merged following one maintainer approval. Otherwise, per Section 2.c of
the Charter, the PR is merged once a majority of the TSC voting members have approved it.

Returning to active status from emeritus status uses the same steps as adding a
new maintainer.
