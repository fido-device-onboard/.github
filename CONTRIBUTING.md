# Contributing to FIDO Device Onboard

Thank you for your interest in contributing to the LF Edge FIDO Device
Onboard (FDO) project.

FDO is developed openly, and contributions from individuals and
organizations are welcome. This document describes the common
contribution workflow across FDO repositories. Individual repositories
may provide additional build, test, style, or development instructions.

For project roles, governance, decision-making, and the TSC process, see
[GOVERNANCE.md](GOVERNANCE.md).

## Before contributing

Before submitting a contribution:

- Review the repository documentation and existing issues or pull
  requests for related work.
- Keep changes focused and provide enough context for reviewers to
  understand the problem and proposed solution.
- Follow any repository-specific coding, testing, and documentation
  requirements.

### Significant changes

Significant changes should be discussed with the community before
substantial implementation work begins.

Examples include:

- Architectural changes.
- Changes affecting multiple FDO repositories or components.
- New major functionality or components.
- Significant API or protocol-facing changes.
- Changes that substantially alter existing behavior or project
  direction.

Open an issue or use the project's public community channels to describe
the problem, motivation, and proposed approach before implementation.

### Incremental changes

Incremental and well-scoped changes may normally be proposed directly
through a pull request.

Examples include:

- Bug fixes.
- Documentation improvements.
- Tests and test improvements.
- Small usability improvements.
- Localized refactoring or maintenance changes.

## Issues

Issues are welcome for bug reports, feature requests, interoperability
problems, usability feedback, and technical proposals.

When applicable, include:

- The FDO component and version or commit.
- Expected and observed behavior.
- Relevant logs, configuration, or reproduction steps.
- Environment information relevant to the issue.

Security vulnerabilities must not be reported through public issues.
Follow the process in `SECURITY.md`.

## Pull requests

Changes should normally be submitted through pull requests.

A pull request should:

- Clearly describe the purpose and scope of the change.
- Reference related issues when applicable.
- Include tests for new behavior or bug fixes when practical.
- Update documentation when behavior, configuration, APIs, or
  user-facing functionality changes.
- Keep unrelated changes separate whenever practical.
- Pass the automated checks required by the repository.

Pull requests should receive appropriate peer review before being
merged. Individual repositories may establish additional review, branch
protection, `CODEOWNERS`, or merge requirements appropriate to their
workflow and risk profile.

Significant or cross-project changes may require broader community or
TSC discussion before merge.

## Developer Certificate of Origin

All new inbound code contributions must include a Developer Certificate
of Origin (DCO) sign-off, as required by the FDO Technical Charter.

Add a `Signed-off-by` line to each commit:

``` text
Signed-off-by: Your Name <your.email@example.com>
```

Git can add this automatically:

``` bash
git commit -s
```

By signing off a commit, you certify that you have the right to submit
the contribution in accordance with the [Developer Certificate of
Origin](https://developercertificate.org/).

## License

FIDO Device Onboard source code is licensed under the **Apache License,
Version 2.0**.

Unless a repository or an approved exception explicitly specifies
otherwise, code contributions are accepted under the Apache License 2.0
and must be compatible with that license. See the `LICENSE` file in the
applicable repository for the authoritative license text.

Project documentation is contributed and made available under the
**Creative Commons Attribution 4.0 International License (CC BY 4.0)**,
as specified by the FDO Technical Charter.

Contributions to upstream projects must follow the contribution and
licensing requirements of the applicable upstream project.

## Governance and community

For project roles, Committer responsibilities and appointment, TSC
membership and voting, decision-making, and project governance, see
[GOVERNANCE.md](GOVERNANCE.md).

The [FDO Technical
Charter](https://lf-edge.atlassian.net/wiki/spaces/SDO/pages/14586413/Technical+Charter)
is the authoritative governance document.

The current TSC membership and Chair are recorded on the [FDO TSC
page](https://lf-edge.atlassian.net/wiki/spaces/SDO/pages/14586891/TSC+Technical+Steering+Committee).
