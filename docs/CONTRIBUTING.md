# Contributing

This document contains a set of guidelines to help you during the contribution
process.

We are happy to welcome all contributions from anyone willing to improve this
project. Thank you for helping out and remember, no contribution is too small.

## Step by step contribution guide

1. [**Install**](#prerequisites) prerequisites
2. **Fork** the repository on GitHub
3. **Clone** the project to your own machine
4. **Start working** on your fix, feature and etc.
5. **Commit** changes to your own branch according to
   [**Commit Message Guidelines**](#commit-message-guidelines)
6. **Push** your work back up to your fork
7. Submit a **Pull Request** so that we can review your changes

**NOTE:** Be sure to get the latest from "**upstream**" before making a pull
request!

### Prerequisites

- [Git](https://git-scm.com/downloads)

## Commit Message Guidelines

We have strict rules over how our **git commit messages** can be formatted. This
leads to **more readable messages** that are easy to follow when looking through
the **project history**.

### Commit Message Format

```sh
<type>: (<scope>) <subject>
<BLANK LINE>
<type>: <body>
<BLANK LINE>
<type>: <footer>
```

The **scope** is optional.

### Template

We use a base commit message template from [dotfiles]. You may find any
other additional *type*, *scope*, and more information below.

[dotfiles]: https://github.com/erdaltsksn/dotfiles/blob/master/git/.gittemplate

### Additional Types

As well as those specified in the [dotfiles] file, The following is the list of
supported types:

### Scopes

The following is the list of supported scopes:

- **git** e.g. gitignore, gitattributes, .github and etc.
- **cid** e.g. travis, pre-commit, netlify, heroku, and etc.
- **readme** e.g. readme, getting started, changelog, license and etc.

### Revert and Merge

We use default GIT templates for revert and merge.

**Caution:** You should check the differences in [CHANGELOG.md](CHANGELOG.md)
and verify the result when you `revert` or `merge` a commit.

## Issues

Before creating a new issue, please search for similar issues, open or closed,
to see if someone else has already noticed the same problem and possible
solutions.

Do not comment on open issues unless you can provide more information to resolve
it. Use the subscribe function to keep up-to-date with the issue or the voting
system to support it.

## Bug reports

When you can't find a previous bug, open an issue keeping in mind the following
considerations:

- Try to reproduce the bug using the code found on the master branch
- Copy and paste the full error message, including the backtrace
- Be as detailed as possible and include any additional information

## Feature requests

If you want to request or implement a new feature please submit an issue
describing the details and possible use cases.

Features that break backward compatibility must provide good reasons to do it
and a deprecation note when applicable.

## Thanks

Thank you to all who have contributed in this great project.
