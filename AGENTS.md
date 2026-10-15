# CALM Governance - AI Assistant Guide

## What this repository owns

This is the governance home of the FINOS Architecture as Code project, also known as CALM. It holds
no code. Every repository in the project defers to the documents here.

| Document | Owns | How it changes |
|---|---|---|
| `GOVERNANCE.md` | Roles, contribution rules, Maintainer voting, how Maintainers are added and removed | A vote of the Maintainers, as set out in the document itself |
| `MAINTAINERS.md` | The project-wide Maintainer roster and the Lead Maintainer | The process in `GOVERNANCE.md`; a pull request records the result |
| `CONTRIBUTING.md` | Project-wide contribution guidelines, including the use of AI coding assistants | Pull request |
| `CODE_OF_CONDUCT.md` | The Code of Conduct for every participant | Pull request |
| `SECURITY.md`, `security-insights.yml` | How to report a vulnerability; the OpenSSF Security Insights data | Pull request. Bump `header.last-updated` in `security-insights.yml` with every edit |
| `.github/ISSUE_TEMPLATE/meeting_minutes.yml` | Minutes of governance meetings, recorded as issues | Pull request |

The FINOS Technical Charter, when published, is a PDF at the root of this repository and takes
precedence over these documents.

## Which repository owns what

| Repository | Owns | Send here |
|---|---|---|
| [calm-governance](https://github.com/finos/calm-governance) | This repository | Governance, the Maintainer roster, project-wide contribution rules, the Code of Conduct |
| [calm-schema](https://github.com/finos/calm-schema) | The CALM Meta Schema (`schema/`), its tests, `CHANGELOG.md`, the example interfaces. Published to npm as `@finos/calm-schema` and to `calm.finos.org` | Schema changes, schema releases, interface definitions |
| [architecture-as-code](https://github.com/finos/architecture-as-code) | The tools: CLI, server, shared libraries, data models, widgets, CALM Hub and its UI, the VS Code extension, CALM Studio, CALM Guard, the docs site and CALM Lab | Tool changes, the documentation site, examples that the tools use |

A change to a code repository's own `CONTRIBUTING.md` or `SECURITY.md` covers only what is specific
to that repository. The project-wide rules stay here.

## Working across the repositories

Clone the three repositories side by side, with the same parent directory:

```
<parent>/
├── architecture-as-code/
├── calm-schema/
└── calm-governance/
```

- Start the agent in `architecture-as-code`, and add the other two repositories as additional
  directories. Each repository has its own `AGENTS.md`; read the one for the repository you change.
- Target commands at the correct repository: `git -C ../calm-governance ...` and
  `gh ... --repo finos/calm-governance`. A command run in the wrong repository branches, commits or
  opens a pull request in the wrong place.
- Each repository is a fork clone: `origin` is the contributor's fork and `upstream` is the FINOS
  repository. Branch from `upstream/main` and open pull requests against `finos/<repo>`.

## Rules for changes here

- Governance changes are made in the open. Open an issue first, then a pull request against the
  relevant document.
- Do not edit `GOVERNANCE.md` without the vote it requires. Do not edit the roster in
  `MAINTAINERS.md` outside the process in `GOVERNANCE.md`.
- Write documentation in Simplified Technical English where possible, as concise as possible. Prefer
  tables to long lists of options.
- Pull requests need a review from `@finos/architecture-as-code-maintainers` (`.github/CODEOWNERS`).
