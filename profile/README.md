# OpenDCKit

An open, vendor-neutral SDK for the IMS data channel.

OpenDCKit gives 5G New Calling applications one standard runtime on the device. It wraps the
chip-level data channel and exposes it through APIs that follow GSMA TS.66 (IMS Data Channel
API) and TS.71 (IMS Data Channel IDL), so an application behaves the same way on any device
and any network. It also exposes open APIs for on-device AI capabilities used during a call.

The project is hosted at [LF Networking](https://lfnetworking.org) under neutral governance,
and is licensed under Apache 2.0 for code and CC BY 4.0 for documentation.

> **In formation.** OpenDCKit is a Linux Foundation project in formation. The Technical
> Charter is in review and the source has not been imported yet. Governance, meetings and
> discussion channels are already open, and the repositories below will fill in as formation
> completes.

## Getting involved

Everyone is welcome, and you do not need to be a member of anything to take part.

- Read [CONTRIBUTING](https://github.com/opendckit/.github/blob/main/CONTRIBUTING) first. It
  covers the roles in the project, how to open a pull request, the sign-off the project
  requires on every commit, and how decisions get made.
- Join the conversation on Zulip at
  [linuxfoundation.zulipchat.com](https://linuxfoundation.zulipchat.com), in
  `#lfn-opendckit-discussion` for general discussion, `#lfn-opendckit-support` for help, and
  `#lfn-opendckit-tsc` for technical governance. Sign in with an LF ID.
- Subscribe to the [mailing list](https://groups.linuxfoundation.org/g/opendckit-formation).

## Meetings

The Technical Steering Committee meets weekly on Mondays at 07:00 America/Los_Angeles. The
meeting is open to the public and anyone may propose an agenda item.

Register and join from [LFX](https://app.lfx.dev), which also carries the recordings and
transcripts of past meetings. Agendas and minutes are on the
[project wiki](https://lf-networking.atlassian.net/wiki/spaces/OpenDCKit).

## Repositories

| Repository | What it holds |
| ---------- | ------------- |
| [governance](https://github.com/opendckit/governance) | The TSC roster, the Technical Charter, policies and election results |
| [.github](https://github.com/opendckit/.github) | CONTRIBUTING, the code of conduct and organization-wide defaults |
| [opendckit.github.io](https://github.com/opendckit/opendckit.github.io) | The project website |

## Governance

The Technical Steering Committee is the technical governing body of the project. The current
roster is [TSC.md](https://github.com/opendckit/governance/blob/main/TSC.md) in the governance
repository, and [CONTRIBUTING](https://github.com/opendckit/.github/blob/main/CONTRIBUTING)
explains how TSC and Maintainer membership is determined. Seats are filled by a vote of the
Maintainers at election time. Linux Foundation staff administer elections as a neutral party
and hold no seat on the TSC.

## Code of conduct

OpenDCKit is a project of LF Projects, LLC. Everyone taking part is expected to follow the
[LF Projects Code of Conduct](https://lfprojects.org/policies/code-of-conduct/), which applies
in every OpenDCKit repository, meeting, mailing list and chat channel. Raise a concern with
the TSC chair, or with conduct@lfprojects.org if you would rather take it outside the project.

## Reporting a security issue

Do not open a public issue for a suspected vulnerability. See the reporting section of
[CONTRIBUTING](https://github.com/opendckit/.github/blob/main/CONTRIBUTING) for where to send
it and what to expect.
