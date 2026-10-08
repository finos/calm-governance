[![FINOS - Graduated](https://cdn.jsdelivr.net/gh/finos/contrib-toolbox@master/images/badge-graduated.svg)](https://community.finos.org/docs/governance/lifecycle-stages/graduated)

# FINOS Architecture as Code (CALM) — Governance

This repository is the governance home for the FINOS Architecture as Code project, also known as CALM.

It contains no code. Its purpose is to hold the project-wide governance documentation in a neutral location, so that no single code repository implies it is the "home" of the project. Every repository in the project defers to the documents here as the authoritative source.

## Documents

| Document | Purpose |
|----------|---------|
| [GOVERNANCE.md](GOVERNANCE.md) | Project governance policies — roles, contribution rules, Maintainer voting, and how Maintainers are added and removed. Applies to all repositories in the project. |
| [CONTRIBUTING.md](CONTRIBUTING.md) | Project-wide contribution guidelines — how to raise issues, submit pull requests, and the responsible use of AI coding assistants. |
| [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | The Code of Conduct all participants are subject to. |
| [MAINTAINERS.md](MAINTAINERS.md) | The current Maintainer roster for the project. |
| [SECURITY.md](SECURITY.md) | How to report a security vulnerability. |

The FINOS Technical Charter for the project will be published as a PDF at the root of this repository once FINOS has issued it. It defines mission, scope, IP and licensing, and takes precedence over the documents here.

## Project repositories

The project is organised across the following repositories:

| Repository | Contents |
|------------|----------|
| [calm-governance](https://github.com/finos/calm-governance) | This repository. Project-wide governance, contribution guidelines, and Code of Conduct. |
| [architecture-as-code](https://github.com/finos/architecture-as-code) | The main repository — CLI, server, shared libraries, data models, widgets, CALM Hub and its UI, the VS Code extension, and the documentation site. |
| [calm-schema](https://github.com/finos/calm-schema) | The CALM Meta Schema, its documentation, and validation test suite. |

A proposed rename of the main repository to `calm` and of the FINOS project itself to CALM is described in [architecture-as-code#2354](https://github.com/finos/architecture-as-code/issues/2354). That is a proposal under discussion — until FINOS approves the rename, the official project name remains "Architecture as Code".

## Proposing a governance change

Governance changes are made in the open:

1. Open an [issue](https://github.com/finos/calm-governance/issues) describing the change you are proposing and the problem it addresses.
2. Discuss it with the Maintainers and the wider community. Governance topics are also raised at the monthly community meetup and weekly Office Hours.
3. Raise a pull request against the relevant document.

Minutes of governance meetings are recorded as issues in this repository using the **Meeting Minutes** issue template, giving governance decisions a public record alongside the policies they change.

Amendments to [GOVERNANCE.md](GOVERNANCE.md) require a vote of the Maintainers, following the Maintainer Voting process set out in that document. Changes to the Maintainer roster follow the process in [MAINTAINERS.md](MAINTAINERS.md).

Security vulnerabilities must be reported privately rather than raised as issues — see [SECURITY.md](SECURITY.md).

_NOTE:_ Pull requests must follow this repository’s contribution policy. FINOS projects typically use **DCO** (signed commits) and/or **CLA** via [EasyCLA](https://community.finos.org/docs/governance/Software-Projects/easycla), depending on configuration. Read [FINOS Contribution Requirements](https://community.finos.org/docs/governance/Software-Projects/contribution-compliance-requirements) before contributing.

*Questions about CLA, DCO, or EasyCLA? Email [help@finos.org](mailto:help@finos.org)*

## License

Copyright 2026 FINOS

Distributed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).

SPDX-License-Identifier: [Apache-2.0](https://spdx.org/licenses/Apache-2.0)
