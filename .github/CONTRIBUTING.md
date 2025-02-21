# Sonar Contributing Guide

Hi! I'm really excited that you are interested in contributing to Sonar. Before submitting your contribution, please make sure to take a moment and read through the following guidelines:

-   [Code of Conduct](https://github.com/MOMENT3D/sonar/blob/main/.github/CODE_OF_CONDUCT.md)
-   [Issue Reporting Guidelines](#issue-reporting-guidelines)
-   [Pull Request Guidelines](#pull-request-guidelines)

## Issue Reporting Guidelines

-   Use [https://github.com/MOMENT3D/sonar/issues](https://github.com/MOMENT3D/sonar/issues) to create new issues.

## Pull Request Guidelines

-   The `main` branch is just a snapshot of the latest stable release. All development should be done in dedicated branches. **Do not submit PRs against the `main` branch.**

-   Checkout a topic branch from the relevant branch, e.g. `develop`, and merge back against that branch.

-   It's OK to have multiple small commits as you work on the PR - GitHub will automatically squash it before merging.

-   If adding a new feature:

    -   Provide a convincing reason to add this feature. Ideally, you should open a suggestion issue first and have it approved before working on it.

-   If fixing bug:
    -   If you are resolving a special issue, add `(fix #xxxx[,#xxxx])` (#xxxx is the issue id) in your PR title for a better release log, e.g. `update entities encoding/decoding (fix #3899)`.
    -   Provide a detailed description of the bug in the PR. Live demo preferred.
    -   Add appropriate test coverage if applicable.

## Code Style

All submitted scripts should meet the settings of [.editorconfig](https://github.com/MOMENT3D/sonar/blob/main/.editorconfig) \
If possible use an PlugIn/Addon for your preferred editor.

-   Try to avoid line lengths above 100 characters, use line breaks instead.
-   Keep your code boring and readable, no fancy things that needs to be read twice.
-   Your code has to be 100% compatible with bash code syntax.
-   Every submit will be checked with [shellcheck](https://shellcheck.net), make sure it met this requirement.

What else?
We prefer a long syntax code style for functions, so make sure it looks like

    function foo_bar {
        do something
    }

Also use capital letters for Variables that has to be global.
Lowercase letters for variables used in functions

## Committing Changes

Commit messages should follow the [commit message convention](https://www.conventionalcommits.org/en/v1.0.0/) so that changelogs can be automatically generated.

## Financial Contribution

As a pure community-driven project without major corporate backing, we also welcome financial contributions via Patreon and OpenCollective.

-   [Become a supporter on Patreon](https://patreon.com/meteyou)
-   [One-time donation via Ko-Fi](https://ko-fi.com/mainsail)

## Credits

Thank you to all the people who have already contributed to projects of MOMENT3D!
