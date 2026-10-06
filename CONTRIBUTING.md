# Contributing to the FINOS Architecture as Code Project

Thank you for your interest in contributing to the FINOS Architecture as Code project, also known as CALM.

This document is the project-wide baseline for contributions and applies to every repository in the project. Individual code repositories add their own `CONTRIBUTING.md` covering repository-specific matters — build steps, test commands, and commit conventions — which supplement, rather than replace, the guidance here.

The project's governance policies — the definitions of Contributor, Maintainer and Lead Maintainer, the contribution rules, Maintainer voting, and how Maintainers are added and removed — are set out in [GOVERNANCE.md](GOVERNANCE.md). That document also lists the Linux Foundation and FINOS policies the project operates under. The current Maintainer roster is in [MAINTAINERS.md](MAINTAINERS.md).

## Technical Charter

FINOS publishes a **Technical Charter** for the project as a PDF at the root of this repository. It defines mission, scope, IP and licensing, and related governance, and takes precedence over the documents in this repository. The charter has not yet been issued for this project; it will be added here when it is.

## Contribution Requirements

Contributions are accepted via git pull requests. Each commit must include a Developer Certificate of Origin sign-off line in the commit message:

```
Signed-off-by: GitHub User Name <your.email@example.com>
```

This sign-off means you agree the commit satisfies the [Developer Certificate of Origin (DCO)](https://developercertificate.org/). `git commit -s` adds it for you.

Some repositories additionally require a CLA via [EasyCLA](https://community.finos.org/docs/governance/Software-Projects/easycla). Please read the [FINOS Contribution Requirements](https://community.finos.org/docs/governance/Software-Projects/contribution-compliance-requirements) before opening a pull request. Questions about CLA, DCO or EasyCLA can go to [help@finos.org](mailto:help@finos.org).

## Contribution Process

Before making a contribution, please take the following steps:

1. Check whether there's already an open issue related to your proposed contribution. If there is, join the discussion and propose your contribution there.
2. If there isn't already a relevant issue, create one, describing your contribution and the problem you're trying to solve.
3. Respond to any questions or suggestions raised in the issue by other developers.
4. Fork the project repository and prepare your proposed contribution.
5. Submit a pull request.

## Contributing Issues

### Prerequisites

* [ ] Have you searched the repository's existing issues for duplicates? A search for the exception message or a summary of the unexpected behaviour should suffice.
* [ ] Are you running the latest version?
* [ ] Are you sure this is a bug or a missing capability?

### Raising an issue

* Raise the issue on the repository the problem relates to. Governance matters belong here; code, documentation and schema matters belong on the relevant code repository.
* Where the repository offers issue templates, pick the most appropriate one and fill it in.
* Please use [Markdown formatting](https://help.github.com/categories/writing-on-github/) liberally to assist in readability. [Code fences](https://help.github.com/articles/creating-and-highlighting-code-blocks/) for exception stack traces and log entries, for example, massively improve readability.

## Contributing Pull Requests

To make review of pull requests easier, please:

* Make sure your pull request will merge cleanly — pull requests that don't are unlikely to be accepted.
* For code contributions, follow the existing code layout.
* For documentation contributions, follow the general structure, language and tone of the existing documentation.
* Keep commits small and cohesive — if you have multiple contributions, please submit them as independent commits, and ideally as independent pull requests too.
* Reference issues if your pull request has anything to do with an issue, even if it doesn't address it.
* Minimise non-functional changes, such as whitespace.
* Ensure all new files include a header comment block containing the [Apache License v2.0 and your copyright information](https://www.apache.org/licenses/LICENSE-2.0#apply).
* If necessary — for example, due to third-party dependency licensing requirements — update the repository's `NOTICE` file with any new attribution or other notices.

### Commit and pull request messages

* Reference issues and pull requests liberally.
* Use the present tense ("Add feature" not "Added feature").
* Use the imperative mood ("Move button left..." not "Moves button left...").
* Limit the first line to 72 characters or less.

Code repositories in this project enforce the [Conventional Commits](https://www.conventionalcommits.org/) specification, which drives automated versioning and changelog generation. See the `CONTRIBUTING.md` of the repository you are contributing to for its accepted commit types and scopes.

## Responsible Use of AI Coding Assistants

This project welcomes the responsible use of AI coding assistants. They can accelerate learning, improve productivity, and help contributors understand the codebase, but AI-generated output should be treated as a draft, not a finished contribution. Contributors remain responsible for every change they submit.

### Understand Before You Submit

Do not submit code you cannot explain. Before opening a pull request, ensure you understand why the change is needed, how it works, its impact on the project, and how you verified that it behaves correctly.

### Use AI as an Assistant, Not an Authority

Treat AI suggestions like code from any unfamiliar contributor. Review and validate them against the project's architecture, coding conventions, documentation, and testing practices rather than assuming they are correct because they compile or appear plausible.

### Start With the Problem

Take time to understand the issue before asking AI to generate code. Focused prompts based on a clear understanding of the problem consistently produce better contributions than asking AI to implement an entire feature from scratch.

### Keep Contributions Focused

AI assistants often generate broader solutions than necessary. Keep pull requests narrowly focused on the problem being solved, minimize unrelated changes, and avoid introducing new abstractions or dependencies unless they are clearly justified.

### Validate Every Change

AI-generated code requires the same level of review and testing as any other contribution. Carefully review the complete diff, run the project's required validation steps, and ensure the implementation and tests accurately solve the intended problem.

### Protect Sensitive Information

Do not share credentials, confidential information, private repository content, or other sensitive data with AI services unless you are authorized to do so. Contributors are responsible for understanding the privacy and data-retention policies of the tools they use.

### Verify, Don't Assume

AI assistants can produce incorrect code, invent APIs, misinterpret project conventions, or generate flawed tests. Verify technical claims using authoritative sources and your own testing rather than relying solely on AI-generated responses.

### Own Your Contribution

AI can help draft code, but it cannot take responsibility for it. Be prepared to explain your design decisions, respond thoughtfully to maintainer feedback, and revise your implementation based on code review.

### Contributor Responsibility

By submitting a contribution, you confirm that you:

1. Reviewed the complete change.
2. Understand and can explain the implementation.
3. Verified the change using the project's required validation steps.
4. Considered security, privacy, licensing, and dependency implications.
5. Accept responsibility for the entire contribution, including any AI-assisted portions.

Maintainers may reject contributions that appear to be AI-generated but are not sufficiently understood, reviewed, or validated by the contributor.

## Need Help?

* For questions about a specific repository, open an issue there.
* For questions about project governance, open an [issue in this repository](https://github.com/finos/calm-governance/issues).
* Governance topics are also raised at the monthly community meetup and weekly Office Hours.
* Security vulnerabilities must be reported privately — see [SECURITY.md](SECURITY.md).

## Changes to this Document

Amendments to this document follow the Maintainer Voting process described in [GOVERNANCE.md](GOVERNANCE.md).
