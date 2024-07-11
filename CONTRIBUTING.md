# Contributing Guide

Thank you for your interest in contributing to Penpot Helm Charts.

This is a generic guide that details how to contribute to Penpot Helm
Charts in a way that is efficient for everyone. If you want a specific
documentation for different parts of the platform, please visit the
[Contributing Guide](https://help.penpot.app/contributing-guide/).

## Reporting Bugs

We are using [GitHub Issues](https://github.com/penpot/penpot-helm/issues)
for our public bugs. We keep a close eye on this and try to make it
clear when we have an internal fix in progress. Before filing a new
task, try to make sure your problem doesn't already exist.

If you found a bug, please report it, as far as possible with:

- a detailed explanation about the error and the expected behavior
- a detailed explanation of steps to reproduce the error, some
  screenshots could help
- the related helm chart and its version
- the version of your tooling (helm, kubectl, relevant information
  about your cluster...)

If you found a bug that you consider better discuss in private (for
example: security bugs), consider first send an email to
`support@penpot.app`.

> [!NOTE]
> We don't have formal bug bounty program for security reports; this
> is an open source application and your contribution will be recognized
> in the changelog.**

## Pull requests

> [!CAUTION]
> This repository is a **work in progress**. We are not able to aacept
> Pull Requests We cannot accept Pull Requests with new functionality
> until the repository with the first functional version is officially
> released.

If you want propose a change or bug fix with the Pull-Request system
firstly you should carefully read the **DCO** section and format your
commits accordingly.

If you intend to fix a bug it's fine to submit a pull request right
away but we still recommend to file an issue detailing what you're
fixing. This is helpful in case we don't accept that specific fix but
want to keep track of the issue.

If you want to implement or start working in a new feature, please
open a **question** / **discussion** issue for it. No pull-request
will be accepted without previous chat about the changes,
independently if it is a new feature, already planned feature or small
quick win.

If is going to be your first pull request, You can learn how from this
free video series:

https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github

We will use the `easy fix` mark for tag for indicate issues that are
easy for beginners.

## Commit Guidelines

To maintain a clear and organized commit history in this repository, we
adhere to the Conventional Commits specification. Conventional Commits
provide a structured format for commit messages, making it easier to
track changes, automate versioning, and improve readability.

Please familiarize yourself with the Conventional Commits rules by
visiting the [official Conventional Commits website](https://www.conventionalcommits.org/en/v1.0.0/).
This specification outlines how to structure your commit messages,
including types, scopes, and descriptions.

## Code of conduct

As contributors and maintainers of this project, we pledge to respect
all people who contribute through reporting issues, posting feature
requests, updating documentation, submitting pull requests or patches,
and other activities.

We are committed to making participation in this project a
harassment-free experience for everyone, regardless of level of
experience, gender, gender identity and expression, sexual
orientation, disability, personal appearance, body size, race,
ethnicity, age, or religion.

Examples of unacceptable behavior by participants include the use of
sexual language or imagery, derogatory comments or personal attacks,
trolling, public or private harassment, insults, or other
unprofessional conduct.

Project maintainers have the right and responsibility to remove, edit,
or reject comments, commits, code, wiki edits, issues, and other
contributions that are not aligned to this Code of Conduct. Project
maintainers who do not follow the Code of Conduct may be removed from
the project team.

This code of conduct applies both within project spaces and in public
spaces when an individual is representing the project or its
community.

Instances of abusive, harassing, or otherwise unacceptable behavior
may be reported by opening an issue or contacting one or more of the
project maintainers.

This Code of Conduct is adapted from the Contributor Covenant, version
1.1.0, available from http://contributor-covenant.org/version/1/1/0/

## Developer's Certificate of Origin (DCO)

By submitting code you are agree and can certify the below:

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

Then, all your code patches (**documentation are excluded**) should
contain a sign-off at the end of the patch/commit description body. It
can be automatically added on adding `-s` parameter to `git commit`.

This is an example of the aspect of the line:

    Signed-off-by: Andrey Antukh <niwi@niwi.nz>

Please, use your real name (sorry, no pseudonyms or anonymous
contributions are allowed).
