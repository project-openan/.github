# Contributing to OpenAN

Thank you for your interest in contributing to OpenAN, an open source suite for Autonomous Networks (AN) as defined by the TM Forum Autonomous Networks Project. This document provides guidelines for contributors and describes how the project's technical roles and Technical Steering Committee (TSC) seats are determined, as provided for in the OpenAN Technical Charter.

## How to Contribute

1. **Join the community.** Subscribe to the [OpenAN mailing lists](https://lists.openan.dev) and introduce yourself.
2. **Find or propose work.** Browse [open issues](https://github.com/project-openan) across the repositories in the [project-openan](https://github.com/project-openan) GitHub organization, or propose a new feature or improvement on the mailing list.
3. **Fork and branch.** Fork the relevant repository and create a feature branch from `main`.
4. **Make your changes.** Write clear, well-documented code and include tests where appropriate.
5. **Sign off your commits.** All commits must include a Developer Certificate of Origin (DCO) sign-off (`git commit -s`). See the DCO section below.
6. **Submit a pull request.** Open a pull request against `main` with a clear description of your changes. On your first PR, the EasyCLA bot prompts you to sign the CLA. A Maintainer will review it, and changes may be requested before merge.

## Developer Certificate of Origin (DCO)

All contributions to OpenAN must be signed off under the [Developer Certificate of Origin (DCO)](https://developercertificate.org/), Version 1.1. The DCO is a lightweight mechanism for contributors to certify that they have the right to submit their contribution under the project's license.

By signing off, you agree to the following:

```
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.

Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```

To sign off on a commit, add a `Signed-off-by` line to your commit message:

```
Signed-off-by: Your Name <your.email@example.com>
```

You can do this automatically with `git commit -s` or `git commit --signoff`.

The name and email in your sign-off must match your Git identity. The GitHub DCO App is installed on all OpenAN repositories and will check every pull request for valid sign-offs.

## Contributor License Agreement (CLA)

In addition to the DCO sign-off, OpenAN uses [EasyCLA](https://docs.linuxfoundation.org/lfx/easycla) to manage Contributor License Agreements. On your first pull request, the EasyCLA bot prompts you to sign the appropriate CLA. If you are contributing on behalf of an employer, your organization's CLA manager approves you under a corporate CLA. Both the DCO check and the EasyCLA check must pass before a pull request can be merged.

## License

Code contributions are accepted under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0). Documentation contributions are accepted under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/). By submitting a contribution, you agree that it will be licensed accordingly.

### SPDX License Headers

All new source files should include the following SPDX license identifier near the top of the file:

```
# SPDX-FileCopyrightText: Copyright contributors to the OpenAN project
# SPDX-License-Identifier: Apache-2.0
```

Adjust the comment syntax for your file type (e.g., `//` for Go/Java/C, `/* */` for CSS, `<!-- -->` for HTML/XML).

## Code Review

All submissions require review before merging. Maintainers will review your pull request for technical correctness, style, and alignment with project goals. Be responsive to feedback and willing to make adjustments.

## Reporting Issues

When reporting issues, please include:

- A clear, descriptive title
- Steps to reproduce the issue
- Expected versus actual behavior
- Your environment (OS, software versions, etc.)
- Any relevant logs or screenshots

## Roles

Per Section 2.c of the Technical Charter:

- **Contributors** are anyone in the technical community who contributes code, documentation, or other technical artifacts to the Project.
- **Maintainers** are Contributors who have earned the ability to commit to a project repository. A Contributor may become a Maintainer by majority approval of the TSC. A Maintainer may be removed by majority approval of the TSC.

### Becoming a Maintainer

Contributors with a sustained record of high quality contributions (code, documentation, reviews, or other technical artifacts) may be nominated by any existing Maintainer or may self-nominate to the TSC. The TSC approves new Maintainers by majority vote.

## TSC Composition

### Startup Period

Per Section 2.b of the Technical Charter, for an initial period of twelve (12) months following the inception of the Project, the Maintainers of the Project, who serve as the voting members of the TSC, are the individuals listed below. Each organization listed appointed one (1) representative as of the Project inception date.

| Organization | Representative | Role | GitHub ID |
|---|---|---|---|
| Huawei Technologies Co., Ltd | Yijun Yu | TSC Chair | amoyuzi |
| China Mobile Communication Company, Ltd | Kailai Zhang | TSC Vice Chair | TBD |
| Advanced Info Service PLC | Boonchoung Tansuthepverawongse | Voting Rep | TBD |
| AsiaInfo Technologies (China) Co., Ltd | Zhiqi Li | Voting Rep | TBD |
| Infosys Limited | Ullas Krishnan | Voting Rep | TBD |
| Orange SA | Bastien Bourgeois | Voting Rep | TBD |
| Telecom Argentina S.A. | Eduardo M Panciera Molanes | Voting Rep | TBD |
| ZTE Corporation | Xiaobin Shi | Voting Rep | TBD |

An organization may replace its representative by written notice to the TSC Chair.

### Steady State

After the Startup Period, TSC seats are filled as follows:

- The TSC consists of up to eleven (11) voting members.
- No organization (including affiliates) may hold more than one (1) voting seat.
- Voting members are elected annually from among the Project's active Maintainers and Contributors, following the election process documented in [GOVERNANCE.md](./GOVERNANCE.md).
- The TSC may adjust this process by majority vote, documented by an update to this file.

## Decision Making

Day to day technical decisions follow the consensus and voting processes documented in [GOVERNANCE.md](./GOVERNANCE.md), subordinate to the TSC Voting provisions of the Technical Charter.

## Code of Conduct

All participants must follow the [LF Projects Code of Conduct](https://lfprojects.org/policies/code-of-conduct/), unless and until a Project-specific code of conduct is adopted per the Technical Charter. Be respectful, inclusive, and constructive in all interactions.

## Communication

- Mailing lists: <https://lists.openan.dev>
- Wiki: [OpenAN Confluence space](https://lf-networking.atlassian.net/wiki/spaces/OpenAN/overview)
- Issues and discussion: GitHub issues in the relevant repository, or [GitHub Discussions](https://github.com/orgs/project-openan/discussions)
- Project operations or governance questions: contact LFN staff at <support@lfnetworking.org>
- Infrastructure issues (GitHub access, SSO/LFID accounts): visit [support.linuxfoundation.org](https://support.linuxfoundation.org)

Copyright © OpenAN a Series of LF Projects, LLC. For web site terms of use, trademark policy and other project policies please see https://lfprojects.org.
