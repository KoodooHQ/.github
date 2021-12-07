## Description

<!--
High level description for the PR, what feature or fix is this PR delivering?
HINT: include link to the GitHub issue, eg. "Fixes #127"
-->

### Summary

<!--
Summary of what has changed in this PR to deliver the feature or fix.
-->

### Prerequisites

<!--
Do I need any specific tools or applications to review and manually test this
PR? Below are some examples:

  - `vagrant`
  - `ansible >= 2.9.10`
  - `molecule < 3.0.0`
  - `terraform > 0.12`
-->

### Commitment to review

<!--
How much time and effort is required to review this PR? If this commitment is
large, can you break the PR up into smaller PRs?
-->

  - Reviewing changes takes about _n minutes_.<!-- Rough estimate.  -->
  - Reviewing _n files_.<!-- The number of relevant files to review.  -->

### Review instructions

<!--
This should be a list of any manual tests to run, or links to the relevant
files to review if there are a lot of formatting changes due to linting errors.

These should form the basis for building an acceptance criteria, think about
how to demonstrate that the changes contribute to the desired fix or feature.

For example:

  - Open the project in the VSCode devcontainer
  - AC1: `molecule test --all`
  - AC2: Ensure this file has changes in the container
    - `molecule login -h sles`
    - `grep "server" /etc/ntp.conf`
  - AC3: Review the changes to [README.md](https://github.com/...)
-->

### Acceptance criteria

<!--
A checklist that relates to how the changes will deliver the desired fix or
feature.

HINT: Think about how can the reviewer of the PR can check off a list of items
that ensures the PR is acceptable.

Examples:

  - [ ] AC1: Molecule tests pass
  - [ ] AC2: NTP config is updated as expected
  - [ ] AC3: README has been updated to include the new NTP options
  - [ ] Tests pass in Travis-CI
  - [ ] LGTM :+1:

The below are standard acceptance criteria that should be included in most
PRs, however feel free to delete items that are not relevant (eg. if there are
no changes to documentation).
-->

  - [ ] Documentation updated
  - [ ] Tests pass in Travis-CI
  - [ ] LGTM :+1: